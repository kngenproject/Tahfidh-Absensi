<div align="center">

# 📖 Tamma-Tahfidh Juz Amma

### Aplikasi Manajemen Hafalan Al-Qur'an Juz Amma Berbasis Web

<br/>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)](https://www.chartjs.org/)
[![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)

<br/>

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square)](https://github.com/)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red.svg?style=flat-square)](https://github.com/)
[![Platform](https://img.shields.io/badge/Platform-Mobile%20%7C%20Web-blue.svg?style=flat-square)](https://github.com/)
[![Language](https://img.shields.io/badge/Language-Indonesia-red.svg?style=flat-square)](https://github.com/)

<br/>

> **Solusi digital lengkap untuk para ustadz/ustadzah dalam mengelola, memantau, dan mendokumentasikan progress hafalan Juz Amma santri secara real-time.**

</div>

---

## 📋 Daftar Isi

- [✨ Tentang Aplikasi](#-tentang-aplikasi)
- [🚀 Fitur Unggulan](#-fitur-unggulan)
- [🖥️ Tampilan Aplikasi](#️-tampilan-aplikasi)
- [🛠️ Teknologi yang Digunakan](#️-teknologi-yang-digunakan)
- [⚙️ Instalasi & Konfigurasi](#️-instalasi--konfigurasi)
- [📱 Cara Penggunaan](#-cara-penggunaan)
- [📁 Struktur Proyek](#-struktur-proyek)
- [🔥 Konfigurasi Firebase](#-konfigurasi-firebase)
- [📤 Export Data](#-export-data)
- [🌐 PWA & Offline Support](#-pwa--offline-support)
- [🤝 Kontribusi](#-kontribusi)
- [📄 Lisensi](#-lisensi)

---

## ✨ Tentang Aplikasi

**Tamma-Tahfidh Juz Amma** adalah aplikasi web progresif (PWA) yang dirancang khusus untuk membantu lembaga pendidikan Al-Qur'an, TPQ, madrasah, dan pesantren dalam mengelola program tahfidh (hafalan) Juz Amma (Juz 30) secara efisien dan terstruktur.

Aplikasi ini menggabungkan kemudahan antarmuka mobile-first dengan kekuatan database cloud Firebase, sehingga data santri dapat diakses kapan saja dan di mana saja secara real-time oleh seluruh pengajar yang berwenang.

### 🎯 Tujuan Utama

- Menggantikan pencatatan manual hafalan yang rawan kesalahan dan kehilangan data
- Memberikan visualisasi progress hafalan yang jelas dan mudah dipahami
- Memudahkan pelaporan kepada wali santri dan pimpinan lembaga
- Menyediakan data historis yang lengkap dan terstruktur

---

## 🚀 Fitur Unggulan

### 🏠 Dashboard Beranda
- **Ringkasan statistik** jumlah santri aktif, total setoran hari ini, dan rata-rata progress
- **Notifikasi & pengumuman** terkini
- **Quick action** untuk menandai kehadiran massal dengan satu klik
- **Indikator koneksi** online/offline secara real-time

### 📖 Manajemen Tahfidh (Hafalan)
- **Pencatatan setoran** per surat dan per ayat dengan validasi otomatis
- **3 mode setoran**: Belum Khatam, Muroja'ah, dan Tasmi'
- **Tracking progress** hafalan per siswa secara visual (progress bar)
- **Pencapaian awal** (input data hafalan existing) dengan mode otomatis & manual
- **Filter per kelas** untuk mempercepat navigasi
- **Riwayat setoran** lengkap dengan detail tanggal dan catatan

### 👥 Absensi Harian
- **Pencatatan kehadiran** dengan 4 status: Hadir, Ijin, Sakit, Alpha
- **Riwayat absensi** per tanggal dengan detail lengkap
- **Filter kelas** dalam tampilan absensi
- **Reset absensi harian** dengan konfirmasi
- **Export per kelas** untuk distribusi laporan

### 📊 Statistik & Analitik
- **Grafik progress** hafalan keseluruhan menggunakan Chart.js
- **Statistik per surat** Juz Amma (37 surat, Al-Fatihah s.d. An-Nas)
- **Perbandingan antar kelas** untuk evaluasi program
- **Tren setoran** harian, mingguan, dan bulanan
- **Highlight pencapaian** santri terbaik

### 📋 Viewer Data
- **Tampilan tabel** data setoran dan absensi yang bisa difilter
- **Pencarian** santri berdasarkan nama atau kelas
- **Preview import** sebelum data masuk ke database
- **Deteksi kolom otomatis** saat import Excel

### 👤 Manajemen Siswa
- **Import massal** dari file Excel (.xlsx)
- **Tambah siswa manual** satu per satu
- **Edit data siswa**: nama, kelas, dan status
- **Status santri**: Aktif, Lulus, Arsip/Pindah
- **Filter per kelas** dan status

### 📤 Export & Laporan
- **Export ke Excel** untuk absensi harian, per kelas, dan rekap setoran
- **Laporan setoran** per tanggal dengan detail lengkap
- **Format laporan** profesional siap cetak

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Versi | Kegunaan |
|-----------|-------|----------|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=flat-square) HTML5 | Latest | Struktur antarmuka |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white&style=flat-square) CSS3 | Latest | Styling & animasi |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square) Vanilla JS | ES2020+ | Logika aplikasi |
| ![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?logo=firebase&logoColor=black&style=flat-square) Firebase | 10.7.1 | Database & autentikasi |
| ![Chart.js](https://img.shields.io/badge/-Chart.js-FF6384?logo=chart.js&logoColor=white&style=flat-square) Chart.js | 4.4.0 | Visualisasi data |
| ![SheetJS](https://img.shields.io/badge/-SheetJS-217346?logo=microsoftexcel&logoColor=white&style=flat-square) SheetJS (XLSX) | 0.18.5 | Import/Export Excel |
| ![PWA](https://img.shields.io/badge/-PWA-5A0FC8?logo=pwa&logoColor=white&style=flat-square) PWA | - | Instalasi mobile & offline |

### Arsitektur
```
Frontend (SPA)  ──►  Firebase Firestore (NoSQL Cloud DB)
     │
     ├── Vanilla HTML/CSS/JS (Single File App)
     ├── Mobile-first Responsive Design
     ├── PWA (installable, offline-capable)
     └── LocalStorage (cache & state lokal)
```

---

## ⚙️ Instalasi & Konfigurasi

### Prasyarat

Pastikan Anda memiliki:
- Akun [Google Firebase](https://firebase.google.com/) (gratis)
- Browser modern (Chrome, Safari, Firefox, Edge)
- Koneksi internet untuk setup awal

### Langkah 1 — Clone Repositori

```bash
git clone https://github.com/username/tamma-tahfidh-juz-amma.git
cd tamma-tahfidh-juz-amma
```

### Langkah 2 — Setup Firebase

1. Buka [Firebase Console](https://console.firebase.google.com/)
2. Klik **"Add project"** → isi nama proyek (misal: `tamma-tahfidh`)
3. Aktifkan **Firestore Database** (pilih mode *production* atau *test*)
4. Buka **Project Settings** → **General** → salin konfigurasi Firebase

### Langkah 3 — Konfigurasi Aplikasi

Buka file `index.html` dan cari bagian konfigurasi Firebase, lalu ganti dengan data proyek Anda:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

### Langkah 4 — Jalankan Aplikasi

Karena ini adalah **Single File App**, tidak perlu build process. Cukup:

```bash
# Opsi 1: Buka langsung di browser
open index.html

# Opsi 2: Gunakan live server (VSCode extension)
# Install "Live Server" → klik kanan index.html → "Open with Live Server"

# Opsi 3: Deploy ke hosting (disarankan untuk penggunaan tim)
# Firebase Hosting, Vercel, Netlify, GitHub Pages, dll.
```

### Langkah 5 — Deploy ke Firebase Hosting (Opsional)

```bash
# Install Firebase CLI
npm install -g firebase-tools

# Login ke Firebase
firebase login

# Inisialisasi project
firebase init hosting

# Deploy
firebase deploy
```

---

## 📱 Cara Penggunaan

### 🔰 Setup Pertama Kali

```
1. Buka aplikasi di browser
2. Masuk ke halaman "Absen" atau "Tahfidh"
3. Import data santri melalui tombol "Import Excel"
   - Siapkan file .xlsx dengan kolom: Nama Siswa, Kelas
4. Atau tambah manual via tombol "Tambah Siswa"
```

### 📖 Mencatat Setoran Hafalan

```
1. Buka tab "Tahfidh"
2. Pilih nama santri dari daftar
3. Pilih surat yang disetorkan
4. Tentukan rentang ayat
5. Pilih keterangan: Belum Khatam / Muroja'ah / Tasmi'
6. Klik "Simpan Setoran"
```

### ✅ Mencatat Absensi

```
1. Buka tab "Absen"
2. Gunakan FAB (tombol bulat bawah) untuk "Tandai Semua Hadir"
3. Ubah status santri yang tidak hadir secara individual
4. Data tersimpan otomatis ke Firebase
```

### 📊 Melihat Statistik

```
1. Buka tab "Statistik"
2. Pilih rentang waktu atau filter kelas
3. Grafik akan otomatis diperbarui
```

---

## 📁 Struktur Proyek

```
tamma-tahfidh-juz-amma/
│
├── index.html              # Seluruh aplikasi (Single File App)
│   ├── <head>              # Meta, PWA config, CDN scripts
│   ├── <style>             # CSS Variables, komponen, responsif
│   ├── <body>
│   │   ├── #pgwrap         # Container 6 halaman (sliding)
│   │   │   ├── #pg0        # Beranda / Dashboard
│   │   │   ├── #pg1        # Tahfidh (Hafalan)
│   │   │   ├── #pg2        # Absensi
│   │   │   ├── #pg3        # Statistik
│   │   │   ├── #pg4        # Viewer
│   │   │   └── #pg5        # Tentang
│   │   ├── .bnav           # Bottom Navigation Bar
│   │   └── [Modals]        # Edit, Import, Preview, Detail
│   └── <script>            # Semua logika JavaScript
│
├── README.md               # Dokumentasi ini
└── LICENSE                 # Lisensi MIT
```

---

## 🔥 Konfigurasi Firebase

### Koleksi Firestore yang Digunakan

| Koleksi | Deskripsi | Contoh Dokumen |
|---------|-----------|----------------|
| `siswa` | Data master santri | `{ nama, kelas, status, createdAt }` |
| `setoran` | Riwayat setoran hafalan | `{ siswaId, surat, ayatMulai, ayatAkhir, keterangan, tanggal }` |
| `absensiHarian` | Data kehadiran harian | `{ tanggal, siswa: [{nama, kelas, status, waktu}] }` |
| `pencapaianAwal` | Data hafalan awal santri | `{ siswaId, suratHafal: [], tanggal }` |

### Rules Firestore (Contoh)

```javascript
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    // Sesuaikan dengan kebutuhan autentikasi Anda
    match /{document=**} {
      allow read, write: if true; // Development only
      // Production: gunakan autentikasi Firebase
    }
  }
}
```

> ⚠️ **Catatan Keamanan**: Untuk produksi, aktifkan Firebase Authentication dan sesuaikan Firestore Rules agar data hanya bisa diakses oleh pengguna yang berwenang.

---

## 📤 Export Data

Aplikasi mendukung export ke format **Excel (.xlsx)** untuk berbagai keperluan:

| Jenis Export | Deskripsi | Lokasi |
|---|---|---|
| Absensi Harian | Rekap kehadiran satu tanggal | Tab Absen → Detail Tanggal |
| Absensi Per Kelas | File terpisah per kelas | Tab Absen → Detail Tanggal |
| Setoran Per Tanggal | Rekap setoran satu hari | Tab Statistik → Detail Setoran |
| Setoran Per Kelas | Dikelompokkan per kelas | Tab Statistik → Detail Setoran |

---

## 🌐 PWA & Offline Support

Aplikasi ini adalah **Progressive Web App (PWA)** yang dapat:

- 📲 **Diinstal** di layar utama HP (Android & iOS)
- 🔌 **Bekerja offline** untuk data yang sudah di-cache
- 🔔 **Notifikasi** status koneksi (online/offline)
- 📐 **Responsif** untuk semua ukuran layar
- ⚡ **Performa tinggi** dengan desain mobile-first

### Cara Install di HP

**Android (Chrome):**
```
Buka aplikasi → Klik ikon "Add to Home Screen" di banner bawah
atau Menu Chrome (⋮) → "Add to Home Screen"
```

**iOS (Safari):**
```
Buka aplikasi → Klik tombol Share (□↑) → "Add to Home Screen"
```

---

## 🤝 Kontribusi

Kontribusi sangat diterima! Berikut cara berkontribusi:

### Cara Berkontribusi

1. **Fork** repositori ini
   ```bash
   # Klik tombol "Fork" di pojok kanan atas halaman GitHub
   ```

2. **Clone** fork Anda
   ```bash
   git clone https://github.com/username-anda/tamma-tahfidh-juz-amma.git
   ```

3. **Buat branch** untuk fitur/perbaikan Anda
   ```bash
   git checkout -b feature/nama-fitur-baru
   # atau
   git checkout -b fix/nama-bug-yang-diperbaiki
   ```

4. **Commit** perubahan Anda
   ```bash
   git add .
   git commit -m "feat: tambah fitur export PDF laporan bulanan"
   ```

5. **Push** ke branch Anda
   ```bash
   git push origin feature/nama-fitur-baru
   ```

6. Buat **Pull Request** ke branch `main`

### Panduan Commit Message

```
feat:     Fitur baru
fix:      Perbaikan bug
docs:     Perubahan dokumentasi
style:    Perubahan formatting/style (bukan logika)
refactor: Refaktor kode
test:     Penambahan atau perbaikan test
chore:    Perubahan build/config
```

### Ide Pengembangan

- [ ] 🔐 Autentikasi multi-pengguna (guru per kelas)
- [ ] 📊 Laporan PDF otomatis
- [ ] 🔔 Push notification pengingat setoran
- [ ] 🌙 Dark mode
- [ ] 🌍 Dukungan multi-bahasa
- [ ] 📅 Kalender setoran dan absensi
- [ ] 🏆 Sistem reward dan leaderboard santri
- [ ] 📧 Email laporan mingguan otomatis

---

## 🐛 Melaporkan Bug

Temukan bug? Silakan [buka issue baru](https://github.com/username/tamma-tahfidh-juz-amma/issues/new) dengan:

- **Judul** yang deskriptif
- **Langkah reproduksi** bug
- **Screenshot** jika memungkinkan
- **Informasi device/browser** Anda

---

## ❓ FAQ

<details>
<summary><b>Apakah data aman tersimpan di Firebase?</b></summary>
Ya, Firebase Firestore menggunakan enkripsi data-in-transit (TLS) dan data-at-rest. Untuk keamanan maksimal, aktifkan Firebase Authentication dan atur Firestore Security Rules yang ketat.
</details>

<details>
<summary><b>Apakah bisa digunakan tanpa internet?</b></summary>
Aplikasi memiliki dukungan offline parsial — data yang sudah di-cache dapat dilihat, namun perubahan baru membutuhkan koneksi internet untuk tersimpan ke Firebase.
</details>

<details>
<summary><b>Berapa banyak santri yang bisa dikelola?</b></summary>
Tidak ada batas dari sisi aplikasi. Batas praktis bergantung pada kuota Firebase (paket Spark gratis: 1GB penyimpanan, 50.000 pembacaan/hari).
</details>

<details>
<summary><b>Apakah bisa digunakan untuk Juz selain Juz 30?</b></summary>
Saat ini aplikasi difokuskan untuk Juz Amma (Juz 30). Pengembangan untuk Juz lain ada dalam roadmap.
</details>

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License** — lihat file [LICENSE](LICENSE) untuk detail lengkap.

```
MIT License

Copyright (c) 2024 Tamma-Tahfidh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions: ...
```

---

<div align="center">

### 🌟 Jika aplikasi ini bermanfaat, jangan lupa beri bintang!

[![GitHub stars](https://img.shields.io/github/stars/username/tamma-tahfidh-juz-amma?style=social)](https://github.com/username/tamma-tahfidh-juz-amma/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/username/tamma-tahfidh-juz-amma?style=social)](https://github.com/username/tamma-tahfidh-juz-amma/network/members)
[![GitHub watchers](https://img.shields.io/github/watchers/username/tamma-tahfidh-juz-amma?style=social)](https://github.com/username/tamma-tahfidh-juz-amma/watchers)

<br/>

**Dibuat dengan ❤️ untuk kemudahan para pengajar Al-Qur'an**

*"وَرَتِّلِ الْقُرْآنَ تَرْتِيلًا"*
*"Dan bacalah Al-Qur'an itu dengan tartil (perlahan-lahan)."*
*(QS. Al-Muzzammil: 4)*

<br/>

[![forthebadge](https://img.shields.io/badge/Built%20For-Quran%20Teachers-1a7040?style=for-the-badge&logo=quora&logoColor=white)](https://github.com/)
[![forthebadge](https://img.shields.io/badge/Powered%20By-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)

</div>
