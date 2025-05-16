# Mirror-CDN

📡 _Custom DNS Blocklist & Whitelist untuk AdGuard Home_

Repositori ini berisi daftar blokir dan daftar putih DNS yang dapat digunakan secara otomatis oleh **AdGuard Home** maupun sistem DNS sinkron lain. Seluruh daftar ini dikelola oleh [ariefwindhiarto](https://github.com/ariefwindhiarto) dan tersedia dalam format *Adblock-style syntax* untuk mendukung penyaringan cerdas dan auto-update dari GitHub Pages.

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

## ✅ Format

Semua file menggunakan sintaks AdGuard-style:
- Blokir domain: `||domain.com^`
- Izinkan domain (whitelist): `@@||domain.com^`

---

## 🧠 Tujuan Proyek

- Membantu komunitas menjalankan penyaringan DNS yang ringan, efisien, dan bisa dikendalikan sepenuhnya
- Menyediakan daftar publik yang modular, terbuka, dan bebas digunakan
- Mendukung fokus, privasi, dan akses internet yang lebih sehat

---

## 🤝 Kontribusi

Silakan fork repo ini atau ajukan **pull request** untuk menambah domain baru ke blocklist atau whitelist. Semua masukan dipertimbangkan secara terbuka.

---

## 🌐 Lisensi

Proyek ini dirilis sebagai **open-source** untuk tujuan edukasi dan penggunaan pribadi. Silakan gunakan, modifikasi, dan bagikan.

