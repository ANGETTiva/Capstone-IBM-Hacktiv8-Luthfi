# Analisis Penggunaan Internet Rumah & Bottleneck Wi‑Fi

## 📌 Deskripsi Proyek
Proyek ini bertujuan menganalisis tren penggunaan internet rumah dan mengidentifikasi bottleneck performa Wi‑Fi berdasarkan data publik dari NTIA dan simulasi pengukuran kecepatan.

## 📊 Dataset
- `ntia_adopsi.csv` — Data tingkat penggunaan internet rumah (2015–2020)
- `wifi_bottleneck.csv` — Data perbandingan kecepatan Wi‑Fi vs ISP

## ⚙️ Tools
- Google Colab
- Pandas, Matplotlib, Seaborn
- AI Summarization: `Replicate API` dengan model `a16z-infra/llama-2-13b-chat`

## 🔍 Insight & Temuan
- Adopsi internet rumah meningkat 14.4% selama 5 tahun terakhir.
- Sekitar 50% rumah mengalami bottleneck Wi‑Fi (Wi‑Fi lebih lambat dari akses ISP).
- Ringkasan otomatis menunjukkan pentingnya optimasi jaringan lokal rumah.

## 🤖 Dukungan AI
Model `ibm-granite/granite-3.3-8b-instruct` dari Replicate digunakan untuk menyarikan insight dari teks hasil analisis. Prompt diarahkan untuk membuat ringkasan singkat dan relevan.

## 📈 Output
- Notebook: `summarization_colab.ipynb`
- Slide presentasi: `slides/presentasi_capstone.pdf`
