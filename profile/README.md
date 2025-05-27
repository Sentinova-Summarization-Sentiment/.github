# Sentinova

<div align="center">
  <img src="https://github.com/Sentinova-Summarization-Sentiment/.github/blob/main/sentinova-logo.png?raw=true" width="200">
  <h1 align="center">SENTINOVA</h1>
  <h2 align="center">Summarization dan Sentiment Analysis Bahasa Indonesia</h2>
</div>

---

## Tentang Proyek

**Sentinova** adalah sistem berbasis AI yang menggabungkan dua teknik utama dalam NLP (Natural Language Processing): **abstractive summarization** dan **sentiment analysis** untuk Bahasa Indonesia.

Proyek ini dikembangkan untuk membantu pengguna dalam:
- Menyederhanakan ulasan panjang dari e-commerce menjadi ringkasan otomatis menggunakan model **IndoT5**
- Mengklasifikasikan opini pelanggan (positif, netral, negatif) menggunakan **IndoBERT** atau metode tradisional seperti **SVM dan Naive Bayes**

📘 Proyek ini dikembangkan sebagai bagian dari tugas akhir untuk memenuhi **3 mata kuliah utama**, yaitu:
- **Natural Language Processing**
- **Machine Learning**
- **Data Mining**

---

## Anggota Tim

| Nama Lengkap                    | NIM           |
| :----------------------------- | :------------ |
| Aditya Farras Zaky Firmansyah | 2207412020    |
| Laiqah Noor Muin               | 2207412023    |
| Muhammad Husain Al Ghazaly    | 2207412027    |
| Ragiliawan Putra Rencana      | 2207412013    |

---

## Struktur Repositori

| Modul                  | Deskripsi                                                                                  | Repository                                                                                   |
|------------------------|---------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| **Model Summarization**| Fine-tuning IndoT5 untuk menghasilkan ringkasan ulasan produk (abstractive summarization) | [modelsumarisasi](https://github.com/Sentinova-Summarization-Sentiment/modelsumarisasi)     |
| **Model Sentiment (ML)** | Menggunakan IndoBERT untuk klasifikasi sentimen (fine-tuning pretrained transformer)       | [modelsentimen-ml](https://github.com/Sentinova-Summarization-Sentiment/modelsentimen-ml)   |
| **Model Sentiment (DM)** | Menggunakan RapidMiner dan algoritma klasik seperti SVM/Naive Bayes pada data ulasan      | [modelsentimen-dm](https://github.com/Sentinova-Summarization-Sentiment/modelsentimen-dm)   |
| **Frontend Aplikasi**  | Aplikasi web (React + FastAPI) untuk mengakses fitur summarization dan sentimen            | [frontend](https://github.com/Sentinova-Summarization-Sentiment/frontend)                   |

---

## Fitur Utama

- 🔍 **Ringkasan Otomatis** – Merangkum review panjang menjadi kalimat yang lebih singkat dan padat.
- 😊 **Analisis Sentimen** – Mengklasifikasikan review ke dalam sentimen positif, netral, atau negatif.
- 🌐 **Aplikasi Web** – User interface interaktif untuk menjalankan fitur dengan mudah.

---

## Teknologi Digunakan

- IndoT5, IndoBERT (HuggingFace)
- TensorFlow / PyTorch
- Scikit-learn, RapidMiner
- ReactJS & FastAPI
- Sastrawi, NLTK, SpaCy

---

## Tujuan Proyek

- Membantu pengguna memahami banyak ulasan produk secara efisien
- Menyediakan insight yang ringkas dan bermakna dari teks tidak terstruktur
- Mendemonstrasikan pemahaman lintas-mata kuliah dalam proyek berbasis NLP

---

