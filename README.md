# 📊 Digital Marketing Performance Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/status-completed-success)

Analisis performa iklan digital dari **6 klien** sebuah *digital marketing agency* sepanjang **2023**, untuk menemukan sumber kebocoran budget dan menyusun rekomendasi realokasi budget berbasis data.

> **Studi kasus:** Kompetisi Data Analyst — Digital Marketing Performance Optimization
> **Peran:** Data Analyst di sebuah digital marketing agency

---

## 🎯 Business Problem

Sebuah agency mengelola budget iklan 6 klien di 3 industri (Fashion, Beauty, FMCG). Secara agregat:

- **Total Spend:** Rp 12,95 miliar
- **Total Revenue:** Rp 10,45 miliar
- **Blended ROAS:** 0,81 → **defisit Rp 2,5 miliar**

Pertanyaannya: apakah iklan benar-benar merugi, atau ada budget boros yang menutupi campaign yang sebenarnya menguntungkan?

---

## ❓ Pertanyaan Analisis

1. Berapa CTR & ROAS keseluruhan, dan bedanya antar objective (Traffic vs Sales)?
2. Seberapa besar campaign Traffic menyeret ROAS agregat?
3. Industri & akun mana yang paling efisien?
4. Di tahap funnel mana konversi paling banyak bocor?
5. Bagaimana tren & pola musiman sepanjang tahun?
6. Strategi realokasi budget apa yang menaikkan ROAS di atas titik impas?

---

## 🔑 Temuan Utama

| # | Temuan |
|---|--------|
| 1 | **50% budget (Rp 6,5 M) dialokasikan ke Traffic** yang revenue langsungnya nol — inilah penyebab utama defisit. |
| 2 | Campaign **Sales sebenarnya untung** (ROAS 1,62); yang menyeret agregat ke 0,81 hanyalah bobot Traffic. |
| 3 | Kebocoran funnel terbesar di **Content → Add to Cart (10,1%)**, bukan di checkout (yang justru sehat, 91%). |
| 4 | Efisiensi antar akun berdekatan; **Client A** paling jauh dari titik impas, **Client C & B** paling efisien. |
| 5 | Omzet memuncak di **April** & **akhir tahun (Q4)**. |

---

## 💡 Rekomendasi

1. **Realokasi budget Traffic → Sales** untuk mendorong blended ROAS di atas titik impas (>1,0), tanpa menambah total budget.
2. **Perbaiki kebocoran tengah funnel** (Content → Cart) lewat diskon/bundling, retargeting, dan perbaikan halaman produk.
3. **Prioritaskan akun efisien** (Client C & B) untuk scale, dengan guardrail ROAS.
4. **Budget pacing** — geser spend dari bulan lemah ke bulan kuat mengikuti pola musiman.

---

## 🛠️ Tools

- **Python** (pandas, matplotlib) — analisis & visualisasi

---

## 📁 Isi Repository

| File | Deskripsi |
|------|-----------|
| `ads_analysis_simple.py` | Notebook analisis: data understanding, quality check, EDA, funnel, rekomendasi |
| `Data_Ads.csv` | Dataset performa iklan (4.380 baris, 2023) |
| `Ads_Performance_Presentation.pdf` | Deck presentasi (21 slide) — Business Understanding → Analisis → Rekomendasi |


---

*Dibuat oleh **Ghifarry Al Naffriza Shahdan** — Regional Economic Development, Sekolah Vokasi UGM*
