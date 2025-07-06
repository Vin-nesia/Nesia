# Vin Nesia - Direktori Alat AI

Vin Nesia adalah direktori alat AI yang menyerupai desain `anaiorthat.com`, dibangun sebagai situs statis dengan HTML, CSS, dan JavaScript. Di-deploy di [https://vinnesia.github.io/ToolsNesia/](https://vinnesia.github.io/ToolsNesia/).

## Fitur
- **Header**: Menu, mode toggle, dan spotlight feature.
- **Hero Section**: Tagline, stats, search bar, quick links, dan nav tabs.
- **Featured Section**: Tombol berita dan daftar alat terbaru.
- **Footer**: Navigasi sederhana.
- **Responsif**: Desain mobile-friendly.

## Struktur File
- `index.html`: Struktur utama situs.
- `styles.css`: Styling menyerupai `anaiorthat.com`.
- `script.js`: Logika sederhana untuk search dan toggle.
- `tools.json`: Data alat AI.
- `logo.svg`: Logo situs dengan tema AI.

## Cara Menjalankan
1. Clone repository: `git clone https://github.com/vinnesia/ToolsNesia.git`.
2. Buka `index.html` di browser atau jalankan server lokal (`python -m http.server 8000`).
3. Tambahkan data alat ke `tools.json`.

## Deployment ke GitHub Pages
1. Push semua file ke repository `vinnesia/ToolsNesia`.
2. Aktifkan GitHub Pages di pengaturan (branch: `main`, folder: `/`).
3. Akses situs di [https://vinnesia.github.io/ToolsNesia/](https://vinnesia.github.io/ToolsNesia/).

## Catatan
- Desain meniru `anaiorthat.com` dengan warna dan tata letak serupa.
- Fungsi penuh (filter, bookmark) dapat ditambahkan di `script.js` jika diperlukan.
