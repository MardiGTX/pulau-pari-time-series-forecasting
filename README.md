<p align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Statsmodels-ARIMA-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Time%20Series-Forecasting-success?style=for-the-badge"/>

</p>

---

## 📌 Gambaran Proyek

Proyek ini merupakan latihan **time series forecasting** menggunakan metode **ARIMA (AutoRegressive Integrated Moving Average)** untuk memprediksi pola jumlah pengunjung berdasarkan data historis.

Proses forecasting dilakukan dengan menganalisis pola data historis, melakukan pengujian stasioneritas (*stationarity test*), mencari parameter terbaik menggunakan nilai **AIC**, membangun model ARIMA, dan melakukan prediksi untuk periode selanjutnya.

Data yang digunakan memiliki frekuensi mingguan (*weekly frequency*) sehingga hasil prediksi digunakan untuk melihat pola perubahan jumlah pengunjung pada periode mendatang.

---

## 🎯 Tujuan Proyek

- Melakukan analisis data time series  
- Menguji apakah data bersifat stationer menggunakan **ADF Test**  
- Menentukan parameter terbaik **(p,d,q)** menggunakan nilai **AIC**  
- Membangun model forecasting menggunakan **ARIMA**  
- Melakukan prediksi jumlah pengunjung berdasarkan pola historis data  

---

## 🛠 Tech Stack

| Tools | Fungsi |
|--------|--------|
| Python | Bahasa pemrograman utama |
| Pandas | Pengolahan data time series |
| Statsmodels | Pembuatan model ARIMA |
| Matplotlib | Visualisasi data dan hasil prediksi |

---

## ⚙️ Alur Pengerjaan

1. Melakukan eksplorasi data time series  
2. Mengecek stasioneritas data menggunakan **ADF Test**  
3. Menentukan parameter terbaik **(p,d,q)** berdasarkan nilai **AIC terkecil**  
4. Membangun model **ARIMA** berdasarkan parameter terbaik  
5. Melakukan evaluasi model menggunakan **MSE** dan **MAE**  
6. Membandingkan hasil prediksi dengan data aktual  
7. Melakukan forecasting untuk melihat pola prediksi periode berikutnya

---

## 📦 Data yang Digunakan

Data yang digunakan berupa data time series jumlah pengunjung dengan frekuensi:

| Data | Deskripsi |
|------|------------|
| Weekly Visitor Data | Jumlah pengunjung mingguan |
| Historical Trend | Pola historis jumlah pengunjung |

---

## ▶️ Cara Menjalankan

1. Buka notebook menggunakan **Jupyter Notebook** atau **Google Colab**  
2. Jalankan setiap cell secara berurutan  
3. Lakukan pengecekan stasioneritas menggunakan **ADF Test**  
4. Cari parameter terbaik ARIMA menggunakan **AIC**  
5. Jalankan forecasting dan visualisasi hasil prediksi

---

## 📈 Hasil Analisis

Hasil prediksi menunjukkan bahwa model ARIMA mampu mengikuti pola historis data dengan cukup baik pada periode observasi. Namun, model masih memiliki keterbatasan dalam menangkap lonjakan ekstrem pada periode tertentu sehingga hasil forecast jangka panjang cenderung mengikuti rata-rata pola historis sebelumnya.

---

## 👨‍💻 Author

**Mardi Wicaksana**  
Data Analyst Enthusiast | SQL | Python | Data Analysis | Time Series Forecasting