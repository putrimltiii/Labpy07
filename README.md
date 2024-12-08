# Labpy08
# Putri Melati Ramadhaniati
# TI.24.A2

Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah
class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan:

• Method tambah() untuk menambah 

• Method tampilkan() untuk menampilkan data

• Method hapus(nama) untuk menghapus data berdasarkan nama

• Method ubah(nama) untuk mengubah data berdasarkan nama

# Kode Program
![kode 1 per 12](https://github.com/user-attachments/assets/f897fb58-74c6-4fd4-b616-a1d3ab8b6a83)

![kode 2 per 12](https://github.com/user-attachments/assets/2d524360-3d18-4278-8e64-103f146a8a86)

# Penjelasan Program

1. Metode init
   
   • Metode ini adalah konstruktor yang dipanggil saat objek dari kelas Mahasiswa dibuat.

   • Di sini, kita menginisialisasi atribut daftar_mahasiswa sebagai list kosong yang akan digunakan untuk menyimpan data mahasiswa.

2. Menambahkan Data Mahasiswa (tambah method):

   • Metode ini menerima dua parameter: nama dan nilai. Data mahasiswa baru ditambahkan ke dalam daftar_mahasiswa dalam bentuk dictionary yang berisi nama dan nilai.

   • Setelah menambahkan, metode ini mencetak pesan konfirmasi

3. Menampilkan Data Mahasiswa (tampilkan method):

   • Metode ini menampilkan semua data mahasiswa yang ada dalam daftar_mahasiswa.

   • Jika daftar kosong, akan mencetak pesan bahwa daftar mahasiswa kosong.

   • Jika ada data, akan mencetak nama dan nilai setiap mahasiswa.

4. Menghapus Data Mahasiswa (hapus method):

   • Metode ini mencari mahasiswa berdasarkan nama. Jika ditemukan, data mahasiswa tersebut dihapus dari daftar_mahasiswa dan mencetak pesan konfirmasi.

   • Jika tidak ditemukan, akan mencetak pesan bahwa data mahasiswa tidak ditemukan.

5. Mengubah Data Mahasiswa (ubah method):
   
   • Metode ini juga mencari mahasiswa berdasarkan nama. Jika ditemukan, nilai mahasiswa tersebut diubah menjadi nilai_baru dan mencetak pesan konfirmasi.

   • Jika tidak ditemukan, akan mencetak pesan bahwa data mahasiswa tidak ditemukan.

# Run
![run pertemuan 12](https://github.com/user-attachments/assets/5c131e6f-74cc-430d-bc73-33399ca1d322)

# Diagram Class
![diagram class per12](https://github.com/user-attachments/assets/c1d1b872-7123-461e-b431-c19b5667ba1d)

# Penjelasan Diagram Class

• _init_(): Konstruktor yang menginisialisasi daftar_mahasiswa sebagai list kosong.

• tambah(nama, nilai): Menambahkan data mahasiswa baru ke dalam daftar_mahasiswa.

• tampilkan(): Menampilkan semua data mahasiswa yang ada dalam daftar_mahasiswa.

• hapus(nama): Menghapus data mahasiswa berdasarkan nama yang diberikan.

• ubah(nama, nilai_baru): Mengubah nilai mahasiswa berdasarkan nama yang diberikan.

• Tanda +: Menunjukkan bahwa metode atau atribut tersebut bersifat publik (dapat diakses dari luar kelas).

• Tanda -: Menunjukkan bahwa atribut tersebut bersifat privat (tidak dapat diakses dari luar kelas).

# Flowchart
![flowchart 12](https://github.com/user-attachments/assets/9f72cb7f-b3fb-43d3-a29d-7274014dfc6d)
