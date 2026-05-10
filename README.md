# Prediksi Stabilitas Rantai Pasok

## Gambaran Umum
Repositori ini berisi proyek Tugas Akhir (TA) yang membahas prediksi kategori stabilitas rantai pasok menggunakan Long Short-Term Memory (LSTM).

Penelitian ini berfokus pada klasifikasi multikelas pada data tidak seimbang dengan tujuan menganalisis pengaruh teknik normalisasi dan penyeimbangan data pada tahap pra-pemrosesan terhadap performa model LSTM.

---

## Tujuan Penelitian
- Mempersiapkan data time-series rantai pasok untuk proses pemodelan
- Menangani nilai kosong dan nilai ekstrem pada data
- Menganalisis pengaruh normalisasi dan teknik balancing terhadap performa model

---
## Penjelasan Penelitian
Penelitian dilakukan menggunakan dataset dengan total 649.999 baris data yang melalui beberapa tahapan, mulai dari data cleaning, eksplorasi data, preprocessing, hingga proses training model seperti yang ditunjukkan pada flowchart yang ditampilkan di slide presentation.

Dilakukan beberapa perbandingan teknik preprocessing, yaitu normalisasi Robust Scaler tanpa balancing, Min-Max Scaler tanpa balancing, Robust Scaler dengan balancing, serta Min-Max Scaler dengan balancing. Berdasarkan hasil eksperimen yang dilakukan, penggunaan Min-Max Scaler tanpa balancing memberikan performa terbaik untuk dataset ini dengan nilai akurasi sebesar 0,97. 

---

## Identitas
Nadia Pavita Amelia

Program Studi S1 Sains Data

Fakultas Informatika

Telkom University

2025
