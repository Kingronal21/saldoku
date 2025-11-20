# 💰 Saldoku

**Saldoku** adalah bot Telegram untuk **mencatat dan memantau keuangan pribadi maupun UMKM**.  
Kelola pemasukan, pengeluaran, dan saldo harian dengan mudah melalui Telegram.

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Telegram](https://img.shields.io/badge/Telegram-Bot-green)](https://telegram.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

---

## 🚀 Fitur Utama
- 📥 **Catat Pemasukan & Pengeluaran**  
  Tambahkan transaksi harian dengan cepat dan mudah.
- 📊 **Ringkasan Keuangan**  
  Lihat total pemasukan, pengeluaran, dan saldo secara realtime.
- 🏷️ **Kategori Transaksi**  
  Klasifikasikan transaksi untuk analisis pengeluaran.
- ⏰ **Notifikasi Harian (opsional)**  
  Ingatkan untuk mencatat transaksi setiap hari.
- 🌐 **Aktif 24/7**  
  Bisa dijalankan di Replit dan dipantau via UptimeRobot.

---

## 🛠️ Persyaratan
- Akun Telegram
- Akun Replit
- Token Bot Telegram dari [@BotFather](https://t.me/BotFather)
- UptimeRobot (opsional untuk bot aktif terus)

---

## ⚡ Cara Install & Deploy

### 1️⃣ Buat Bot Telegram
1. Buka Telegram, cari `@BotFather`.
2. Ketik `/newbot` → ikuti instruksi.
3. Simpan **TOKEN** yang diberikan.

### 2️⃣ Deploy ke Replit
1. Login ke [Replit](https://replit.com/), buat **Repl baru** pilih Python.
2. Upload semua file bot (`main.py`, `requirements.txt`, dsb.).
3. Tambahkan **Environment Variable**:
   - Key: `TOKEN`
   - Value: token dari BotFather
4. Jalankan bot:
```bash
python main.py
