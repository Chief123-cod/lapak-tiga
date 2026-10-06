# Prompt untuk Antigravity

Salin seluruh teks di bawah garis, tempel ke Antigravity, dengan folder `lapak-tiga/` terbuka sebagai workspace.

---

Kamu adalah front-end developer. Workspace ini berisi website statis "Lapak Tiga": booth Angkatan Tingkat 2 (Semester 3) Fakultas Ilmu Komputer untuk acara Filkom Day 2026. Teknologi WAJIB: HTML, CSS, Bootstrap 5.3.3 (sudah ada lokal di `assets/vendor/bootstrap/`).

## Aturan keras
- Jangan buat `node_modules`, `package.json`, bundler, atau framework. Jangan pakai CDN atau font eksternal.
- Jangan tulis JavaScript sendiri. Hanya `bootstrap.bundle.min.js` yang boleh dimuat. (Aku akan putuskan soal JS setelah melihat hasilnya; jangan menambahkannya tanpa izin.)
- Pertahankan struktur folder: halaman HTML di root; CSS di `assets/css/`; gambar di `assets/img/`; vendor di `assets/vendor/`.
- Pertahankan Content-Security-Policy di setiap `<head>`: tanpa inline `style=""`, tanpa inline `<script>`.
- Jangan mengarang data. Tanggal, lokasi, rekening, nama crew, dan kontak PIC yang belum ada tetap "menyusul/TBA".

## Ketentuan tugas yang harus tetap terpenuhi
Min. 4 halaman, Navbar, Hero, min. 4 section di Home, min. 6 card, min. 6 gambar, Gallery, min. 1 Form, Footer, min. 4 komponen Bootstrap, Custom CSS, Responsive. Gunakan semantic HTML (header, nav, main, section, article, figure, footer), heading berurutan, alt text yang bermakna, dan label pada setiap input.

## Arah desain (jangan ubah jadi tampilan template/AI generik)
Konsep: lapak/tenda pasar. Krem berpapan titik, tinta hijau tua, tomat, mustard. Garis tebal 3px, bayangan keras offset, kartu agak miring saat hover, stiker bulat, tenda belang di bawah navbar. Heading Fraunces, isi DM Sans. Hindari gradasi ungu/biru, glassmorphism, dan emoji sebagai dekorasi.

## Tugas
1. Tinjau seluruh file, jalankan server lokal (`python -m http.server`), dan cek tiap halaman di lebar 360, 768, 1280 px.
2. Perbaiki bug tata letak, kontras warna (target WCAG AA), dan fokus keyboard tanpa mengubah konsep desain.
3. Rapikan CSS di `assets/css/style.css`: kelompokkan dengan komentar, hapus aturan tak terpakai.
4. Laporkan perubahan dalam daftar singkat. Jangan menambah halaman atau fitur baru sebelum aku setuju.
