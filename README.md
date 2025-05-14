# Proyek Klasifikasi Gambar: Vegetable Image Dataset

Proyek ini merupakan bagian dari submission akhir kelas Pengembangan Machine Learning Dicoding. 

Tujuan dari proyek ini ialah membangun model klasifikasi gambar untuk mengenali berbagai jenis sayuran menggunakan dataset Vegetable Image Dataset. 

## 📊 Dataset

Dataset yang digunakan adalah **Vegetable Image Dataset**, yang terdiri dari gambar-gambar sayuran dengan beberapa kategori seperti:
- Bean
- Bitter_Gourd
- Bottle_Gourd
- Brinjal
- Broccoli
- Cabbage
- Capsicum
- Carrot
- Cauliflower
- Cucumber
- Papaya
- Potato
- Pumpkin
- Radish
- Tomato

Kaggle : ![dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset)

Dataset dibagi ke dalam direktori training, validation, dan testing.

## 📦 Library yang Digunakan

Beberapa library utama yang digunakan dalam proyek ini:
- TensorFlow & Keras
- NumPy
- Matplotlib
- PIL (Python Imaging Library)

## 🧪 Langkah-langkah Proyek

1. **Import Library:** Mengimpor semua library yang diperlukan.
2. **Data Preparation:** 
   - Meload dataset dari direktori.
   - Melakukan augmentasi dan preprocessing data.
3. **Modeling:**
   - Menggunakan arsitektur CNN (Convolutional Neural Network).
   - Melatih model menggunakan data training dan validasi.
4. **Evaluasi Model:**
   - Mengevaluasi performa model menggunakan data testing.
   - Visualisasi hasil akurasi dan loss.
5. **Model Deployment (opsional):**
   - Menyimpan model untuk keperluan prediksi lebih lanjut.

## 📈 Hasil

Model yang dibangun mencapai akurasi validasi dan testing yang cukup baik dalam membedakan jenis-jenis sayuran. Visualisasi training dan validation accuracy atau loss juga ditampilkan untuk mengevaluasi performa model.

## 🚀 Cara Menjalankan

1. Clone repositori ini atau download file `Submission_Akhir.ipynb`.
2. Jalankan di Google Colab atau Jupyter Notebook.
3. Pastikan struktur folder dataset sesuai dan semua dependensi yang sudah diinstal.

```bash
pip install tensorflow numpy matplotlib pillow
