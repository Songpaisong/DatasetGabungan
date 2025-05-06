# DatasetGabunganUTS
project saya ini adalah project untuk UTS Mata Kuliah Data Mining.
Codingan ini bertujuan untuk mendeteksi dan mengklasifikasikan jaringan berdasarkan data rekaman dari dua jenis aktivitas reconnaissance (pengintaian), yaitu:
Recon Ping Sweep
Recon Vulnerability Scan
Dengan menggunakan teknik Machine Learning (Decision Tree), program ini akan belajar dari data untuk bisa memprediksi jenis serangan dari data baru yang belum pernah dilihat sebelumnya.
Saya Menggunakan dan membaca dataset dari Google Colab.
Terdapat dua file CSV yang masing-masing berisi data aktivitas jaringan
ini adalah 2 dataset yang saya gabung yaitu file Recon Ping Sweep.csv dan Recon Vulnerability Scan.csv

# Membangun dan Melatih Model Decision Tree
Digunakan algoritma Decision Tree Classifier dengan metode pembelajaran berbasis Entropy (Information Gain).
Model akan belajar pola dari training data.

# Visualisasi Decision Tree
Struktur decision tree ditampilkan agar bisa dilihat bagaimana model membuat keputusan dari fitur-fitur yang ada.

# Hasil yang Didapat
Model berhasil mengklasifikasikan jenis serangan dengan akurasi tertentu (misalnya 95.00% tergantung hasil training).
Visualisasi pohon keputusan dan confusion matrix membantu memudahkan interpretasi hasil model.




