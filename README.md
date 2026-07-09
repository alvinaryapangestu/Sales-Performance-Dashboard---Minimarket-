# 📊 Sales Performance Dashboard — Minimarket (Excel)

[![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?logo=microsoftexcel&logoColor=white)]()
[![PivotTable](https://img.shields.io/badge/Feature-PivotTable%20%7C%20Slicer%20%7C%20Timeline-2E7D32)]()
[![Status](https://img.shields.io/badge/status-completed-brightgreen)]()

## 📌 Overview

Dashboard analisis performa penjualan produk **FMCG (Fast-Moving Consumer
Goods)** untuk jaringan minimarket di **10 negara ASEAN**, dibangun sepenuhnya
menggunakan **Microsoft Excel** — memanfaatkan PivotTable, PivotChart, Slicer,
dan Timeline untuk menghasilkan dashboard interaktif tanpa tools eksternal.

Dataset mencakup 1.000 transaksi penjualan sepanjang tahun 2025 dari 10 produk
(Indomie, Ultra Milk, Chitato, Biskuat, Aqua, dll), 4 segmen pelanggan, dan
10 negara.

## 🎯 Business Problem

Manajemen membutuhkan cara cepat untuk memonitor performa penjualan lintas
produk, negara, dan segmen pelanggan — tanpa harus membuka laporan mentah
setiap kali ingin menjawab pertanyaan bisnis seperti "negara mana yang paling
kontributif?" atau "bagaimana tren penjualan bulan ini?". Dashboard ini
dirancang untuk menjawab kebutuhan tersebut secara real-time dan self-service.

## 🛠️ Tools & Skills

| Kategori | Tools/Skills |
|---|---|
| Tools | Microsoft Excel |
| Fitur Excel | PivotTable, PivotChart, Slicer, Timeline, Excel Table, Structured Reference Formula |
| Analysis | Data Cleaning, Aggregation, Business Insight |

## 📂 Struktur Repository
```
sales-dashboard-minimarket-excel/
├── data/
│   ├── raw/                    -> data_mentah.csv (data transaksi awal)
│   └── processed/               -> data_olah.csv (data bersih + kolom %Profit)
├── dashboard/
│   └── dashboard_sales_minimarket.xlsx  -> file dashboard Excel lengkap
├── docs/
│   ├── data_processing.md       -> alur pengolahan data (Data Mentah -> Dashboard)
│   ├── dashboard_overview.md    -> penjelasan PivotTable, Slicer, Timeline, Chart
│   ├── business_recommendation.md
│   └── screenshots/
└── README.md
```


## 🔍 Proses Pengerjaan

### 1. Data Processing
Data mentah dibersihkan dan distrukturkan menjadi Excel Table, termasuk
penambahan kolom %Profit menggunakan formula structured reference. Detail:
[`docs/data_processing.md`](docs/data_processing.md)

### 2. Dashboard Interaktif
Dashboard dibangun dengan 7 PivotTable, beberapa PivotChart, 2 Slicer
(Segment & Country), dan 1 Timeline (Date) yang saling terhubung. Detail:
[`docs/dashboard_overview.md`](docs/dashboard_overview.md)

### 3. Business Recommendation
Insight kunci: Malaysia & Indonesia adalah pasar terbesar, segmen Midmarket
paling kontributif, dan terdapat pola musiman jelas di Desember-Januari.
Detail lengkap & rekomendasi strategis:
[`docs/business_recommendation.md`](docs/business_recommendation.md)

## 📈 Key Insights (Ringkas)

- 💰 Total Sales: **Rp 25.728.657.750**
- 📦 Total Units Terjual: **1.533.803 unit**
- 💹 Margin Profit: **20%** (konsisten di semua lini)
- 🌏 Negara kontribusi tertinggi: **Malaysia**
- 🏢 Segmen kontribusi tertinggi: **Midmarket**
- 📅 Bulan penjualan tertinggi: **Desember**

## 🖼️ Screenshot Dashboard

> ![Dashboard](https://github.com/alvinaryapangestu/Sales-Performance-Dashboard---Minimarket-/blob/5d60c36b5597e2d0730d96af65686301880ab011/docs/screenshots/dashboard1.png)
> ![Dashboard](https://github.com/alvinaryapangestu/Sales-Performance-Dashboard---Minimarket-/blob/0503f5ed21d93b118d9bd6c7a47026354b03c905/docs/screenshots/dashboard%202.png)

## 👤 Author

**Alvin Arya Pangestu**
Fresh Graduate — Informatika, Universitas Darussalam Gontor
[LinkedIn](https://www.linkedin.com/in/alvinaryapangestu) 
