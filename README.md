# 📝 Naive Bayes, Logistic Regression, dan BERT

## 📘 Implementasi Naive Bayes dan Logistic Regression dengan BERT di Python
Proyek Python yang mendemonstrasikan implementasi **Naive Bayes manual** dan **Logistic Regression berbasis embedding BERT** untuk klasifikasi teks spam, menggunakan data latihan dan model **IndoBERT**.

---

## 📖 Deskripsi Proyek
**Implementasi_Naive_Bayes_dan_Logistic_Regression_BERT_Python** adalah proyek Python yang menunjukkan pendekatan klasifikasi teks menggunakan **Naive Bayes** dan **Logistic Regression** dengan dukungan model **BERT** khusus bahasa Indonesia. Program ini memproses teks contoh untuk mengklasifikasikan spam dan non-spam, menghitung probabilitas dengan Naive Bayes, dan melatih Logistic Regression menggunakan embedding dari IndoBERT.

### 🎯 Fokus Proyek:
- 📊 **Persiapan Data**: Memuat teks latihan (spam dan non-spam) dan melakukan tokenisasi sederhana.
- 🔍 **Naive Bayes Manual**: Menghitung probabilitas prior, likelihood, dan posterior untuk klasifikasi teks berdasarkan frekuensi kata.
- 🔍 **Logistic Regression dengan BERT**: Menggunakan model IndoBERT untuk ekstraksi embedding (CLS), dilanjutkan dengan pelatihan manual Logistic Regression menggunakan gradient descent.
- 🔍 **Prediksi**: Menguji model pada teks baru untuk menentukan label spam atau non-spam.

---

## 🧠 Teknologi
- Python  
- Transformers (Hugging Face)  
- NumPy  
- Collections  

---

## 📂 Struktur File
```
Implementasi_Naive_Bayes_dan_Logistic_Regression_BERT_Python/
├── Tugas6_235314099.ipynb     # 📊 File Jupyter Notebook dengan kode klasifikasi
```

---

## ▶️ Menjalankan Program

### 1️⃣ Kloning Repositori
```bash
git clone https://github.com/MBAHSINGO22/Implementasi_Naive_Bayes_dan_Logistic_Regression_BERT_Python.git
cd Implementasi_Naive_Bayes_dan_Logistic_Regression_BERT_Python
```

---

## 🟢 Catatan
- Data latihan mencakup contoh **spam** seperti `"Promo besar hari ini diskon 50%!"` dan **non-spam** seperti `"Halo, bagaimana kabarmu hari ini?"`  
- Naive Bayes menghitung probabilitas dengan **Laplace smoothing (α = 1)**  
- Logistic Regression menggunakan **embedding IndoBERT (768 dimensi)** dan diperbarui dengan **gradient descent manual**  
- Prediksi seperti `"Dapatkan diskon spesial sekarang!"` diklasifikasikan sebagai spam berdasarkan probabilitas.

---

## 📈 Contoh Output
```text
Spam words: ['promo', 'besar', 'hari', 'ini', 'diskon', 'gratis', 'hadiah', 'untuk', 'pelanggan', 'setia', 'segera', 'klaim', 'spesial', 'kamu']
Not Spam words: ['halo', 'bagaimana', 'kabarmu', 'hari', 'ini', 'jangan', 'lupa', 'meeting', 'besok', 'pukul', 'dokumen', 'penting', 'sudah', 'dikirim', 'ke', 'email']

P(spam) = 0.6
P(not spam) = 0.4

Log priors:
log P(spam) = -0.5108
log P(not spam) = -0.9162

Prediction for 'Dapatkan diskon spesial sekarang!':
Spam probability = 0.9876
Class: spam

Embedding shape from IndoBERT: (1, 768)
Logistic Regression weights updated: [0.001234, -0.002345, ...]
Prediction (BERT + LR): spam
```

---

## 👨‍💻 Pengembang
**MBAHSINGO22**  
🔗 GitHub: [github.com/MBAHSINGO22](https://github.com/MBAHSINGO22)
