# Identitas
Nama : Kevin Rally Richardo Mintje

NIM : 250211060024

Kelas: E

Mata Kuliah: Pemrograman Berbasis Objek

Dosen Pengampu: RENDY SYAHPUTRA S.Kom., M.Kom

Teknik Informatika
Universitas Sam Ratulangi

# Sistem Inventaris Perusahaan (Company System)

Repository ini berisi implementasi kode Python untuk memenuhi **Tugas Praktikum Mandiri - Minggu Ke-5** pada mata kuliah Pemrograman Berorientasi Objek. Topik utama dari tugas ini adalah penerapan **Property Visibility & Enkapsulasi di Python 3.12**.

##  Deskripsi Proyek
Program ini adalah simulasi sederhana dari sistem pendataan karyawan dan perhitungan total gaji di sebuah perusahaan. Program ini didesain dengan fokus pada arsitektur data yang aman menggunakan konsep enkapsulasi, guna mencegah manipulasi data secara langsung dari luar *class* (menghindari *Side-Effect Cascades*).

##  Fitur Utama (Sesuai Kriteria Tugas)
Sistem ini telah memenuhi seluruh kriteria wajib dari instruksi praktikum:
1. **Pembuatan `class Company`**: Sebagai *class* utama yang membungkus logika bisnis perusahaan.
2. **Enkapsulasi Array Data**: Data karyawan disimpan dalam atribut *private* `self.__employees = []` sehingga tidak dapat diakses atau diubah secara sembarangan dari luar.
3. **Private Method**: Implementasi fungsi komputasi `__calculate_payroll()` yang sepenuhnya dikunci (bersifat *private*) dan hanya bisa dieksekusi dari dalam lingkup *class* itu sendiri.
4. **Validasi Objek**: Menggunakan fungsi bawaan Python `isinstance(obj, ClassName)` pada method penambahan karyawan untuk memvalidasi bahwa input yang masuk benar-benar merupakan objek dari *class* `Employee` yang sah.
