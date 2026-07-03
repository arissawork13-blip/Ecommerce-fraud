# Ecommerce-fraud
<img width="1024" height="1536" alt="Poster STATIS" src="https://github.com/user-attachments/assets/c4d13d21-b057-4f99-80ec-f363c9a0ff71" />
[Statistika Kelompok 1 EAS.pdf](https://github.com/user-attachments/files/29630898/Statistika.Kelompok.1.EAS.pdf)
# 🛒 Analisis Fraud Transaksi E-Commerce Menggunakan Uji Chi-Square

 Deskripsi Proyek

Proyek ini merupakan tugas **Evaluasi Akhir Semester (EAS)** mata kuliah **Statistika dan Analitika** yang bertujuan untuk menganalisis hubungan antara **metode pembayaran (Payment Method)** dengan **status fraud (Is Fraudulent)** pada transaksi e-commerce.

Analisis dilakukan menggunakan **Uji Chi-Square Independensi**, yaitu metode statistik yang digunakan untuk mengetahui apakah terdapat hubungan yang signifikan antara dua variabel kategorik.

---

 Anggota Kelompok

- Muhammad Yani Ardiansyah (1482400064)
- Muhammad Fahreza Rizky (1482400070)
- Kevin Cristian Putra Nugraha (1482400071)
- Kevin Aris (1482400055)

**Mata Kuliah:** Statistika dan Analitika  
**Program Studi:** Sistem dan Teknologi Informasi

---

 Tujuan Penelitian

Penelitian ini bertujuan untuk:

- Mengetahui apakah terdapat hubungan antara metode pembayaran dengan status fraud.
- Mengidentifikasi metode pembayaran yang memiliki tingkat fraud tertinggi.
- Mengimplementasikan Uji Chi-Square menggunakan Python.
- Menginterpretasikan hasil analisis statistik sebagai dasar pengambilan keputusan.

---

 Dataset

Dataset yang digunakan adalah **Fraudulent E-Commerce Transaction Dataset**.

Informasi dataset:

- **Jumlah transaksi:** 1.472.952 data
- **Jumlah variabel:** 16 kolom
- **Missing Value:** 0

Variabel utama yang dianalisis:

- `Payment Method`
- `Is Fraudulent`

---

Tools dan Library

Analisis dilakukan menggunakan bahasa pemrograman **Python** dengan beberapa library berikut:

- Pandas
- NumPy
- Matplotlib
- SciPy

---

 Alur Analisis

Tahapan analisis pada proyek ini meliputi:

1. Import library Python
2. Membaca dataset
3. Pemeriksaan missing value
4. Melihat informasi dataset
5. Analisis statistik deskriptif
6. Visualisasi data
7. Membuat tabulasi silang (Contingency Table)
8. Melakukan Uji Chi-Square
9. Menginterpretasikan hasil
10. Menarik kesimpulan

### Flowchart

```text
Import Library
      │
      ▼
 Load Dataset
      │
      ▼
 Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
 Contingency Table
      │
      ▼
 Chi-Square Test
      │
      ▼
Interpretasi Hasil
      │
      ▼
 Kesimpulan
```

---

 Hasil Exploratory Data Analysis (EDA)

Berdasarkan hasil eksplorasi data diperoleh informasi sebagai berikut:

- Dataset tidak memiliki **missing value**.
- Distribusi setiap metode pembayaran relatif seimbang.
- Sebanyak **94,99%** transaksi merupakan transaksi normal.
- Sebanyak **5,01%** transaksi teridentifikasi sebagai fraud.

---

 Uji Chi-Square

### Hipotesis

**H₀ (Null Hypothesis)**

Tidak terdapat hubungan antara metode pembayaran dengan status fraud.

**H₁ (Alternative Hypothesis)**

Terdapat hubungan antara metode pembayaran dengan status fraud.

---

 Hasil Pengujian

| Parameter | Nilai |
|-----------|-------|
| Chi-Square | **2.0369** |
| p-value | **0.5648** |
| Degree of Freedom | **3** |

Karena nilai **p-value > 0,05**, maka **H₀ tidak ditolak**.

Artinya, **tidak terdapat hubungan yang signifikan antara metode pembayaran dengan status fraud** pada dataset yang digunakan.

---

 Kesimpulan

Berdasarkan hasil analisis dapat disimpulkan bahwa:

- Dataset terdiri dari **1.472.952 transaksi** tanpa missing value.
- Tingkat fraud pada dataset sebesar **5,01%**.
- Hasil Uji Chi-Square menunjukkan nilai **χ² = 2.0369** dengan **p-value = 0.5648**.
- Metode pembayaran tidak memiliki hubungan yang signifikan terhadap kemungkinan terjadinya fraud.
- Meskipun **Bank Transfer** memiliki persentase fraud tertinggi (**5,04%**), perbedaannya sangat kecil sehingga tidak signifikan secara statistik.

---

 Pengembangan Selanjutnya

Analisis ini masih dapat dikembangkan menggunakan metode Machine Learning, seperti:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Support Vector Machine (SVM)

dengan menambahkan variabel lain seperti:

- Nominal transaksi
- Lokasi pelanggan
- Umur akun
- Perangkat yang digunakan
- Waktu transaksi

agar model prediksi fraud memiliki tingkat akurasi yang lebih baik.

---

 Struktur Repository

```text
📦 Fraud-Ecommerce-ChiSquare
├── dataset/
│   └── ecommerce_fraud.csv
├── notebook/
│   └── UAS_STATIS.ipynb
├── report/
│   └── Statis_UAS.pdf
├── images/
│   └── visualisasi/
├── README.md
```

---
 Referensi

- Python Documentation
- Pandas Documentation
- SciPy Documentation
- Matplotlib Documentation

---

 Lisensi

Repository ini dibuat untuk memenuhi tugas **Evaluasi Akhir Semester (EAS)** mata kuliah **Statistika dan Analitika** pada Program Studi Sistem dan Teknologi Informasi.
