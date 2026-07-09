# Data Processing — Dari Data Mentah ke Data Siap Analisis

## 1. Struktur Data

| Kolom | Deskripsi |
|---|---|
| Segment | Segmen pelanggan (Government, Enterprise, Midmarket, Channel Partners) |
| Country | Negara penjualan (10 negara ASEAN) |
| Product | Nama produk (10 produk FMCG) |
| Discount Band | Kategori diskon |
| Units Sold | Jumlah unit terjual |
| Manufacturing Price | Harga produksi per unit |
| Sale Price | Harga jual per unit |
| Sales | Total penjualan (Units Sold × Sale Price) |
| COGS | Cost of Goods Sold |
| Profit | Sales − COGS |
| Date | Tanggal transaksi |
| %Profit | Margin keuntungan (kolom tambahan, dihitung di tahap Data Olah) |

## 2. Alur Kerja (Sheet by Sheet)

Workbook ini menggunakan pendekatan **layered sheet** — praktik umum di Excel untuk
memisahkan data mentah, data olahan, kalkulasi, dan tampilan akhir agar mudah
di-maintain dan diaudit:
Data Mentah  →  Data Olah  →  Calculation  →  Dashboard
(raw)         (cleaned)      (aggregasi)     (visual)

### Sheet "Data Mentah"
Data transaksi asli (50 baris sample awal), belum diproses. Format tanggal masih
berupa teks (`DD-MM-YYYY`) dan belum ada kolom margin keuntungan.

### Sheet "Data Olah"
Data lengkap (1.000 baris) yang sudah:
- Diformat ulang menjadi **Excel Table** (`Table1`) agar formula otomatis
  meluas ketika ada baris baru
- Kolom `Date` dikonversi ke tipe Date asli (bukan teks) agar bisa digunakan
  oleh fitur **Timeline** di dashboard
- Ditambahkan kolom **%Profit** dengan formula:

menggunakan **structured reference** (bukan cell reference biasa seperti
  `D2/H2`), sehingga lebih robust saat data bertambah.

### Sheet "Calculation"
Area kerja untuk agregasi manual sebelum divisualisasikan — total Sales, COGS,
Profit, dan Units Sold dikelompokkan per produk sebagai persiapan sebelum
dimasukkan ke PivotTable/Chart.

### Sheet "Dashboard" & "Dashboard (2)"
Tampilan akhir berisi 7 PivotTable, beberapa Chart, 2 Slicer (Segment, Country),
dan Timeline (Date) untuk eksplorasi data secara interaktif. Detail lengkap di
[`dashboard_overview.md`](dashboard_overview.md).

## 3. Ringkasan Angka (Full Dataset — 1.000 transaksi, tahun 2025)

| Metrik | Nilai |
|---|---|
| Total Sales | Rp 25.728.657.750 |
| Total COGS | Rp 20.583.516.064 |
| Total Profit | Rp 5.145.141.686 |
| Total Units Sold | 1.533.803 unit |
| Margin Profit Keseluruhan | ~20% |
| Jumlah Negara | 10 (ASEAN) |
| Jumlah Produk | 10 |
| Jumlah Segmen | 4 |
| Periode Data | 1 Januari 2025 – 31 Desember 2025 |

