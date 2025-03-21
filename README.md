# Pybot

Pybot adalah asisten AI pribadi yang dibuat oleh saya dan dikembangkan oleh **Nebula Enterprise**. Pybot dirancang untuk memberikan jawaban yang cerdas, efisien, dan tetap sopan kepada pengguna. Setiap interaksi dengan Pybot bersifat **stateless**, artinya percakapan tidak disimpan untuk menjaga keamanan dan kinerja optimal.

## Fitur Utama
✅ **Tidak Menyimpan Riwayat Chat** → Setiap percakapan selalu dianggap baru.  
✅ **Model Terenkripsi** → File model dienkripsi agar tidak bisa dibaca manusia secara langsung.  
✅ **Fokus pada Jawaban yang Berguna** → Menghindari percakapan tidak relevan atau tidak bermanfaat.  
✅ **Tidak Mudah Dipengaruhi** → Pybot tidak akan mudah percaya jika ada user yang mengaku sebagai penciptanya.  
✅ **Ringan & Cepat** → Tidak membebani sistem dengan penyimpanan log chat.

## Instalasi

### 1. **Kloning Repository**
```bash
git clone https://github.com/Hamzah82/pybot.git
cd pybot
```

### 2. **Install Dependencies**
Pastikan kamu sudah menginstal dependensi yang diperlukan:
```bash
pip install requests
```

### 3. **Jalankan Chatbot**
```bash
python bot.py
```

## File & Struktur
```
pybot/
├── bot.py                 # Script utama chatbot
├── Model_Encrypt.json     # Model yang sudah dienkripsi
├── pyarmor_runtime_000000/
│   ├── __init__.py        # File inisialisasi Python
│   ├── pyarmor_runtime.so # Runtime protection (PyArmor)
├── README.md              # Dokumentasi proyek ini
```

## Lisensi
Proyek ini dilindungi oleh **[MIT License](LICENSE)**. Silakan gunakan, modifikasi, dan kontribusikan! 🚀

