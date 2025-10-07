# Plymouth Custom Theme

Custom theme untuk Plymouth Linux Mint dengan logo baru.

## Preview
![Screenshot](https://github.com/edzardVOID/linux-logo-plymouth/blob/main/preview.png)

## Fitur
- Ganti logo Plymouth bawaan Linux Mint
- Simple dan mudah di-install
- Kompatibel dengan Linux Mint versi 21+

## Instalasi
1. Clone atau download repo ini:
https://github.com/edzardVOID/linux-logo-plymouth.git

2. Jalankan script install:

sudo cp -r THEME /usr/share/plymouth/themes

sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/linux-logo/linux-logo.plymouth 250

sudo update-alternatives --config default.plymouth  # pilih linux-logo

sudo update-initramfs -u


3. Reboot untuk melihat theme baru.

Lisensi
-------
Tema ini fork dari https://www.gnome-look.org/u/eren16 dan dimodifikasi oleh EdzardVOID.
Distribusi dan modifikasi diizinkan di bawah ketentuan GNU General Public License v3 (GPL-3.0). 
Lihat LICENSE file untuk detail.

