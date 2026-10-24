# CV Online — HTML, CSS, Bootstrap 5.3.8

## Struktur file
- `index.html` — halaman CV online.
- `css/style.css` — gaya tambahan agar tampilan lebih rapi dan profesional.
- `assets/foto-profil.jpg` — tempat foto profil (buat folder `assets`, lalu masukkan foto Anda).
- `bootstrap-5.3.8-dist/` — salin folder Bootstrap 5.3.8 lokal Anda ke lokasi ini, atau sesuaikan path CSS dan JS pada `index.html`.

## Cara menjalankan
1. Ekstrak ZIP.
2. Letakkan folder distribusi Bootstrap lokal sehingga path berikut tersedia:
   - `bootstrap-5.3.8-dist/css/bootstrap.min.css`
   - `bootstrap-5.3.8-dist/js/bootstrap.bundle.min.js`
3. Buat folder `assets` di samping `index.html`, lalu letakkan foto Anda dengan nama `foto-profil.jpg`.
4. Buka `index.html` di browser.

Jika folder Bootstrap Anda bernama lain, ubah dua path `href` dan `src` Bootstrap di `index.html`.

## Bagian yang perlu diganti
Cari teks dalam tanda kurung siku, misalnya `[Nama Proyek Pertama]`, lalu ganti dengan informasi Anda. Ganti juga `Nama Anda`, email, lokasi, tautan LinkedIn/GitHub, pendidikan, pengalaman, dan teknologi yang dikuasai.

Untuk setiap kartu portofolio, ganti `href="#"` dengan tautan proyek yang benar. Kartu memakai blok visual warna sederhana tanpa gambar agar tetap rapi sebelum Anda menambahkan thumbnail proyek.

## Catatan
Template ini tidak memakai CDN; Bootstrap dimuat dari file lokal. Tidak ada framework JavaScript tambahan.
