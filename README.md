# Komodo Season Trip – Web Publik

- `index.html` : halaman web (satu file).
- `kapal.json` : data kapal dan nomor WhatsApp. File ini diperbarui oleh repo admin.

Hosting: GitHub Pages (Settings → Pages → Deploy from branch → main / root).

`kapal.json` juga memuat `orderUrl` (alamat Google Apps Script). Selama kosong, tombol pesan membuka WhatsApp. Setelah diisi lewat web admin, muncul form pesanan yang menyimpan ke Google Sheets.
