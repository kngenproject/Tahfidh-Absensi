# Tahfidh & Absensi PWA

Aplikasi Progressive Web App (PWA) untuk pencatatan presensi siswa dan rekapitulasi setoran hafalan Al-Qur'an (Tahfidh).

## Fitur Utama

- Presensi Siswa: Pencatatan kehadiran harian siswa secara terstruktur.
- Pencatatan Tahfidh: Monitoring dan rekapitulasi setoran hafalan Al-Qur'an / Juz 'Amma.
- PWA & Offline Support: Terintegrasi dengan Service Worker (sw.js) & Web App Manifest.
- Auto Deployment: Integrasi CI/CD dengan GitHub Actions ke Firebase Hosting.

## Stack & Teknologi

- Frontend: HTML5, CSS3, Vanilla JavaScript
- PWA: Web App Manifest (manifest.json) & Service Worker (sw.js)
- Hosting: Firebase Hosting (tahfidh-dan-absensi)
- CI/CD Pipeline: GitHub Actions (.github/workflows/firebase-deploy.yml)

## Struktur Repositori

Tahfidh-Absensi/
├── .github/workflows/    # Workflow deployment otomatis
├── assets/               # File aset CSS, JS, dan gambar
├── icons/                # Ikon PWA
├── index.html            # Tampilan utama aplikasi
├── manifest.json         # PWA Manifest
├── sw.js                 # Service Worker cache
├── firebase.json         # Konfigurasi Firebase Hosting
└── README.md             # Dokumentasi proyek

## Alur Kerja & Deployment

1. Commit dan push perubahan ke branch main:
   git add .
   git commit -m 'Update application'
   git push origin main
2. GitHub Actions akan otomatis mendeploy aplikasi ke Firebase Hosting.
