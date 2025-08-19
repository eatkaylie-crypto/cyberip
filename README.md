# CyberIP

CyberIP adalah script Python sederhana untuk melakukan pengecekan alamat IP dari sebuah domain/URL.  
Hasil lookup akan ditampilkan dengan tampilan berwarna di terminal.

# Fitur
- Resolusi domain ke alamat IP
- Menampilkan informasi detail IP target
- Output berwarna (dengan Colorama)
- Ringan & mudah digunakan

# Persyaratan
- Python 3.8 atau lebih baru
- Modul Python yang diperlukan:
  - `colorama`

# Instalasi
```bash
pkg update && pkg upgrade -y
pkg install git -y
pkg install python -y 
 git clone https://github.com/markasibervteam/cyberip.git 
cd cyberip
pip install -r requirements.txt
pip install colorama

#jalankan tool 
python cyberip.py

Kemudian masukkan URL atau alamat IP target ketika diminta.
Contoh:

Masukkan alamat website/IP: google.com

Disclaimer: Tool ini dibuat hanya untuk tujuan edukasi & riset. Jangan digunakan untuk aktivitas ilegal.
