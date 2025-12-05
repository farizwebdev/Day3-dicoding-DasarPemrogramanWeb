# Submission Tugas Akhir: Belajar Dasar Pemrograman Web

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

Website ini adalah portofolio pribadi yang dirancang dan dibangun dari nol menggunakan HTML5 dan CSS3 murni. Proyek ini dibuat untuk memenuhi kriteria kelulusan kelas "Belajar Dasar Pemrograman Web" di Dicoding, menampilkan profil, latar belakang pendidikan, dan keahlian teknis saya sebagai mahasiswa Informatika.

---

## Deskripsi Proyek

Website ini berfungsi sebagai *landing page* personal yang responsif. Konten utamanya meliputi:
* **Tentang Saya**: Perkenalan diri sebagai mahasiswa Informatika UIN Sunan Kalijaga dengan minat pada UI/UX dan Data Analysis.
* **Pendidikan**: Riwayat pendidikan formal dari MA Wahid Hasyim hingga jenjang universitas saat ini.
* **Skill**: Daftar kemampuan teknis yang dimiliki (HTML, CSS, JS, Python).
* **Biodata**: Informasi personal tambahan yang diletakkan pada *sidebar*.

Desain visual menggunakan tema warna merah maroon (`#781919`) yang konsisten, memberikan kesan profesional dan berani.

## Fitur Utama

1.  **Responsive Layout (Mobile-First/Adaptive)**:
    * Tampilan menyesuaikan berbagai ukuran layar (Desktop, Tablet, Mobile) menggunakan *CSS Media Queries*.
    * Pada layar kecil (< 768px), layout berubah menjadi satu kolom vertikal untuk kemudahan navigasi.
2.  **Semantic HTML5**:
    * Penggunaan tag semantik yang tepat (`<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>`) untuk struktur dokumen yang baik dan SEO-friendly.
3.  **Sticky Navigation Bar**:
    * Menu navigasi tetap menempel di bagian atas layar saat pengguna melakukan *scroll* ke bawah.
4.  **Flexbox Styling**:
    * Tata letak elemen diatur menggunakan Flexbox untuk kerapian dan fleksibilitas konten.
5.  **Custom CSS**:
    * Tidak menggunakan framework CSS (seperti Bootstrap/Tailwind), murni menggunakan *custom style* untuk pembelajaran mendalam.

## Teknologi yang Digunakan

* **HTML5**: Markup bahasa untuk struktur konten.
* **CSS3**: Styling halaman, layouting (Flexbox), dan responsivitas.
* **Google Fonts**: Menggunakan font **'Quicksand'** untuk tipografi yang modern dan mudah dibaca.
* **VS Code**: Code editor yang digunakan selama pengembangan.

## Struktur Folder

Berikut adalah struktur direktori dari proyek ini:

```text
Submission_Fariz Husain Albar/
│
├── assets/
│   ├── gambar/
│   │   ├── foto_fariz.jpg          # Foto profil utama
│   │   ├── tentang_saya.jpeg       # Gambar section tentang saya
│   │   ├── pendidikan.jpg          # Gambar header section pendidikan
│   │   ├── skill.jpeg              # Gambar ilustrasi skill
│   │   ├── ma_wahid_hasyim.png     # Logo/Foto MA
│   │   └── uin_sunan_kalijaga.jpg  # Foto UIN Suka
│   │
│   └── styles/
│       └── style.css               # File CSS utama (Styling)
│
├── index.html                      # Halaman utama website
└── README.md                       # Dokumentasi proyek (File ini)
