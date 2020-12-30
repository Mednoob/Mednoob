# Necron Auto Role
Auto-role bot dibuat oleh Mednoob menggunakan Javascript dan Eris

## Instalasi
Sebelum kamu menjalankan bot tersebut, kamu harus download `Node.js` terlebih dahulu. Disarankan menggunakan versi terbaru.
Lalu, kamu juga harus ada Visual Studio C++ Compiler. Bisa didapat dari menggunakan Admin Command Prompt lalu ketik `npm i -g windows-build-tools`

1. Extract file zip
![ExtractImage](https://cdn.discordapp.com/attachments/671666700847939604/793708291133538324/unknown.png)

2. Buka hasil dari extract tersebut, lalu ke folder `src`. Disana, kamu bisa menemukan file `config.yml`. Buka, lalu tulis token dan prefix bot disana
![ConfigImage](https://cdn.discordapp.com/attachments/671666700847939604/793707421625090058/unknown.png)

3. Mundur satu langkah dari folder `src` agar kamu kembali lagi ke hasil extract
![BackImage](https://cdn.discordapp.com/attachments/671666700847939604/793707795706806281/unknown.png)

4. Buka Command Prompt di hasil extract. Lalu ketik `npm i`. Setelah proses selesai, jangan tutup Command Prompt tersebut.
![PackageImage](https://cdn.discordapp.com/attachments/671666700847939604/793709273845858314/unknown.png)

5. Jalankan bot dengam mengetik `node .`
![RunImage](https://cdn.discordapp.com/attachments/671666700847939604/793710386519343164/unknown.png)

## Penggunaan
Untuk melihat daftar command, kamu bisa pake command `help`

1. `createautorole <nama>` Membuat autorole.
![CreateImage](https://cdn.discordapp.com/attachments/671666700847939604/793714345115910194/unknown.png)

2. `addrole <IDAutorole> <emoji> <IDRole/MentionRole>` Menambah role ke suatu Autorole
![AddImage](https://cdn.discordapp.com/attachments/671666700847939604/793711682466873344/unknown.png)

3. `initialize <IDAutorole> [MentionChannel]` Mengirim reaction message
![InitImage](https://cdn.discordapp.com/attachments/671666700847939604/793713906555027490/unknown.png)
