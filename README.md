<p align="center">
  <img src="https://raw.githubusercontent.com/ariefwindhiarto/Mirror-CDN/main/logo-cdn-kerajaan.png" alt="Logo Mirror-CDN" width="200"/>
</p>

<h1 align="center">Mirror-CDN 👑</h1>
<p align="center"><i>DNS Blocklist & Whitelist untuk AdGuard Home - Aman, Terbuka, Berdaulat.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/status-AKTIF-success" alt="Status Aktif"/>
  <img src="https://img.shields.io/badge/aturan%20blokir-25-red" alt="Jumlah Aturan Blokir"/>
  <img src="https://img.shields.io/badge/aturan%20whitelist-16-blue" alt="Jumlah Aturan Whitelist"/>
  <img src="https://img.shields.io/github/last-commit/ariefwindhiarto/Mirror-CDN?label=update" alt="Last Updated"/>
  <img src="https://img.shields.io/github/license/ariefwindhiarto/Mirror-CDN" alt="License"/>
</p>

---

## 📁 Daftar File

| Nama File | Deskripsi | Link RAW |
|-----------|-----------|----------|
| `speedtest-blocklist-for-cdn.txt` | Blokir domain speedtest dari berbagai ISP dan aplikasi | [Raw Link](https://raw.githubusercontent.com/ariefwindhiarto/Mirror-CDN/main/speedtest-blocklist-for-cdn.txt) |
| `whitelist-essential-domains.txt` | Daftar domain penting yang selalu diizinkan (Google, BCA, Shopee, dll) | [Raw Link](https://raw.githubusercontent.com/ariefwindhiarto/Mirror-CDN/main/whitelist-essential-domains.txt) |

---

## ⚙️ Cara Pakai (untuk AdGuard Home)

1. Masuk ke:  
   `AdGuard Home > Penyaringan > Daftar blokir DNS`
2. Klik **Tambahkan daftar hitam**
3. Tempel salah satu URL raw dari daftar di atas
4. Aktifkan ✅ dan klik **Simpan**
5. Selesai. Filter akan diperbarui otomatis sesuai jadwal.

---

## 🧪 Format

Semua file menggunakan sintaks AdGuard-style:
- Blokir domain: `||domain.com^`
- Izinkan domain (whitelist): `@@||domain.com^`

---

## 💡 Tujuan Proyek

- Menyediakan penyaringan DNS ringan dan bebas kontrol
- Mendukung DNS privat yang bersih, sadar, dan manusiawi
- Membuka akses terbuka ke daftar modular yang mudah digunakan

---

## 🤝 Kontribusi

Silakan fork repo ini atau ajukan **pull request** untuk menambah domain baru ke blocklist atau whitelist.

---

## 🧾 Lisensi

Repositori ini bersifat **open-source** untuk edukasi, kesadaran digital, dan penggunaan pribadi. Silakan modifikasi dan bagikan.

