MAKEUP FLOREN — WEBSITE + ADMIN EDITABLE V3

FILES
- index.html: website pelanggan
- admin.html: dashboard booking + editor konten website
- assets/: foto default

FITUR ADMIN V3
- Ubah nama brand, tagline, deskripsi, teks promo, teks tentang
- Ubah nomor WhatsApp dan link Instagram/Facebook/TikTok
- Ganti foto model utama dan foto layanan/galeri melalui upload file
- Ubah nama dan harga menu layanan
- Tambah menu baru dan hapus menu yang tidak digunakan
- Ekspor/impor pengaturan JSON sebagai cadangan
- Tetap mencakup dashboard booking, status, tambah booking manual, dan ekspor CSV

CARA UPDATE DI GITHUB/VERCEL
1. Upload/replace index.html dan admin.html di root repository GitHub.
2. Pastikan semua gambar ada di folder assets/ dengan nama yang sesuai.
3. Commit changes. Vercel akan deploy ulang otomatis.
4. Buka https://makeupfloren.vercel.app/admin.html untuk mengelola.
5. Setelah menyimpan pengaturan, buka website pada browser yang sama dan refresh.

BATASAN PENTING
Versi ini masih website statis. Pengaturan disimpan di localStorage browser pada domain website. Perubahan teks/menu akan dibaca website di browser yang sama; foto yang diunggah disimpan sebagai data lokal browser. Pengaturan tidak otomatis tersinkron ke browser/perangkat pelanggan lain. Booking dari perangkat pelanggan tidak otomatis masuk ke admin. Admin belum memiliki login aman. Untuk sistem produksi yang benar-benar sinkron diperlukan backend/database, autentikasi server, dan penyimpanan foto online.
