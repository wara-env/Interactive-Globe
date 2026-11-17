# // 03.PLANET_EARTH — Interactive Globe 🌍

***MASIH DALAM TAHAP PENGEMBANGAN***

Proyek iseng-iseng untuk mengeksplorasi visualisasi 3D di web sekaligus latihan merancang **UI/UX bergaya *minimalist telemetry HUD***. 

Dibangun menggunakan **Three.js** dengan pendekatan *zero-network request* (tekstur bumi di-embed langsung menggunakan base64), jadi bisa langsung jalan di mana saja tanpa perlu aset eksternal.

## ✨ Fitur Utama
* **Real-time Day/Night Terminator:** Rotasi bumi mengikuti arah cahaya matahari, lengkap dengan lampu kota (*city lights*) yang otomatis menyala saat memasuki sisi malam.
* **Interactive Camera:** Bebas *drag* untuk memutar sudut pandang globe dan *scroll* untuk zoom menggunakan `OrbitControls`.
* **HUD Controls & Telemetry:**
  * Kontrol **Play/Pause** rotasi bumi.
  * Pengaturan **Speed Multiplier** kecepatan rotasi.
  * Toggle layer **Clouds** (awan).
  * Indikator koordinat (`LAT`/`LON`), `SUN TIME`, dan status rotasi secara *real-time*.

## 🛠️ Tech Stack
* **HTML5 & CSS3** (Custom HUD layout dengan tipografi `monospace` & efek `backdrop-filter`)
* **JavaScript (Vanilla)**
* **Three.js (r128)** & **OrbitControls**

## 🚀 Cara Menjalankan
Karena proyek ini berjalan murni dalam satu file HTML tanpa *build tools* atau *dependencies* tambahan:
1. Clone atau download repository ini.
2. Buka file `index.html` langsung di browser favoritmu.

---
*Dibuat sebagai bahan latihan eksplorasi antarmuka dan grafis 3D berbasis web.*
