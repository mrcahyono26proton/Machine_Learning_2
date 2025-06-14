# Klasifikasi Sentimen Ulasan TikTok dengan LSTM

Proyek ini merupakan tugas individu mata kuliah NLP, dengan fokus pada klasifikasi teks menggunakan arsitektur RNN (LSTM).

## 📁 Struktur Proyek
- `training_model.ipynb`: Notebook utama berisi preprocessing, pembuatan model, dan evaluasi.
- `Ulasan_Aplikasi_Tiktok.csv`: Dataset 200 ulasan (100 positif, 100 negatif).
- `laporan_tugas_individu.pdf`: Laporan akhir dokumentasi dan refleksi tugas ini.

## 📊 Dataset
Dataset berisi ulasan aplikasi TikTok yang dikategorikan menjadi dua sentimen: positif dan negatif. Terdapat variasi panjang dan gaya bahasa.

## ⚙️ Model
Model yang digunakan adalah LSTM dengan parameter:
- Epoch: 10
- Dropout: 0.5
- Optimizer: Adam
- Loss: Binary Crossentropy

## 🔍 Evaluasi
- Akurasi validasi terbaik: ~80.5%
- Visualisasi hasil tersedia di notebook

## 🚀 Menjalankan Kode
1. Install dependency:
```bash
pip install -r requirements.txt

jupyter notebook training_model.ipynb
