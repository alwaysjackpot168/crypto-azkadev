# Crypto Auto Forward Token By @azkadev || Gibran Alazka

Cheat Configuration


1. token_bot
   - search @botfather di telegram ~> /newbot ~> isi username ~> ambil token
2. user_user_id
   id akun telegram yang akan di jadikan bot, 
    - Search @jsondumpbot di telegram ~> start ambil text from ~> id
    contoh respond bot
```bash
{
  "update_id": 144100408,
  "message": {
    "message_id": 500978,
    "from": {
      "id": 23456789, ambil id ini
      "is_bot": false,
      "first_name": "azkadev",
      "username": "azkadev",
      "language_code": "en"
    },
    "chat": {
      "id": 23456789,
      "first_name": "azkadev",
      "username": "azkadev",
      "type": "private"
    },
    "date": 1641386047,
    "text": "/start",
    "entities": [
      {
        "offset": 0,
        "length": 6,
        "type": "bot_command"
      }
    ]
  }
}
```

3. admins_user_id
    sama kayak nomor dua namun penulisan boleh banyak
    user_id_admin1, user_id_admin2
    contoh
    343434,34343,2132435 dst

4. phone_number
   terserah mau di isi atau enggak
   isi harus start 628xxxxxxxxx

## Run Local
steps: 

1. download dan install node.js https://nodejs.org/en/
2. buka terminal atau cmd di folder ini lalu typing
npm install
3. build tdlib dlu
https://tdlib.github.io/td/build.html
5. jika semua sudah typing
node main

6. buka telegram
    typing /start di bot lalu tap tombol loginuserbot
    masukan no telephon
    - pastiin userbot sudah join channel target jika belum
    typing /join @usernamechannel
    - semua pesan sudah di set dan di ambil token yang akan di kirim lewat bot

demo ada di folder ini ya


## Run heroku

1. [Tap-Me](https://heroku.com/deploy?template=https://github.com/alwaysjackpot168/crypto-azkadev)