# 🎬 Shopee Video Generator 9:16 (v3.8)

Aplikasi web **100% gratis dan ringan** untuk membuat video promosi vertikal **9:16** siap unggah ke **Shopee Video**, **Instagram Reels**, maupun **TikTok** langsung dari browser (HP maupun laptop) tanpa perlu server atau langganan berbayar.

---

## ✨ Fitur Utama

* **Anti-Blank Canvas Rendering:** Pratinjau kanvas sinkron secara langsung dengan animasi *Ken Burns* (*slow zoom* halus) untuk 1 hingga 5 foto produk sekaligus.
* **Export Langsung ke `.MP4`:** Menggunakan *Pure JS ISO-BMFF MP4 Muxer* (`H.264 + AAC Audio`) yang dilengkapi *fallback* perekam bawaan perangkat agar kompatibel di berbagai browser mobile maupun desktop.
* **Impor Data Produk / Google Sheets:** Mendukung impor massal melalui unggah file `.CSV` / `.TSV` / `.TXT` maupun tempel (*paste*) baris langsung dari Google Sheets, lengkap dengan tombol navigasi **Prev / Next**.
* **Voice Over & Subtitle Dinamis:**
  * *AI Text-to-Speech* otomatis berbahasa Indonesia beserta *subtitle* sinkron di layar.
  * Dukungan **Rekam Mic** langsung dari browser atau unggah file audio VO sendiri (`.MP3` / `.WAV` / `.M4A`).
* **Musik Latar Bawaan:** Pilihan *beat* audio bebas hak cipta (*Shopee Upbeat*, *Lo-Fi Santai*, *Flash Sale Cepat*) atau unggah musik latar kustom.
* **Panduan Safe-Zone Shopee Video:** Garis bantu visual agar teks *hook*, harga promo, dan tombol ajakan (*CTA*) tidak tertutup ikon interaksi di sisi kanan maupun keranjang oranye di bagian bawah aplikasi.

---

## 🚀 Cara Penggunaan

1. **Siapkan Data Produk:**
   * Klik **⚡ Isi Contoh** atau **📥 Impor CSV / Paste** untuk memuat daftar produk dari Google Sheets, atau isi langsung kolom *Hook*, *Nama Produk*, *Harga Promo*, dan *CTA*.
2. **Unggah Foto Produk:**
   * Pilih **1 hingga 5 foto produk** (`JPG`/`PNG`/`WebP`). Gambar otomatis dikompresi agar tetap ringan di memori perangkat.
3. **Atur Narasi & Musik:**
   * Tulis naskah narasi di kolom **Naskah Narasi**, lalu klik **🔊 Tes Narasi** atau gunakan **🎤 Rekam Mic** untuk merekam suara asli.
   * Pilih *beat* musik latar bawaan atau unggah file audio sendiri.
4. **Preview & Generate MP4:**
   * Klik **▶ Preview Animasi** untuk memeriksa tampilan dan sinkronisasi suara.
   * Klik **⬇ Generate Video MP4**, tunggu proses rendering hingga `100%`, lalu tekan tombol **💾 Simpan File MP4 ke HP**.

---

## 🌐 Cara Menjalankan via GitHub Pages

1. Pastikan file aplikasi utama (`index_3.html`) sudah di-*rename* menjadi **`index.html`** dan diunggah ke *root* repository GitHub bersama file **`README.md`** ini.
2. Buka tab **Settings** > **Pages** pada repository GitHub Anda.
3. Pada bagian **Build and deployment > Branch**, pilih `main` dan folder `/ (root)`, lalu klik **Save**.
4. Tunggu sekitar 1 menit hingga tautan aplikasi GitHub Pages aktif dan siap dibuka dari browser HP maupun PC.