# UTS Praktikum Basis Data - Role-Based Access Control (RBAC) PostgreSQL

Repositori ini berisi dokumentasi, konfigurasi *Docker Compose*, dan skrip pendukung untuk Ujian Tengah Semester (UTS) Praktikum Basis Data. Proyek ini berfokus pada implementasi dan pengujian pembatasan hak akses berbasis peran (*Role-Based Access Control* / RBAC) pada basis data PostgreSQL.

## 🛠️ Environment & Tools
* **Database Server:** PostgreSQL (berjalan di dalam *container* Docker)
* **Port Database:** `22117`
* **Management Tool:** DBeaver
* **Database Name:** `salam_db`
* **Schema:** `salam`
* **Table:** `mahasiswas` (Kolom: `nim`, `nama_lengkap`, `email`, `jalur_masuk`, `ipk`, `created_at`)

---

## 🚀 Panduan Menjalankan Proyek dari Awal (Step-by-Step)

Ikuti langkah-langkah berikut untuk mengatur dan menjalankan lingkungan basis data di komputer lokal Anda:

### 1. Clone Repositori
Clone repositori ini ke komputer lokal Anda menggunakan terminal atau Git Bash:
```bash
git clone [https://github.com/username/nama-repositori.git](https://github.com/username/nama-repositori.git)
cd nama-repositori