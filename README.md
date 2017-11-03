# AIOBot V1
Selfbot All In One [ Without Admin Function ]

Catatan : 
- Ini Adalah Selfbot
- Hanya Bisa Digunakan Sendiri
- Belum Bisa Dipakai Protect Group [ Akan Terus Saya Kembangkan ]
- Fitur AutoLike [ 1x Login 100x Like ]

### Cara ubah login versi authtoken ( Login Otomatis )
Ubah script dibawah ini
```bash
cl = LINETCR.LINE()
cl.login(qr=True)
cl.loginResult()
```
menjadi
```bash
cl = LINETCR.LINE()
cl.login(token="authtoken-ente")
cl.loginResult()
```

### Cara mendapatkan authtoken
Saat pertama login, pada terminal / termux kalian, kalian akan diberi authtoken kalian, contohnya
```bash
authToken -> EmGxXwhjizYIReLFxxxx.eFtfXEQQ9zeBAclHFogALq.3sv5woAxxxxHYXBJFxxxxxxxPToPfzUNv2VYvSXXXX=
```

Chat Apa Aja Yang akan berkicau :
- Member Join Grup
- Member Keluar Grup
- Ada Member Kick Member Lainnya

Keyword Bot :
- Speed / speed [Cek Kecepatan Bot]
- Summon [Tag All Semua Member Grup]
- Spam: <on/off> <jumlah spam> <kata2> [Untuk Spam Di Grup]
- Spamcontact @TAGTARGET [Untuk SPAM Di PC Target]
- Bye @OrangPertama @OrangKedua @OrangKetiga [Untuk Kick Orang Yang Di Tag (Bisa Kick Lebih dari 1 sekaligus)]
- Gcreator:inv [ADD + INVITE Ke Grup]
- Gbc <text> [BroadCast Ke Semua Grup]
- Kick all [Kick Semua Member]
- Fbc <text> [BroadCast Ke Semua Teman]

### Created By Farzain - zFz
