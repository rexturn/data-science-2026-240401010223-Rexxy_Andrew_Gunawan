# 📊 Data Science Portfolio — Universitas Siber Asia

## Identitas Mahasiswa

| Keterangan     | Detail                        |
|----------------|-------------------------------|
| **Nama**       | Rexxy Andrew Gunawan          |
| **NIM**        | 240401010223                  |
| **Kelas**      | IF403                         |
| **Program Studi** | S1 PJJ Informatika UNSIA   |
| **Mata Kuliah** | Data Science  |

---

## 👋 Perkenalan

Halo! Saya Rexxy Andrew Gunawan, mahasiswa S1 PJJ Informatika di Universitas Siber Asia. Repository ini merupakan portofolio perjalanan belajar saya di mata kuliah **Data Science**, yang mencakup hasil aktivitas hands-on dari Pertemuan 1 hingga Pertemuan 7.

Tujuan saya dalam mempelajari Data Science adalah untuk memahami proses pengolahan data secara end-to-end, mulai dari eksplorasi awal, pembersihan data, visualisasi, hingga penerapan algoritma machine learning dasar. Saya percaya bahwa kemampuan mengolah dan menginterpretasikan data merupakan kompetensi kunci di era digital saat ini.

Repository ini berisi 7 notebook (.ipynb) yang masing-masing merekam proses belajar, eksperimen kode, analisis data nyata, dan refleksi pembelajaran dari setiap pertemuan. Setiap notebook dapat dijalankan ulang dari awal hingga akhir tanpa error, dan telah dilengkapi dengan kesimpulan di sel terakhir.

---

## 📚 Daftar Pertemuan & Notebook

| No | Pertemuan | Topik | Link Notebook |
|----|-----------|-------|---------------|
| 1 | Pertemuan 1 | Pengantar Python untuk Data Science — Output, Variabel, List, Fungsi | [Pertemuan1_Rexxy_Andrew_Gunawan_240401010223.ipynb](https://colab.research.google.com/drive/12jhO-Cmfp_PdrKIwMbI1ldO_bFbfEj6O?usp=sharing) |
| 2 | Pertemuan 2 | Pandas & NumPy — Eksplorasi Dataset Titanic, Filtering, Groupby | [Pertemuan2_Rexxy_Andrew_Gunawan_240401010223.ipynb](https://colab.research.google.com/drive/10skpV2K1RGo9BEakc3dXCbkXEsFxypn3?usp=sharing) |
| 3 | Pertemuan 3 | Data Cleaning — Missing Values, Outlier, Normalisasi String, REST API | [Pertemuan3_Rexxy_Andrew_Gunawan_240401010223.ipynb](https://colab.research.google.com/drive/1hEZ5lrQlNwFbysSp-I58UYCgjfX-jzvc?usp=sharing) |
| 4 | Pertemuan 4 | Statistika Deskriptif & Visualisasi — Distribusi, Korelasi, Heatmap | [Pertemuan4_Rexxy_Andrew_Gunawan_240401010223.ipynb](https://colab.research.google.com/drive/1w_TUrcHaMf5iJ-lOJq0FJjfJReeveA-W?usp=sharing) |
| 5 | Pertemuan 5 | Dashboard Visualisasi — Matplotlib Gridspec, Seaborn, Analisis Tips | [Pertemuan5_Rexxy_Andrew_Gunawan_240401010223.ipynb](https://colab.research.google.com/drive/1MSP9dSKdTg193p1UfnXxBqbI2bSpJwfg?usp=sharing) |
| 6 | Pertemuan 6 | Data Preparation for ML — Encoding, StandardScaler, Train-Test Split | [Pertemuan6_Rexxy_Andrew_Gunawan_240401010223.ipynb](https://colab.research.google.com/drive/1h_3o43HBNUEaRk75k7jFuZFHnBEhAoDh?usp=sharing) |
| 7 | Pertemuan 7 | Supervised Learning — Regresi Linear, Evaluasi Model, Residual Plot | [Pertemuan7_Rexxy_Andrew_Gunawan_240401010223.ipynb](https://colab.research.google.com/drive/1K0UIYBa8l8IY3mxSw1dl3p39w5PEEQ1T?usp=sharing) |

---

## 🛠️ Tools & Library yang Digunakan

| Kategori | Tools / Library |
|----------|----------------|
| **Bahasa Pemrograman** | Python 3 |
| **Environment** | Google Colab |
| **Manipulasi Data** | Pandas, NumPy |
| **Visualisasi** | Matplotlib, Seaborn |
| **Machine Learning** | scikit-learn (LinearRegression, StandardScaler, train\_test\_split) |
| **Statistik** | SciPy (scipy.stats) |
| **Networking / API** | Requests, json\_normalize |
| **Version Control** | Git, GitHub |

---

## ▶️ Cara Menjalankan Notebook

Seluruh notebook dikerjakan menggunakan **Google Colab**. Setiap notebook menyertakan link Google Colab di sel pertama yang dapat langsung dibuka dan dijalankan tanpa instalasi apapun.

**Langkah menjalankan:**
1. Klik link Google Colab yang tersedia di sel pertama notebook yang diinginkan.
2. Pastikan sudah login dengan akun Google.
3. Pilih **Runtime → Run all** (atau `Ctrl+F9`) untuk menjalankan seluruh sel dari atas ke bawah.

---

## 🔍 Ringkasan Perjalanan Belajar Data Science Pertemuan 1–7

Selama tujuh pertemuan ini, saya menempuh perjalanan belajar yang terstruktur terkait bidang Data Science.

**Pertemuan 1** menjadi fondasi dengan mempraktikkan dasar-dasar Python — variabel, tipe data, list, perulangan, dan fungsi — menggunakan Google Colab, sekaligus membiasakan diri mendokumentasikan dan mengunggah hasil kerja ke GitHub.

**Pertemuan 2** memperkenalkan dua library utama: NumPy untuk komputasi numerik dan Pandas untuk manipulasi data tabular. Analisis dataset Titanic mengajarkan teknik filtering, groupby, dan perhitungan agregasi, sekaligus mengungkap temuan menarik seperti tingkat keselamatan penumpang kelas 1 yang mencapai 63% dan dominasi keselamatan penumpang wanita dibanding pria.

**Pertemuan 3** berfokus pada Data Cleaning yang komprehensif menggunakan dataset properti *housing_dirty.csv*. Saya belajar menangani missing values dengan imputasi (median/modus), menormalisasi inkonsistensi teks, mendeteksi dan menangani outlier menggunakan metode IQR Fence dan clipping, serta mengakses data melalui REST API publik (JSONPlaceholder).

**Pertemuan 4** masuk ke ranah statistika deskriptif dan visualisasi dengan dataset Iris. Saya mempraktikkan analisis distribusi (histogram + KDE), visualisasi per kelompok (boxplot dan violin plot), serta analisis korelasi Pearson. Temuan utama adalah korelasi sangat kuat antara *petal_length* dan *petal_width* dengan nilai 0,963.

**Pertemuan 5** mengangkat level ke pembuatan dashboard statis multi-panel menggunakan Matplotlib GridSpec dan Seaborn. Analisis dataset Tips menghasilkan berbagai insight bisnis yang bermakna: hari Minggu memiliki rata-rata tagihan tertinggi, sesi makan malam adalah motor utama pendapatan, dan terdapat korelasi positif antara total tagihan dan jumlah tip.

**Pertemuan 6** adalah persiapan data sebelum melatih model Machine Learning. Saya mempraktikkan One-Hot Encoding untuk variabel kategorikal, StandardScaler untuk feature scaling, dan stratified Train-Test Split pada dataset Titanic, sehingga data siap digunakan untuk tahap modelling.

**Pertemuan 7** merupakan puncak dari perjalanan ini: implementasi Supervised Learning dengan algoritma Regresi Linear menggunakan dataset sintetis prediksi gaji. Model yang dibangun mencapai R² sebesar 0,974, artinya 97,4% variasi gaji dapat dijelaskan oleh fitur yang tersedia. Residual Plot menunjukkan asumsi linearitas terpenuhi, menandakan model baseline ini layak digunakan.

Secara keseluruhan, perjalanan tujuh pertemuan ini membantu menambah pemahaman saya di bidang Data Science yang sebelumnya telah saya pelajari. Setiap tahap saling berkaitan dan membentuk fondasi yang kuat untuk eksplorasi Data Science yang lebih lanjut.

---

> *"Data is the new oil, but like oil, it needs to be refined to be useful."*  
> Repository ini adalah bukti nyata dari proses 'pemurnian' data yang saya pelajari selama tujuh pertemuan pertama mata kuliah Data Science.
