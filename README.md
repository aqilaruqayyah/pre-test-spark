# UTS-KomputasiNumerik
Anggota Kelompok 1:
1.Fira Ramadhani (2408107010019)
2.Aqila Ruqayyah (2408107010070)
3.Muhammad Fazel Mawla (2408107010074)
4.M. Rayan Zishan (2408107010063)
5.Khalish Aufa (2408107010068)
6.M. Anis Fathin (2408107010045)

Kalkulator Metode Biseksi
Ini adalah aplikasi desktop sederhana yang dibuat dengan Python untuk menemukan akar dari fungsi matematika f(x) pada interval [a, b] menggunakan metode biseksi. Aplikasi ini menyediakan antarmuka grafis yang ramah pengguna untuk memasukkan parameter yang diperlukan dan menampilkan langkah-langkah iterasi dari perhitungan secara rinci.

🌟 Fitur
1.Antarmuka Grafis (GUI): UI yang interaktif dan mudah digunakan.
2.Perhitungan Biseksi: Menghitung akar fungsi dengan metode biseksi secara akurat.
3.Tabel Iterasi: Menampilkan detail setiap langkah iterasi, termasuk nilai a, b, xr, f(a), f(b), f(xr), dan |b-a|.
4.Validasi Fungsi: Memungkinkan pengguna untuk memeriksa validitas sintaks fungsi matematika sebelum perhitungan.
5.Hasil Cepat: Opsi untuk menampilkan jawaban akhir secara langsung tanpa menampilkan tabel iterasi.
6.Penanganan Error: Memberikan peringatan jika input tidak valid atau tidak ada akar dalam interval yang diberikan.

📂 Struktur Kode
Proyek ini terdiri dari dua file utama:

# main_gui.py

a.Berisi semua kode untuk membangun antarmuka grafis (GUI) menggunakan pustaka tkinter.
b.Mengelola input dari pengguna, aksi tombol, dan menampilkan hasil perhitungan pada tabel.
c.Mengimpor logika perhitungan dari bisectionLogic.py.

# bisectionLogic.py
a.Berisi logika inti matematika.
b.Fungsi f_eval(f_str, x): Mengevaluasi string fungsi matematika yang dimasukkan pengguna secara aman. Fungsi ini juga mengganti operator ^ dengan ** untuk perhitungan pangkat.
c.Fungsi bisection(f_str, a, b, N, eps): Mengimplementasikan algoritma metode biseksi untuk menemukan akar.

🚀 Cara Menjalankan
syarat:
Python 3.x terpasang di sistem Anda. (Pustaka tkinter biasanya sudah termasuk dalam instalasi standar Python).

Langkah-langkah:
1.Simpan kedua file (main_gui.py dan bisectionLogic.py) dalam direktori yang sama.
2.Buka terminal atau command prompt.
3.Jalankan aplikasi dengan perintah: python3 main_gui.py 

📝 Panduan Penggunaan
f(x) =: Masukkan fungsi matematika Anda. Gunakan x sebagai variabel. Untuk operasi pangkat, Anda bisa menggunakan ^ atau ** (contoh: x^2 - 4 atau x**2 - 4).
a : Masukkan batas bawah interval.
b : Masukkan batas atas interval.
ε (epsilon) : Masukkan nilai toleransi error yang diinginkan (contoh: 0.0001).
N (iterasi) : Masukkan jumlah maksimum iterasi yang akan dilakukan.

Tombol :

✅ Cek Fungsi: Klik untuk menguji apakah sintaks fungsi f(x) Anda valid. Tombol ini akan menghitung nilai f(1) untuk verifikasi.

🌿 Hitung: Klik untuk menjalankan metode biseksi. Tabel iterasi akan diisi, dan sebuah popup akan menampilkan hasil akar yang ditemukan.

💡 Tampilkan Jawaban: Klik untuk menjalankan perhitungan tanpa mengisi tabel iterasi, dan hanya menampilkan hasil akhir dalam sebuah popup.
