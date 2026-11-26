# UTS MACHINE LEARNING
## Analisis Pengelompokan Pola Harga Komoditas Pangan di Berbagai Pasar Indonesia Menggunakan Algoritma K-Means

### 1. Identitas Mahasiswa

| Keterangan | Informasi |
|---|---|
| Nama | [Gerandi Maylion Nggiri] |
| NIM | [2401010110] |
| Program Studi | Informatika |
| Kelas | [xx] |
| Mata Kuliah | Machine Learning |
| Dosen Pengampu | Dr. I Gede Totok Suryawan, S.Kom., M.T. |
| Institusi | INSTIKI |

---

### 2. Deskripsi Proyek

Proyek ini merupakan tugas Ujian Tengah Semester (UTS) mata kuliah Machine Learning yang bertujuan untuk menganalisis dan mengelompokkan pola harga komoditas pangan di berbagai pasar Indonesia menggunakan algoritma K-Means Clustering.

Penelitian ini dilakukan untuk mengetahui pola atau karakteristik kelompok harga berdasarkan fitur-fitur numerik pada dataset. Hasil pengelompokan diharapkan dapat memberikan gambaran mengenai perbedaan karakteristik harga komoditas pangan sehingga dapat membantu proses analisis dan pengambilan keputusan.

Pengembangan proyek menggunakan metodologi CRISP-DM (Cross Industry Standard Process for Data Mining) yang terdiri dari enam tahapan, yaitu Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, dan Deployment.

### 3. Tujuan Penelitian

1. Memahami karakteristik data harga komoditas pangan di berbagai pasar Indonesia.
2. Melakukan eksplorasi dan visualisasi pola harga komoditas pangan.
3. Mengelompokkan data berdasarkan karakteristik harga menggunakan algoritma K-Means.
4. Menentukan jumlah cluster terbaik menggunakan Elbow Method dan Silhouette Score.
5. Menganalisis karakteristik setiap kelompok yang dihasilkan.

### 4. Metode dan Algoritma

- **Metodologi:** CRISP-DM.
- **Algoritma:** K-Means Clustering.
- **Bahasa Pemrograman:** Python.
- **Platform:** Google Colab.
- **Library:** Pandas, NumPy, Matplotlib, Seaborn, dan Scikit-learn.
- **Preprocessing:** Pembersihan data dan StandardScaler.
- **Evaluasi:** Elbow Method dan Silhouette Score.
- **Visualisasi:** Scatter Plot, Heatmap, Boxplot, dan visualisasi hasil clustering.

Pengujian dilakukan dengan membandingkan hasil clustering tanpa scaling dan dengan scaling. Jumlah cluster diuji dari k = 2 sampai k = 8.

### 5. Dataset

Dataset yang digunakan dalam penelitian ini adalah data harga komoditas pangan di berbagai pasar Indonesia.

-Nama Dataset: Indonesia Commodity Price

Sumber Dataset: Kaggle – Datavidia

Link Dataset: https://www.kaggle.com/datasets/datavidia/indonesia-commodity-price

Tanggal Akses: 21 November 2026

Format: CSV

Jumlah Data: 1.493 baris

Jumlah Fitur: 5 kolom

Lisensi: GNU General Public License v2.0 (GPL-2.0)


Dataset digunakan untuk proses eksplorasi, preprocessing, pemodelan, dan evaluasi clustering.


### 6. Struktur Repository

```text
UTS-ML-NIM-Nama/
│
├── README.md
│
├── notebook/
│   └── UTS_ML_NIM_Nama.ipynb
│
├── data/
│   └── dataset.csv
│
└── reports/
    ├── grafik/
    └── presentasi/
```

Keterangan:

- `README.md`: Dokumentasi proyek dan informasi penelitian.
- `notebook/`: Berisi notebook Google Colab yang memuat seluruh tahapan analisis Machine Learning.
- `data/`: Berisi dataset yang digunakan dalam penelitian.
- `reports/`: Berisi grafik hasil analisis dan slide presentasi.

### 7. Tahapan Pengerjaan

Proyek ini dilaksanakan berdasarkan tahapan CRISP-DM:

1. Business Understanding: Menentukan permasalahan dan tujuan penelitian.
2. Data Understanding: Mengumpulkan dan memahami dataset.
3. Data Preparation: Melakukan pembersihan dan persiapan data.
4. Modeling: Membangun model K-Means Clustering.
5. Evaluation: Mengevaluasi hasil clustering menggunakan Elbow Method dan Silhouette Score.
6. Deployment: Menyajikan hasil analisis dalam bentuk visualisasi dan laporan.

### 8. Pernyataan Penggunaan AI

Dalam pengerjaan proyek UTS Machine Learning ini, saya menggunakan bantuan Artificial Intelligence (AI) berupa Claude sebagai alat bantu pembelajaran dan pengembangan proyek.

Penggunaan AI meliputi:

1. Membantu memahami konsep dan tahapan metodologi CRISP-DM.
2. Membantu menyusun struktur notebook Google Colab.
3. Membantu memberikan referensi dan penjelasan kode Python.
4. Membantu memahami penggunaan algoritma K-Means, Elbow Method, dan Silhouette Score.
5. Membantu mengidentifikasi kesalahan kode dan memberikan alternatif penyelesaian.

Seluruh kode, proses pengolahan data, hasil visualisasi, serta evaluasi model diperiksa dan dijalankan kembali menggunakan dataset yang sebenarnya. Hasil analisis dipahami dan dipelajari agar dapat dijelaskan serta dipertanggungjawabkan secara mandiri pada saat presentasi.

### 9. Hasil dan Kesimpulan

Bagian ini memuat hasil akhir penelitian setelah seluruh proses pemodelan dan evaluasi selesai dilakukan.

Hasil Analisis

Jumlah Cluster Terpilih: 3 cluster, yaitu Cluster 0, Cluster 1, dan Cluster 2.

Nilai Silhouette Score: [Isi berdasarkan hasil evaluasi Silhouette Score dari Google Colab].

Hasil Pengelompokan:

Cluster 0 – Kelompok Harga Menengah: Memiliki karakteristik harga beras dan bawang putih yang lebih tinggi dibandingkan Cluster 1, tetapi harga cabai merah dan bawang merah relatif lebih rendah.

Cluster 1 – Kelompok Harga Campuran: Memiliki rata-rata harga beras dan bawang putih paling rendah, tetapi harga cabai merah relatif lebih tinggi dibandingkan Cluster 0.

Cluster 2 – Kelompok Harga Relatif Tinggi: Memiliki rata-rata harga tertinggi pada keempat komoditas yang dianalisis, sehingga menunjukkan kelompok dengan tingkat harga relatif tinggi.

Hasil Pengelompokan: Data harga komoditas pangan dikelompokkan berdasarkan kemiripan pola harga. Setiap cluster akan dianalisis untuk mengetahui karakteristik harga komoditas, seperti kelompok harga relatif rendah, menengah, dan tinggi, apabila karakteristik tersebut didukung oleh hasil analisis.

Kesimpulan: Penelitian ini menggunakan algoritma K-Means untuk mengidentifikasi pola harga komoditas pangan di berbagai pasar Indonesia. Hasil pengelompokan diharapkan dapat memberikan gambaran mengenai kemiripan karakteristik harga sehingga membantu proses pemantauan dan analisis harga pangan.
### 10. Penutup

Proyek ini diharapkan dapat menjadi sarana penerapan pengetahuan Machine Learning, khususnya dalam penggunaan algoritma K-Means Clustering untuk menganalisis dan menemukan pola pengelompokan pada data harga komoditas pangan.

Seluruh hasil penelitian disusun berdasarkan proses pengolahan dan evaluasi dataset yang digunakan dalam proyek ini.

---

**Institut Bisnis dan Teknologi Indonesia (INSTIKI)**  
**Program Studi Informatika**  
**Tahun Akademik 2026/2027**
