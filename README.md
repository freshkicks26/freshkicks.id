
<div align="center">

<img src="logo.png" alt="FreshKicks.id" width="150">

# FreshKicks.id

**Sistem Informasi Manajemen Layanan Perawatan Sepatu**

Aplikasi berbasis web untuk memudahkan pelanggan memesan layanan perawatan sepatu dan membantu admin mengelola pesanan.

</div>

## Tentang FreshKicks.id

FreshKicks.id merupakan aplikasi web yang dikembangkan untuk mendukung proses pemesanan dan pengelolaan layanan perawatan sepatu. Pelanggan dapat memilih layanan, melakukan booking, dan memantau perkembangan pesanan. Admin dapat mengelola data pelanggan serta memperbarui status pengerjaan.

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
| HTML | Struktur halaman |
| CSS | Tampilan aplikasi |
| JavaScript | Fungsi dan interaksi |
| Firebase Authentication | Autentikasi pengguna |
| Cloud Firestore | Penyimpanan data |
| Fonnte | Notifikasi WhatsApp |
| PWA | Pengalaman aplikasi web |

## Struktur Repository

```text
freshkicks.id/
├── icons/
├── admin.html
├── index.html
├── logo.png
├── manifest.json
├── sw.js
├── Kelompok2_Diagram_FreshKicks.drawio
└── SRS_FreshKicks_Kelompok2.pdf
```

## Desain UI/UX dan Wireframe

Desain antarmuka FreshKicks.id mencakup dua bagian utama:

- **UI Design:** rancangan visual tampilan aplikasi.
- **Wireframe:** rancangan struktur dan tata letak halaman aplikasi.

Seluruh rancangan dapat dilihat melalui Figma berikut:

**[Figma — FreshKicks_UIUX](https://www.figma.com/design/oY8Xnbu6TE6PXTe7FqmTMn/FreshKicks_UIUX)**

## Cara Menjalankan Aplikasi

### 1. Clone Repository

```bash
git clone https://github.com/freshkicks26/freshkicks.id.git
cd freshkicks.id
```

### 2. Konfigurasi Firebase

Buat project melalui [Firebase Console](https://console.firebase.google.com/). Aktifkan Firebase Authentication dengan metode Email/Password dan siapkan Cloud Firestore.

Sesuaikan konfigurasi Firebase pada file aplikasi dengan konfigurasi project yang digunakan.

### 3. Jalankan Aplikasi

Buka folder project menggunakan Visual Studio Code dan jalankan dengan Live Server.

Alternatif melalui terminal:

```bash
python -m http.server 8000
```

Buka browser:

```text
http://localhost:8000
```

Halaman admin:

```text
http://localhost:8000/admin.html
```

## Dokumentasi Proyek

| File | Keterangan |
|---|---|
| SRS_FreshKicks_Kelompok2.pdf | Dokumen spesifikasi kebutuhan perangkat lunak |
| Diagram_FreshKicks_Kelompok2.drawio | Diagram perancangan sistem |

## Keamanan

Pastikan akses admin dilindungi autentikasi dan otorisasi yang sesuai. Jangan menyimpan token API, password, atau informasi rahasia di dalam kode frontend maupun repository publik.

## Tim Pengembang

**FreshKicks.id — Kelompok 2**

| Nama | NPM |
|---|---|
| Java Fauzan | 202343501705 |
| Asni Anjely | 202343501708 |
| Dede Ahmad | 202343501720 |

## Repository

[GitHub — FreshKicks.id](https://github.com/freshkicks26/freshkicks.id)

<div align="center">

**FreshKicks.id**

Perawatan sepatu jadi lebih mudah dan terorganisir.

</div>

