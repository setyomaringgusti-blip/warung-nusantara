# Warung Nusantara — Multi-page Website

Warung Nusantara adalah platform web bisnis kuliner berbasis responsif yang dirancang untuk mengoptimalkan pengalaman pengguna (User Experience) dalam menjelajahi informasi produk, daftar harga, dan profil usaha kuliner khas Indonesia. Proyek ini dibangun dengan fokus pada performa pemuatan halaman, struktur kode yang semantik, dan fleksibilitas tampilan di berbagai perangkat.

---

## Spesifikasi Teoretis & Solusi Teknis

Proyek ini tidak hanya berfokus pada visual, melainkan juga mengimplementasikan beberapa standardisasi pengembangan web modern untuk mengatasi kendala performa:

* **Implementasi Image Optimization 80%:** Melakukan kompresi dan konversi aset gambar ke format modern untuk memangkas ukuran berkas tanpa merusak kualitas visual. Langkah ini berhasil mereduksi beban *bandwidth* secara signifikan.
* **Native Lazy Loading:** Menerapkan atribut pemuatan tertunda pada elemen gambar di luar area pandang (*viewport*). Hal ini mempercepat metrik *First Contentful Paint* (FCP) dan menghemat konsumsi data pengguna.
* **Multi-page Architecture:** Memisahkan komponen informasi ke dalam struktur berkas HTML yang modular (`index.html`, `about.html`, `produk.html`, `harga.html`, `contact.html`) untuk mempermudah pemeliharaan kode (*maintainability*) dan optimasi SEO spesifik per halaman.
* **Responsive Layout Grid:** Memanfaatkan utilitas grid dan komponen fleksibel dari Bootstrap 5 untuk menjamin konsistensi antarmuka saat diakses melalui perangkat seluler, tablet, maupun desktop.

---

## Teknologi yang Digunakan

* **HTML5:** Penyusunan struktur dokumen web menggunakan elemen semantik untuk aksesibilitas dan optimasi mesin pencari.
* **CSS3 & Bootstrap 5:** Framework tata letak utama untuk mempercepat proses *styling* yang konsisten dan pemanfaatan sistem grid responsif.
* **JavaScript:** Implementasi logika interaktivitas dasar pada komponen antarmuka web (jika ada).

---

## Struktur Repositori

```text
├── images/          # Direktori penyimpanan aset gambar yang telah dioptimasi
├── about.html       # Halaman informasi profil bisnis
├── contact.html     # Halaman informasi kontak dan lokasi
├── harga.html       # Halaman daftar harga menu kuliner
├── index.html       # Halaman utama (Landing Page)
├── produk.html      # Halaman katalog produk kuliner
└── style.css        # Berkas kustomisasi gaya visual (CSS)

# Cara Menjalankan Project secara lokal
1. Salin repositori ini menggunakan perintah Git:
git clone [https://github.com/setyomaringgusti-blip/nama-repositori-anda.git](https://github.com/setyomaringgusti-blip/nama-repositori-anda.git)
2. Buka direktori proyek:
cd warung-nusantara
3. Buka berkas index.html menggunakan peramban (browser) pilihan Anda, atau gunakan ekstensi Live Server di Visual Studio Code untuk mendapatkan pembaruan pratinjau secara langsung.

---

## Cara Mengirim File README Ini ke GitHub

Setelah Anda membuat file dan menempelkan teks di atas, jalankan 3 perintah ini secara berurutan di terminal VS Code Anda untuk memperbarui repositori GitHub:

```bash
git add README.md
git commit -m "docs: add professional README for Warung Nusantara"
git push