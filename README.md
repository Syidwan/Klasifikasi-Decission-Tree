# 📊 Klasifikasi Decision Tree – UTS Praktikum Machine Learning

Proyek ini dibuat untuk menyelesaikan Ujian Tengah Semester (UTS) pada mata kuliah Praktikum Machine Learning. Proyek ini menerapkan algoritma **Decision Tree** untuk mengklasifikasikan data dari sebuah dataset.

## 📁 Dataset
Dataset yang digunakan adalah `dataset_buys _comp.csv`. Dataset ini berisi data-data yang akan digunakan untuk klasifikasi keputusan.

## 📌 Langkah-Langkah Pengerjaan

1. **Import Library yang Dibutuhkan**  
   Menggunakan library seperti:
   - `pandas` untuk manipulasi data,
   - `sklearn.tree.DecisionTreeClassifier` untuk klasifikasi,
   - `sklearn.model_selection.train_test_split` untuk membagi data training dan testing.

2. **Load Dataset**  
   Membaca dataset menggunakan `pandas.read_csv()` dan menampilkannya untuk memastikan struktur data.

3. **Preprocessing Data**  
   - Melakukan konversi data kategorikal ke numerik menggunakan `LabelEncoder`.
   - Menyiapkan fitur (`X`) dan label (`y`) untuk proses klasifikasi.

4. **Split Data**  
   - Data dibagi menjadi data training dan testing dengan proporsi 80:20 menggunakan `train_test_split()`.

5. **Modeling dengan Decision Tree**  
   - Menginisialisasi model `DecisionTreeClassifier` dan melatihnya dengan data training.

6. **Evaluasi Model**  
   - Memprediksi data testing.
   - Menampilkan hasil prediksi dan menghitung akurasi model menggunakan `accuracy_score`.
