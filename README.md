# Studi Kasus Pengaruh atau Mempredikisi Hubungan Biaya Promo terhadap Peningkatan Penjualan dengan Algoritma Simple Regresi Linear

## Deskripsi:

Proyek ini bertujuan untuk menganalisis apakah biaya promosi (_BiayaPromo_) berdampak pada nilai penjualan (_NilaiPenjualan_) menggunakan metode _Simple Linear Regression_. Dengan memanfaatkan teknik machine learning, proyek ini mencoba memprediksi hubungan antara variabel _BiayaPromo_ dan _NilaiPenjualan_ berdasarkan data yang ada.

## Dataset:

Dataset yang digunakan adalah `Sales_Data.CSV`, yang berisi dua kolom:

- **BiayaPromo**: Biaya yang dihabiskan untuk promosi dalam satuan tertentu.
- **NilaiPenjualan**: Total penjualan yang dicapai dalam satuan tertentu.

## Contoh data:

- BiayaPromo, NilaiPenjualan 1000, 5000 1500, 7000 2000, 8500 2500, 9000 3000, 11000.

## Fitur

- Analisis regresi linear sederhana.
- Perhitungan koefisien regresi untuk melihat hubungan antara variabel.
- Prediksi nilai penjualan berdasarkan biaya promosi yang diberikan.
- Visualisasi hubungan antara _BiayaPromo_ dan _NilaiPenjualan_ menggunakan grafik regresi.

## Persyaratan

- Python 3.x
- Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Scikit-learn

## Instalasi

1. Clone repository ini:
   ```bash
   git clone https://github.com/veendysuseno/Studi-Kasus-Promosi-Terhadap-Penjualan-Dengan-Simple-Regresi-Linear.git
   ```
2. Masuk ke direktori proyek:
   ```bash
   cd Studi-Kasus-Promosi-Terhadap-Penjualan-Dengan-Simple-Regresi-Linear
   ```
3. Install library yang diperlukan:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

## Cara Menggunakannya (Penggunaan):

1. Pastikan file Sales_Data.CSV sudah ada di direktori proyek.
2. Jalankan skrip regresi linear:
   ```bash
   python Simple_Linear_Regression.py
   ```
3. Skrip akan melakukan analisis dan menampilkan grafik hubungan antara BiayaPromo dan NilaiPenjualan.

## Contoh Hasil

- Setelah menjalankan skrip, berikut adalah persamaan regresi yang dihasilkan:

  ```bash
  NilaiPenjualan = 3.5 * BiayaPromo + 2000
  ```

- Grafik akan menunjukkan garis regresi yang menggambarkan hubungan antara biaya promosi dan nilai penjualan.
