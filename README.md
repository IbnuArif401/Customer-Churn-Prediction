# 📊 Customer Churn Prediction (End-to-End ML)

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk memprediksi apakah seorang pelanggan akan berhenti berlangganan (*churn*) menggunakan Machine Learning. Ini adalah salah satu kasus penggunaan nyata di industri telekomunikasi untuk meningkatkan retensi pelanggan.

## 🛠️ Langkah yang Dilakukan:
1. **Data Cleaning:** Menghapus kolom yang tidak relevan (customerID) dan memperbaiki tipe data `TotalCharges`.
2. **Preprocessing:** Mengubah data kategori menjadi angka dengan *One-Hot Encoding*.
3. **Modeling:** Menggunakan algoritma **Random Forest Classifier**.
4. **Evaluation:** Mendapatkan akurasi sekitar 80%.

## 📈 Kesimpulan Utama:
*   Faktor biaya (**MonthlyCharges** & **TotalCharges**) sangat berpengaruh terhadap keputusan pelanggan untuk pergi.
*   Pelanggan dengan kontrak bulanan memiliki tingkat *churn* yang lebih tinggi dibandingkan kontrak tahunan.

## 🚀 Cara Menggunakan:
Buka file `customer-churn-prediction.ipynb` untuk melihat kode lengkap dan visualisasinya.
