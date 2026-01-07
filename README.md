# Project-UAS-Pemrograman-Mobile-Simple-Notes-
# Simple Notes

Aplikasi catatan sederhana dengan desain **minimalis aesthetic** bertema **pink pastel** & **biru pastel**. Cocok untuk catatan harian, reminder, atau ide-ide spontan.

Aplikasi ini dibuat dengan **Java + XML Layout** dan fokus pada pengalaman pengguna yang nyaman serta tampilan yang menyenangkan.

<p align="center">
  <img src="https://via.placeholder.com/360x640/FFFFC1CC/000000?text=Splash+Screen" width="200" />
  <img src="https://via.placeholder.com/360x640/FFFFC1CC/000000?text=Loading+Screen" width="200" />
  <img src="https://via.placeholder.com/360x640/FFFFC1CC/000000?text=Halaman+Utama" width="200" />
</p>

## Fitur Utama

- **Splash Screen** elegan dengan teks "Hallo Welcome To Simple Notes" + dekorasi lingkaran biru pastel
- **Loading Screen** dengan animasi progres oval (mengisi dari kiri ke kanan) + logo besar
- **Daftar catatan** dalam grid 2 kolom dengan warna acak (pink muda, biru muda, putih)
- **Tambah, edit, hapus** catatan melalui dialog sederhana
- **Floating Action Button** (FAB) berwarna biru pastel untuk menambah catatan baru
- **Toolbar** dengan judul hitam tebal + icon notes
- **Permintaan izin lokasi** otomatis saat pertama kali buka (siap untuk fitur masa depan seperti catatan berlokasi)
- **Tema pastel** yang lembut dan eye-catching (pink #FFFFC1CC, biru #A0E7E5)

## Preview

| Splash Screen                  | Loading Screen                 | Halaman Utama                  |
|--------------------------------|--------------------------------|--------------------------------|
| ![Splash](https://via.placeholder.com/180x320/FFFFC1CC/000000?text=Splash) | ![Loading](https://via.placeholder.com/180x320/FFFFC1CC/000000?text=Loading) | ![Main](https://via.placeholder.com/180x320/FFFFC1CC/000000?text=Catatan) |

> **Catatan**: Ganti gambar placeholder di atas dengan screenshot asli aplikasi kamu (upload ke repo lalu copy link raw).

## Teknologi & Library

- **Bahasa Pemrograman**: Java
- **UI Framework**: Android XML Layout + RecyclerView + CoordinatorLayout
- **Permission Handling**: ActivityResultLauncher (modern & aman)
- **Location Service**: FusedLocationProviderClient dari Google Play Services
- **Desain**: Tema custom pink-biru pastel (tidak menggunakan Material 3 default)

## Cara Instal & Jalankan

1. **Clone repository**
   ```bash
   git clone https://github.com/[username-kamu]/simple-notes.git
   cd simple-notes
