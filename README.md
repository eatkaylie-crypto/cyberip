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

#1 update & upgrade package
pkg update && pkg upgrade -y

#2 install git
pkg install git -y

#3 install python
pkg install python -y

#4 clone repository cyberip 
git clone https://github.com/markasibervteam/cyberip.git

#5 masukan ke folder project 
cd cyberip

#6 install dependensi (colorama)
pip install -r requirements.txt
#atau langsung 
pip install colorama

#7 jalankan tool 
python cyberip.py

Kemudian masukkan URL atau alamat IP target ketika diminta.
Contoh:

Masukkan alamat website/IP: google.com

Disclaimer: Tool ini dibuat hanya untuk tujuan edukasi & riset. Jangan digunakan untuk aktivitas ilegal.
