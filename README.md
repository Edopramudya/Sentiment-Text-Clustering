# Sentiment Text Clustering

Proyek ini berfokus pada preprocessing dan clustering data teks dari dataset sentimen. Dataset yang digunakan berisi teks dan label sentimen (positif, negatif, netral), dan dilakukan pembersihan teks sebelum proses klastering.

## 📂 Dataset
Dataset yang digunakan: `sentiment100.csv`
Kolom utama:
* `Text`: kalimat atau ulasan dari pengguna
* `Sentiment`: label sentimen (misalnya positif, negatif, netral)

## 🔧 Tahapan Proses

### 1. Preprocessing Teks
* Menghapus tanda baca, angka, dan karakter non-alfabet
* Mengubah huruf menjadi huruf kecil (lowercase)
* Menghapus stopwords menggunakan NLTK
* Menyimpan hasil pembersihan ke file `data_bersih.csv`

### 2. Analisis Awal
* Menampilkan distribusi label sentimen
* Menghitung jumlah kata pada setiap teks dan menambahkannya sebagai fitur `count_words`

### Visualisasi
* Menggunakan WordCloud, Seaborn, dan Matplotlib untuk eksplorasi data

## 🛠 Teknologi & Library
* Python
* Pandas, NumPy
* NLTK
* Matplotlib, Seaborn, WordCloud
* (Opsional: scikit-learn, jika digunakan untuk clustering)

## 📈 Output
* File hasil preprocessing: `data_bersih.csv`
* Visualisasi distribusi kata dan sentimen
* \[Hasil clustering jika tersedia]

