**Struktur Direktori Generator** 
Sebuah **script HTML sederhana** yang memungkinkan pengguna untuk memilih folder lokal mereka dan menampilkan struktur direktori dalam format pohon (tree structure). Aplikasi ini berguna untuk mengakses dan menampilkan struktur folder dengan cara yang mudah dan visual di aplikasi berbasis web.

## Fitur
* **Pilih Folder Lokal**: Pengguna dapat memilih folder lokal menggunakan **file input** dengan atribut **webkitdirectory**.
* **Tampilkan Struktur Folder**: Struktur folder akan ditampilkan dalam format pohon yang memudahkan pemahaman hirarki folder.
* **Salin Struktur Folder**: Pengguna dapat menyalin struktur folder ke clipboard dengan satu klik.
* **Pesan Umpan Balik**: Setelah menyalin, aplikasi akan menampilkan pesan umpan balik untuk memberitahukan pengguna bahwa salinan berhasil.
* **Minimalis dengan SweetAlert**: Notifikasi tampilan minimalis dengan **SweetAlert2** untuk pengalaman pengguna yang lebih baik.

## Teknologi yang Digunakan
* **HTML5**: Untuk elemen form dan struktur dasar aplikasi.
* **CSS (Bootstrap 5)**: Untuk tampilan aplikasi yang responsif dan modern.
* **JavaScript/jQuery**: Untuk menangani interaksi pengguna seperti pemilihan folder dan salinan struktur folder.
* **SweetAlert2**: Untuk menampilkan pesan umpan balik dan notifikasi minimalis.

## Prasyarat
Browser yang mendukung input **`webkitdirectory`**.

## Instalasi dan Penggunaan

1. **Clone atau Unduh Repository**:

   ```bash
   git clone https://github.com/firmangunajaya/struktur-direktori-generator.git
   ```
2. **Buka di Browser**:
   Cukup buka file **`index.html`** di browser Anda. Aplikasi ini tidak membutuhkan konfigurasi server PHP secara khusus untuk berfungsi.
3. **Pilih Folder**:
   Gunakan input **Browse** untuk memilih folder yang ingin Anda tampilkan strukturnya.
4. **Proses Folder**:
   Klik tombol **Proses Folder** untuk menampilkan struktur folder dalam format pohon di halaman.
5. **Salin Struktur Folder**:
   Klik tombol **Salin Struktur Folder** untuk menyalin struktur folder ke clipboard Anda.
6. **Notifikasi**:
   Setelah menyalin, pesan **"Struktur folder berhasil disalin!"** akan muncul di samping tombol Salin.

## Contoh Penggunaan
* Pilih folder yang berisi beberapa file dan subfolder.
* Setelah struktur folder ditampilkan, Anda dapat menyalinnya ke clipboard dengan tombol **Salin Struktur Folder**.
* Anda juga dapat menyalin struktur folder dan menggunakannya di aplikasi lain.

## Contoh Struktur Folder
Struktur folder ditampilkan dalam format pohon (tree structure), misalnya:
```
├── app
│   ├── .htaccess
│   ├── Common.php
│   ├── Config
│   │   ├── App.php
│   │   ├── Autoload.php
│   │   ├── Boot
│   │   │   ├── development.php
│   │   │   ├── production.php
│   │   │   └── testing.php
│   └── ...
```

## Teknologi yang Digunakan
* **HTML5**: Untuk input file yang memungkinkan pemilihan folder.
* **CSS3 (Bootstrap 5)**: Untuk styling dan tata letak responsif.
* **JavaScript/jQuery**: Untuk manipulasi DOM dan memperbarui path folder yang dipilih.
* **SweetAlert2**: Untuk menampilkan pesan umpan balik setelah menyalin struktur folder.

## Referensi
Berikut adalah beberapa referensi yang digunakan dalam proyek ini:
1. [WebKitDirectory Attribute - MDN](https://developer.mozilla.org/en-US/docs/Web/API/HTMLInputElement/webkitdirectory)
2. [SweetAlert2](https://sweetalert2.github.io/)
3. [jQuery Documentation](https://jquery.com/)
4. [Bootstrap 5 Documentation](https://getbootstrap.com/)

## Lisensi
Proyek ini menggunakan **lisensi MIT**. Lihat [LICENSE](LICENSE) untuk detail lebih lanjut.
