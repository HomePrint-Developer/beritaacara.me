# beritaacara.me 💸

Sebuah aplikasi web ringan dan interaktif untuk mempermudah pembuatan **Berita Acara Penghitungan Uang**. Didesain dengan antarmuka yang bersih dan modern, aplikasi ini membantu kasir, admin, atau bendahara untuk menghitung total pecahan uang kertas dan koin secara akurat dan cepat.

🌐 **Live Demo:** [https://homeprint-developer.github.io/beritaacara.me/](https://homeprint-developer.github.io/beritaacara.me/)

---

## ✨ Fitur Utama

- **Kalkulasi Otomatis (Real-time):** Menghitung subtotal per pecahan dan *Grand Total* secara instan saat angka dimasukkan.
- **Format Rupiah Otomatis:** Angka langsung diformat dengan standar mata uang Indonesia (Rp).
- **Penyimpanan Lokal (Local Storage):** Data riwayat laporan tersimpan dengan aman di dalam *browser* perangkat pengguna tanpa memerlukan *database server*. Sangat cepat dan bisa diakses secara *offline*.
- **Desain Modern & Responsif:** Tampilan UI/UX bergaya *dashboard* profesional, nyaman digunakan di layar Desktop maupun Mobile.
- **Manajemen Data:** Mudah untuk membuat laporan baru, melihat detail, mengedit, dan menghapus riwayat penghitungan.

## 🛠️ Teknologi yang Digunakan

Aplikasi ini dibangun murni di sisi klien (Client-side) tanpa *backend*, menggunakan:
- **HTML5 & Vanilla JavaScript**
- **Tailwind CSS** (via CDN) untuk *styling*
- **SweetAlert2** untuk pop-up *alert* dan konfirmasi interaktif
- **FontAwesome** (via CDN) untuk ikon
- **Google Fonts (Figtree)** untuk tipografi

## 🚀 Cara Menjalankan Secara Lokal

Karena aplikasi ini berjalan sepenuhnya di sisi *browser*, Anda bisa langsung menjalankannya di komputer Anda tanpa instalasi *server*.

1. Clone repositori ini:
   ```bash
   git clone [https://github.com/homeprint-developer/beritaacara.me.git](https://github.com/homeprint-developer/beritaacara.me.git)
2. Buka folder hasil *clone*.
3. Klik dua kali pada file `index.html` untuk membukanya di *browser* pilihan Anda.

## ⚠️ Catatan Penting
Aplikasi ini menggunakan fitur Local Storage pada browser. Artinya, data laporan yang Anda simpan:
- Hanya tersedia di perangkat dan browser yang sama saat Anda membuatnya.
- Akan hilang jika Anda membersihkan data browser (Clear Cache/History/Cookies).