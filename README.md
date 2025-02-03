# Data-Analytics
Performance Analytics; Analisis kinerja bisnis Kimia Farma Tahun 2020-2023

📌 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis kinerja Kimia Farma dari tahun 2020 hingga 2023 dengan menggunakan Google BigQuery dan Google Looker Studio. Analisis ini mencakup berbagai aspek bisnis, termasuk transaksi, pendapatan, profitabilitas, dan performa cabang.

📊 Tujuan Analisis
Menganalisis pendapatan tahunan Kimia Farma untuk melihat tren pertumbuhan bisnis.
Mengidentifikasi cabang dengan performa terbaik dan terburuk berdasarkan transaksi dan pendapatan.
Menampilkan data dalam visualisasi yang interaktif melalui Looker Studio untuk memudahkan pengambilan keputusan.

🛠 Teknologi yang Digunakan
Google BigQuery (untuk pengolahan dan transformasi data)
Google Looker Studio (untuk visualisasi dan dashboard)
SQL (untuk ekstraksi dan transformasi data)

📂 Struktur Data
Dataset utama yang digunakan dalam analisis ini adalah kimia_farma, yang terdiri dari beberapa tabel:
kf_final_transaction → Data transaksi pelanggan
kf_kantor_cabang → Data cabang dan lokasi
kf_product → Data produk dan harga
kf_inventory -> Data inventory produk
kf_analisis → Tabel hasil transformasi untuk analisis lebih lanjut

🔍 Hasil Analisis
Dashboard Looker Studio yang dibuat mencakup:
- Perbandingan pendapatan dari tahun ke tahun 
- Top 10 cabang dengan total transaksi terbanyak
- Top 10 cabang dengan nett sales tertinggi
- Top 5 cabang dengan rating tertinggi dan transaksi terendah
- Geo Map untuk distribusi total profit
- Summary dan snapshot data untuk insight lebih cepat
