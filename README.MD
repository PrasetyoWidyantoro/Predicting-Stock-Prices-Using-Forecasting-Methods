# Stock Price Prediction

* `Predicting Stock Prices` adalah sebuah proyek analisis data yang bertujuan untuk melakukan prediksi harga saham menggunakan eksperimen berbagai metode time series forecasting analysis, seperti ARIMA, FBprophet, Holtwinter, dan metode-metode lainnya. Dataset yang digunakan dalam proyek ini mencakup dua variabel utama, yaitu "Date" yang merepresentasikan tanggal penutupan, dan "Close" yang mencerminkan harga saham pada saat penutupan.

* Proses analisis dimulai dengan eksplorasi data, di mana kita melihat dan memahami karakteristik dari dataset, termasuk tren dan pola yang mungkin ada dalam harga saham. Setelah itu, kita akan memproses data dengan menyusun informasi tanggal dan harga penutupan untuk digunakan dalam pembangunan model.

* Berbagai metode time series forecasting analysis akan dieksplorasi dan diuji dalam memprediksi harga saham. Setiap metode akan dievaluasi dengan menggunakan metrik bisnis seperti "Mean Absolute Error (MAE)" untuk mengukur sejauh mana model dapat memprediksi harga saham yang mendekati nilai sebenarnya.

* Dengan memanfaatkan MAE sebagai metrik evaluasi, proyek ini akan memberikan pemahaman yang mendalam tentang seberapa baik setiap metode forecasting dapat digunakan untuk prediksi harga saham. Semakin kecil nilai MAE, semakin baik model dalam memberikan perkiraan harga yang akurat.

* Dengan penekanan pada metrik bisnis, proyek ini dapat memberikan pandangan yang lebih holistik dan informatif tentang kinerja berbagai metode forecasting dalam konteks prediksi harga saham. Informasi ini dapat memberikan nilai tambah bagi investor, analis keuangan, dan pelaku pasar untuk membuat keputusan investasi yang lebih cerdas dan informasional di pasar saham.

## Kesimpulan

* Hasil eksperimentasi model antara ARIMA, ARMA, Damped trend, Holtwinter Exponential Smoothing, FBProphet, Double Moving Averages, Brown satu parameter, dan Pemodelan ARMA jika dibandingkan metrics MAE, maka model FBprophet memiliki MAE yang cukup baik untuk memprediksi kasus kali ini yakni dengan MAE sebesar `MAE: 2.20`

## Further Research

* Dapat dicoba dengan menambahkan variabel lain, misalnya suku bunga acuan, ihk, inflasi, kurs, dan saham dengan satu bidang atau sektor serta variabel lainnya untuk membantu memprediksi harga saham tersebut
* kalau data tambahan diatas sudah tersedia bisa dibuatkan lagged terlebih dahulu lalu bisa dilanjutkan dengan model ARIMA bahkan dapat juga dicoba untuk menggunakan model LSTM dan GRU
* bisa juga ditambahkan dengan metode lain seperti ARCH karena Karena bisa jadi LM test signifikan pada lag-lag awal (short memory)
