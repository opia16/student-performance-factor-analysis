# Student Performance Analysis Using Exploratory Data Analysis (EDA)

## Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis faktor-faktor yang mempengaruhi performa akademik siswa menggunakan pendekatan Exploratory Data Analysis (EDA).

Dataset terdiri dari 10.000 data siswa yang disediakan oleh klien EdTech dan mencakup berbagai variabel seperti jam belajar, nilai sebelumnya, aktivitas ekstrakurikuler, jam tidur, serta jumlah latihan soal yang dikerjakan.

Melalui analisis ini, diharapkan dapat diperoleh insight yang membantu institusi pendidikan dalam merancang strategi pembelajaran dan intervensi akademik yang lebih efektif.

---

## Business Problem

Perusahaan EdTech ingin memahami faktor utama yang mempengaruhi performa akademik siswa agar dapat:

* Mengidentifikasi siswa yang berisiko memiliki performa rendah.
* Menentukan faktor yang paling berpengaruh terhadap hasil belajar.
* Menyusun program intervensi yang lebih tepat sasaran.
* Mendukung pengambilan keputusan berbasis data dalam pengembangan produk pembelajaran.

---

## Dataset

Dataset terdiri dari 10.000 data siswa dengan variabel:

| Variabel                         | Deskripsi                     |
| -------------------------------- | ----------------------------- |
| Hours Studied                    | Jam belajar siswa             |
| Previous Scores                  | Nilai akademik sebelumnya     |
| Extracurricular Activities       | Keikutsertaan ekstrakurikuler |
| Sleep Hours                      | Jam tidur per hari            |
| Sample Question Papers Practiced | Jumlah latihan soal           |
| Performance Index                | Nilai performa siswa          |

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## Metodologi Analisis

### 1. Data Understanding

Memahami struktur dataset, tipe data, dan distribusi masing-masing variabel.

### 2. Statistical Profiling

Menggunakan statistik deskriptif untuk menganalisis:

* Mean
* Median
* Standar Deviasi
* Minimum
* Maximum

### 3. Exploratory Data Analysis (EDA)

Analisis dilakukan menggunakan:

* Correlation Matrix
* Scatter Plot
* Boxplot
* Distribution Analysis

### 4. Insight Generation

Mengidentifikasi hubungan antar variabel dan faktor yang paling berpengaruh terhadap Performance Index.

---

## Hasil Analisis

### 1. Previous Scores Menjadi Faktor Terkuat

Analisis korelasi menunjukkan bahwa Previous Scores memiliki korelasi sebesar **0.92** terhadap Performance Index.

### Insight

Siswa dengan nilai akademik sebelumnya yang tinggi cenderung mempertahankan performa akademik yang baik.

Temuan ini menunjukkan bahwa kemampuan dasar akademik memiliki pengaruh yang sangat besar terhadap performa saat ini.

---

### 2. Jam Belajar Tidak Selalu Menentukan Hasil

Visualisasi hubungan antara Hours Studied dan Performance Index menunjukkan tren positif, tetapi dengan penyebaran data yang cukup lebar.

### Insight

Tidak semua siswa yang belajar lebih lama memperoleh hasil yang lebih baik.

Hal ini mengindikasikan bahwa kualitas belajar kemungkinan lebih berpengaruh dibanding kuantitas belajar semata.

---

### 3. Aktivitas Ekstrakurikuler Tidak Memberikan Perbedaan Signifikan

Perbandingan Performance Index antara siswa yang mengikuti ekstrakurikuler dan yang tidak menunjukkan distribusi yang relatif mirip.

### Insight

Keikutsertaan dalam ekstrakurikuler bukan faktor utama yang menentukan performa akademik siswa.

---

### 4. Sleep Hours dan Practice Papers Sebagai Faktor Pendukung

Jam tidur dan jumlah latihan soal menunjukkan hubungan positif terhadap Performance Index, meskipun tidak sekuat Previous Scores.

### Insight

Pola hidup yang baik dan latihan yang konsisten tetap berkontribusi terhadap peningkatan performa siswa.

---

## Business Insight

### Temuan Utama

✅ Previous Scores merupakan prediktor terkuat performa siswa.

✅ Jam belajar memiliki pengaruh positif namun tidak dominan.

✅ Aktivitas ekstrakurikuler tidak menunjukkan dampak signifikan terhadap performa akademik.

✅ Faktor pendukung seperti tidur yang cukup dan latihan soal tetap berkontribusi terhadap hasil belajar.

---

## Rekomendasi

### Untuk Institusi Pendidikan

* Fokus pada siswa dengan nilai awal rendah sebagai target intervensi utama.
* Mengembangkan program remedial berbasis kemampuan dasar akademik.
* Tidak hanya meningkatkan durasi belajar, tetapi juga kualitas pembelajaran.

### Untuk Platform EdTech

* Mengembangkan sistem rekomendasi belajar yang dipersonalisasi.
* Memberikan materi tambahan bagi siswa dengan Previous Scores rendah.
* Memanfaatkan data historis siswa untuk memprediksi performa akademik di masa depan.

---

## Kesimpulan

Analisis menunjukkan bahwa Previous Scores merupakan faktor yang paling mempengaruhi Performance Index siswa dengan korelasi yang sangat kuat.

Temuan ini mengindikasikan bahwa performa akademik cenderung bersifat konsisten dari waktu ke waktu. Oleh karena itu, strategi peningkatan hasil belajar sebaiknya difokuskan pada siswa dengan kemampuan dasar yang masih rendah melalui program intervensi yang lebih terarah dan personal.

---

## Visualisasi

### Correlation Matrix

(Tambahkan gambar heatmap korelasi)

### Previous Scores vs Performance Index

(Tambahkan scatter plot)

### Hours Studied vs Performance Index

(Tambahkan scatter plot)

### Extracurricular Activities Comparison

(Tambahkan boxplot)

---

## Skill yang Ditunjukkan

* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Correlation Analysis
* Data Visualization
* Business Insight Generation
* Data Storytelling
* Python for Data Analytics

---

## Author

**Shofia Nabila**
Universitas Pendidikan Indonesia
Data Analyst Portfolio
