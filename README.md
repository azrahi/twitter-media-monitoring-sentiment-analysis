# Twitter Media Monitoring – Sentiment Analysis

## Deskripsi
Project ini bertujuan melakukan media monitoring berbasis Twitter dengan melakukan proses pengambilan data (crawling), pelabelan manual, serta analisis sentimen untuk memahami opini publik terhadap suatu topik.

Project ini merupakan bagian dari tugas mata kuliah Pemrosesan Teks Praktik dan dikembangkan sebagai portofolio analisis data berbasis teks.

## Dataset
- ±1000 tweet hasil crawling Twitter
- Data diberi label secara manual ke dalam dua kelas sentimen:
  - Positif
  - Negatif
- Data yang ditampilkan pada repository ini merupakan **data sampel** yang telah dianonimkan untuk keperluan portofolio.

## Metodologi
Tahapan yang dilakukan dalam project ini meliputi:
1. Crawling data Twitter menggunakan Harvesting Crawling (oleh: Helmi Satria)
2. Pelabelan manual sentimen (positif dan negatif)
3. Preprocessing teks (cleaning, normalisasi, tokenisasi)
4. Ekstraksi fitur menggunakan TF-IDF
5. Pelatihan dan pengujian menggunakan model Random Forest, Decision Tree, dan SVM
6. Evaluasi performa model dan analisis hasil

## Hasil
- Perbandingan performa beberapa model klasifikasi sentimen
- Distribusi sentimen positif dan negatif
- Insight sederhana terkait kecenderungan opini publik berdasarkan data yang dianalisis

## Tools & Library
- Python
- pandas
- scikit-learn
- nltk / library pemrosesan teks lainnya

## Catatan
Dataset lengkap digunakan untuk keperluan akademik dan tidak dipublikasikan secara penuh pada repository ini untuk menjaga privasi dan etika penggunaan data.
