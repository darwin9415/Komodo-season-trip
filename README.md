# Komodo Season Trip – Web Publik

- `index.html` : halaman web (satu file).
- `kapal.json` : data kapal dan nomor WhatsApp. File ini diperbarui oleh repo admin.

Hosting: GitHub Pages (Settings → Pages → Deploy from branch → main / root).

`kapal.json` juga memuat `orderUrl` (alamat Google Apps Script). Selama kosong, tombol pesan membuka WhatsApp. Setelah diisi lewat web admin, muncul form pesanan yang menyimpan ke Google Sheets.

Galeri foto: file `pukaya-01.webp` sampai `pukaya-09.webp`, `citytour-01.webp` sampai `citytour-08.webp`, dan `charter-01.webp` sampai `charter-05.webp` harus berada di folder yang sama dengan `index.html`. Daftar dan keterangan fotonya ada di `kapal.json` (kolom `gal`), atau diatur lewat admin (Paket → Edit → Galeri foto).
