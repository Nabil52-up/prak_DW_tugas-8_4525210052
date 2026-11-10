# Form Registrasi Event

Project formulir registrasi event menggunakan HTML dan CSS.

## Struktur Folder

- `index.html` — struktur dan elemen formulir.
- `css/style.css` — desain, tata letak, dan tampilan responsif.

## Cara Menjalankan

1. Ekstrak file ZIP.
2. Buka folder `Registrasi-Event`.
3. Buka file `index.html` menggunakan browser.

## Komponen Form

- Input nama, email, dan nomor telepon.
- Radio button kategori peserta.
- Checkbox fasilitas tambahan dan persetujuan.
- Select jenis event.
- Textarea alasan mengikuti event.
- Upload dokumen.
- Tombol submit dan reset.

## Catatan Validasi

Validasi dasar menggunakan fitur bawaan HTML seperti `required`, `type="email"`, `pattern`, `minlength`, dan `maxlength`. Atribut `accept` membantu menyaring pilihan file pada file picker, tetapi bukan pemeriksaan keamanan file.

Project ini belum memiliki backend. Karena itu, data belum disimpan dan validasi sisi server belum diterapkan. Dalam implementasi sesungguhnya, data dan file tetap harus diperiksa di server.
