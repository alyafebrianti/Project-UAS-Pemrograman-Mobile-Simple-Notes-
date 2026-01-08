# Simple Notes

Aplikasi catatan sederhana dengan desain **lucu aesthetic** bertema **pink pastel** yang super lembut dan menyenangkan. Cocok untuk mencatat ide, reminder harian, atau curhatan random dengan tampilan yang bikin hari menjadi lebih berwarna😊

<p align="center">
  <img src="lokasi.jpeg" width="200" alt="Izin lokasi" />
  <img src="splashh.jpeg" width="200" alt="Splash Screen" />
  <img src="loading.jpeg" width="200" alt="Loading Screen" />
  <img src="halamanutama.jpeg" width="200" alt="Halaman Utama" />
</p>

## Fitur Utama

- **Splash Screen**  
  Tampilan pembuka berwarna pink pastel dengan gambar buku catatan lucu + pensil + teks "Hallo Welcome To Simple Notes" yang menggemaskan

- **Loading Screen**  
  Animasi loading lurus (oval) dengan karakter buku catatan lucu yang sedang menulis + teks "Loading..." — dengan durasi singkat tapi bikin gemes

- **Halaman Utama**  
  - Toolbar teal pastel dengan judul "Simple Notes" (hitam bold)
  - Kartu catatan berlatar pink pastel dengan judul & isi catatan
  - Timestamp di setiap catatan (contoh: 07 Jan 2026 • 16:04)
  - Tombol hapus (ikon tong sampah) di setiap kartu
  - Floating Action Button (FAB) berbentuk lingkaran biru pastel dengan ikon +

- **Tema Keseluruhan**  
  Pink pastel lembut (#FFFFC1CC) sebagai background utama, aksen biru pastel (#A0E7E5) untuk toolbar & FAB, desain minimalis tapi penuh kehangatan

## Preview Aplikasi

| Lokasi          | Splash Screen         | Loading Screen          | Halaman Utama      |
|---------------------------------|---------------------------------|---------------------------------|---------------------------------|
| ![Splash](lokasi.jpeg) | ![Splash](splashh.jpeg) | ![Loading](loading.jpeg) | ![Main](halamanutama.jpeg) |

## Cara Instal & Jalankan

1. Clone repository
   ```bash
   git clone https://github.com/[username-kamu]/simple-notes.git
   cd simple-notes
   
# Struktur Project Singkat

```text
simple-notes/
├── app/
│   ├── src/main/
│   │   ├── java/com/example/simplenotes/
│   │   │   ├── SplashActivity.java
│   │   │   ├── LoadingActivity.java
│   │   │   ├── MainActivity.java
│   │   │   └── (adapter/model jika pakai RecyclerView)
│   │   └── res/
│   │       ├── layout/
│   │       │   ├── activity_splash.xml
│   │       │   ├── activity_loading.xml
│   │       │   └── activity_main.xml
│   │       ├── drawable/
│   │       │   ├── circle_blue.xml
│   │       │   ├── progress_oval_filled.xml
│   │       │   └── logo.png (atau ic_launcher)
│   │       └── values/
│   │           └── colors.xml
│   └── AndroidManifest.xml
├── screenshots/               # folder untuk gambar demo
└── README.md
```

