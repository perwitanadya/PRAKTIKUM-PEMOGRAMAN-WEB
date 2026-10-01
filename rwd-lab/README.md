<!-- # Praktikum Pemrograman Web — RWD Lab

## Deskripsi
Proyek portal katalog solusi TI menggunakan HTML5 semantik dan CSS3 murni dengan pendekatan mobile-first.

## Cara menjalankan
1. Buka folder `rwd-lab` di Visual Studio Code.
2. Jalankan `index.html` menggunakan ekstensi Live Server.
3. Uji ukuran layar 360px, 768px, 1024px, 1440px, dan 1920px melalui DevTools.

## Fitur
- Landmark semantik: header, nav, main, section, article, footer.
- Skip link untuk melewati navigasi.
- CSS reset dan design tokens.
- Flexbox untuk navigasi dan komponen.
- CSS Grid fluid untuk katalog.
- Media queries mobile-first.
- Penanganan teks panjang menggunakan `min-width: 0` dan `overflow-wrap: anywhere`.

## Matriks pengujian
| ID | Fitur | Viewport/Metode | Ekspektasi | Hasil aktual | Status | Bukti |
|---|---|---|---|---|---|---|
| TC-01 | Navigasi menu | 360–480px | Menu membungkus rapi dan terbaca | Isi setelah diuji | Isi setelah diuji | screenshot |
| TC-02 | Hero section | 768px | Layout menjadi seimbang | Isi setelah diuji | Isi setelah diuji | screenshot |
| TC-03 | Grid katalog | 360–1920px | Kolom menyesuaikan tanpa scrollbar horizontal | Isi setelah diuji | Isi setelah diuji | screenshot |
| TC-04 | Skip link | Keyboard Tab | Skip link muncul saat fokus pertama | Isi setelah diuji | Isi setelah diuji | screenshot |

## Catatan
Isi kolom hasil aktual dan status berdasarkan pengujian yang benar-benar dilakukan. Jangan menandai Pass sebelum diuji. -->