# Fahri
Face Recognition Attendance Web App

Aplikasi Absensi Berbasis Pengenalan Wajah berbasis web menggunakan Python, Flask, OpenCV, dan face_recognition. Aplikasi ini memungkinkan pengguna untuk menambahkan data wajah, melakukan absensi otomatis melalui webcam, serta melihat riwayat absensi yang tersimpan dalam file CSV.

Fitur Utama

Tambah Data Wajah
Mengambil gambar wajah dari webcam melalui browser dan menyimpan encoding wajah ke dalam file .pkl.

Absensi Otomatis
Sistem mendeteksi wajah menggunakan webcam, mencocokkan dengan encoding yang tersimpan, dan mencatat absensi secara otomatis ke Attendance/attendance.csv.

Riwayat Absensi
Menampilkan seluruh riwayat absensi dalam bentuk tabel.

Berbasis Web
Backend menggunakan Flask, sedangkan frontend menggunakan HTML, CSS, dan JavaScript.

Teknologi yang Digunakan

Python 3.x

Flask

OpenCV

face_recognition

NumPy

Pickle

CSV

Struktur Folder (Contoh)
project/
│
├── app.py
├── encodings/
│   └── user_encodings.pkl
├── Attendance/
│   └── attendance.csv
├── static/
│   └── style.css
├── templates/
│   ├── index.html
│   ├── add_face.html
│   └── riwayat.html
└── README.md

Cara Instalasi

Clone repository

git clone hhttps://github.com/genmclones/Fahri
cd face-recognition-attendance


Install dependencies

pip install -r requirements.txt


Jika tidak ada requirements.txt, install manual:

pip install flask opencv-python face_recognition numpy

Cara Menjalankan Aplikasi

Jalankan perintah berikut:

python app.py


Akses melalui browser:

http://127.0.0.1:5000

Cara Penggunaan

Tambah Wajah Baru

Masuk ke menu Tambah Wajah

Aktifkan webcam

Masukkan nama

Simpan wajah

Sistem menyimpan encoding wajah

Absensi Wajah

Masuk ke menu Absensi

Webcam akan mendeteksi wajah

Jika cocok, absensi dicatat otomatis

Riwayat Absensi

Masuk ke menu Riwayat

Sistem menampilkan data dari attendance.csv****
