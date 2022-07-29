<p align="center">
<img src="https://telegra.ph/file/c4b65a881f6a95599d39d.jpg" alt="SATRIA BOT" width="500"/>

</p>
<p align="center">
<a href="https://github.com/satriabot99/SATRIABOT-Md/releases/tag/V2"><img title="SATRIABOT BOT MULTI DEVICE" src="https://img.shields.io/badge/SATRIABOT BOT MULTI DEVICE-red?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://https://github.com/Satriabot99/SATRIABOT-Md"><img title="Author" src="https://img.shields.io/badge/Author-Satriabot99-red.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/satriabot99/SATRIABOT-Md"><img title="Followers" src="https://img.shields.io/github/followers/satriabo99?color=blue&style=flat-square"></a>
<a href="https://github.com/satriabot99/SATRIABOT-Md"><img title="Stars" src="https://img.shields.io/github/stars/satriabot9/SATRIABOT-Md?color=red&style=flat-square"></a>
<a href="https://github.com/satriabot99/SATRIABOT-Md/network/members"><img title="Forks" src="https://img.shields.io/github/forks/satriabot/SATRIABOT-Md?color=red&style=flat-square"></a>
<a href="https://github.com/satriabot99/SATRIABOT-Md/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/koleksibot/BLACKHATBOT-Md?label=Watchers&color=blue&style=flat-square"></a>
</p>

---

## SATRIABOT BIASA [Click](https://github.com/Satriabot99/SATRIABOT-Md)
## FREE CLOUD BOT MD [Click](https://github.com/Satriabot99/satriabotfree)
## WHITEHATBOT MD [Click](https://github.com/satriabot99)
# BLACKHAT BOT Whatsapp MD
## Install Module [here](https://www.mediafire.com/file/trl8cy4ba1bcimn/node_modules-master.zip/file)
## Information

> Tutorial Install [Disini](https://s.id/Satriabot99/2022/02/script-bot-whatsapp-baileys-md.html?m=1)

> BLACKHATBOT @Whatsapp using a Baileys library-md.
> Jika kamu menemukan semacam bug, harap untuk dimaklumi sementara
>
> • NOTE: Pastikan Jaringan kalian lancar dan device kalian bagus v: 
> 
> • Kalo pake termux mungkin bakal lama respon nya, saya sarankan pake heroku
> 
> • Kalo mau nambah fitur buat file baru [disini](https://github.com/satriabot/BLACKHATBOT-Md/tree/main/plugins) *Contoh* menu.js
>
> • Kalo Ampi Key nya Habis Ya Beli Lah Anjay....

<h3 align="center">Made by :</h3>
<p align="center">
  <a href="https://github.com/satriabot99"><img src="https://telegra.ph/file/38ee4b1d667df385eca78.jpg?size=128" height="128" width="128" /></a>
  <a href="https://github.com/raselcomel"><img src="https://github.com/raselcomel.png?size=128" height="128" width="128" /></a>
  <a href="https://github.com/ilhamhdyt"><img src="https://github.com/ahmadchen.png?size=128" height="128" width="128" /></a>
</p>

## Testing Bot
* <img src="https://i.ibb.co/64CtK3V/Screenshot-2021-12-25-03-35-07.png" height="500" width="500" /></a>
* Jika kamu menemukan bug jangan lupa buka Issues
* Info Lebih Lanjut, Chat [Owner-BLACKHATBOT](https://wa.me/6285708233494)
* Kamu bisa testing fitur Coming Soon [disini](https://wa.me/6285708233494?text=save20%dari20%github)

## How To Change Menu Display
----
### Gif Menu Display 😏
```ts
 let message = await prepareWAMessageMedia({ video: fs.readFileSync('./media/menu.mp4'), gifPlayback: true }, { upload: conn.waUploadToServer })
     const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
     templateMessage: {
         hydratedTemplate: {
           videoMessage: message.videoMessage,
           hydratedContentText: text.trim(),
           hydratedFooterText: wm,
           hydratedButtons: [{
```

### Image Menu Display 😏
```ts
let message = await prepareWAMessageMedia({ image: fs.readFileSync('./media/menu.jpg')}, { upload: conn.waUploadToServer })
     const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
     templateMessage: {
         hydratedTemplate: {
           imageMessage: message.imageMessage,
           hydratedContentText: text.trim(),
           hydratedFooterText: wm,
           hydratedButtons: [{
```

### Location Menu Display 😏
```ts
 const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
     templateMessage: {
         hydratedTemplate: {
           hydratedContentText: text.trim(),
           locationMessage: { 
           jpegThumbnail: fs.readFileSync('./media/shiraori.jpg') },
           hydratedFooterText: wm,
           hydratedButtons: [{       
```

### Video Menu Display 😏
```ts
let message = await prepareWAMessageMedia({ video: fs.readFileSync('./media/menu.mp4')}, { upload: conn.waUploadToServer })
     const template = generateWAMessageFromContent(m.chat, proto.Message.fromObject({
     templateMessage: {
         hydratedTemplate: {
           videoMessage: message.videoMessage,
           hydratedContentText: text.trim(),
           hydratedFooterText: wm,
           hydratedButtons: [{           	
```
----           


## HOW TO CONNECT TO MONGODB WHEN RUN IN HEROKU 👍

* Create account and database in mongodb atlas [`watch here`](https://youtu.be/rPqRyYJmx2g)
* when you already have a database, you just need to take mongourl
* Put mongourl in Procfile `web: node . --db 'mongourl'`
* Example `web: node . -- db 'mongodb+srv://koleksibot:<password>@cluster0.iiede.mongodb.net/BLACKHATBOT-Md?retryWrites=true&w=majority'`

## UNTUK PENGGUNA WINDOWS/VPS/RDP 👍

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)
* Unduh & Instal ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/Satriabot99/SATRIABOT-Md
cd SATRIABOT-Md
npm install
npm update
npm start
```

---------

## UNTUK PENGGUNA TERMUX 🗿
```bash
pkg update && pkg upgrade
pkg install git
pkg install nodejs
pkg install ffmpeg
pkg install imagemagick
pkg install yarn
git clone https://github.com/Satriabot99/SATRIABOT-Md
cd BLACKHATBOT-Md
yarn
node .
```

## UNTUK PENGGUNA HEROKU 👍

### Instal Buildpack ⬇
* heroku/nodejs
* [`Klik Dan Copy`](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git)
* [`Klik Dan Copy`](https://github.com/DuckyTeam/heroku-buildpack-imagemagick.git) 

## Installing the FFmpeg for Windows 👍

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

# Thanks to
 [![ilmanhdyt](https://github.com/Ilmanhdyt.png?size=150)](https://github.com/Nurutomo) | [![satriabot](https://telegra.ph/file/38ee4b1d667df385eca78.jpg?size=150)](https://github.com/satriabot99) | [![Istikmal](https://github.com/BochilGaming.png?size=150)](https://github.com/BochilGaming)
----|----|----
[ilmanhdyt](https://github.com/ilmanhdyt) | [Satriabot99](https://github.com/satriabot99) | [raselcomel](https://github.com/raselcomel)
 Author | yang nambah fitur | yang punya

## Donate
- [Saweria](https://saweria.co/Stapgs)
- [Dana](https://wa.me/6285708233494)
