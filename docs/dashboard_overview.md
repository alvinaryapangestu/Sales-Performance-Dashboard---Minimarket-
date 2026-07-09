# Dashboard Overview — Fitur Interaktif Excel

Dashboard dibangun sepenuhnya di Excel menggunakan kombinasi **PivotTable,
PivotChart, Slicer, dan Timeline** — tanpa tools eksternal — untuk menghasilkan
pengalaman eksplorasi data yang interaktif langsung di dalam spreadsheet.

## 1. PivotTable (7 buah)

Ketujuh PivotTable menjadi sumber data untuk seluruh visual di dashboard,
masing-masing meng-agregasi metrik berbeda:

| PivotTable | Fungsi |
|---|---|
| PivotTable1 | Sum of Sales & COGS per dimensi (Segment/Country/Product) |
| PivotTable2 | Sum of Sales & Units Sold |
| PivotTable3–5 | Sum of Units Sold per berbagai breakdown |
| PivotTable6–7 | Sum of Sales & COGS untuk chart pendukung |

## 2. Chart

- **"Quantity Sold in 2025"** — tren jumlah unit terjual sepanjang tahun
- **"Quantity Sold by Country"** — perbandingan volume penjualan antar 10 negara ASEAN

## 3. Slicer (Filter Interaktif)

- **Segment** — filter cepat berdasarkan Government / Enterprise / Midmarket / Channel Partners
- **Country** — filter cepat berdasarkan salah satu dari 10 negara

Slicer memungkinkan pengguna dashboard mengeksplorasi data tanpa perlu
mengedit PivotTable secara manual — cukup klik kategori yang diinginkan.

## 4. Timeline

- **Date** — navigasi data berdasarkan rentang waktu (bulan/kuartal), terhubung
  langsung ke seluruh PivotTable & Chart sehingga semua visual ter-update
  otomatis saat rentang tanggal diubah.

## 5. Cara Menggunakan Dashboard

1. Buka file `dashboard/dashboard_sales_minimarket.xlsx`
2. Masuk ke sheet **Dashboard**
3. Gunakan Slicer di bagian atas untuk filter Segment atau Country tertentu
4. Geser Timeline untuk melihat tren di periode waktu spesifik
5. Seluruh chart & angka akan otomatis ter-update mengikuti filter yang dipilih

## 6. Screenshot
> ![Dashboard Overview](docs/screenshots/dashboard1.png)
