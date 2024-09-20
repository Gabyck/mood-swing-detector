## Project Overview
Repositori ini berisi implementasi dari **Mood Swing Detector**, sebuah aplikasi berbasis machine learning yang dirancang untuk mendeteksi gejala depresi. Alat ini menggunakan berbagai algoritma machine learning untuk memprediksi kemungkinan seseorang mengalami depresi berdasarkan pola perilaku.

Pengembangan model melibatkan beberapa algoritma berikut:
- Logistic Regression
- Random Forest
- Decision Tree
- Bagging

Proyek ini merupakan respon terhadap tantangan kesehatan mental global yang semakin meningkat dan bertujuan untuk menyediakan solusi inovatif bagi deteksi dini depresi.

## Objectives
Tujuan utama dari proyek ini adalah:
1. Mengidentifikasi pola perilaku yang berkaitan dengan depresi.
2. Membangun model machine learning yang akurat untuk menganalisis data dan mendeteksi indikator depresi.
3. Menguji dan memvalidasi model dengan dataset yang beragam untuk memastikan keandalan aplikasi.

## Features
- **Deteksi Dini**: Membantu mengidentifikasi tanda-tanda awal depresi berdasarkan data perilaku.
- **Antarmuka Pengguna yang Mudah**: Menyediakan antarmuka yang sederhana dan responsif bagi pengguna untuk memasukkan data dan menerima umpan balik prediktif.
- **Algoritma Beragam**: Mengintegrasikan beberapa model machine learning untuk memastikan prediksi yang akurat dan andal.
- **Pembelajaran Berkelanjutan**: Menggunakan umpan balik dan pembaruan dataset untuk terus meningkatkan kinerja model.

## Algoritma
### 1. Logistic Regression
Teknik klasifikasi yang memprediksi hasil biner (depresi/tidak depresi) berdasarkan data pengguna.

### 2. Random Forest
Metode ensemble learning yang menciptakan beberapa pohon keputusan dan menggabungkan hasilnya untuk mendapatkan prediksi yang lebih akurat.

### 3. Decision Tree
Model berbentuk pohon yang digunakan untuk klasifikasi, membantu membuat keputusan berdasarkan fitur input seperti perilaku dan riwayat pribadi.

### 4. Bagging
Meningkatkan kinerja model klasifikasi dengan menghasilkan beberapa versi dari algoritma yang sama, menjalankannya secara paralel, dan menggabungkan hasilnya.

## Dataset
Model ini dilatih menggunakan dataset dari Kaggle yang berisi data anonim terkait depresi, serta umpan balik dari individu yang telah mengalami tantangan kesehatan mental.

## Instalasi
1. Clone repositori ini:
   ```bash
   git clone https://github.com/yourusername/mood-swing-detector.git
   ```
2. Instal dependensi yang dibutuhkan:
   ```bash
   pip install -r requirements.txt
   ```

## Penggunaan
1. Jalankan aplikasi:
   ```bash
   python app.py
   ```
2. Masukkan input yang diperlukan seperti usia, jenis kelamin, dan jawaban pada kuesioner kesehatan mental.
3. Lihat hasil prediksi untuk mengetahui apakah ada indikator depresi.

## Hasil
Berikut adalah metrik yang digunakan untuk mengevaluasi model:
- **Akurasi**: Persentase prediksi yang benar.
- **Presisi**: Proporsi dari prediksi positif yang benar.
- **Recall**: Kemampuan model dalam menemukan semua kasus positif.
- **F1-Score**: Rata-rata harmonis antara presisi dan recall.

Model **Random Forest** menunjukkan kinerja terbaik dengan akurasi dan F1-score tertinggi.

## Future Improvements
- Memperluas dataset agar lebih beragam.
- Menambah fitur untuk meningkatkan akurasi deteksi depresi.
- Mengintegrasikan umpan balik real-time untuk terus meningkatkan prediksi model.
- Menerapkan model ini ke dalam aplikasi mobile agar lebih mudah diakses.
