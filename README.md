[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9493828&assignment_repo_type=AssignmentRepo)
# Phase 2 - Milestones 1

_Milestones ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Full Time Program Phase 2 khususnya pada Artificial Neural Network._

---

## Data Sources

Unduh dataset yang akan digunakan [disini](https://www.kaggle.com/blastchar/telco-customer-churn)

## Assignment Instructions

*Milestones 1* dikerjakan dalam format *notebook* dengan/atau dengan *model deployment* dengan beberapa *kriteria wajib* di bawah ini:

1. Deep Learning framework yang digunakan adalah *Tensorflow*.

2. Ada penggunaan library visualisasi, seperti *matplotlib*, *seaborn*, atau yang lain.

3. Isi *notebook* harus mengikuti *outline* di bawah ini:
   1. Perkenalan
      > Bab pengenalan harus diisi dengan identitas, gambaran besar dataset yang digunakan, dan *objective* yang ingin dicapai.
   
   2. Import Libraries
      > *Cell* pertama pada *notebook* **harus berisi dan hanya berisi** semua *library* yang digunakan dalam *project*.
   
   3. Data Loading
      > Bagian ini berisi proses penyiapan data sebelum dilakukan eksplorasi data lebih lanjut. Proses Data Loading dapat berupa memberi nama baru untuk setiap kolom, mengecek ukuran dataset, dll.
   
   4. Exploratory Data Analysis (EDA)
      > Bagian ini berisi explorasi data pada dataset diatas dengan menggunakan query, grouping, visualisasi sederhana, dan lain sebagainya.

   5. Data Preprocessing
      > Bagian ini berisi proses penyiapan data untuk proses pelatihan model, seperti pembagian data menjadi train-dev-test, transformasi data (normalisasi, encoding, dll.), dan proses-proses lain yang dibutuhkan.   
   
   6. Model Definition
      > Bagian ini berisi cell untuk mendefinisikan model. Jelaskan alasan menggunakan suatu algoritma/model, hyperparameter yang dipakai, jenis penggunaan metrics yang dipakai, dan hal lain yang terkait dengan model.

   7. Model Training
      > Cell pada bagian ini hanya berisi code untuk melatih model dan output yang dihasilkan. Lakukan beberapa kali proses training dengan hyperparameter yang berbeda untuk melihat hasil yang didapatkan. Analisis dan narasikan hasil ini pada bagian Model Evaluation.
   
   8. Model Evaluation
      > Pada bagian ini, dilakukan evaluasi model yang harus menunjukkan bagaimana performa model berdasarkan metrics yang dipilih. Hal ini harus dibuktikan dengan visualisasi tren performa dan/atau tingkat kesalahan model. **Lakukan analisis terkait dengan hasil pada model dan tuliskan hasil analisisnya**.

   9. Model Saving
      > Dengan melihat hasil evaluasi model, pilihlah model terbaik untuk disimpan. Model terbaik ini akan digunakan kembali dalam melakukan deployment di Heroku.
   
   10. Model Inference
       > Model yang sudah dilatih akan dicoba pada data yang bukan termasuk ke dalam train-set ataupun test-set. Data ini harus dalam format yang asli, bukan data yang sudah di-scaled.
   
   11. Pengambilan Kesimpulan
       > Pada bagian terakhir ini, **harus berisi** kesimpulan yang mencerminkan hasil yang didapat dengan *objective* yang sudah ditulis di bagian pengenalan.

5. *Notebook* harus diupload dalam akun GitHub masing-masing siswa untuk selanjutnya dinilai.

6. Penilaian project dilakukan berdasarkan *notebook* dan *service/API* model yang sudah di-deploy.

7. Presentasikan model yang telah dibuat pada P2W2D5AM.

## Assignment Submission

- Simpan assignment pada sesi ini dengan nama `h8dsft_P2M1_<nama-student>.ipynb`, misal `h8dsft_P2M1_raka_ardhi.ipynb`.
- Push Assigment yang telah dibuat ke akun Github.
- Untuk Model Deployment :
  * Buat sebuah folder bernama `deployment` dan masukkan semua file yang berkaitan dengan deployment ke folder ini.
  * Buat sebuah file bernama `url.txt` yang berisi URL Dataset dan URL deployment (baik untuk frontend dan backend).
  * Contoh bentuk isi repository dengan Model Deployment.
    ```
    ├── deployment/
    │   ├── frontend
    │   │   ├── app.py
    │   │   ├── requirements.txt
    │   │   ├── *dst*
    │   ├── backend
    │   │   ├── app.py
    │   │   ├── requirements.txt
    │   │   ├── model.pkl
    │   │   ├── *dst*
    ├── h8dsft_P2M1_raka_ardhi.ipynb
    ├── url.txt
    └── README.md
    ```

## Assignment Objectives

*Milestones 1* ini dibuat guna mengevaluasi Pembelajaran Phase 2 :

- Mampu memahami konsep Artificial Neural Network.
- Mampu mempersiapkan data untuk digunakan dalam model Artificial Neural Network.
- Mampu mengimplementasikan Artificial Neural Network dengan data yang diberikan.
- Mampu menganalisis dan menjelaskan layer yang dibuat.

---

## Assignment Rubrics

### Code Review

| Criteria|Meet Expectations|Points|
| --- | --- | --- |
| Feature Engineering | Mampu melakukan proses Feature Engineering sebelum melakukan proses modeling | 20 pts |
| Pipelines | Mampu membangun Pipeline. **Pipeline yang dimaksud adalah Pipeline yang menggunakan modul `Tensorflow`** | 5 pts |
| Modeling | Membuat model Artifical Neural Network dengan menggunakan Sequential API dan Functional API  | 20 pts (untuk Sequential API), <br><br> 20 pts (untuk Functional API) |
| Model Evaluation | Mampu melakukan Model Evaluation | 10 pts |
| Model Improvement | Mampu melakukan Model Improvement baik untuk Sequential API dan Functional API. | 10 pts (untuk Sequential API), <br><br> 10 pts (untuk Functional API) |
| Model Inference | Mencoba model yang telah dibuat dengan data baru | 10 pts |
| Apakah Kode Berjalan Tanpa Ada Error? | Kode berjalan tanpa ada error. Seluruh kode berfungsi dan dibuat dengan benar. | 10 pts |

### Readability

| Criteria | Meet Expectations | Points|
| --- | --- | --- |
| Tertata Dengan Baik | Semua baris kode terdokumentasi dengan baik dengan menggunakan Markdown untuk penjelasan kode. | 10 pts |

```
Kriteria tertata dengan baik diantaranya adalah : 

1. Terdapat section Perkenalan yang jelas
2. Tidak menyalin markdown dari tugas lain.
3. Import library rapih (terdapat dalam 1 cell dan tidak ada unused libs).
4. Pemakaian fungsi markdown yang optimal (Heading, text formating, dll). 
5. Terdapat komentar pada setiap baris kode.
6. Adanya pemisah yang jelas antar section, dll.
```

### Analysis

| Criteria | Meet Expectations | Points|
| --- |--- |--- |
| Model Analysis | Menganalisa informasi dari model yang telah dibuat | 30 pts |
| Overall Analysis | Menarik informasi/kesimpulan dari keseluruhan kegiatan yang dilakukan | 20 pts |

### Deployment

| Criteria | Meet Expectations | Points |
| --- | --- | --- |
| Model Deployment | Membuat webapps terhadap project yang telah dibuat. | 10 pts (menggunakan Flask), <br><br> 5 pts (tanpa menggunakan Flask) |

---

```
Total Points : 185
```
