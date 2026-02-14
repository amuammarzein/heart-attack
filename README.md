# ❤️ Heart Attack: Deteksi Tangan, Isi Daya, Hancurkan!

Game web bertema cyber-noir yang intens di mana gerakan tanganmu adalah senjata utama! Menggunakan **MediaPipe Hands AI**, pemain harus mengisi daya energi melalui gestur hati untuk menghancurkan virus sistem yang menginfeksi.

![Lisensi](https://img.shields.io/badge/license-MIT-blue.svg)
![Teknologi](https://img.shields.io/badge/AI-MediaPipe-green.svg)
![Library](https://img.shields.io/badge/Library-jQuery-orange.svg)

---

## 🚀 Fitur Utama

-   **AI Motion Tracking:** Pelacakan tangan real-time menggunakan MediaPipe (tidak butuh stik/controller!).
-   **Boss Battle System:** Pertarungan epik melawan Boss yang berevolusi dalam 3 fase serangan yang berbeda.
-   **Love Gesture Mechanic:** Gunakan gestur tangan berbentuk hati untuk mengisi daya serangan (Kinetic Charging).
-   **HUD Interaktif:** Bar kesehatan Boss, indikator pengisian daya (syncing), dan sistem timer serangan.
-   **Procedural Audio:** Efek suara synth futuristik yang dihasilkan langsung oleh kode secara internal.

## 🛠️ Dibuat Menggunakan

* **MediaPipe Hands:** Untuk deteksi gestur tangan dan titik biometrik yang akurat.
* **HTML5 Canvas:** Untuk rendering pertarungan, efek petir, dan sistem partikel.
* **jQuery:** Untuk manipulasi UI, transisi menu, dan feedback status game.
* **Google Fonts (Orbitron):** Memberikan tampilan futuristik ala sci-fi.

---

## 📖 Panduan Pemakaian (User Guide)

Agar pengalaman bermain maksimal, ikuti langkah berikut:

### 1. Persiapan Perangkat
* Pastikan laptop/komputer kamu memiliki **Webcam** yang berfungsi.
* Pastikan pencahayaan cukup agar AI bisa mendeteksi kedua tangan dengan jelas.

### 2. Memulai Game
* Buka file `index.html` di browser (Disarankan Google Chrome atau Edge).
* Klik **"Allow/Izinkan"** saat browser meminta akses kamera.
* Klik tombol **"START MISSION"** untuk memulai operasi pembersihan virus.

### 3. Cara Bermain
* **Isi Daya:** Satukan kedua tangan membentuk hati (Love Gesture) dan gerakkan tanganmu secara aktif.
* **Serang:** Setelah daya 100%, tabrakkan ikon hati ke arah Boss sebelum waktu 5 detik habis.
* **Bertahan:** Potong peluru merah yang ditembakkan Boss menggunakan garis energi di antara kedua tanganmu.
* **Warning:** Jangan menyentuh Boss jika daya belum penuh, atau energi kamu akan di-reset (Critical Error)!

## 📜 Lisensi & Hak Cipta
Proyek ini menggunakan lisensi MIT. Kamu bebas untuk menggunakan, memodifikasi, dan membagikan ulang kode ini.

## ⚖️ Atribusi Teknologi
Terima kasih kepada Google MediaPipe untuk teknologi tracking tangan dan Google Fonts untuk tipografi Orbitron yang digunakan dalam proyek ini.

---

## 📂 Struktur Proyek

```text
.
├── index.html            # File tunggal utama (HTML, CSS, & JS)
└── README.md             # Dokumentasi proyek