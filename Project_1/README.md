# ☕ Coffee Shop Sales Dashboard (Power BI Project)

Sebuah proyek analisis berbasis data transaksi penjualan toko kopi. Fokus utama proyek ini adalah **mengidentifikasi pola penjualan, memahami performa produk, dan mengevaluasi efektivitas lokasi toko** untuk mendukung pengambilan keputusan bisnis.
Proyek ini menggunakan dataset transaksi fiktif dari coffee shop yang disediakan oleh Maven Analytics. Tujuannya adalah mengubah data mentah menjadi visualisasi interaktif yang memberikan insight bisnis terkait performa penjualan berdasarkan lokasi toko, kategori produk, dan waktu.

## PREVIEW (Tunggu Beberapa Saat)
![CoffeeDashboard1](https://github.com/user-attachments/assets/6fb9e396-a4d7-46f3-9c8a-dbdf9ed3e6b2)



---

## 🧩 Business Problem

> Manajemen ingin memahami **kapan dan di mana** penjualan paling tinggi, serta **produk apa saja** yang paling menguntungkan. Mereka juga ingin tahu apakah semua lokasi memiliki performa yang seimbang, dan bagaimana perilaku pembelian pelanggan berubah berdasarkan waktu.

---

## 💡 Business Questions
1. Di jam berapa penjualan paling tinggi terjadi?
2. Lokasi toko mana yang paling menghasilkan revenue?
3. Produk dan kategori apa yang paling populer?
4. Adakah perbedaan performa penjualan antara hari kerja dan akhir pekan?
5. Apakah ada waktu-waktu yang bisa digunakan untuk promo karena penjualannya rendah?

---


## 🛠️ How I Solved It (Analytical Approach)

### ✅ Data Preparation
- Menambahkan kolom kalkulasi seperti `total_sales`, `hour`, `day_name`, dan `month`
- Membersihkan data dan memeriksa data hilang (tidak ditemukan)

### ✅ Dashboard & Insight
- Membuat dashboard interaktif Power BI dengan:
  - Slicer untuk memfilter berdasarkan `store` dan `kategori produk`
    ![Capture](https://github.com/user-attachments/assets/5fcc6f29-2573-47fe-8751-6d17214159fc)

  - KPI cards: total transaksi, revenue, Total barang terjual
    ![asd](https://github.com/user-attachments/assets/7cb7d184-1e2b-41e6-83de-ef908d2b03ff)
  - Visualisasi tren per jam dan hari
  - Analisis lokasi dan kategori produk

---

## 📈 Key Insights
Analisis ini tidak hanya menyajikan data, tetapi juga menghasilkan rekomendasi berbasis insight untuk mendukung pengambilan keputusan bisnis. Berikut beberapa contoh problem solving yang ditemukan berdasarkan dashboard Power BI:

1. Penjualan Tertinggi Jam 8–10 Pagi
   
 ![Rev Hour](https://github.com/user-attachments/assets/5c0903e3-22af-43eb-b9f4-e8dca4b5c265)
 - Insight: Penjualan tertinggi terjadi antara pukul 08.00–10.00.
 - *Asumsi*: Pelanggan cenderung membeli kopi di pagi hari sebelum berangkat kerja.
 - *Solusi*:
  - Menawarkan promo khusus pagi hari (contoh: beli kopi + pastry dengan harga spesial).
  - Menambah barista/kasir di jam sibuk untuk efisiensi layanan.
  - Menyediakan layanan pre-order untuk pelanggan tetap.

3. Revenue Tertinggi Hari Senin & Jumat

  ![Rev Day](https://github.com/user-attachments/assets/fa2c206a-f19e-4327-8037-0f51a9e4e530)
  - Insight: Senin dan Jumat mencatat pendapatan tertinggi. Sabtu dan Minggu justru paling rendah.
  - *Asumsi*: Aktivitas kantor mendorong pelanggan membeli kopi di weekday, sementara weekend lebih sepi.
  - *Solusi*:
    - Fokuskan promosi weekday (contoh: "Monday Mood Booster" atau "Friday Treat").
    - Manfaatkan weekend untuk testing menu baru atau bundling keluarga.
    - Dorong penjualan online/delivery saat weekend.

3. Toko dengan Penjualan Tertinggi Didominasi oleh Produk Kopi
   
![rev prduct](https://github.com/user-attachments/assets/2c90742f-598f-4deb-8097-c65d8f610e32)
- Insight: Semua toko dengan penjualan tertinggi (termasuk Hell’s Kitchen dan Lower Manhattan) memiliki kategori kopi sebagai kontributor utama pendapatan.
- *Asumsi*: Kopi adalah produk utama yang paling diminati pelanggan.
- *Solusi*:
  - Tingkatkan variasi kopi (ukuran, rasa, seasonal).
  - Kembangkan strategi upselling dengan pairing produk (kopi + bakery).
  - Pasang display visual khusus kopi di toko.

4. Hell’s Kitchen Mencatatkan Revenue Tertinggi
- Insight: Walaupun quantity terjual sama dengan Lower Manhattan (72k), Hell’s Kitchen menghasilkan revenue lebih besar (50.74k vs 47.78k).
- *Asumsi*: Produk yang dijual di Hell’s Kitchen cenderung lebih mahal atau premium.
- *Solusi*:
  - Terapkan strategi produk premium di store lain.
  - Benchmark strategi Hell’s Kitchen (penataan produk, pricing).
  - Buat program loyalitas bagi pelanggan yang membeli produk high-end.

7. Produk Terlaris per Kategori
- Insight Produk Unggulan:
- Coffee: Barista Espresso
- Tea: Brewed Chai Tea
- Bakery: Scone
- Chocolate: Hot Chocolate
- Coffee Beans: Premium Beans
- Branded: Housewares
- Loose Tea: Chai Tea
- Flavour: Regular Syrup
- Packaged Chocolate: Drinking Chocolate
- *Asumsi*: Setiap kategori memiliki “produk bintang” yang konsisten dipilih pelanggan.
- *Solusi*:
  - Prioritaskan display dan promosi produk unggulan tiap kategori.
  - Lakukan analisis margin untuk memastikan profitabilitas.
  - Kembangkan strategi upsell/cross-sell berbasis produk unggulan.

---

## 🎯 Impact

Dashboard ini memberikan landasan bagi manajemen untuk:
- Merancang **strategi promo berbasis waktu**
- **Memfokuskan stok** dan staf di jam/jumlah tertinggi
- Mengevaluasi **performa masing-masing lokasi** untuk pengembangan cabang

---

