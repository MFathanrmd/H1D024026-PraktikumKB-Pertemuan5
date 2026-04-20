# H1D024026-PraktikumKB-Pertemuan5
# SISTEM PAKAR
# Nama    : Muhammad Fathan Ramdani
# NIM     : H1D024026
# Shif Awal  : A
# Shif Akhir : B


# 1. Pendahuluan ##
   Sistem pakar merupakan bagian dari kecerdasan buatan yang dibuat untuk meniru cara berpikir seorang ahli dalam menyelesaikan suatu masalah. Dalam dunia kesehatan, sistem ini dapat digunakan untuk membantu proses diagnosa penyakit berdasarkan gejala yang dirasakan oleh pasien.

Pada tugas ini dibuat sebuah sistem pakar sederhana berbasis console menggunakan bahasa Python yang digunakan untuk mendiagnosa penyakit THT (Telinga, Hidung, Tenggorokan).#

# 2. Tujuan ##
   Adapun tujuan dari pembuatan program ini adalah:
   * Mengimplementasikan konsep sistem pakar ke dalam program Python sederhana.
   * Membantu pengguna mengetahui kemungkinan penyakit berdasarkan gejala yang dipilih.
   * Menerapkan metode pencocokan gejala menggunakan pendekatan scoring.
     
# 3. Metode ##
   Metode yang digunakan pada program ini adalah metode berbasis aturan (rule-based) dengan teknik perhitungan skor (scoring). #
   Langkah-langkah yang dilakukan dalam metode ini yaitu: #
   * Pengguna memasukkan kode gejala yang dirasakan.
   * Sistem akan mencocokkan gejala tersebut dengan data setiap penyakit.
   * Setiap gejala yang cocok akan menambah nilai skor.
   * Penyakit dengan nilai skor tertinggi akan dijadikan hasil diagnosa.
     
# 4. Struktur Data ##
   Dalam program ini digunakan struktur data dictionary untuk menyimpan data gejala dan penyakit.#
  4.1 Data Gejala##
  Data gejala disimpan dalam bentuk key dan value, di mana key berupa kode gejala dan value berupa keterangan dari gejala tersebut.
  4.2 Data Penyakit##
  Data penyakit juga disimpan dalam dictionary, dengan nama penyakit sebagai key dan daftar kode gejala sebagai value.

# 5. Cara Kerja Program
   Alur kerja program adalah sebagai berikut:
   * Program menampilkan daftar seluruh gejala beserta kodenya.
   * Pengguna memasukkan kode gejala yang dialami (dipisahkan dengan spasi).
   * Input tersebut diubah menjadi list agar mudah diproses.
   * Sistem menghitung jumlah kecocokan gejala pada setiap penyakit.
   * Sistem menentukan penyakit dengan skor tertinggi menggunakan fungsi tertentu.
   * Hasil diagnosa ditampilkan ke layar.

# 6. Contoh Penggunaan
   Contoh input:
   G34 G9
   Contoh output:
   Hasil diagnosa: ('Osteosklerosis', 2) 

# 7. Kelebihan Program
   * Menggunakan struktur data yang sederhana sehingga mudah dipahami.
   * Program dibagi ke dalam beberapa fungsi sehingga lebih terstruktur.
   * Metode scoring membuat hasil diagnosa lebih fleksibel dibandingkan metode langsung.

# 8. Kekurangan Program
   * Validasi input masih terbatas.
   * Belum memberikan informasi penanganan atau solusi penyakit.
   * Tampilan masih sederhana karena berbasis console.
  
# 9. Kesimpulan
  Program sistem pakar ini dapat membantu memberikan gambaran awal mengenai kemungkinan penyakit THT berdasarkan gejala yang dimasukkan oleh pengguna. Metode scoring yang digunakan memungkinkan sistem memberikan hasil yang lebih fleksibel meskipun masih sederhana.

# 10. Cara Menjalankan Program
  * Pastikan Python sudah terinstal di perangkat anda.
  * Setelah itu, buka terminal atau command prompt, lalu jalankan file program dengan perintah: python nama_file.py
  * Selanjutnya, program akan menampilkan daftar gejala. Masukkan kode gejala yang sesuai dengan kondisi yang dialami.
  * Setelah input diberikan, sistem akan memproses dan menampilkan hasil diagnosa penyakit berdasarkan gejala yang dimasukkan.
