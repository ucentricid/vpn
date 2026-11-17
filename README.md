# 🛡️ Ucentric VPN Client

Aplikasi klien VPN WireGuard resmi yang ultra-ringan, cepat, dan mandiri (*standalone*) untuk mengakses jaringan internal **Ucentric** secara aman.

![Platform](https://img.shields.io/badge/Platform-macOS%20(Intel%20%26%20Apple%20Silicon)-brightgreen)
![WireGuard](https://img.shields.io/badge/Protocol-WireGuard%20ChaCha20--Poly1305-blue)
![Package Size](https://img.shields.io/badge/Ukuran-~6%20MB-success)
![Memory](https://img.shields.io/badge/RAM%20Usage-~15%20MB-informational)

---

## 📥 Download Aplikasi

Unduh versi rilis terbaru untuk sistem operasi Anda:

| Sistem Operasi | File Unduhan | Status |
| :--- | :--- | :---: |
| **macOS (Monterey / Ventura / Sonoma / Sequoia)** | [📦 **Download Ucentric-VPN-macOS.zip**](https://github.com/ucentricid/vpn/raw/main/Ucentric-VPN-macOS.zip) | ✅ **Tersedia** |
| **Windows 10 / 11 (64-bit)** | Segera Hadir | ⏳ *Coming Soon* |

---

## 🚀 Panduan Penggunaan

### 1. Ekstrak & Jalankan Aplikasi
1. Unduh file **`Ucentric-VPN-macOS.zip`**.
2. Klik dua kali file zip untuk mengekstrak aplikasi **`Ucentric VPN.app`**.
3. Pindahkan **`Ucentric VPN.app`** ke folder **Applications** (atau buka langsung).
4. Klik dua kali untuk membuka aplikasi.

> **Catatan Pengguna macOS:**  
> Saat pertama kali menghubungkan tunnel VPN, macOS akan meminta otorisasi keamanan Touch ID atau Password untuk membuat antarmuka jaringan virtual internal. Cukup izinkan 1 kali saja.

---

### 2. Memuat Profil VPN (`.conf`)
1. Dapatkan file konfigurasi profil resmi Anda (contoh: `nama-anda-vpn-ucentric.conf`) dari Administrator IT Ucentric.
2. Di aplikasi Ucentric VPN, klik tombol **Import .conf** di pojok kanan bawah.
3. Pilih file konfigurasi yang telah diberikan, atau cukup seret (*drag & drop*) file `.conf` ke dalam jendela aplikasi.

---

### 3. Menghubungkan VPN
1. Klik tombol **Power (🔘)** besar di tengah aplikasi.
2. Indikator status akan berubah menjadi **TERHUBUNG (Hijau)** lengkap dengan informasi latensi dan durasi waktu.
3. Seluruh jaringan dan layanan internal kini siap diakses secara aman sesuai hak akses Anda.
4. Untuk memutuskan sambungan, cukup klik kembali tombol **Power (🔘)**.

---

## 🔒 Fitur Keamanan

* **Kriptografi Mutakhir:** Menggunakan enkripsi modern *ChaCha20-Poly1305*, pertukaran kunci *Curve25519 (ECDH)*, dan hashing *BLAKE2s*.
* **100% Standalone:** Tidak membutuhkan aplikasi pihak ketiga atau instalasi driver tambahan.
* **Split Tunneling Aman:** Hanya rute internal jaringan kerja Ucentric yang dilewatkan ke tunnel enkripsi; koneksi internet reguler Anda (seperti browsing umum, streaming) tetap berjalan normal dengan kecepatan penuh.
* **Auto-Update Aman:** Notifikasi pembaruan otomatis langsung dari dalam aplikasi saat versi baru tersedia.

---

## 📞 Bantuan & Dukungan

Jika mengalami kendala koneksi atau membutuhkan file konfigurasi baru, silakan hubungi tim Administrator Ucentric.
