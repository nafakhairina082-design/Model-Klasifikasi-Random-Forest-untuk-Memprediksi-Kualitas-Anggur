# Model-Klasifikasi-Random-Forest-untuk-Memprediksi-Kualitas-Anggur
Tugas ini bertujuan untuk membangun model klasifikasi berbasis Random Forest untuk memprediksi kualitas anggur berdasarkan fitur-fitur kimiawinya. Dataset yang digunakan berisi informasi tentang komposisi kimia anggur (seperti kadar gula, pH, keasaman, dan lainnya) dan label kualitas yang diberikan dalam skala numerik.
Prediksi Kualitas Anggur dengan Random Forest

**Konteks**
Evaluasi kualitas anggur secara manual seringkali memakan waktu dan subjektif. Dengan menggunakan pembelajaran mesin, khususnya model Random Forest, kita dapat memprediksi kualitas anggur secara otomatis berdasarkan fitur kimiawinya, sehingga mempercepat proses penentuan kualitas dan mendukung analisis data yang lebih objektif.

**Dataset**
data_training.csv: berisi fitur kimiawi anggur dan label kualitas (target quality dengan skala 0–10).
data_testing.csv: berisi fitur kimiawi anggur tanpa label kualitas, yang akan digunakan untuk prediksi.

**Tujuan**
Membangun model klasifikasi Random Forest untuk memprediksi kualitas anggur.
Memprediksi nilai kualitas untuk dataset testing berdasarkan model yang dilatih dari data_training.csv.

**Proses**
1. Data diproses dengan menangani missing value (jika ada) dan normalisasi.
2. Analisis eksploratif (EDA) dilakukan untuk memahami distribusi dan korelasi antar fitur.
3. Model Random Forest Classifier dilatih menggunakan data_training.csv.
4. Prediksi kualitas dilakukan pada data_testing.csv, dan hasil disimpan dalam format CSV yang hanya memuat 2 kolom: id dan quality.
