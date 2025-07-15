# 🧪 K6 Dummy API Performance Test

Repo ini berisi skrip pengujian performa API menggunakan [K6](https://k6.io/), 
yang ditujukan untuk dummy API dari (https://automationexercise.com).

---

## 📥 Instalasi K6

### Untuk Mac (Homebrew)
-Bash
brew install k6

## Untuk Windows (via Chocolatey)
-Bash
choco install k6

## Untuk Windows (via VisualCode)
-Bash
Npm Install K6


## Untuk Linux (Ubuntu/Debian)
-Bash
sudo apt update
sudo apt install gnupg ca-certificates
curl -s https://packagecloud.io/install/repositories/loadimpact/k6/script.deb.sh | sudo bash
sudo apt install k6


Contoh Menjalankan 1 File Test
-Bash
k6 run k6/get-user-by-email.js

Note: 

- Tidak diperlukan konfigurasi tambahan untuk menjalankan skrip.
- Untuk melihat hasil lebih detail, K6 akan mencetak ringkasan (summary) langsung di terminal.
- Tidak menghasilkan file HTML atau JSON, hanya output CLI (Command Line Interface).
