# Praktikum Mikrokontroler - Modul I: Percabangan dan Perulangan

**Nama:** Ibnu Abbas  
**NIM:** H1H024038  
**Mata Kuliah:** TK244005 - Praktikum Mikrokontroler  
**Program Studi:** Informatika, Universitas Jenderal Soedirman  

---

## 📌 Deskripsi Repositori
Repositori ini berisi *source code*, skematik rangkaian, dan dokumentasi hasil praktikum Modul I yang berfokus pada implementasi struktur kontrol percabangan (`if-else`) dan perulangan (`for`) menggunakan platform mikrokontroler Arduino. 

Praktikum ini dirancang untuk memahami bagaimana pengambilan keputusan logika dan perulangan memengaruhi jalannya eksekusi program perangkat keras, khususnya dalam memanipulasi pin *Output* untuk menyalakan susunan komponen LED.

---

## 📁 Penjelasan File Program

### 1. `Praktikum_Percobaan_1.ino` (Percabangan)
**Tujuan Kode:** File ini berisi program untuk mendemonstrasikan fungsi struktur logika percabangan menggunakan instruksi `if-else`. Program ini bertujuan untuk mengevaluasi kondisi parameter batas waktu tunda (*delay*) dan secara dinamis mengubah kecepatan fase kedipan sebuah LED tunggal tanpa memerlukan intervensi manual dari pengguna. Pada tugas modifikasi praktikum ini, program dirancang agar siklus nyala LED berubah secara bertahap: mulai dari fase berkedip cepat, kemudian memelan (kecepatan sedang), dan pada akhirnya sistem akan menahan LED dalam kondisi mati secara permanen (*reset*).

### 2. `Modul_1_Percobaann_2.ino` (Perulangan)
**Tujuan Kode:** File ini berisi program untuk mendemonstrasikan efisiensi struktur kendali perulangan menggunakan instruksi `for` *loop*. Program ini bertujuan untuk memanipulasi rentetan banyak pin digital secara otomatis hanya dengan sedikit baris kode guna menciptakan efek visual pergerakan cahaya pada susunan enam buah LED. Pada tugas modifikasi praktikum ini, instruksi perulangan direkayasa untuk membagi deretan 6 LED menjadi dua blok terpisah (3 LED di sisi kiri dan 3 LED di sisi kanan), di mana program akan memerintahkan kedua kelompok tersebut untuk menyala secara bergantian secara terus-menerus.

---

## 📸 Dokumentasi Praktikum

*([Lampiran percobaan 1 Praktikum](https://github.com/ibasKs81/Praktikum-Modul1/blob/main/WhatsApp%20Image%202026-04-07%20at%2013.12.22.jpeg))*
*([Lampiran percobaan 2 Praktikum](https://github.com/ibasKs81/Praktikum-Modul1/blob/main/WhatsApp%20Image%202026-04-07%20at%2013.12.27.jpeg))*

### 1. Skematik Rangkaian
!Skematik Rangkaian prcobaan 1([Tautan Gambar Skematik_1 Di Sini](https://github.com/ibasKs81/Praktikum-Modul1/blob/main/Screenshot%202026-04-08%20015201.png))
!Skematik Rangkaian prcobaan 2([Tautan Gambar Skematik_2 Di Sini](https://github.com/ibasKs81/Praktikum-Modul1/blob/main/Screenshot%202026-04-08%20015551.png))

### 2. Video Hasil Percobaan 1
[Klik di sini untuk melihat video jalannya program Praktikum_Percobaan_1](Tautan Video Percobaan 1 Anda Di Sini)

### 3. Video Hasil Percobaan 2
[Klik di sini untuk melihat video jalannya program Modul_1_Percobaann_2](Tautan Video Percobaan 2 Anda Di Sini)

---
*Laporan praktikum lengkap beserta analisis data tersedia pada direktori utama repositori ini dalam format dokumen.*
