# 🛡️ Ucentric VPN Client

Aplikasi klien VPN resmi yang ultra-ringan, cepat, dan mandiri (*standalone*) untuk mengakses jaringan internal **Ucentric** secara aman.

![macOS Universal](https://img.shields.io/badge/macOS-Universal%20(Intel%20%26%20Apple%20Silicon%20M--Series)-brightgreen)
![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011%20(64--bit)-blue)
![WireGuard](https://img.shields.io/badge/Protocol-WireGuard%20ChaCha20--Poly1305-blue)
![RAM Usage](https://img.shields.io/badge/RAM%20Usage-~15%20MB-informational)

---

## 📥 Download Aplikasi

Unduh paket rilis resmi sesuai dengan perangkat Anda:

| Sistem Operasi | Arsitektur | File Unduhan | Status |
| :--- | :--- | :--- | :---: |
| **macOS** (Monterey / Ventura / Sonoma / Sequoia) | **Universal** (Apple Silicon Seri M & Intel) | [📦 **Download Ucentric-VPN-macOS.zip**](https://github.com/ucentricid/vpn/raw/main/Ucentric-VPN-macOS.zip) | ✅ **Tersedia** |
| **Windows** (Windows 10 / 11) | **64-bit (x64)** | [📦 **Download Ucentric-VPN-Windows-x64.zip**](https://github.com/ucentricid/vpn/raw/main/Ucentric-VPN-Windows-x64.zip) | ✅ **Tersedia** |

---

## 🚀 Panduan Penggunaan

### 🍏 Untuk Pengguna macOS (Intel & Apple Silicon M-Series)
1. Unduh **`Ucentric-VPN-macOS.zip`**.
2. Klik dua kali file zip untuk mengekstrak **`Ucentric VPN.app`**.
3. Pindahkan **`Ucentric VPN.app`** ke folder **Applications** (atau buka langsung).
4. Klik dua kali untuk membuka aplikasi.
> *Catatan macOS:* Saat pertama kali menghubungkan VPN, macOS akan meminta otorisasi Touch ID / Password untuk membuat interface jaringan virtual internal. Cukup izinkan 1 kali.

### 🪟 Untuk Pengguna Windows (10 & 11)
1. Unduh **`Ucentric-VPN-Windows-x64.zip`**.
2. Klik kanan file zip, pilih **Extract All...** ke folder pilihan Anda.
3. Buka folder hasil ekstrak, lalu klik dua kali **`Ucentric VPN.exe`** (disarankan *Run as administrator*).

---

### 📂 Memuat Profil VPN (`.conf`) & Menghubungkan
1. Dapatkan file konfigurasi profil resmi Anda (contoh: `nama-anda-vpn-ucentric.conf`) dari Administrator IT Ucentric.
2. Di aplikasi Ucentric VPN, klik tombol **Import .conf** di pojok kanan bawah (atau *drag & drop* file `.conf` ke jendela aplikasi).
3. Klik tombol **Power (🔘)** besar di tengah aplikasi.
4. Status akan berubah menjadi **TERHUBUNG (Hijau)** lengkap dengan indikator latensi.
5. Seluruh jaringan dan layanan internal kini siap diakses dengan aman sesuai hak akses Anda.
6. Untuk memutuskan sambungan, cukup klik kembali tombol **Power (🔘)**.

---

## 🔒 Fitur Keamanan

* **Arsitektur Universal & Multi-Platform:** Berjalan native pada chip Apple Silicon (M1/M2/M3/M4), Intel Mac, dan Windows 64-bit.
* **Kriptografi Mutakhir:** Enkripsi modern *ChaCha20-Poly1305*, pertukaran kunci *Curve25519 (ECDH)*, dan hashing *BLAKE2s*.
* **Split Tunneling Aman:** Hanya rute internal jaringan kerja Ucentric yang dilewatkan ke tunnel enkripsi; koneksi internet reguler Anda tetap berkecepatan penuh.
* **Auto-Update Aman:** Notifikasi pembaruan otomatis langsung dari dalam aplikasi saat versi baru tersedia.

---

## 📞 Bantuan & Dukungan

Jika mengalami kendala koneksi atau membutuhkan file konfigurasi baru, silakan hubungi tim Administrator Ucentric.
