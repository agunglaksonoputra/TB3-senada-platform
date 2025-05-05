# Senada Platform

Repositori ini merupakan repositori utama untuk **Tugas Besar** dengan nama proyek **Senada**, sebuah hiburan yang fokus pada kesenian daerah, seperti pertunjukan seni dan event budaya yang ada di Indonesia.

---

## 📁 Struktur Proyek

Repositori ini menggunakan **Git Submodule** untuk mengelola tiga komponen utama:

| Modul       | Path Lokal     | Deskripsi                                |
|-------------|----------------|-------------------------------------------|
| Mobile App  | `mobile-app/`      | Aplikasi mobile (Flutter).  |
| Backend API | `api/`         | Layanan backend/API (Node JS dan Express JS).  |
| Dashboard   | `dashboard/`   | Dashboard admin berbasis web.            |

---

## 🚀 Cara Clone Project

Karena proyek ini menggunakan submodule, pastikan untuk meng-clone dengan perintah berikut:

```bash
git clone --recurse-submodules https://github.com/username/tb1-senada-platform.git
