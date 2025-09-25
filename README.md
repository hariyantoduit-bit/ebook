# 📖 Ebook Interaktif dengan Flipbook

Proyek ini berisi **ebook interaktif** berbasis [Turn.js](http://www.turnjs.com/) dan **jQuery**, dibuat agar tampak seperti buku nyata dengan fitur **bolak-balik halaman**.

## 🚀 Demo Online
Lihat langsung di GitHub Pages:  
👉 [https://hariyantoduit-bit.github.io/ebook/](https://hariyantoduit-bit.github.io/ebook/)

---

## 📂 Struktur Folder
/ebook
│── index.html # halaman utama flipbook
│── js/
│ ├── jquery.min.js
│ └── turn.min.js
│── images/
│ ├── page1.jpg
│ ├── page2.jpg
│ ├── page3.jpg
│ └── ... dst


---

## 🔧 Cara Menambahkan Buku Baru
1. Buat folder baru misalnya `/laporan2023/`.
2. Copy `index.html` ke folder tersebut.
3. Masukkan gambar halaman buku ke dalam `images/` (nama: `page1.jpg`, `page2.jpg`, dst).
4. Ubah **`totalPages`** di `index.html` sesuai jumlah halaman.

Contoh:
```js
const totalPages = 20;

Buku bisa diakses lewat URL:
https://hariyantoduit-bit.github.io/ebook/

🛠 Cara Deploy ke GitHub Pages

Push semua file ke branch main (atau master).

Buka tab Settings → Pages.

Pilih Source = Deploy from a branch.

Pilih branch main + folder / (root) lalu Save.

Tunggu 1–2 menit → akses link Pages.

⚡ Tips

Jangan push berulang kali terlalu cepat → bisa bikin deploy error.

Kalau muncul error in progress deployment:

Tunggu deploy selesai atau

Cancel workflow yang masih jalan, lalu deploy ulang.

Untuk mempercepat load, kompres gambar JPG sebelum upload.

✨ Fitur

Tampilan seperti buku nyata 📖

Navigasi dengan klik, drag, swipe

Tombol Next / Prev untuk navigasi manual

Responsive di HP, tablet, dan desktop

📌 Dibuat untuk percobaan digitalisasi buku & laporan agar lebih interaktif.
🛠 Cara Deploy ke GitHub Pages

Push semua file ke branch main (atau master).

Buka tab Settings → Pages.

Pilih Source = Deploy from a branch.

Pilih branch main + folder / (root) lalu Save.

Tunggu 1–2 menit → akses link Pages.

⚡ Tips

Jangan push berulang kali terlalu cepat → bisa bikin deploy error.

Kalau muncul error in progress deployment:

Tunggu deploy selesai atau

Cancel workflow yang masih jalan, lalu deploy ulang.

Untuk mempercepat load, kompres gambar JPG sebelum upload.

✨ Fitur

Tampilan seperti buku nyata 📖

Navigasi dengan klik, drag, swipe

Tombol Next / Prev untuk navigasi manual

Responsive di HP, tablet, dan desktop

📌 Dibuat untuk percobaan digitalisasi buku & laporan agar lebih interaktif.
