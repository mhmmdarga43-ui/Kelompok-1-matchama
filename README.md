# Matchama - Landing Page UMKM

Proyek tugas kelompok mata kuliah Pemrograman Web Statis.
Kelompok: Kelompok 1 - Matchama.

Matchama adalah usaha fiktif minuman berbasis matcha. Seluruh nama, harga, alamat, jam operasional, dan kontak adalah data simulasi untuk pembelajaran.

## Fitur

- Satu landing page dengan bagian Beranda, Katalog, dan Kontak.
- Navigasi anchor (#beranda, #katalog, #kontak).
- Katalog tiga menu beserta harga.
- Layout responsif dengan pendekatan mobile-first.
- Skip link dan indikator fokus untuk pengguna keyboard.
- HTML dan CSS tanpa framework dan tanpa JavaScript.

## Struktur Proyek

```
index.html
css/style.css
assets/images/
docs/requirements.md
docs/testing.md
docs/maintenance.md
docs/wireframe.pdf
README.md
CHANGELOG.md
```

## Cara Menjalankan

1. Buka Visual Studio Code, pilih File > Open Folder, lalu pilih folder proyek ini.
2. Pasang ekstensi Live Server dari Ritwick Dey (cukup sekali).
3. Klik kanan index.html, lalu pilih Open with Live Server.
4. Browser akan membuka alamat lokal, misalnya http://127.0.0.1:5500/index.html.

Halaman juga dapat dibuka langsung dengan mengklik dua kali index.html.

## Mengubah Konten

- Teks, harga, alamat, dan jam buka diubah pada index.html.
- Warna dan tata letak diubah pada css/style.css (warna ada di bagian :root).
- Jika nomor WhatsApp atau akun Instagram sudah ditentukan, ganti teks "Segera tersedia" pada bagian Kontak dengan tautan, misalnya https://wa.me/ diikuti nomor, dan https://instagram.com/ diikuti nama akun.
- Setiap perubahan dicatat pada CHANGELOG.md.

## Pengujian

Rencana dan hasil pengujian dicatat pada docs/testing.md. Uji pada lebar 360, 390, 768, dan 1366 px dengan Chrome dan Firefox.

## Hak Gambar

Logo dan foto menu merupakan aset milik kelompok.

## Lisensi

Proyek pembelajaran, bukan untuk penggunaan komersial.
