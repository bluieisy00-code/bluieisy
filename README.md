# Blueisy — versi dengan halaman input API

## Cara pakai di Acode (Android)
1. Simpan dan ekstrak ZIP ini menggunakan File Manager.
2. Di Acode, buka folder hasil ekstrak `blueisy`.
3. Buka `index.html`, lalu pilih Preview.
4. Halaman awal meminta TMDB API key. Masukkan API key v3 kamu lalu tekan Hubungkan API.
5. Jika berhasil, halaman katalog Blueisy terbuka. Tombol `API ⚙` di header bisa dipakai untuk mengganti key.

## File
- index.html: halaman input API dan halaman katalog
- style.css: tampilan responsif biru gelap
- app.js: koneksi API TMDB, pencarian, kategori, genre, trending, detail, trailer

## Catatan
API key disimpan dalam localStorage browser perangkat ini supaya tidak perlu dimasukkan setiap kali membuka Preview. Jangan gunakan key rahasia atau key yang tidak ingin terlihat di browser. Untuk website publik, gunakan backend/serverless function dan simpan key sebagai environment variable.

Website ini adalah katalog penemuan tontonan, bukan layanan streaming episode penuh. Trailer dibuka di YouTube jika tersedia. Data disediakan oleh TMDB.
