# 📊 Dashboard Analisis Kinerja UMKM Indonesia

> Dashboard interaktif menggunakan **Power BI** untuk menganalisis profil dan kinerja Usaha Mikro, Kecil, dan Menengah (UMKM) berdasarkan berbagai indikator bisnis seperti omzet, laba, marketplace, legalitas usaha, tenaga kerja, dan pelanggan.

---
## 📷 Dashboard

> **Tambahkan screenshot dashboard Power BI di bawah ini**

![Dashboard UMKM](images/<img width="4150" height="2400" alt="umkm" src="https://github.com/user-attachments/assets/9246c74a-52d1-4b8c-ba24-ebf7830025f9" />
umkm.png)
---

# 📖 Deskripsi Proyek

Proyek ini merupakan dashboard analisis data UMKM yang dibangun menggunakan **Microsoft Power BI**. Dashboard dirancang untuk membantu pengguna memahami kondisi dan karakteristik UMKM melalui visualisasi data yang interaktif.

Dataset yang digunakan merupakan **dataset publik dari Kaggle** yang berisi informasi mengenai berbagai UMKM di Indonesia, seperti jenis usaha, omzet, laba, aset, tenaga kerja, marketplace yang digunakan, status legalitas, tahun berdiri, hingga jumlah pelanggan.

Melalui dashboard ini pengguna dapat melakukan eksplorasi data menggunakan filter interaktif sehingga proses analisis menjadi lebih cepat dan mudah dipahami.

---

# 🎯 Tujuan Analisis

Dashboard ini dibuat untuk membantu menjawab beberapa pertanyaan bisnis berikut.

- Berapa total UMKM yang terdapat dalam dataset?
- Berapa total omzet seluruh UMKM?
- Berapa total laba yang dihasilkan UMKM?
- Berapa total pelanggan yang dimiliki UMKM?
- Bagaimana tren pertumbuhan UMKM berdasarkan tahun berdiri?
- Marketplace apa yang paling banyak digunakan oleh UMKM?
- Bagaimana distribusi status legalitas UMKM?
- Jenis usaha apa yang memiliki omzet terbesar?
- Bagaimana perbandingan tenaga kerja laki-laki dan perempuan pada setiap jenis usaha?
- Jenis usaha mana yang memiliki jumlah pelanggan terbanyak?

---

# 📂 Dataset

Dataset yang digunakan merupakan dataset publik dari Kaggle "https://www.kaggle.com/datasets/arumraa/dataset-umkm/data"

Dataset berisi informasi mengenai:

- ID UMKM
- Nama Usaha
- Jenis Usaha
- Tenaga Kerja Laki-laki
- Tenaga Kerja Perempuan
- Aset
- Omzet
- Laba
- Marketplace
- Status Legalitas
- Tahun Berdiri
- Kapasitas Produksi
- Biaya Karyawan
- Jumlah Pelanggan

---

# 🧹 Data Cleaning

Sebelum proses visualisasi dilakukan beberapa tahapan data cleaning, antara lain:

- Menghapus data yang memiliki **ID UMKM tidak valid**.
- Menangani missing value pada kolom kategorikal dengan mengganti nilai kosong menjadi **Unknown**.
- Mempertahankan nilai kosong pada kolom numerik sebagai **NULL** agar proses agregasi tetap akurat.
- Menyesuaikan tipe data numerik dan tanggal agar dapat digunakan dalam analisis Power BI.
- Memastikan konsistensi data sebelum proses visualisasi.

---

# 📊 Dashboard Overview

Dashboard terdiri dari beberapa komponen utama.

## 🔍 Filter (Slicer)

Dashboard menyediakan beberapa filter interaktif yang dapat digunakan untuk mengeksplorasi data.

- Jenis Usaha
- Marketplace
- Status Legalitas
- Tahun Berdiri

---

## 📌 Key Performance Indicators (KPI)

Dashboard menampilkan beberapa indikator utama, yaitu:

| KPI | Deskripsi |
|------|-----------|
| 📌 Total UMKM | Jumlah seluruh UMKM pada dataset |
| 💰 Total Omzet | Total omzet seluruh UMKM |
| 📈 Total Laba | Total laba seluruh UMKM |
| 👥 Total Pelanggan | Total pelanggan seluruh UMKM |

---

# 📈 Visualisasi Dashboard

Dashboard terdiri dari beberapa visualisasi berikut.

| Visualisasi | Tujuan Analisis |
|-------------|-----------------|
| 📈 Tren Pertumbuhan UMKM Berdasarkan Tahun Berdiri | Melihat perkembangan jumlah UMKM berdasarkan tahun berdiri |
| 📊 Jumlah UMKM Berdasarkan Marketplace | Mengetahui marketplace yang paling banyak digunakan UMKM |
| 📊 Total Omzet Berdasarkan Jenis Usaha | Membandingkan omzet setiap jenis usaha |
| 📊 Perbandingan Tenaga Kerja Laki-laki dan Perempuan Berdasarkan Jenis Usaha | Membandingkan komposisi tenaga kerja pada setiap jenis usaha |
| 🍩 Distribusi Status Legalitas UMKM | Mengetahui proporsi UMKM yang sudah dan belum memiliki legalitas |
| 📊 Total Pelanggan Berdasarkan Jenis Usaha | Mengetahui jenis usaha dengan jumlah pelanggan terbesar |

---

# ❓ Pertanyaan yang Dapat Dijawab Dashboard

Dashboard ini membantu menjawab berbagai pertanyaan bisnis, seperti:

### 📌 Gambaran Umum UMKM

- Berapa jumlah total UMKM yang tersedia pada dataset?
- Berapa total omzet yang dihasilkan seluruh UMKM?
- Berapa total laba yang diperoleh UMKM?
- Berapa total pelanggan yang dimiliki seluruh UMKM?

### 📈 Pertumbuhan UMKM

- Pada tahun berapa jumlah UMKM paling banyak berdiri?
- Bagaimana tren pertumbuhan UMKM dari tahun ke tahun?

### 🛒 Marketplace

- Marketplace apa yang paling banyak digunakan oleh UMKM?
- Apakah terdapat perbedaan jumlah UMKM pada setiap marketplace?

### 💰 Kinerja Bisnis

- Jenis usaha apa yang menghasilkan omzet terbesar?
- Bagaimana perbandingan omzet antar jenis usaha?

### 👥 Tenaga Kerja

- Bagaimana komposisi tenaga kerja laki-laki dan perempuan pada setiap jenis usaha?
- Jenis usaha mana yang memiliki tenaga kerja terbanyak?

### 📄 Legalitas

- Berapa persentase UMKM yang telah memiliki legalitas usaha?
- Berapa banyak UMKM yang belum memiliki legalitas?

### 🤝 Pelanggan

- Jenis usaha mana yang memiliki jumlah pelanggan terbanyak?
- Bagaimana distribusi pelanggan pada setiap jenis usaha?

---

# 💡 Insight yang Dapat Diperoleh

Dashboard ini dapat membantu pengguna untuk:

- Mengidentifikasi jenis usaha dengan omzet terbesar.
- Mengetahui marketplace yang paling banyak digunakan UMKM.
- Menganalisis pertumbuhan UMKM berdasarkan tahun berdiri.
- Membandingkan jumlah tenaga kerja laki-laki dan perempuan.
- Mengetahui distribusi legalitas UMKM.
- Mengidentifikasi jenis usaha dengan jumlah pelanggan terbesar.
- Mendukung proses pengambilan keputusan berbasis data melalui visualisasi interaktif.

---

# 🛠 Tools

- Microsoft Power BI
- Microsoft Excel

---

# 📚 Skills

- Data Cleaning
- Data Visualization
- Dashboard Development
- Business Intelligence
- Data Analysis
- Power Query
- Interactive Dashboard Design

---

# 🚀 Hasil Akhir

Dashboard ini dirancang untuk memberikan visualisasi yang interaktif, informatif, dan mudah dipahami sehingga pengguna dapat mengeksplorasi data UMKM berdasarkan berbagai kategori melalui filter yang tersedia. Dashboard juga dapat digunakan sebagai contoh implementasi Business Intelligence menggunakan Microsoft Power BI untuk kebutuhan analisis data.
