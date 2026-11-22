# ELPI Docking Monitor (PWA)

Tampilan ELPI Docking Specialist Monitoring yang diterbitkan lewat GitHub Pages supaya bisa dipasang seperti aplikasi
(tombol **Install aplikasi** di halaman masuk). Data tetap berada di Google Sheets dan diambil dari web app Apps Script
setelah login. Repo ini tidak berisi kode backend, data armada, atau daftar harga.

File ini dibuat otomatis oleh `tools/build-pwa.js` di repo utama (private). Jangan diedit langsung kecuali `config.js`.

- `config.js`: URL web app Apps Script (`/exec`).
- Pembaruan: di repo utama jalankan `node tools/build-pwa.js`, salin isi `pwa/` ke repo ini, commit, push.
