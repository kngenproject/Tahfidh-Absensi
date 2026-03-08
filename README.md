# 📖 Tamma — Tahfidh Juz Amma

Aplikasi manajemen tahfidh Al-Qur'an Juz 30 berbasis web, lengkap dengan:

- ✅ Tracking setoran per siswa & surat
- ✅ Absensi harian dengan status (Hadir/Ijin/Sakit/Alpha)
- ✅ Dashboard statistik & grafik
- ✅ Ekspor laporan ke Excel (.xlsx)
- ✅ Sistem login via Google (Firebase Auth)
- ✅ Sinkronisasi data real-time (Firebase Firestore)
- ✅ Mode offline (Service Worker + localStorage)
- ✅ Progressive Web App (installable)
- ✅ Panel Admin (kelola siswa, guru, kode undangan, tahun ajaran)

## 🚀 Deploy

App ini di-deploy otomatis ke **Firebase Hosting** setiap kali ada push ke branch `main` atau `master` via GitHub Actions.

**URL:** https://tahfidh-dan-absensi.web.app

## 🔧 Setup GitHub Actions

Agar auto-deploy berjalan, tambahkan secret berikut di repo GitHub:

1. Buka **Settings → Secrets and variables → Actions**
2. Tambahkan secret:
   - **Name:** `FIREBASE_SERVICE_ACCOUNT`
   - **Value:** isi dengan Service Account JSON dari Firebase Console

Cara dapat Service Account JSON:
1. Buka [Firebase Console](https://console.firebase.google.com)
2. Project Settings → Service Accounts
3. Generate new private key → Download JSON
4. Copy isi file JSON → paste sebagai value secret

## 🗂️ Struktur Folder

```
├── public/
│   └── index.html        # Aplikasi utama (single file)
├── .github/
│   └── workflows/
│       └── firebase-deploy.yml   # Auto-deploy workflow
├── firebase.json         # Firebase Hosting config
├── .firebaserc           # Firebase project config
└── .gitignore
```

## 🛡️ Firebase Security Rules (Firestore)

Pastikan Firestore Rules sudah dikonfigurasi dengan benar di Firebase Console agar hanya user yang terautentikasi yang bisa mengakses data.

---

Made with ❤️ untuk kemudahan hafalan Juz Amma
