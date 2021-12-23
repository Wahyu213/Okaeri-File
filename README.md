<h1 align="center"><img src="./resources/extras/GeezFire.gif" width="35px">OKAERI-FILE<img src="./resources/extras/GeezFire.gif" width="35px"></h1>

<p align="center">
  <img src="https://telegra.ph/file/1070d9afe04096359f68b.jpg">
</p>


##

Bot Telegram untuk menyimpan Posting atau File yang dapat Diakses melalui Link Khusus.

**Jika Anda memerlukan tambahan module lagi dalam repo atau Jika Anda menemukan bug, silahkan report di group [@OkaeriUserbot](https://www.telegram.dog/OkaeriUserbot)**

### Features
- Sepenuhnya dapat dicustom.
- Pesan sambutan & Forcesub yang dapat dicustom.
- Lebih dari satu Posting dalam Satu Link (batch).
- Dapat di-deploy di heroku secara langsung.

### Setup

- Tambahkan bot ke Channel Database dengan semua izin admin
- Tambahkan bot ke Channel ForceSub tambahkan bot sebagai ADMIN
- Tambahkan bot ke Group ForceSub tambahkan bot sebagai ADMIN

#### Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Wahyu213/Okaeri-File)</br>



### Admin Commands

```
/start - mulai bot atau dapatkan postingan

/batch - buat link untuk lebih dari satu posting

/genlink - buat link untuk satu posting

/users - lihat statistik pengguna bot

/broadcast - menyiarkan/broadcast pesan apa pun ke pengguna bot

/ping - untuk mengecek bot
```

### Variables

* `API_HASH` Dapatkan API HASH di web my.telegram.org.
* `API_ID` Dapatkan APP ID di web my.telegram.org
* `TG_BOT_TOKEN` Dapatkan dari t.me/BotFather
* `OWNER` Masukan Username Telegram untuk Owner BOT
* `OWNER_ID` Masukan User ID Telegram untuk Owner BOT
* `CHANNEL_ID` Masukan ID Channel Untuk [Channel Database] contoh:- -100xxxxxxxx
* `ADMINS` Masukan User ID untuk mendapatkan hak Admin BOT [Hanya dapat membuat link]
* `START_MESSAGE` Opsional: Pesan /start memulai awalan ke bot, Gunakan <a href='https://github.com/Wahyu213/Okaeri-File/blob/main/README.md#start_message'>format</a> 
* parsemode HTML 
* `FORCE_SUB_MESSAGE` Opsional: Pesan Paksa Subscribe bot, Gunakan Format parsemode HTML
* `FORCE_SUB_CHANNEL` Masukan ID dari Channel Untuk Wajib Subscribenya
* `FORCE_SUB_GROUP` Masukan ID dari Group Untuk Wajib Subscribenya

### Extra Variables

* `CUSTOM_CAPTION` letakkan teks teks Kustom Anda jika Anda ingin Mengatur Teks Kustom, Anda dapat menggunakan HTML dan <a href='https://github.com/Wahyu213/Okaeri-File/blob/main/README.md#custom_caption'>fillings</a> untuk pemformatan (hanya untuk dokumen)
* `DISABLE_CHANNEL_BUTTON` Masukan True untuk Nonaktifkan Tombol Berbagi Saluran, Default jika False

### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption


### Credits

- Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
- Thanks To [CodeXBotz](https://github.com/CodeXBotz/File-Sharing-Bot)
- Thanks To [File-Sharing-Man](https://github.com//mrismanaziz/File-Sharing-Man)


[Okaeri-File](https://github.com/Wahyu213/Okaeri-File/) is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
