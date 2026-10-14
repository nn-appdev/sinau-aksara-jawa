# Sinau Aksara Jawa (prototipe)

Aplikasi latihan menulis dan membaca aksara Jawa untuk persiapan FTBI.
Seluruh data tersimpan di perangkat pengguna (localStorage). Tidak ada backend, autentikasi, atau sinkronisasi cloud.

## Menjalankan
- Lokal: jalankan server statis di folder ini (mis. `python3 -m http.server`) lalu buka `http://localhost:8000`.
- GitHub Pages: unggah `index.html` dan `support.js` ke repositori, lalu Settings > Pages > Deploy from branch.

Berkas `support.js` adalah runtime halaman dari editor Design; keduanya harus berada di folder yang sama.
Font aksara Jawa (Noto Sans Javanese) dimuat dari Google Fonts, jadi perlu internet pada kunjungan pertama.

## Status
Materi dan aturan berstatus draf dan belum diverifikasi terhadap pedoman resmi. Penilaian tulisan tangan dilakukan guru.

## Font
Folder `fonts/` berisi Noto Sans Javanese (lisensi SIL OFL 1.1, sumber paket npm @fontsource/noto-sans-javanese) agar aksara tampil juga tanpa internet. Folder ini harus ikut diunggah.
