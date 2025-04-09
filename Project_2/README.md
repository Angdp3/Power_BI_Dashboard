# 📊 Customer Risk Analysis Dashboard

## Preview (Tunggu Beberapa Saat)
![Customer Risk](https://github.com/user-attachments/assets/19f7c9e4-7ea4-4ea4-a004-7531c7660ec4)

## 📌 Deskripsi Proyek
Dashboard ini dirancang menggunakan Microsoft Power BI untuk menganalisis risiko churn pelanggan pada perusahaan layanan internet. Visualisasi ini membantu dalam mengidentifikasi segmentasi pelanggan yang paling rentan berhenti berlangganan, serta memberikan insight untuk strategi retensi yang lebih terfokus.

### Tools & Skills Digunakan
- Microsoft Power BI
- Data Cleaning & Data Modeling
- DAX Expressions
- Exploratory Data Analysis

### Tujuan Analisis
- Mengukur churn rate berdasarkan kontrak, metode pembayaran, dan jenis layanan internet.
- Mengetahui potensi kerugian finansial dari pelanggan yang churn.
- Memberikan insight tentang faktor-faktor yang paling berkontribusi terhadap churn.

### Insight Kritis
- churn rate tertinggi pada pelanggan dengan kontrak month-to-month dan service Fiber Optic → menandakan loyalitas yang sangat rendah pada tipe kontrak dan layanan ini.
- Pelanggan yang menggunakan "Fiber optic" merupakan Terbanyak (3k), namun tetap memiliki churn tinggi → menunjukkan bahwa kualitas layanan belum tentu menjamin retensi.
- Metode pembayaran via Electric Check menjadi metode populer, tetapi juga memiliki nilai churn dan revenue tinggi, perlu pendekatan retensi khusus.
- Total potensi revenue loss sebesar $2.86M jika pelanggan churn tidak dicegah.
- Semakin lama masa kontrak, semakin rendah churn-nya → terbukti pelanggan dengan kontrak ≥2 tahun lebih loyal, disarankan memperluas penawaran kontrak panjang.

### Problem Solving & Rekomendasi
- Perusahaan dapat memberikan insentif bagi pelanggan month-to-month untuk berpindah ke kontrak tahunan atau dua tahun.
- Evaluasi kualitas layanan internet fiber optic yang meskipun banyak digunakan, tetap memiliki churn tinggi.
- Buat program loyalitas berdasarkan metode pembayaran dan histori pembayaran untuk pelanggan dengan potensi nilai tinggi.
- Implementasi churn prediction model berbasis ML bisa menjadi langkah lanjutan untuk pencegahan lebih dini.


