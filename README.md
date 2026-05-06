# Sentiment Analysis: Epstein File
**Menganalisis Diskusi Publik di X (Twitter)**

---

## 📌 Latar Belakang
Kasus Epstein merupakan salah satu kontroversi hukum paling signifikan yang menarik perhatian media global secara luas. Dengan dirilisnya dokumen-dokumen baru, diskusi publik di platform X melonjak tajam. Proyek ini bertujuan untuk menganalisis sentimen dan wawasan dari diskusi tersebut guna mendukung tim **Riset & Strategi Editorial**.

## 🎯 Rumusan Masalah
1. Bagaimana respon publik terhadap liputan media mengenai kasus Epstein di X?
2. Apa tema dominan dan kekhawatiran utama yang perlu disoroti oleh tim editorial?

## Alur Kerja Analisis
1. **Data Collection**: Scraping data dari X menggunakan kata kunci terkait Epstein (Januari - Februari 2026).
2. **Preprocessing**: Pembersihan teks (menghapus URL, simbol, dan *stopwords*).
3. **Sentiment Labeling**: Klasifikasi teks ke dalam kategori Positif, Negatif, dan Netral.
4. **Exploratory Data Analysis (EDA)**: Visualisasi distribusi sentimen dan frekuensi kata.
5. **Insights & Recommendations**: Menyusun rekomendasi berdasarkan pola data yang ditemukan.

## Temuan Utama
* **Sentimen Negatif Mendominasi (~49.6%)**: Mencerminkan kemarahan moral dan kritik terhadap sistem.
* **Sentimen Positif (25.6%) & Netral (24.9%)**: Menunjukkan adanya penyebaran informasi tanpa nada emosional yang kuat.
* **Fokus Publik**: Kata kunci seperti `evidence`, `document`, dan `child` menunjukkan permintaan akan transparansi hukum dan perlindungan korban.

## Rekomendasi Editorial
* **Transparansi Hukum**: Publik menginginkan kejelasan pada proses hukum dan dokumen yang dirilis.
* **Sudut Pandang Korban**: Fokuskan liputan pada perlindungan korban dan proses hukum yang berkaitan dengan mereka.

## Teknologi yang Digunakan
* **Bahasa**: Python
* **Library**: Pandas, Sastrawi, Matplotlib, Seaborn
* **Tools**: Tweet-Harvest (Scraping), Google Colab
