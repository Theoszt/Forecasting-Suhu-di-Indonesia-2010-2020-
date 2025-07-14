
# Forecasting Suhu di Indonesia (2010-2020)

Proyek ini berfokus pada **analisis dan peramalan (forecasting) suhu rata-rata di Indonesia** untuk periode tahun **2010 hingga 2020**. Data yang digunakan berasal dari **BMKG (Badan Meteorologi, Klimatologi, dan Geofisika Indonesia)** dan tersedia di Kaggle.

## 📊 Sumber Data

* **Badan Meteorologi, Klimatologi, dan Geofisika (BMKG)**
  [https://dataonline.bmkg.go.id/](https://dataonline.bmkg.go.id/)

* **Indonesia Climate Dataset (Kaggle)**
  [https://www.kaggle.com/datasets/greegtitan/indonesia-climate](https://www.kaggle.com/datasets/greegtitan/indonesia-climate)

---

## 🎯 Tujuan Proyek

* **Eksplorasi Data (EDA)**
  Menganalisis pola suhu, tren, dan anomali selama 2010–2020.

* **Pra-pemrosesan Data**
  Membersihkan data, mengatasi *missing values*,Data aggregation, Transformation Data, dan menyiapkan data untuk model deret waktu.

* **Peramalan (Forecasting)**
  Melatih model peramalan suhu dengan metode ARIMA/SVR/SARIMA *(sesuaikan dengan model yang digunakan)*.

* **Evaluasi Model**
  Menggunakan metrik seperti MAE, MSE, dan RMSE.

* **Visualisasi**
  Menampilkan grafik suhu aktual dan prediksi.

---

## 📈 Insight dari Data

Berikut adalah salah satu visualisasi hasil pengolahan data suhu di Indonesia:

### 📊 Insight Forecasting Rata-rata 2010–2020

![Tren Suhu Indonesia](Insight_DataMining.png)

**Insight**:

* Terjadi **tren kenaikan suhu** secara bertahap dari tahun 2010 hingga 2020.
* Prediksi Untuk tahun 2021 yang daerah mencapai suhu tertinggi

---

## 🗂️ Struktur Repositori

```
├── Datmin.ipynb                     # Notebook utama
├── Data_iklim.csv                   # Dataset suhu
├── Insight_DataMining.png           # Poster Inseght yang diambil
├── README.md                        # Dokumentasi proyek
```

---
