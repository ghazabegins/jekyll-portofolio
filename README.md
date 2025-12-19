# Ghazabegins Personal Website

Repository ini adalah kode sumber untuk website pribadi **Ghazabegins**, yang dibangun menggunakan **Jekyll** (Static Site Generator) dan dihosting langsung melalui **GitHub Pages**.

Website ini dirancang sebagai platform portofolio dan blog yang cepat, aman, dan responsif, dilengkapi dengan fitur antarmuka modern seperti *Dark Mode*.

## 🚀 Demo Langsung
Kunjungi website yang sudah aktif di sini:
> **[https://ghazabegins.cyou](https://ghazabegins.cyou)**

## ✨ Fitur Utama

- **Jekyll Powered**: Menggunakan arsitektur situs statis untuk performa pemuatan yang sangat cepat dan keamanan tinggi.
- **Default Dark Mode**: Tema gelap diaktifkan secara otomatis saat pengguna pertama kali membuka `login.html` atau `index.html` untuk kenyamanan visual.
- **Sistem Login Kustom**: Halaman `login.html` terpisah sebagai gerbang masuk sebelum mengakses dashboard utama.
- **Penyimpanan Preferensi**: Menggunakan `localStorage` browser untuk menyimpan pilihan tema pengguna.
- **Desain Responsif**: Tampilan menyesuaikan dengan baik di Desktop, Tablet, dan Ponsel.

## 📂 Struktur Direktori

Berikut adalah struktur file utama yang digunakan dalam pengembangan website ini:

```text
ghazabegins.github.io/
├── _config.yml       # Konfigurasi utama pengaturan Jekyll
├── _posts/           # Folder berisi artikel/konten blog (Markdown)
├── _layouts/         # Template HTML untuk tata letak halaman
├── _includes/        # Komponen parsial (Header, Footer, Navigasi)
├── _sass/            # File gaya SCSS/SASS
├── assets/           # Penyimpanan gambar, CSS (compiled), dan JS
├── index.html        # Halaman Utama (Dashboard)
├── login.html        # Halaman Masuk
├── Gemfile           # Daftar dependensi Ruby (Jekyll plugins)
└── README.md         # Dokumentasi proyek
