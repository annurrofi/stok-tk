STOK TK — PWA SIAP PASANG

Isi:
- index.html
- manifest.webmanifest
- sw.js
- icons/

PENTING:
PWA tidak dapat dipasang dari alamat content:// atau file://. Folder ini harus dibuka melalui alamat http:// atau https://.

Cara paling mudah:
1. Upload SELURUH isi folder ini ke hosting statis yang mendukung HTTPS.
2. Buka alamat webnya di Chrome Android.
3. Tunggu aplikasi terbuka sekali agar service worker aktif.
4. Buka menu Chrome → pilih "Install app" / "Tambahkan ke layar utama" (nama menu dapat berbeda).
5. Setelah terpasang, Stok TK akan terbuka seperti aplikasi, tanpa bilah alamat.

DATA:
- Data aplikasi tetap menggunakan penyimpanan lokal browser (localStorage).
- Tidak ada koneksi Google otomatis.
- Gunakan menu Laporan → Backup untuk membuat backup JSON.
- Simpan backup JSON ke folder HP atau upload manual ke Google Drive.

CATATAN:
- Jika cache/service worker belum aktif, reload sekali.
- Jangan menghapus data situs/browser jika belum mempunyai backup.
