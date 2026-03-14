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

## 🧠 Penjelasan Konsep Array

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

## 🖥 Screenshot Hasil Eksekusi Program

Berikut adalah hasil eksekusi program saat dijalankan:

Program menampilkan:

- Input nilai mahasiswa



- Daftar nilai mahasiswa
- Nilai maksimum
- Nilai minimum
- Nilai rata-rata
- Jumlah mahasiswa lulus dan tidak lulus



- Grafik perbandingan nilai


- Grafik persentase kelulusan



## ⚙️ Analisis Kompleksitas Algoritma

Analisis kompleksitas dilakukan untuk mengetahui efisiensi algoritma yang digunakan.

1️⃣ Input Data Mahasiswa
for i in range(10):
    nilai_mahasiswa.append(angka)

Kompleksitas:

O(n)

Karena program harus melakukan input sebanyak n data mahasiswa.

2️⃣ Mencari Nilai Maksimum dan Minimum
max(nilai_mahasiswa)
min(nilai_mahasiswa)

Kompleksitas:

O(n)

Karena Python harus mengecek seluruh elemen dalam array untuk menemukan nilai terbesar dan terkecil.

3️⃣ Menghitung Rata-rata
sum(nilai_mahasiswa)/len(nilai_mahasiswa)

Kompleksitas:

O(n)

Karena fungsi sum() menjumlahkan semua elemen array.

4️⃣ Menghitung Jumlah Mahasiswa Lulus
for nilai in nilai_mahasiswa:
    if nilai >= 75:
        jumlah_lulus += 1

Kompleksitas:

O(n)

Karena program harus memeriksa setiap nilai mahasiswa.

5️⃣ Menampilkan Grafik

Grafik dibuat menggunakan matplotlib.

Kompleksitas:

O(1)

Karena jumlah data grafik tetap (nilai tertinggi dan terendah saja).

📊 Ringkasan Kompleksitas
Proses	Kompleksitas
Input nilai	            O(n)
Mencari max/min	        O(n)
Menghitung rata-rata	O(n)
Menghitung kelulusan	O(n)
Menampilkan grafik	    O(1)
📈 Visualisasi Data

Program menghasilkan dua jenis grafik:

1️⃣ Grafik Batang

Menampilkan perbandingan:

Nilai tertinggi

Nilai terendah

2️⃣ Grafik Pie

Menampilkan persentase:

Mahasiswa Lulus

Mahasiswa Tidak Lulus

Visualisasi ini membantu memahami data nilai dengan lebih mudah.

## 💡 Refleksi Pembelajaran

Dari tugas ini saya mempelajari beberapa hal penting, yaitu:

Memahami konsep array atau list dalam Python untuk menyimpan banyak data dalam satu variabel.

Menggunakan perulangan (loop) untuk memproses data dalam array.

Menggunakan fungsi bawaan Python seperti:

max()

min()

sum()

len()

Memahami konsep analisis kompleksitas algoritma seperti O(n) dan O(1).

Menggunakan library matplotlib untuk membuat visualisasi data.

Memahami bagaimana mengolah data menjadi informasi yang lebih mudah dipahami melalui grafik.

Tugas ini juga membantu meningkatkan pemahaman saya dalam pemrograman Python, struktur data dasar, dan analisis algoritma.
