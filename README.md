nomer 1

Program di atas adalah aplikasi berbasis konsol yang digunakan untuk menghitung distribusi suara dari pemilih, dengan pilihan suara dalam rentang 1 hingga 20.

1. Input Suara: Program meminta pengguna untuk memasukkan angka yang merepresentasikan suara dari 1 hingga 20 secara berulang. Input dihentikan dengan memasukkan angka 0.
2. Validasi Input: Program memverifikasi bahwa setiap angka yang dimasukkan berada dalam rentang 1-20. Jika input tidak valid, program memberikan pesan kesalahan dan meminta input ulang.
3. Penghitungan Suara: Program menggunakan map (hitungSuara) untuk mencatat jumlah suara yang diterima oleh setiap calon (1-20).
4. Output Hasil: Setelah input dihentikan, program menampilkan:
Jumlah total suara yang terbaca.
Distribusi suara untuk setiap calon yang menerima suara.

nomer 2

Program di atas adalah aplikasi berbasis konsol yang digunakan untuk menghitung suara dalam sebuah pemilihan sederhana dan menentukan dua calon dengan suara terbanyak (Ketua dan Wakil Ketua).

1. Input Suara:

Program meminta pengguna untuk memasukkan angka yang merepresentasikan suara untuk calon (1-20).
Pengguna dapat memasukkan angka secara berulang, dan proses input dihentikan dengan memasukkan angka 0.

2. Validasi Input:

Hanya angka dalam rentang 1-20 yang diterima. Jika angka di luar rentang dimasukkan, program akan meminta input ulang dengan pesan kesalahan.

3. Penghitungan Suara:

Program menggunakan struktur data map untuk mencatat jumlah suara setiap calon.
Suara yang valid akan dihitung, dan jumlah total suara yang masuk juga dilacak.

4. Penentuan Ketua dan Wakil Ketua:

Setelah input dihentikan, program menentukan Ketua dan Wakil Ketua berdasarkan suara terbanyak:
Ketua adalah calon dengan jumlah suara terbanyak.
Wakil Ketua adalah calon dengan jumlah suara terbanyak kedua.
Jika ada jumlah suara yang sama, calon dengan nomor lebih kecil akan diutamakan.

5. Output Hasil:

Program menampilkan jumlah total suara yang terbaca.
Menampilkan distribusi suara untuk setiap calon yang mendapat suara.
Menampilkan nomor calon yang terpilih sebagai Ketua dan Wakil Ketua.

nomer 3

Program di atas adalah aplikasi berbasis konsol untuk mencari posisi pertama kemunculan elemen tertentu dalam sebuah array.

1. Konstanta dan Variabel:

NMAX adalah konstanta yang menetapkan ukuran maksimum array (1.000.000 elemen).
data adalah array global dengan ukuran maksimum NMAX.

2. Fungsi isiArray:

Bertugas mengisi array dengan elemen yang dimasukkan pengguna.
Meminta input sejumlah elemen sesuai dengan jumlah yang ditentukan (n).

3. Fungsi posisi:

Mencari elemen k dalam array.
Mengembalikan posisi pertama kemunculan elemen tersebut (dalam indeks 1-based).
Jika elemen tidak ditemukan, fungsi mengembalikan -1.

4. Fungsi main:

Meminta input jumlah elemen array (n) dan elemen yang akan dicari (k).
Memvalidasi bahwa n berada dalam rentang yang diizinkan (1 hingga NMAX).
Mengisi array dengan elemen dari input pengguna.
Menggunakan fungsi posisi untuk mencari elemen k:
Jika ditemukan, mencetak posisi pertama elemen tersebut.
Jika tidak ditemukan, mencetak TIDAK ADA.
