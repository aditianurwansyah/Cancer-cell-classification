# Breast Cancer Classification using Gaussian Naive Bayes

Project ini berisi implementasi machine learning sederhana untuk melakukan klasifikasi kanker payudara (malignant vs benign) menggunakan algoritma **Gaussian Naive Bayes** pada dataset bawaan `scikit-learn`.

## Struktur Project
- Memuat dan eksplorasi dataset *Breast Cancer* (569 baris, 30 fitur).
- Visualisasi distribusi kelas target menggunakan *pie chart*.
- Preprocessing & pembagian data (Train/Test split 67:33).
- Pelatihan model menggunakan `GaussianNB`.
- Evaluasi performa model dengan metrik akurasi.

## Library yang Digunakan
- `Python`
- `scikit-learn`
- `pandas`
- `matplotlib`

## Hasil Evaluasi
Model Gaussian Naive Bayes yang dilatih pada project ini berhasil mencapai tingkat **akurasi sebesar 94.15%** pada data uji.

## Cara Menjalankan
Anda dapat menjalankan file notebook (`.ipynb`) ini langsung melalui Google Colab atau Jupyter Notebook dengan menginstal dependensi yang dibutuhkan:
```bash
pip install scikit-learn pandas matplotlib
