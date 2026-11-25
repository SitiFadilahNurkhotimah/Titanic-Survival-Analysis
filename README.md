# Analisis Komparatif Logistic Regression dan Decision Tree Untuk Memprediksi Keselamatan Penumpang Kapal RMS Titanic

#### Disusun oleh: Siti Fadilah Nurkhotimah 
---
## Deskripsi Proyek
Proyek ini membandingkan algoritma Logistic Regression dan Decision Tree untuk mengidentifikasi determinan utama tingkat keselamatan penumpang melalui Exploratory Data Analysis (EDA) dan feature engineering mendalam—mencakup ekstraksi gelar sosial (Title), imputasi data hilang berbasis demografi, serta encoding—yang menyoroti peran dominan variabel Title, Fare, Pclass, dan Sex. Evaluasi performa dan stabilitas model dilakukan menggunakan 5-Fold Cross Validation, metrik evaluasi klasifikasi, serta analisis Feature Importance pada model terbaik. Hasilnya menunjukkan Decision Tree mengungguli Logistic Regression dengan akurasi 82,12% dan F1-score 76,81%, lalu diterapkan untuk memprediksi probabilitas keselamatan pada 418 data penumpang baru secara objektif.

## Deskripsi Fitur Dataset
- Survived = Status keselamatan (0 = Tidak Selamat, 1 = Selamat)
Tipe data: Biner (Target Varibel)
- Pclass = Kelas penumpang (1, 2, 3)
Tipe data: Kategorik
- Sex = Jenis kelamin penumpang
Tipe data: Kategorik
- Age = Usia penumpang
Tipe data: Numerik
- SibSp = Jumlah saudara kandung atau pasangan di kapal Titanic
Tipe data: Numerik
- Fare = Harga tiket penumpang
Tipe data: Numerik
- PassengerId = Identitas (ID) penumpang
Tipe data: Integer (Identitas)
- Name = Nama penumpang
Tipe data: Object (Identitas)
- Ticket = Nomor tiket
Tipe data: Kategorik (Identitas)
- Cabin = Nomor cabin
Tipe data: Kategorik
- Parch = Jumlah orang tua atau anak di kapal Titanic
Tipe data: Numerik
- Embarked = Pelabuhan keberangkatan (C = Cherbourg; Q = Queenstown; S = Southampton)
Tipe data: Kategorik

## Struktur Data
- data_titanic.xlsx: Dataset historis yang digunakan sebagai data latih untuk membangun dan melatih model Logistic Regression dan Decision Tree.
- data_prediksi.xlsx: Dataset independen (418 penumpang) yang digunakan sebagai data uji untuk mengevaluasi kemampuan generalisasi model terhadap data baru.
- hasil_prediksi.xlsx: Output akhir yang berisi label prediksi keselamatan (0 atau 1) yang dihasilkan oleh model terbaik untuk kebutuhan analisis lebih lanjut.


_© 2025 Siti Fadilah Nurkhotimah. All rights reserved. Dokumen ini disusun untuk kepentingan portofolio akademik._
