# KLASIFIKASI PEMBELIAN KOMPUTER DENGAN NAIVE BAYES

Proyek ini bertujuan untuk membangun model klasifikasi menggunakan algoritma `Gaussian Naive Bayes` untuk memprediksi apakah seseorang akan membeli komputer berdasarkan data yang tersedia.

# Tahapan Pembuatan Model Klasifikasi dengan Naive Bayes

## 1. Import Library

Mengimpor pustaka yang dibutuhkan seperti `pandas, numpy, seaborn, matplotlib`, serta modul dari `sklearn` untuk preprocessing, pelatihan model, dan evaluasi.

---

## 2. Load Dataset

Dataset dimuat dari file `dataset_buys _comp.csv`, kemudian dilakukan pemeriksaan awal seperti melihat kolom, data sampel, dan nilai kosong (missing value).

---

## 3. Pra-pemrosesan Data

Fitur dengan tipe data kategorikal dikonversi ke bentuk numerik menggunakan `LabelEncoder` agar bisa digunakan oleh model machine learning.

---

## 4. Pemisahan Data

Data dipisahkan menjadi variabel fitur (X) dan target (y). Target yang diprediksi adalah kolom `Buys_Computer`.
Data kemudian dibagi menjadi data latih dan data uji dengan rasio 80:20 menggunakan `train_test_split`.

---

## 5. Pelatihan Model

Model klasifikasi dilatih menggunakan algoritma Gaussian Naive Bayes.

---

## 6. Evaluasi Model

Model dievaluasi menggunakan:
Confusion Matrix
Classification Report (Precision, Recall, F1-Score)
Accuracy Score

Confusion matrix juga divisualisasikan menggunakan heatmap `(seaborn)`.

---

🗂️ File Terkait

`dataset_buys _comp.csv` – Dataset sumber

`naive_bayes_model.py` – File Python yang berisi implementasi lengkap

## Hasil

Model berhasil dijalankan dan memberikan output berupa metrik evaluasi serta visualisasi confusion matrix.

---
