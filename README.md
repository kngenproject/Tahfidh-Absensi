<div align="center">

<img src="https://img.shields.io/badge/🕌-Tamma--Tahfidh-0c4a2a?style=for-the-badge&labelColor=145c35" alt="Tamma-Tahfidh" height="40"/>

# 📖 Tamma-Tahfidh — Sistem Manajemen Tahfidh Juz Amma

**Aplikasi pelacak hafalan Al-Qur'an Juz 30 berbasis web, modern, dan siap digunakan secara offline.**

---

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)](https://web.dev/progressive-web-apps/)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat-square)](LICENSE)
[![Offline Ready](https://img.shields.io/badge/Offline-Ready-brightgreen?style=flat-square&logo=serviceworker)](.)
[![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-blue?style=flat-square&logo=android)](.)
[![Single File](https://img.shields.io/badge/Deploy-Single%20File-orange?style=flat-square)](index.html)

</div>

---

## 🌟 Tentang Aplikasi

**Tamma-Tahfidh** adalah aplikasi manajemen tahfidh Al-Qur'an Juz Amma yang dirancang khusus untuk **guru, ustadz/ustadzah, dan pengelola pesantren/madrasah**. Dengan tampilan mobile-first yang bersih dan intuitif, seluruh proses pencatatan hafalan, absensi, hingga evaluasi dapat dilakukan langsung dari smartphone — bahkan tanpa koneksi internet.

> _"Tamma"_ berarti **sempurna/selesai** dalam bahasa Arab — mencerminkan semangat khatam Juz Amma bersama para santri.

---

## ✨ Fitur Utama

### 📚 Manajemen Setoran Hafalan
- Input setoran per surat dan per ayat dengan tampilan grid interaktif
- Evaluasi kesalahan bacaan (tajwid, makhraj, dll.)
- Riwayat setoran lengkap dengan detail per tanggal
- Export laporan setoran ke **Excel (.xlsx)**

### 🧑‍🎓 Manajemen Siswa
- Tambah siswa secara manual atau **import massal via Excel**
- Edit nama, kelas, dan status siswa (Aktif / Lulus / Arsip)
- Pencapaian awal — catat hafalan siswa yang sudah ada sebelum menggunakan aplikasi
- Filter dan kelola siswa per kelas

### 📋 Absensi Digital
- Catat kehadiran harian dengan cepat
- Riwayat absensi per tanggal
- Export data absensi ke Excel (keseluruhan atau per kelas)
- Hapus data absensi yang salah

### 📊 Statistik & Progres
- Visualisasi progres hafalan dengan **Chart.js**
- Ringkasan jumlah surat & ayat yang sudah dihafal per siswa
- Tampilan pencapaian kelompok (summary per kelas)

### 📱 Progressive Web App (PWA)
- **Offline Ready** — berfungsi penuh tanpa internet setelah pertama kali dibuka
- **Installable** — dapat dipasang di layar utama Android & iOS
- Responsif untuk semua ukuran layar

### ☁️ Sinkronisasi Cloud
- Didukung **Firebase Firestore** untuk sinkronisasi data real-time
- Data aman tersimpan di cloud dan dapat diakses dari perangkat manapun

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Versi | Keterangan |
|-----------|-------|------------|
| HTML5 / CSS3 / JS | — | Single-file app, tanpa framework |
| [Firebase](https://firebase.google.com/) | `10.7.1` | Backend & Firestore database |
| [Chart.js](https://www.chartjs.org/) | `4.4.0` | Grafik & visualisasi data |
| [SheetJS (xlsx)](https://sheetjs.com/) | `0.18.5` | Import/Export file Excel |
| Service Worker | — | Offline caching (PWA) |

---

## 🚀 Cara Penggunaan

### 1. Clone Repository

```bash
git clone https://github.com/kngenproject/tamma-tahfidh.git
cd tamma-tahfidh
```

### 2. Setup Firebase

1. Buka [Firebase Console](https://console.firebase.google.com/) dan buat project baru.
2. Aktifkan **Firestore Database** (mode produksi atau uji coba).
3. Salin konfigurasi Firebase kamu dan tempelkan di bagian berikut dalam `index.html`:

```javascript
const firebaseConfig = {
  apiKey: "...",             // ← isi dengan API Key dari Firebase Console
  authDomain: "....firebaseapp.com",
  projectId: "...",
  storageBucket: "....appspot.com",
  messagingSenderId: "...",
  appId: "..."
};
```

> ⚠️ **Penting:** Jangan pernah meng-commit `firebaseConfig` yang berisi API key asli ke repository publik. Gunakan [Firebase Security Rules](https://firebase.google.com/docs/rules) untuk membatasi akses database.

### 3. Deploy / Buka Aplikasi

Karena aplikasi ini **single-file**, kamu cukup:

```bash
# Opsi A: Buka langsung di browser
open index.html

# Opsi B: Jalankan server lokal sederhana
npx serve .
# atau
python -m http.server 8080
```

> **Rekomendasi hosting:** [Firebase Hosting](https://firebase.google.com/docs/hosting), [GitHub Pages](https://pages.github.com/), atau [Netlify](https://www.netlify.com/) — gratis dan mudah.

---

## 📂 Struktur Proyek

```
tamma-tahfidh/
│
├── index.html        # Seluruh aplikasi dalam satu file (HTML + CSS + JS)
├── README.md         # Dokumentasi proyek
└── LICENSE           # Lisensi MIT
```

---

## 📸 Tampilan Aplikasi

| Halaman Utama | Input Setoran | Statistik |
|:---:|:---:|:---:|
| _(screenshot)_ | _(screenshot)_ | _(screenshot)_ |

> Tambahkan screenshot aplikasi kamu di sini untuk tampilan yang lebih menarik di GitHub.

---

## 🤝 Kontribusi

Kontribusi sangat disambut! Berikut cara berkontribusi:

1. **Fork** repository ini
2. Buat branch fitur baru: `git checkout -b fitur/nama-fitur`
3. Commit perubahan: `git commit -m 'Tambah fitur: nama-fitur'`
4. Push ke branch: `git push origin fitur/nama-fitur`
5. Buat **Pull Request**

Untuk perubahan besar, silakan buka **Issue** terlebih dahulu untuk diskusi.

---

## 🐛 Laporan Bug

Temukan bug? Silakan [buat issue baru](https://github.com/kngenproject/tamma-tahfidh/issues/new) dengan menyertakan:
- Langkah-langkah untuk mereproduksi bug
- Perangkat & browser yang digunakan
- Screenshot (jika ada)

---

## 📜 Lisensi

Proyek ini dilisensikan di bawah **MIT License** — lihat file [LICENSE](LICENSE) untuk detail lengkap.

---

## 🙏 Ucapan Terima Kasih

- [Firebase](https://firebase.google.com/) — Database & hosting
- [Chart.js](https://www.chartjs.org/) — Library grafik
- [SheetJS](https://sheetjs.com/) — Library Excel
- Seluruh guru dan ustadz/ustadzah yang menginspirasi pembuatan aplikasi ini

---

<div align="center">

Dibuat dengan ❤️ untuk kemudahan para pengajar tahfidh

**بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيم**

⭐ Jika aplikasi ini bermanfaat, jangan lupa **beri bintang** pada repository ini!

</div>
