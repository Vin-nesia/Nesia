# Vin Nesia - Direktori Alat AI

Vin Nesia adalah direktori alat AI berbasis static site yang cepat, responsif, dan SEO-friendly. Dibangun tanpa backend menggunakan HTML, CSS, dan JavaScript dengan data dari `tools.json`. Situs ini di-deploy di [https://vinnesia.github.io/ToolsNesia/](https://vinnesia.github.io/ToolsNesia/).

## Fitur
- **Filter Kategori**: Pilih kategori alat AI via dropdown.
- **Pencarian**: Cari alat berdasarkan nama/deskripsi tanpa reload.
- **Dark Mode**: Toggle mode terang/gelap, tersimpan di LocalStorage.
- **Bookmark**: Simpan alat favorit ke LocalStorage dengan tombol bookmark.
- **Halaman Favorit**: Lihat daftar alat yang dibookmark.
- **Pagination**: Tampilkan 9 alat per halaman dengan tombol Prev/Next.
- **Responsif**: Desain mobile-friendly untuk HP dan desktop.
- **SEO-Friendly**: Meta tag, Open Graph, dan Twitter Card dioptimalkan.
- **GitHub Pages**: Siap di-deploy ke GitHub Pages.

## Struktur File
- `index.html`: Struktur utama situs.
- `styles.css`: Styling situs, termasuk dark mode dan responsif.
- `script.js`: Logika untuk filter, search, pagination, bookmark, dan dark mode.
- `tools.json`: Data alat AI.
- `logo.svg`: Logo situs dengan tema AI (biru #4A90E2, ungu #9B59B6).
- `favicon.ico`: Ikon situs.

## Cara Menjalankan
1. Clone repository: `git clone https://github.com/vinnesia/ToolsNesia.git`.
2. Buka `index.html` di browser atau jalankan server lokal (`python -m http.server 8000`).
3. Tambahkan data alat AI ke `tools.json` dengan format:
   ```json
   {
       "id": "unique-id",
       "name": "Nama Alat",
       "description": "Deskripsi alat",
       "category": "Kategori",
       "url": "https://example.com"
   }
