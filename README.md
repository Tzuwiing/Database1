# Simple Phonebook App

Aplikasi pengelola kontak minimalis yang dirancang khusus untuk satu tujuan utama: **menyimpan nomor telepon dengan cepat dan mudah**. Aplikasi ini berfokus pada fungsionalitas inti tanpa antarmuka yang rumit, memberikan pengalaman pengguna yang ringan dan langsung pada tujuannya.

## ✨ Fitur Utama

* **Simpan Nomor Telepon**: Fokus utama aplikasi untuk mencatat dan menyimpan daftar nomor telepon.
* **Tampilan Minimalis (Single Theme)**: Menggunakan satu tema bawaan yang bersih dan cerah, tanpa pengaturan mode gelap/terang (Light/Dark mode) untuk menjaga ukuran aplikasi tetap ringan dan sederhana.
* **Akses Cepat**: Desain UI yang *to-the-point* memungkinkan pengguna untuk langsung melihat daftar kontak dan menambahkan nomor baru dalam hitungan detik.
* **Penyimpanan Lokal**: Data nomor telepon disimpan secara aman di dalam perangkat pengguna.

## 📸 Tangkapan Layar (Screenshots)

*(Ganti URL gambar di bawah ini dengan tangkapan layar aplikasi Anda)*

| Halaman Utama (Daftar Nomor) |
| :---: |
| <img width="474" height="1038" alt="Screenshot 2026-05-04 100435" src="https://github.com/user-attachments/assets/6849ff6a-a6c0-4c2e-9b4c-cd9c7ba9c99d" /> | 

## 🛠️ Teknologi yang Digunakan

* **[Flutter](https://flutter.dev/)**: Framework UI untuk membangun aplikasi.
* **[sqflite](https://pub.dev/packages/sqflite)**: Database lokal SQLite untuk menyimpan data nomor telepon.
* **[path_provider](https://pub.dev/packages/path_provider)**: Untuk menentukan lokasi penyimpanan database di dalam perangkat.

## 🚀 Cara Menjalankan Proyek

Ikuti langkah-langkah di bawah ini untuk menjalankan aplikasi di lingkungan pengembangan Anda.

### Prasyarat

Pastikan Anda telah menginstal Flutter SDK. Jika belum, baca [Panduan Instalasi Flutter](https://docs.flutter.dev/get-started/install).

### Langkah-langkah

1.  **Clone repositori proyek:**
    ```bash
    git clone [https://github.com/username-anda/nama-repo-kontak.git](https://github.com/username-anda/nama-repo-kontak.git)
    ```

2.  **Masuk ke folder proyek:**
    ```bash
    cd nama-repo-kontak
    ```

3.  **Unduh semua *dependencies*:**
    ```bash
    flutter pub get
    ```

4.  **Jalankan aplikasi** di emulator atau perangkat fisik:
    ```bash
    flutter run
    ```

## 📂 Skema Database Lokal

Tabel database (misalnya `contacts`) dibuat dengan struktur yang sangat sederhana:

| Kolom | Tipe Data | Keterangan |
| :--- | :--- | :--- |
| `id` | INTEGER | Primary Key, Auto Increment |
| `name` | TEXT | Nama pemilik nomor (Opsional/Sesuai kebutuhan) |
| `phone_number` | TEXT | Nomor telepon yang disimpan |

---

**Dibuat untuk kepraktisan dan kecepatan mencatat.**
