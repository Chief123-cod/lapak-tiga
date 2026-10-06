# Lapak Tiga – Filkom Day 2026

Website statis booth Angkatan Tingkat 2 (HTML + CSS + Bootstrap 5.3.3). Tanpa node_modules, tanpa build step, tanpa CDN.
Buka `index.html` di browser, atau jalankan server lokal: `python -m http.server 8000`.

## Struktur folder
```
lapak-tiga/
├── index.html  menu.html  dukung-kami.html  tim.html  galeri.html  kontak.html
├── _headers              # header keamanan (Netlify / Cloudflare Pages)
├── assets/
│   ├── css/style.css     # custom CSS
│   ├── fonts/            # Fraunces + DM Sans (lokal)
│   ├── img/              # hero, menu/, galeri/ (SVG ilustrasi sementara)
│   └── vendor/bootstrap/ # Bootstrap lokal (css + bundle js)
└── docs/PROMPT_ANTIGRAVITY.md
```

## Checklist ketentuan tugas
- 6 halaman (min. 4) · Navbar · Hero · Beranda 6 section (min. 4)
- 16+ card/content item (min. 6) · 13 gambar (min. 6) · Galeri (grid + carousel)
- Form kontak · Footer · Custom CSS · Responsive (Bootstrap grid)
- Komponen Bootstrap: navbar, card, accordion, carousel, progress, list-group, badge, breadcrumb, form

## Keamanan
- Semua aset lokal (tidak ada CDN/font pihak ketiga), Content-Security-Policy ketat, tanpa inline style/script.
- Tidak ada JavaScript buatan sendiri; hanya JS bawaan Bootstrap untuk navbar, accordion, carousel.
- Form: validasi HTML, batas panjang, honeypot anti-spam. Tidak ada kata sandi/data sensitif.

## Yang WAJIB kamu ganti
1. `GANTI_DENGAN_ID_FORM` di `kontak.html` (buat form gratis di formspree.io lalu tempel ID-nya).
2. Menu, harga, angka dana, nama crew, tanggal, lokasi, rekening, dan kontak PIC masih contoh/TBA.
3. Gambar SVG di `assets/img/` ganti foto asli (nama file boleh sama, ubah ekstensi di HTML).
