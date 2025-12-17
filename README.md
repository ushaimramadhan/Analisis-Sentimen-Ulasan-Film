# Analisis Sentimen Ulasan Film IMDB 

Proyek ini bertujuan untuk mengklasifikasikan ulasan film dari dataset IMDB menjadi dua kategori sentimen: **Positif** atau **Negatif**. Proyek ini dikembangkan sebagai tugas ujian mata kuliah Praktikum Kecerdasan Artificial.

## Metode
Proyek ini dibangun menggunakan bahasa pemrograman **Python** dengan tahapan sebagai berikut:
1. **Text Preprocessing**: Pembersihan teks (lowercase, hapus HTML tags, tanda baca, dan stopwords) menggunakan `NLTK` dan `Regex`.
2. **Feature Extraction**: Mengubah teks menjadi vektor angka menggunakan **TF-IDF Vectorization** (max features: 5000).
3. **Modeling**: Menggunakan algoritma **Multinomial Naive Bayes**.
4. **Evaluasi**: Mengukur performa model dengan Akurasi, Precision, Recall, dan F1-Score.

**Library yang digunakan:**
* `pandas`, `numpy`: Manipulasi data.
* `nltk`: Pemrosesan teks (stopwords, tokenization).
* `scikit-learn`: Pembuatan model Machine Learning dan evaluasi.
* `matplotlib`, `seaborn`, `wordcloud`: Visualisasi data.

## Hasil Evaluasi
Model berhasil mencapai tingkat akurasi sekitar **85%** pada data uji (20% dari total dataset).

| Metric | Score |
|---|---|
| **Accuracy** | 85.06% |
| **Precision** | 0.85 |
| **Recall** | 0.85 |
| **F1-Score** | 0.85 |

## Cara Menjalankan Proyek
1. Clone repository ini:
   ```bash
   git clone [https://github.com/ushaimramadhan/Analisis-Sentimen-Ulasan-Film.git](https://github.com/ushaimramadhan/Analisis-Sentimen-Ulasan-Film.git)
