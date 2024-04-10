# BOT IS BACK #AIUPDATE
Update:
✅ Migrasi base bot ke @whiskeysockets/baileys
✅ Added coins (bisa claim coins)
✅ Added fitur tebak-tebakan, susun kata, kuis math, tictactoe
✅ Menfess is back
✅ Added fitur SpeedTest (Tes Internet)
✅ Pairing code (jadi tidak perlu scan qr)
✅ Bisa run di panel
✅ Updated menu
✅ Connectnya pakai bahasa Indonesia
✅ Added fitur remini (Prem only) 
✅ More stable (fitur welcome dimatikan di index (bisa dihidupkan lagi))
✅ Bug fixes dll.

Last Updated Version: GabutBot-MD v6.0

# BOT APAKAH INI?
Bot ini adalah bot MD (Multi-Device), sehingga bot ini dapat digunakan meskipun hp pengguna mati. Bot ini masih dalam pengembangan (baileys beta) sehingga terdapat masih banyak bug di dalamnya. Bot ini No Encrypt, sehingga pengguna dapat recode (asal jangan dijual juga) dan dapat menambah fitur tertentu dengan apikey. 

Recode by me and [`ManzSteviaOFC`](https://www.youtube.com/channel/UCHEszLndQmgMITqKtwy2DXQ))

# GabutBot-Reborn
Full Featured Bot Updated Script 🤖

## NOTE
This script is for everyone, not for sale. Jika dijual neraka menunggumu brother !

<p align="center">
	<img src="https://i.ibb.co/HNrcfzB/wallpapersden-com-ao-no-exorcist-okumura-rin-man-1996x1413.jpg" width="35%" style="margin-left: auto;margin-right: auto;display: block;">
</p>
<h1 align="center">GabutBot-MD</h1>

This is Script of WhatsApp multi device, working with [`@whiskeysockets/baileys`](https://github.com/WhiskeySockets/Baileys)

## UNTUK PENGGUNA WINDOWS/RDP

* Unduh & Instal Git [`Klik Disini`](https://git-scm.com/downloads)
* Unduh & Instal NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Unduh & Instal FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html) (**Jangan Lupa Tambahkan FFmpeg ke variabel lingkungan PATH**)


```bash
npm install yarn --global
git clone https://github.com/YangJunMing12/GabutBot-mD
cd GabutBot-MD
npm install
npm start
```

## FOR TERMUX/UBUNTU/SSH USER

```bash
apt update && apt upgrade
apt install git -y
apt install nodejs -y
apt install ffmpeg -y
git clone https://github.com/YangJunMing12/GabutBot-IV
cd GabutBot-MD
npm i
```

## RECOMMENDED INSTALL ON PTERODACTYL PANEL
1. Beli panel di lapak terpercaya
2. Minta penjual untuk mengkonfigurasi Startup Command sebagai berikut
```bash
$ if [[ -d .git ]] && [[ {{AUTO_UPDATE}} == "1" ]]; then git pull; fi; if [[ ! -z ${NODE_PACKAGES} ]]; then /usr/local/bin/npm install ${NODE_PACKAGES}; fi; if [[ ! -z ${UNNODE_PACKAGES} ]]; then /usr/local/bin/npm uninstall ${UNNODE_PACKAGES}; fi; if [ -f /home/container/package.json ]; then /usr/local/bin/npm install; fi; if [[ ! -z ${CUSTOM_ENVIRONMENT_VARIABLES} ]]; then vars=$(echo ${CUSTOM_ENVIRONMENT_VARIABLES} | tr ";" "\n"); for line in $vars; do export $line; done fi; /usr/local/bin/${CMD_RUN};
```
3. Download git ini dan upload file zip ke panel
4. Ekstrak zip, buka folder GabutBot-MD-6.0-main, select semua file dan move ke ../
5. Setting Command Run di startup menjadi
``` bash
$ npm install
```
6. Setting Command Run di startup menjadi
``` bash
$ node .
```
7. Selesai (lihat known issues di bawah)


## Execute bot
```bash
$ node .
```

## Features

| Group |                     Feature                |
| :------------: | :---------------------------------------------: |
|       ✅        |  Hidetag               |
|       ✅        |  Grup close atau open       |
|       ✅        |  Gcname          |
|       ✅        |  Gcdesk       |
|       ✅        |  Add              |
|       ✅        |  Kick              |
|       ✅        |  Ownergc              |
|       ✅        |  Leave              |
|       ✅        |  Promote              |
|       ✅        |  Demote              |
|       ✅        |  Ephemeral             |
|       ✅        |  Vote           |
|       ✅        |  Antilink         |

| Search |                     Feature                |
| :------------: | :---------------------------------------------: |
|       ✅        |  Youtube play             |
|       ✅        |  Youtube search     |
|       ✅        |  Google & google image      |
|       ✅        |  Pinterest       |
|       ✅        |  Search Wallpaper           |
|       ✅        |  Youtube Search             |
|       ✅        |  Spotify Search           |
|       ✅        |  Wikimedia             |
|       ✅        |  Ringtone             |
|       ✅        |  Stalk People          |
|       ✅        |  Gsmarena            |
|       ✅        |  Kamus KBBI          |

| Creator |                     Feature                |
| :------------: | :---------------------------------------------: |
|       ✅        |  ATTP & TTP            |
|       ✅        |  Sticker To Image/Video/GIF   |
|       ✅        |  Emoji Mix     |
|       ✅        |  Pinterest       |
|       ✅        |  Sticker          |
|       ✅        |  Sticker WM            |
|       ✅        |  Sticker Meme         |
|       ✅        |  KTP Fake Maker         |
|       ✅        |  Sertifikat Bucin/Pacaran/Tolol        |
|       ✅        |  Translate Kode Biner         |

| Downloader |                     Feature                |
| :------------: | :---------------------------------------------: |
|       ✅        |  Tiktok WM/No WM/Slide Show            |
|       ✅        |  Spotify/Joox/SoundCloud Download |
|       ✅        |  Youtube Music     |
|       ✅        |  Youtube Video      |
|       ✅        |  Facebook/IG/Twitter Download          |
|       ✅        |  ZippyShare Download       |
|       ✅        |  Get Music or Get Video        |

| AI Chat (NEW!) |                     Feature                |
| :------------: | :---------------------------------------------: |
|       ✅        |  Chat Open AI & Open AI Turbo 3.5           |
|       ✅        |  Dall-E & Diffusion (Buat gambar dari AI) |
|       ✅        |  Speech to text    |

... and more! Menfess, fun menu ready 

## Known Issues
1. Ketika run di panel, ketemu tulisan "can't find ffmpeg"
   
   Ganti path di file index.js (./node_modules/@ffmpeg-installer/index.js) di line 18, tambahkan path 'ffmpeg' disana!
   
   Sebelum:
   ```bash
   var topLevelPath = path.resolve(__dirname.substr(0, __dirname.indexOf('node_modules')), 'node_modules', '@ffmpeg-installer', platform);
   ```
   Sesudah:
   ```bash
   var topLevelPath = path.resolve(__dirname.substr(0, __dirname.indexOf('node_modules')), 'node_modules', '@ffmpeg-installer', 'ffmpeg', platform);
   ```

   Kemudian download file fix [`disini`](https://www.mediafire.com/file/sbc6bafga5x5l7g/fix-bot.zip/file), ekstrak foldernya dan kemudian letakkan di 
   ./node_modules/@ffmpeg-installer/ffmpeg


3. Ketika menggunakan command seperti sticker, smeme dll, ada error EACCES ketika execute ffmpeg
   
   Pada file ffmpeg di ./node_modules/@ffmpeg-installer/ffmpeg, klik titik tiga di sebelah kanan dan klik Permissions, setting permissionsnya ke 777.

## ❗ Warning
WhatsApp Bot is still in the development stage, so there are a few bugs
WhatsApp Connection (BETA, not working perfectly)

Editing Number Owner & session name in ```config.js```
Get Apikey LolHuman on [`LolHuman`](https://api.lolhuman.xyz) and [`BetaBotz`](https://api.betabotz.eu.org)harga murah kok sans 


## Thanks To
* [`@adiwajshing/baileys`](https://github.com/adiwajshing/baileys)
* [`Nurutomo`](https://github.com/Nurutomo)
* [`Mhankbarbar`](https://github.com/MhankBarBar)
* [`Faiz`](https://github.com/FaizBastomi)
* [`Shiny Sebastian`](https://github.com/YangJunMing12)

```Thanks to all who have participated in the development of this script```


License: [MIT](https://en.wikipedia.org/wiki/MIT_License)

Support Me
* ```OVO``` 08116646665

# Thank you and have fun!
