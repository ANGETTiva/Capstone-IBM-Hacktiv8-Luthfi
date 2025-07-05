# 📊 Analisis Penggunaan Internet Rumah & Bottleneck Wi‑Fi

## 🧾 Ringkasan Proyek
Proyek ini menganalisis tren peningkatan penggunaan internet rumah dan mengidentifikasi masalah bottleneck Wi‑Fi menggunakan dua dataset. Dengan bantuan AI (Large Language Model dari IBM Granite 3.3 via Replicate API), proyek ini menghasilkan ringkasan otomatis dari temuan utama.

## 📂 Dataset
1. **ntia_adopsi.csv**  
   Dataset adopsi internet rumah di Amerika Serikat dari tahun 2015–2020.  
   Kolom: `year`, `internet_use_percent`
   
2. **wifi_bottleneck.csv**  
   Dataset simulasi performa jaringan Wi‑Fi di rumah vs kecepatan ISP.  
   Kolom: `wifi_mbps`, `access_mbps`

## ⚙️ Tools & Platform
- **Google Colab** – Untuk pemrosesan data dan visualisasi
- **Pandas, Seaborn, Matplotlib** – Untuk analisis dan grafik
- **Replicate API** – Menjalankan model LLM dari IBM
- **Model AI**: `ibm-granite/granite-3.3-8b-instruct` via Replicate

## 🔍 Insight & Temuan
- **Adopsi Internet Rumah** meningkat dari **70.3% (2015)** ke **84.7% (2020)**.
- Sekitar **55% rumah mengalami bottleneck Wi‑Fi**, yaitu kecepatan Wi‑Fi lebih rendah dari kecepatan ISP.
- Bottleneck ini disebabkan oleh kualitas perangkat, gangguan sinyal, dan tata letak jaringan di rumah.
- Terdapat kebutuhan nyata untuk edukasi dan peningkatan infrastruktur jaringan rumah tangga.

## 📄 Ringkasan Otomatis oleh AI
Ringkasan dihasilkan menggunakan prompt berbasis analisis data, lalu diringkas dengan model LLM IBM Granite 3.3 via Replicate. Prompt diarahkan agar hasil:
- Tidak menggantung
- Terstruktur dalam paragraf
- Mencakup faktor teknis dan sosial

## 📈 Visualisasi Output
- Grafik tren adopsi internet rumah (line chart)
- Histogram distribusi kecepatan Wi‑Fi
