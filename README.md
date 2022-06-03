<p align="center">
<img src="https://telegra.ph/file/91e1c3af213527b277eb8.jpg" alt="Kaysa Bot" width="128" height="128"/>
</p>
<p align="center">
<a href="#"><img title="Kaysa Bot" src="https://img.shields.io/badge/Kaysa Bot-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/xdlyy404"><img title="Author" src="https://img.shields.io/badge/Author-Fadly ID-red.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/xdlyy404/followers"><img title="Followers" src="https://img.shields.io/github/followers/xdlyy404?color=blue&style=flat-square"></a>
<a href="https://github.com/xdlyy404/megumikato2/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/xdlyy404/kaysabot?color=red&style=flat-square"></a>
<a href="https://github.com/xdlyy404/megumikato2/network/members"><img title="Forks" src="https://img.shields.io/github/forks/xdlyy404/kaysabot?color=red&style=flat-square"></a>
<a href="https://github.com/xdlyy404/megumikato2/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/xdlyy404/kaysabot?label=Watchers&color=blue&style=flat-square"></a>
</p>

<p align="center">
  <a href="https://github.com/xdlyy404/kaysabot#requirements">Requirements</a> •
  <a href="https://github.com/xdlyy404/kaysabot#instalasi">Installation</a> •
  <a href="https://github.com/xdlyy404/kaysabot#feature-test">Fature test</a> •
  <a href="https://github.com/xdlyy404/kaysabot#bug-report">Bug report</a> •
  <a href="https://github.com/xdlyy404/kaysabot#features">Features</a> •
  <a href="https://github.com/xdlyy404/kaysabot#thanks-to">Thanks to</a>
</p>
</div>


---



# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker command)
* [Libwebp](https://developers.google.com/speed/webp/download) (for sticker wm)
* [Image Magic](https://imagemagick.org/script/download.php) ( for nulis command, Centang Kolom 1,2,3,5,6)
* Any text editor

# Instalasi
## Module
* [`node_modules`](https://github.com/xdlyy404/node_modules)
## For Windows
```bash
git clone https://github.com/xdlyy404/kaysabot
cd kaysabot
npm install
npm start
```
## For Termux
```bash
termux-setup-storage
apt update && apt upgrade
pkg install nodejs git ffmpeg libwebp imagemagick
git clone https://github.com/xdlyy404/kaysabot
cd kaysabot
npm install
npm start
```

## Error For Install Module
```bash
pkg install yarn
yarn
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
- [Saweria](https://saweria.co/fadlyid)

# Feature Test
- [X-NoneBot-MD](https://wa.me/6283847262479)

# Bug Report
- [Developer](https://wa.me/6285921969852)

# Features
- Cek [disini](https://github.com/xdlyy404/kaysabot/blob/main/message/help.js)

# Thanks to
* [`Baileys`](https://github.com/adiwajshing/Baileys)
* [`Fadly ID`](https://github.com/xdlyy404)
* [`rtwone`](https://github.com/rtwone)
* [`X-None Team`](https://github.com/X-NoneTeam)
