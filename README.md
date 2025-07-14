# 🚀 Analisis Segmentasi Pelanggan & Diskon SaaS AWS: Memaksimalkan Penjualan dan Keuntungan\!

Proyek ini adalah puncak dari perjalanan saya di Bootcamp Data Analyst DQLab Batch 16\! 

## 🎯 Tujuan Proyek

Misi utama kami adalah:

  * Mengidentifikasi segmen pelanggan yang berbeda (High, Medium, Low Sales).
  * Menganalisis bagaimana berbagai tingkat diskon memengaruhi penjualan dan keuntungan di setiap segmen.
  * Merumuskan strategi diskon yang tepat sasaran untuk mendorong pertumbuhan penjualan, terutama pada segmen pelanggan "Medium Sales" dan "Low Sales", sambil menjaga profitabilitas tetap positif.

## ❓ Permasalahan yang Dipecahkan

Bagaimana cara AWS mengoptimalkan strategi diskonnya untuk mendorong penjualan tanpa mengorbankan profit, terutama bagi pelanggan dengan penjualan menengah dan rendah? Proyek ini menjawab pertanyaan kunci:

1.  Siapa saja pelanggan yang masuk kategori penjualan tinggi, sedang, dan rendah?
2.  Bagaimana hubungan antara diskon yang diberikan dengan penjualan dan keuntungan pada setiap kategori pelanggan ini?

## 📊 Sumber Data

Data transaksi AWS SaaS (penjualan, keuntungan, diskon) dari tahun 2020 hingga 2023.

  * **Dataset**: `SaaS-Sales.csv` (diunduh dari Kaggle).

## 💡 Garis Besar Analisis Data & Insight Utama

Kami melakukan eksplorasi data mendalam, pembersihan, dan analisis statistik untuk mengungkap pola-pola penting:

### **1. Kinerja Penjualan & Keuntungan**

  * **Penjualan**: Menunjukkan tren kenaikan yang kuat dari tahun 2022 hingga 2023, dengan kinerja kuartalan dan semesteran yang positif.
  * **Keuntungan**: Mengalami peningkatan yang konsisten dari tahun ke tahun. Namun, terdapat fluktuasi bulanan dan kuartalan yang menunjukkan area untuk optimasi.

### **2. Dampak Diskon pada Profitabilitas**

  * **Korelasi Negatif**: Ditemukan korelasi negatif yang signifikan antara diskon dan profit (-0.54), yang berarti semakin besar diskon, semakin rendah keuntungan.
  * **Kerugian**: Diskon besar dapat menyebabkan keuntungan negatif. Sebesar 18.72% dari total transaksi menunjukkan kerugian.
  * **Tren Diskon**: Diskon 20% adalah yang paling umum, dengan puncak pemberian diskon pada bulan September dan November (musim diskon).

### **3. Segmentasi Pelanggan Berdasarkan Penjualan**

Kami mengelompokkan pelanggan berdasarkan rentang penjualan interquartile:

  * **High Sales Segment**: Diskon bervariasi antara 0.3 hingga 0.6, dengan fokus sekitar 0.5.
  * **Medium Sales Segment**: Cenderung menggunakan diskon lebih tinggi, sekitar 0.4 hingga 0.6.
  * **Low Sales Segment**: Juga cenderung menggunakan diskon lebih tinggi, sekitar 0.4 hingga 0.6.

### **4. Menemukan Diskon "Sweet Spot"**

  * **Profit Positif Terjaga**: Pelanggan dengan profit tertinggi cenderung menggunakan diskon sekitar 0.4 hingga 0.5.
  * **Keseimbangan Optimal**: Diskon antara **50% hingga 60%** menunjukkan keseimbangan terbaik antara menjaga penjualan tetap tinggi dan keuntungan tetap positif. **Diskon 50% adalah pilihan teraman** untuk menghindari kerugian.

## 🛠️ Rekomendasi Strategis

Berdasarkan insight yang ditemukan, kami merekomendasikan:

  * **Batas Maksimum Diskon**: Terapkan batas maksimum diskon **50%**. Pemberian diskon di atas angka ini secara signifikan menurunkan profitabilitas.
  * **Strategi Diskon Bertahap**: Implementasikan strategi diskon berjenjang (hingga 50% maksimal) yang terkait dengan penggunaan layanan yang lebih banyak (`Pay less by using more`) atau pembelian paket layanan (`Bundled Discounts`). Ini dapat mendorong peningkatan pembelian.
  * **Personalisasi Diskon**: Kembangkan strategi diskon yang dipersonalisasi khusus untuk setiap segmen pelanggan, terutama untuk segmen "Medium Sales" dan "Low Sales" untuk mendorong pertumbuhan penjualan secara optimal.

## 🔗 Tautan Penting

  * **Dashboard Interaktif**: Lihat hasil analisis secara visual di [Looker Studio Dashboard](https://www.google.com/search?q=https://lookerstudio.google.com/reporting/a10a4fdd-42c5-4b0d-834b-57fcfa41ecaf)
  * **Dataset Mentah**: Unduh data yang digunakan untuk analisis dari [SaaS-Sales.csv](https://www.google.com/search?q=https://github.com/rahmawtnisa/ProjectDQLab_BNSP/blob/main/SaaS-Sales.csv)
  * **Kode Analisis**: Telusuri langkah-langkah analisis kami di [Code\_AWS\_SaaS.ipynb](https://www.google.com/search?q=https://github.com/rahmawtnisa/ProjectDQLab_BNSP/blob/main/Code_AWS_SaaS.ipynb)

## 👤 Kontak

**Rahmawati Annisa Salsadilla**
Email: rahmawati.salsadila@gmail.com
