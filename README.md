# BRIMO Google Play Review Sentiment Analysis

Proyek ini bertujuan untuk menganalisis sentimen dari ulasan pengguna BRIMO di Google Play. Data akan diolah untuk mengidentifikasi sentimen positif, dan negatif.

## Fitur
- Pengumpulan dan praproses data ulasan
- Labelling menggunakan w11wo/indonesian-roberta-base-indolem-sentiment-classifier-fold-0 via huggingface
- Klasifikasi sentimen berbasis model SVM
- Laporan singkat tentang hasil analisis

## Instalasi
1. Clone repositori ini.
2. Pastikan Python 3.x sudah terpasang.
3. Jalankan `pip install -r requirements.txt`.

## Penggunaan
1. Jalankan skrip utama untuk mengambil dan mengolah data.
2. Akses hasil analisis yang disimpan sebagai laporan atau visualisasi grafis.

## Visualisasi
### Distribusi Ulasan Berdasarkan Bulan Pembuatan Ulasan
![Distribusi Ulasan Berdasarkan Bulan Pembuatan Ulasan](figures/distribusi_ulasan_berdasarkan_bulan_pembuatan_ulasan.png)

### Distribusi Ulasan Berdasarkan Versi Aplikasi
![Distribusi Ulasan Berdasarkan Versi Aplikasi](figures/distribusi_ulasan_berdasarkan_versi_aplikasi.png)

### Polaritas Sentimen Ulasan
![Polaritas Sentimen Ulasan](figures/polaritas_sentimen_ulasan.png)

### Polaritas Skor Ulasan
![Polaritas Skor Ulasan](figures/polaritas_skor_ulasan.png)

### Sentiment Ulasan Berdasarkan Skor
![Sentiment Ulasan Berdasarkan Skor](figures/sentiment_ulasan_berdasarkan_skor.png)

## Lisensi
Bebas digunakan dan dimodifikasi sesuai kebutuhan dengan Izin Author.