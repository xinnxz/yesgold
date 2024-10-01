# YesCoinBot

YesCoinBot adalah bot otomatis untuk membantu mengelola akun pada platform YesCoin. Bot ini dapat melakukan berbagai tugas seperti login, mengumpulkan koin, mengaktifkan kotak spesial, upgrade level, dan bergabung dengan squad secara otomatis.

## Fitur
- **Login otomatis**: Bot akan login menggunakan akun yang disimpan di file `data.txt` dan token di file `token.json`.
- **Pengumpulan Koin**: Bot dapat mengumpulkan koin secara otomatis dari kotak spesial atau koin harian.
- **Upgrade Level**: Bot mendukung peningkatan level untuk multi value atau fill rate hingga level maksimum yang diatur.
- **Manajemen Squad**: Bot bisa memeriksa apakah akun sudah bergabung dengan squad tertentu, dan jika belum, akan otomatis bergabung dengan squad yang ditentukan.
- **Mengaktifkan SwipeBot**: Bot akan membeli dan mengaktifkan SwipeBot jika belum diaktifkan.
- **Mendapatkan Bonus Offline**: Klaim bonus koin dari sesi offline.
  
## Persyaratan

- Node.js (versi terbaru)
- Paket npm yang diperlukan:
  - `axios`
  - `colors`
  - `fs`

Untuk menginstal dependensi yang diperlukan, jalankan perintah berikut di terminal:

```bash
npm install axios colors
