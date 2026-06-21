# Sharing Caring Blog 📝

Template weblog statis yang sangat cepat, responsif, dan premium. Dibuat khusus untuk di-host secara gratis di **GitHub Pages** menggunakan database berbasis **JSON**.

## 🚀 Fitur Utama
- **Tanpa Database Server**: Menggunakan file `posts.json` sebagai pengganti database MySQL.
- **Pencarian Artikel**: Fitur pencarian kata kunci instan langsung di sisi client.
- **Filter Kategori**: Menyaring artikel berdasarkan kategori secara dinamis.
- **Desain Premium**: Tampilan modern bernuansa gelap (*dark-first*) dengan aksen gradasi ungu-pink (*violet-magenta*), font Outfit & Inter, serta animasi mikro yang halus.
- **100% Gratis & Aman**: Host di GitHub Pages gratis selamanya, tanpa resiko serangan keamanan SQL injection.

---

## ⚙️ Cara Mengaktifkan di GitHub Pages

Agar blog ini bisa diakses secara online oleh siapa saja, ikuti langkah-langkah berikut:

1. **Upload Semua File ke GitHub**:
   Upload isi dari folder ini (`index.html`, `post.html`, `posts.json`, `style.css`, `README.md`) ke repositori GitHub Anda (misal: `sharingcaring`).

2. **Aktifkan GitHub Pages**:
   - Masuk ke repositori Anda di GitHub.
   - Klik tab **Settings** (Pengaturan).
   - Di sidebar kiri, klik menu **Pages**.
   - Di bagian **Build and deployment** -> **Source**, pilih **Deploy from a branch**.
   - Di bawah **Branch**, pilih branch utama Anda (biasanya `master` atau `main`), lalu pilih folder `/ (root)`.
   - Klik tombol **Save** (Simpan).

3. **Kunjungi Website Anda**:
   Tunggu sekitar 1–2 menit. Segarkan halaman Settings tersebut, Anda akan melihat pesan seperti ini di bagian atas:
   > *Your site is live at `https://username.github.io/repository-name/`*

---

## ✍️ Cara Menambah / Mengubah Artikel Blog

Setiap kali Anda ingin memposting tulisan baru atau mengedit tulisan lama:

1. Buka file `posts.json`.
2. Tambahkan objek JSON baru di dalam array seperti contoh berikut:
   ```json
   {
     "id": 4,
     "title": "Judul Artikel Baru Anda",
     "slug": "judul-artikel-baru",
     "date": "2026-06-09",
     "category": "Kategori",
     "author": "Nama Penulis",
     "image": "https://url-gambar-unggulan.com/gambar.jpg",
     "excerpt": "Ringkasan pendek artikel yang akan tampil di halaman depan...",
     "content": "<p>Teks isi artikel lengkap di sini. Anda bisa menggunakan tag HTML seperti <strong>tebal</strong>, <em>miring</em>, atau tautan.</p>"
   }
   ```
3. Simpan dan lakukan **commit** / push file tersebut ke GitHub.
4. Blog Anda online akan langsung terupdate secara otomatis!
