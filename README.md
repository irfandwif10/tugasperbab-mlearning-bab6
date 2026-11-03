# tugasperbab-mlearning-bab6

## 6. Praktikum Bab 6: KNN & Naive Bayes

### 1. Perbandingan KNN vs Naive Bayes (Praktikum 6.5 & 6.7):
- **K-Nearest Neighbors (KNN):** Memerlukan proses *feature scaling* agar jarak antar fitur terhitung akurat. Waktu pelatihan KNN cenderung sangat cepat (karena *lazy learning*), namun waktu prediksinya bisa lebih lambat pada data yang besar.
- **Gaussian Naive Bayes:** Berbasis probabilitas statistik (Teorema Bayes) dan tidak memerlukan *scaling*. Proses pelatihan dan prediksinya sangat cepat.

### 2. Klasifikasi Teks dengan Multinomial Naive Bayes (Praktikum 6.7):
- **CountVectorizer:** Digunakan untuk mengubah data teks mentah menjadi representasi matriks angka (vektor frekuensi kemunculan kata).
- **MultinomialNB:** Sangat efektif digunakan untuk klasifikasi dokumen atau teks (seperti filter *spam* email) dengan menerapkan *Laplace Smoothing* (`alpha`) untuk mengatasi kata yang tidak muncul pada data latih[cite: 9].
