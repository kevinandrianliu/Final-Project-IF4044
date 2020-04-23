# Final-Project-IF4044

## Dataset
Dataset terdiri dari 3600000 data pada training dan 400000 pada test. Dataset diambil dari pranala [berikut](https://drive.google.com/drive/folders/0Bz8a_Dbh9Qhbfll6bVpmNUtUcFdjYmF2SEpmZUZUcVNiMUw1TWN6RDV3a0JHT3kxLVhVR2M) dan disimpan dalam folder data.  
Dataset terdiri dari label, judul review, dan teks review. Terdapat beberapa teks dan judul yang kosong dan akan mempengaruhi proses training dan prediksi data.  

## Cara Menjalankan Program
1. Download semua library yang diperlukan: 
- pyspark.sql untuk mengolah ke dalam dataframe  
- pyspark.ml untuk melakukan training dan prediksi 
- pyspark_dist_explore dengan matplotlib untuk menggambar histogram frekuensi kata dan panjang teks  
2. Run semua cell dari awal hingga akhir.  
