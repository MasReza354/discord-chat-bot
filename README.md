# discord-bot

ini di buat untuk membuat bot discord AI

## Wajib
* **Python 3.9 atau diatasnya**
* **copy file yang bernama `.env.example` menjadi `.env`**
* Jalankan `pip3 install -r requirements.txt` untuk menginstal dependensi yang diperlukan
---

## Langkah 1: Buat Bot Discord
1. Buka Website https://discord.com/developers/applications untuk membuat bot discord
2. Login Discord-mu terlebih dahulu
3. Buat discord bot di dalam aplikasi baru
4. Simpan token dari pengaturan token
5. Simpan token tersebut di `.env` pada kode baris yang bertuliskan `DISCORD_BOT_TOKEN`
6. Nyalakan MESSAGE CONTENT INTENT `ON` [Fitur ini ada di bagian `bot`]
7. Invite bot kamu ke dalam server tujuan melalui OAuth2 [Letakan Undangan di `Redirects`]

## Langkah 2: Jalankan bot di desktop [CMD]
1. Buka `Terminal` atau `Command Prompt`
2. Arahkan ke direktori tempat kalian menginstall bot Discord AI
3. Jalankan dengan kode perintah `python main.py` atau bisa juga `python3 main.py`untuk menjalankan BOT
---

### OpenAI 
1. Pergi ke https://chat.openai.com/api/auth/session

2. Salin value bagian `access_token` dan letakkan didalam `.env` dibagian `OPENAI_TOKEN`

### Microsoft Bing 
1. pergi ke https://www.bing.com/chat dan masuk ke akun

2. Buka `console` dengan menekan tombol pada keyboard `F12`

3. Buka `Application` tab > Cookies

4. Salin value bagian `_U` dari cookies dan letakkan didalam `.env` dibagian `BING_COOKIE`

### Google Gemini 
1. Pergi ke https://gemini.google.com/app dan masuk ke akun

2. Buka `console` dengan menekan tombol pada keyboard `F12`

3. Buka `Application` tab > Cookies

4. Salin value bagian `__Secure-1PSID` dari cookies dan letakkan didalam `.env` dibagian `GOOGLE_PSID`
---

## Commands

* `/chat [message]` Chat dengan ChatGPT/Gemini
* `/draw [prompt]` Membuat Gambar dengan Gemini/OpenAI/Bing
* `/private` ChatGPT beralih ke mode private
* `/public` ChatGPT beralih ke mode publik
* `/replyall` ChatGPT switch between replyAll mode and default mode
* `/reset` Menghapus riwayat percakapan Chat
* `/chat-model` mengganti mode obrolan
   * `gpt-4`: GPT-4 model
   * `Gemini`: Google Gemini Model
   * 
### Selamat Menggunakan Bot Chat!
