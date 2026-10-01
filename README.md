# 🏛️ Website Promosi Wisata Candi Borobudur

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![UNPAM](https://img.shields.io/badge/Universitas_Pamulang-Teknik_Informatika-003366?style=for-the-badge)](https://unpam.ac.id)
[![GitHub Pages](https://img.shields.io/badge/Live_Demo-GitHub_Pages-2EA44F?style=for-the-badge&logo=github)](https://h45t4ck.github.io/Pemro-web-wisata/)

Website promosi objek wisata **Candi Borobudur** berbasis HTML5. Dibuat untuk memenuhi tugas terstruktur mata kuliah **Pemrograman Web 1 (Pertemuan 7)** di Universitas Pamulang, dengan menerapkan tata letak (*layout*) menggunakan elemen **Tabel** serta integrasi multimedia.

---

## 🌐 Live Demo

Situs ini dapat diakses secara *live* melalui link berikut:
👉 **[https://h45t4ck.github.io/Pemro-web-wisata/](https://h45t4ck.github.io/Pemro-web-wisata/)**

---

## ✨ Fitur Utama & Integrasi Modul

Proyek ini menggabungkan seluruh materi pembelajaran praktikum **Pertemuan 1 hingga Pertemuan 7**:

- 📐 **Layout Berbasis Tabel (P3 & P7):** Pembagian struktur halaman menjadi *Header*, *Navigation Bar*, *Main Content* (kolom kiri `480px`), *Sidebar* (kolom kanan `220px`), dan *Footer*.
- ⚓ **Navigasi Internal & Eksternal (P5):** 
  - *Anchor Bookmark* (`#tentang`, `#fasilitas`, `#tiket`, `#video`) untuk *jump-link* cepat di halaman yang sama.
  - Link eksternal ke portal tiket resmi (`target="_blank"`).
  - Link kontak email pengelola (`mailto:`).
- 🎬 **Penyematan Multimedia (P4):**
  - Galeri foto utama Candi Borobudur (`<img>`).
  - Pemutar video dokumenter MP4 dengan kontrol (`<video controls>`).
  - Pemutar musik pengiring gamelan MP3 (`<audio controls>`).
- 📊 **Pengolahan Tabel Kompleks (P3):** Tabel rincian harga tiket lokal vs mancanegara menggunakan teknik penggabungan sel (`rowspan` & `colspan`).
- 📝 **Format Teks & List Bersarang (P1 & P2):** Penataan informasi menggunakan *heading*, paragraf, serta *nested list* (`<ol type="A">` dan `<ul>`).

---

## 📁 Struktur Folder

```text
Pemro-web-wisata/
├── index.html           # Halaman utama website
├── README.md            # Dokumentasi repositori
├── gambar/              # Berisi aset gambar (.jpg)
│   └── borobudur.jpg
├── video/               # Berisi aset video (.mp4)
│   └── borobudur.mp4
└── musik/               # Berisi aset audio (.mp3)
    └── gamelan.mp3
