# BioVIRUS 10 - Media Pembelajaran Interaktif Biologi (Kurikulum Merdeka)

Media Pembelajaran Interaktif Mata Pelajaran Biologi SMA Kelas 10 Materi **Virus dan Peranannya** berbasis Kurikulum Merdeka. Aplikasi ini dirancang dengan pendekatan *mobile-first* dan **Bottom Navigation Toolbar** agar nyaman diakses di smartphone maupun desktop.

![Preview App](https://img.shields.io/badge/Kurikulum-Merdeka-emerald?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-blue?style=for-the-badge)

---

## 🌟 Fitur Utama

1. **Bottom Toolbar Navigation (Mobile-First)**:
   - 🏠 **Beranda**: Capaian Pembelajaran (CP), Peta Konsep, Sejarah Penemuan Virus, dan Sifat-sifat khusus.
   - 🧬 **Struktur**: Eksplorator Anatomi Virus SVG Interaktif (Bakteriofag T4 & Coronavirus) dengan titik organel bernomor yang dapat diklik.
   - 🔄 **Replikasi**: Visualisasi Stepper perbandingan **Siklus Litik** vs **Siklus Lisogenik** beserta tabel perbandingan.
   - 🦠 **Peranan & Video**: Katalog Peran Menguntungkan, Peran Merugikan, Pencegahan (Vaksinasi & PHBS), serta **Player Video YouTube Embedded** (`https://www.youtube.com/watch?v=8glI_X1XoBE`).
   - 📝 **Kuis 20 Soal Bergambar & Glosarium**: 20 Soal Pilihan Ganda dengan diagram SVG interaktif, indikator jawaban langsung, pembahasan, skor otomatis, dan kamus glosarium.

---

## 🛠️ Cara Menjalankan Secara Lokal

1. **Clone repositori**:
   ```bash
   git clone https://github.com/afifmashum61-oss/virus.git
   cd virus
   ```

2. **Jalankan server lokal (Pilih salah satu)**:
   - Menggunakan Python:
     ```bash
     python -m http.server 8080
     ```
   - Menggunakan PowerShell (Windows):
     ```powershell
     powershell -ExecutionPolicy Bypass -File server.ps1
     ```

3. **Buka di Browser**:
   Buka `http://localhost:8080` di browser favorit Anda!

---

## 📄 Lisensi
[MIT License](LICENSE) - Bebas digunakan dan dikembangkan untuk keperluan pendidikan.
