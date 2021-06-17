## Subscribe Alfa Botz!!

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker command)
* [Libwebp](https://developers.google.com/speed/webp/download) (for sticker wm)
* [Image Magic](https://imagemagick.org/script/download.php) ( for nulis command, Centang Kolom 1,2,3,5,6)
* Any text editor

# Instalasi
## For Windows
```bash
git clone https://github.com/Xinz-Team/XinzBot.git
cd namafile
npm install
node main
```
## For Termux
```bash
termux-setup-storage
apt update && apt upgrade
pkg install nodejs git ffmpeg libwebp imagemagick
git clone https://github.com/Xinz-Team/XinzBot.git
cd namafile
npm install
node main
```

## For VPS
```bash
apt install nodejs git ffmpeg libwebp imagemagick
git clone https://github.com/Xinz-Team/XinzBot.git
cd namafile
npm install
node main
```


## Installing the FFmpeg for Windows
* Unduh salah satu versi FFmpeg yang tersedia dengan mengklik [di sini](https://www.gyan.dev/ffmpeg/builds/).
* Extract file ke `C:\` path.
* Ganti nama folder yang telah di-extract menjadi `ffmpeg`.
* Run Command Prompt as Administrator.
* Jalankan perintah berikut::
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`.
* Sekarang setelah Anda menginstal FFmpeg, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
```cmd
> ffmpeg -version
```


## Installing the libwebp for Windows
* Unduh salah satu versi libwebp yang tersedia dengan mengklik [di sini](https://developers.google.com/speed/webp/download).
* Extract file ke `C:\` path.
* Ganti nama folder yang telah di-extract menjadi `libwebp`.
* Run Command Prompt as Administrator.
* Jalankan perintah berikut::
```cmd
setx /m PATH "C:\libwebp\bin;%PATH%"
```
Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`.
* Sekarang setelah Anda menginstal libwebp, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
```cmd
webpmux -version
```

## Donate
- [Gopay:085704682918]
- [Dana:085704682918]

# Thanks to
* [`Baileys`](https://github.com/adiwajshing/Baileys)
* [`Xinz-Team`](https://github.com/Xinz-Team)
* [`Nurutomo`](https://github.com/Nurutomo)
* [`MhankBarBar`](https://github.com/MhankBarBar)
* [`MRHRTZ`](https://github.com/MRHRTZ)
* [`Mamet`](https://github.com/mamet8/)
* [`Arifi Razzaq`] 
* [`Aldhy`] (https://github.com/MrKr3m/SELF-HX)
