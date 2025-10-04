# 🌈 EduLearn

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/eggball1945/web-pendidikan?style=social)](https://github.com/username/repo-edu-learn/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/eggball1945/web-pendidikan?style=social)](https://github.com/username/repo-edu-learn/network/members)

EduLearn adalah platform pembelajaran interaktif berbasis web yang memungkinkan pengguna untuk menambahkan, menonton, dan belajar dari **video edukatif** secara mudah. Website ini dibangun menggunakan **HTML, CSS, Bootstrap, dan JavaScript**, memanfaatkan **localStorage** untuk menyimpan data video tanpa backend.

---

## 🔹 Fitur Utama

- Navbar modern dengan efek blur dan efek scroll
- Form tambah video interaktif (Judul, Link YouTube, Deskripsi)
- Daftar video yang dapat **diedit** atau **dihapus**
- Animasi background gradient yang dinamis
- Card materi dengan ukuran gambar **konsisten** menggunakan `object-fit: cover`
- Responsif di desktop, tablet, dan mobile
- Storage lokal menggunakan **localStorage**

---

## 🔹 Instalasi

1. Clone repositori:

```bas
git clone https://github.com/username/repo-edu-learn.git
```

Copy code
```bas
cd web-pendidikan
```
Buka index.html di browser atau gunakan Live Server di VS Code.

🔹 Struktur Folder
repo-edu-learn/
│
├─ index.html           # Halaman landing
├─ add-materi.html      # Halaman tambah video
├─ materi.html          # Halaman daftar materi
├─ style.css            # CSS utama
└─ README.md            # Dokumentasi

🔹 Cara Menambahkan Video
Buka halaman add-materi.html.

Isi form:

Judul Video

Link YouTube (embed)
1. Buka bagian bagikan
2. Klik sematkan
3. Cari dan salin link contoh : https://www.youtube.com/embed/dV_lf1kyV9M?si=-U6blkbhmNJLW5Lq

Deskripsi

Klik tombol Simpan.

Video akan muncul di daftar di bawah form.

Video tersimpan di localStorage sehingga tetap ada meskipun halaman direload.

🔹 Tampilan Proyek
Landing Page

Form Tambah Video

Daftar Video

🔹 Kontribusi
Fork repositori ini

Buat branch fitur: git checkout -b fitur-baru

Commit perubahan: git commit -m "Tambah fitur baru"

Push branch: git push origin fitur-baru

Buat Pull Request

🔹 Lisensi
MIT License © 2025

Dibuat dengan ❤️ oleh kaka ibal tercinta
