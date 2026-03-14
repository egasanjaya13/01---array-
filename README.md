# 📚 Tugas Pemrograman Python — Konsep Array
## 📌 Deskripsi Program

Program ini dibuat menggunakan Python untuk mengelola dan menganalisis nilai mahasiswa menggunakan konsep array (list pada Python).

Program melakukan beberapa proses utama:

Memasukkan nilai mahasiswa ke dalam array

Menampilkan seluruh nilai

Mencari nilai maksimum dan minimum

Menghitung rata-rata nilai

Menghitung jumlah mahasiswa lulus dan tidak lulus

Menampilkan grafik batang perbandingan nilai

Menampilkan grafik pie persentase kelulusan menggunakan library matplotlib

🧠 Penjelasan Konsep Array

Array adalah struktur data yang digunakan untuk menyimpan sekumpulan data dengan tipe yang sama dalam satu variabel.

Dalam Python, array biasanya direpresentasikan menggunakan list.

Contoh pada program:

nilai_mahasiswa = []

List tersebut digunakan untuk menyimpan nilai mahasiswa yang dimasukkan oleh pengguna.

Nilai dimasukkan menggunakan perulangan:

for i in range(10):
    angka = int(input("Masukkan nilai mahasiswa ke-"))
    nilai_mahasiswa.append(angka)

Fungsi dari array dalam program ini adalah untuk:

Menyimpan banyak nilai mahasiswa

Mempermudah proses perhitungan statistik

Mempermudah pengolahan data menggunakan perulangan

Beberapa operasi array yang digunakan dalam program:

Operasi	Fungsi
append()	Menambahkan data ke dalam array
max()	Mencari nilai terbesar
min()	Mencari nilai terkecil
sum()	Menjumlahkan semua elemen
len()	Menghitung jumlah data
