# Membangun Proyek Machine Learning: Klustering dan Klasifikasi

## Deskripsi Proyek
Proyek ini bertujuan untuk menerapkan teknik klustering dan klasifikasi pada dataset transaksi bank guna mendeteksi potensi penipuan. Dataset yang digunakan berasal dari Kaggle: [Bank Transaction Dataset for Fraud Detection](https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection).

## Tujuan
1. **Klustering:**
   - Menggunakan minimal 2500 baris data.
   - Menggunakan minimal 5 fitur dengan kombinasi numerikal dan kategorikal.
   - Menerapkan feature selection untuk memilih fitur terbaik.
   - Membandingkan silhouette score sebelum dan sesudah feature selection.
   - Memastikan silhouette score akhir minimal 0.70.

2. **Klasifikasi:**
   - Menggunakan dua algoritma klasifikasi berbeda.
   - Membandingkan performa model berdasarkan metrik akurasi dan F1-score.
   - Meningkatkan akurasi dan F1-score pada testing set minimal 92%.

## Dataset
- **Sumber:** Kaggle ([link](https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection))
- **Jumlah baris yang digunakan:** ≥ 2500
- **Fitur yang digunakan:**
  - Numerikal: Contoh (`TransactionAmount`, `TransactionDuration`, `AccountBalance`, `CustomerAge`)
  - Kategorikal: Contoh (`TransactionType`, `Channel`)

## Kesimpulan
Proyek ini bertujuan untuk memahami bagaimana feature selection memengaruhi klustering dan bagaimana klasifikasi dapat mendeteksi transaksi yang mencurigakan dengan tingkat akurasi tinggi.

