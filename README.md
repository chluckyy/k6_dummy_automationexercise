# 🧪 K6 Dummy API Performance Tests – automationexercise.com

Repository ini berisi skrip performance dan stress test menggunakan [k6](https://k6.io/) untuk menguji endpoint dummy API yang tersedia di [https://automationexercise.com](https://automationexercise.com).

---

## 📁 Struktur Folder

- `k6/` → Folder utama untuk semua skrip pengujian
  - `get-user-by-email.js` → Menguji endpoint GET user by email
  - `get-all-brands-list.js` → Menguji endpoint daftar merek
  - `run-all-tests.sh` → Menjalankan semua tes sekaligus, menghasilkan report HTML
- `reports/` → Folder tempat file `.json` dan `.html` hasil tes disimpan (tidak dipush ke GitHub)
- `.github/workflows/k6.yml` → File konfigurasi GitHub Actions (CI)

---

## 🚀 Cara Menjalankan Tes Secara Lokal

### ✅ 1. Pastikan sudah menginstal:

- `k6`: [cara instal](https://k6.io/docs/getting-started/installation/)
- `k6-reporter`: plugin untuk export hasil jadi HTML

```bash
npm install -g k6-reporter
