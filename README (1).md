<div align="center">

<img src="logo.png" alt="FreshKicks.id" width="150">

# FreshKicks.id

**Sistem Informasi Manajemen Layanan Perawatan Sepatu**

Aplikasi berbasis web untuk memudahkan pelanggan memesan layanan perawatan sepatu dan membantu admin mengelola pesanan.

</div>

## Tentang FreshKicks.id

FreshKicks.id merupakan aplikasi web yang dikembangkan untuk mendukung proses pemesanan dan pengelolaan layanan perawatan sepatu. Melalui aplikasi ini, pelanggan dapat memilih layanan, melakukan booking, dan memantau perkembangan pesanan. Admin dapat mengelola data pelanggan serta memperbarui status pengerjaan.

## Fitur Aplikasi

### Pelanggan

- Registrasi dan login akun
- Melihat pilihan layanan perawatan sepatu
- Melakukan booking layanan
- Memantau status pesanan
- Melihat riwayat pesanan
- Mengelola profil dan alamat
- Mengumpulkan poin reward

### Admin

- Melihat ringkasan data pesanan
- Mengelola pesanan pelanggan
- Memperbarui status pengerjaan
- Melihat data pelanggan
- Mengirim notifikasi WhatsApp

## Teknologi yang Digunakan

| Teknologi | Kegunaan |
|---|---|
| HTML | Membuat struktur halaman |
| CSS | Mengatur tampilan aplikasi |
| JavaScript | Menjalankan fungsi dan interaksi |
| Firebase Authentication | Mengelola autentikasi pengguna |
| Cloud Firestore | Menyimpan dan mengelola data |
| Fonnte | Mendukung pengiriman notifikasi WhatsApp |
| PWA | Mendukung pengalaman aplikasi web |

## Struktur Repository

```text
freshkicks.id/
├── icons/
├── admin.html
├── index.html
├── logo.png
├── manifest.json
├── sw.js
├── Diagram_FreshKicks_Kelompok2.drawio
└── SRS_FreshKicks_Kelompok2.pdf
```

## Cara Menjalankan Aplikasi

### 1. Clone Repository

```bash
git clone https://github.com/freshkicks26/freshkicks.id.git
cd freshkicks.id
```

### 2. Konfigurasi Firebase

Buat project melalui [Firebase Console](https://console.firebase.google.com/). Aktifkan Firebase Authentication dengan metode Email/Password dan siapkan Cloud Firestore.

Sesuaikan konfigurasi Firebase pada file aplikasi dengan konfigurasi project yang digunakan. Pastikan aturan keamanan Firestore sudah diatur sesuai hak akses pelanggan dan admin.

### 3. Jalankan Aplikasi

Buka folder project menggunakan Visual Studio Code. Jalankan aplikasi dengan ekstensi Live Server.

Alternatif lainnya, jalankan perintah berikut melalui terminal:

```bash
python -m http.server 8000
```

Kemudian buka alamat berikut di browser:

```text
http://localhost:8000
```

Halaman admin dapat dibuka melalui:

```text
http://localhost:8000/admin.html
```

## Dokumentasi Proyek

Dokumen pendukung yang tersedia di repository:

| File | Keterangan |
|---|---|
| SRS_FreshKicks_Kelompok2.pdf | Dokumen spesifikasi kebutuhan perangkat lunak |
| Diagram_FreshKicks_Kelompok2.drawio | Diagram perancangan sistem |

## Keamanan

Pastikan akses admin dilindungi dengan autentikasi dan otorisasi yang sesuai. Jangan menyimpan token API, password, atau informasi rahasia di dalam kode frontend maupun repository publik. Gunakan backend yang aman untuk mengelola token layanan pihak ketiga.

## Tim Pengembang

**FreshKicks.id — Kelompok 2**

| Nama | NPM |
|---|---|
| Java Fauzan | 202343501705 |
| Asni Anjely | 202343501708 |
| Dede Ahmad | 202343501720 |

## Repository

Source code dan dokumentasi proyek dapat dilihat melalui:

https://github.com/freshkicks26/freshkicks.id

<div align="center">

**FreshKicks.id**

Perawatan sepatu jadi lebih mudah dan terorganisir.

</div>
