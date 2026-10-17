MAKEUP FLOREN — WEBSITE + ADMIN V2

FILES
- index.html: website pelanggan
- admin.html: admin untuk booking, layanan/harga, konten, foto, WhatsApp, sosial media, dan teks
- assets/: foto default

CARA MENCOBA
1. Ekstrak seluruh ZIP ke satu folder (jangan pisahkan index.html, admin.html, dan assets).
2. Buka admin.html di browser untuk mengatur konten.
3. Menu Konten Website dapat mengubah nama brand, tagline, deskripsi, nomor WhatsApp, URL Instagram/Facebook/TikTok, teks promo, teks Tentang, foto, nama layanan, dan harga.
4. Tekan Simpan pengaturan.
5. Buka index.html pada browser/perangkat yang sama untuk melihat perubahan.
6. Ekspor pengaturan JSON untuk cadangan.

BATASAN PENTING VERSI INI
Ini prototipe statis. Pengaturan disimpan dalam localStorage pada browser/perangkat yang sama. Perubahan tidak otomatis tersinkron ke perangkat pelanggan atau admin lain, dan belum ada login admin yang aman. Booking pelanggan melalui perangkat lain tidak otomatis masuk ke dashboard. Jangan mempublikasikan halaman admin ini sebagai sistem bisnis online sebelum ditambahkan autentikasi server dan database.

AGAR BENAR-BENAR ONLINE
Perlu hosting dan backend/database (misalnya Supabase/Firebase atau backend khusus), autentikasi admin, penyimpanan gambar online, serta menghubungkan formulir booking ke database. Setelah itu perubahan admin dapat langsung terlihat oleh semua pengunjung tanpa edit kode.
