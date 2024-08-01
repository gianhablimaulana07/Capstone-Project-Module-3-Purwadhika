# Capstone-Project-Module-3-Purwadhika

## Study Case: Saudi Arabia Used Cars
Studi kasus ini merupakan Capstone Project Modul 3 Job Connector Data Scientist and Machine Learning dari Purwadhika Digital Technology School.

Pemilik : Gian Habli Maulana

Tanggal : 16 Juli 2024 - 04 Agustus 2024

## Business Problem
### Context
Seiring dengan pertumbuhan populasi dan urbanisasi di Arab Saudi, kebutuhan akan mobil sebagai alat transportasi semakin meningkat. Mobil tidak hanya berfungsi sebagai sarana mobilisasi individu, tetapi juga sebagai alat untuk pengiriman barang. Selain itu, rendahnya biaya bahan bakar dan iklim yang kurang mendukung penggunaan sepeda motor menjadikan mobil sebagai pilihan utama bagi masyarakat Arab Saudi.

Dalam beberapa tahun terakhir, pasar mobil bekas di Arab Saudi telah berkembang pesat akibat meningkatnya permintaan akan kendaraan yang terjangkau. Calon pembeli mobil di Arab Saudi cenderung mencari penawaran terbaik dengan mempertimbangkan berbagai faktor seperti merek, model, tahun pembuatan, kondisi, dan harga. Namun, karena adanya keragaman dalam spesifikasi dan kondisi mobil, calon pembeli sering kali kesulitan untuk menilai harga yang adil untuk kendaraan yang mereka minati. Oleh karena itu, perusahaan yang beroperasi di sektor otomotif, baik itu platform jual beli mobil atau dealer, perlu memahami faktor-faktor yang mempengaruhi harga mobil bekas.

### Problem Statement
Dalam pasar mobil bekas di Arab Saudi, salah satu tantangan utama adalah menentukan harga jual yang kompetitif dan akurat bagi kendaraan yang akan dipasarkan. Data yang tidak konsisten dan beragam tentang harga mobil bekas mengakibatkan kesulitan bagi pembeli dan penjual dalam mengambil keputusan yang tepat. Konsumen sering kali bingung apakah harga yang mereka tawarkan atau diterima sesuai dengan tren pasar saat ini. Selain itu, penjual membutuhkan panduan untuk menetapkan harga yang wajar agar bisa bersaing di pasar, tanpa merugikan diri mereka sendiri.

Oleh karena itu, perlu dikembangkan model machine learning untuk memprediksi harga mobil bekas yang didasarkan pada berbagai fitur seperti merek, model, tahun produksi, tipe mesin, kilometer yang telah ditempuh, dan kondisi mobil. Dengan pendekatan ini, diharapkan model bisa memberikan estimasi yang akurat mengenai harga, sehingga pembeli dapat membuat keputusan yang lebih informasi dan penjual dapat menetapkan harga jual yang sesuai dengan kondisi pasar.

### Goals
1. Mengembangkan Model Prediksi Harga:
- Menggunakan algoritma machine learning untuk memprediksi harga mobil bekas berdasarkan fitur-fitur yang tersedia dalam dataset.
- Mencapai akurasi model prediksi yang tinggi sehingga dapat memberikan informasi harga yang akurat.

2. Meningkatkan Efisiensi Penentuan Harga:
- Mengurangi waktu penelitian dan perbandingan harga yang dilakukan oleh pembeli dan penjual dengan memberikan estimasi harga yang cepat.
- Memberikan solusi otomatisasi dalam penetapan harga yang bisa diakses kapan saja dan di mana saja.

3. Meningkatkan Kepercayaan Pasar:
- Membangun kepercayaan di antara pembeli dan penjual dengan menyediakan estimasi harga yang bersifat transparan dan dapat dipertanggungjawabkan.

4. Menarik Pelanggan Potensial:
- Menarik lebih banyak pengguna ke platform jual beli mobil bekas dengan menawarkan harga yang sesuai dan kompetitif, sehingga dapat meningkatkan volume transaksi.

### Key Stakeholders
1. Pemilik Bisnis (Dealers / Penjual Mobil):
Memanfaatkan hasil prediksi untuk menentukan harga jual mobil bekas yang kompetitif.

2. Konsumen:
Individu yang mencari informasi tentang harga mobil bekas dan diharapkan terbantu melalui rekomendasi harga yang akurat.

3. Pemasar:
Menggunakan data dan prediksi untuk strategi pemasaran dan pemahaman pasar.

### Analytic Approach
Prediksi Nilai Price Menggunakan Model Regresi

1. Preprocessing Data:
- Cleaning Data: Menangani missing values, duplikasi, dan outliers.
- Feature Engineering: Pengkodean kategori, normalisasi, atau skala fitur numerik.

2. Exploratory Data Analysis (EDA):
- Menggunakan visualisasi untuk memahami distribusi harga dan hubungan antar fitur.
- Identifikasi fitur yang memiliki pengaruh signifikan terhadap Price, seperti Year, Make, Type, Engine Size, Mileage, Options, Gear Type, Origin, dan Region.

3. Pemilihan Model:
Mencoba beberapa algoritma machine learning seperti:
 - Linear Regression
 - KNN Regressor
 - Decision Tree Regression
 - Ridge Regression
 - Lasso Regression
 - ElasticNet
 - Random Forest Regression
 - Xtreme Gradient Boosting Regression
 - LightGBM Regressor
 - CatBoostRegressor

4. Pengaturan Parameter dan Validasi:
Menggunakan teknik seperti cross-validation untuk menghindari overfitting dan memilih hyperparameter yang optimal.

5. Evaluasi Model:
Menggunakan data uji untuk mengevaluasi kinerja model yang telah dibangun.

### Evaluation Metric
Beberapa Evaluation Metric yang digunakan dalam model ini diantaranya adalah sebagai berikut.
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)
- RMSE(Root Mean Squared Error)
- R² (R-squared)
Nilai Evaluation Metric diatas dari setiap model akan diperbandingkan dan akan dipilih nilai Evaluation Metric yang sesuai dengan karakteristik data sebagai pengambilan keputusan model terbaik.
