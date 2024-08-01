# Bookshelf API
Bookshelf API adalah sebuah proyek yang dibangun menggunakan Node.js dan framework Hapi untuk mengelola data buku. API ini menyediakan berbagai endpoint untuk menyimpan, melihat, mengedit, dan menghapus data buku.

## Fitur Utama
- Menyimpan Buku: Menyimpan buku baru dengan informasi seperti nama buku, tahun terbit, penulis, penerbit, dan lain-lain.  
- Semua Buku: Menampilkan seluruh buku yang tersimpan.
- Detail Buku: Menampilkan detail buku berdasarkan ID.
- Edit Buku: Mengubah data buku yang sudah ada berdasarkan ID buku.
- Hapus Buku: Menghapus buku berdasarkan ID buku.

## Teknologi yang Digunakan
- Node.js: Platform untuk menjalankan kode JavaScript di server.
- Hapi: Framework untuk membangun aplikasi web dan API dengan lebih mudah dan terstruktur.
- Nodemon: Alat untuk pengembangan yang secara otomatis me-restart aplikasi ketika ada perubahan kode.
- NanoID: Alat untuk membuat ID secara acak.
- ESLint: Alat untuk mengidentifikasi dan melaporkan pola yang ditemukan dalam kode ECMAScript/JavaScript, dengan tujuan membuat kode lebih konsisten dan menghindari bug.

## Endpoint
- POST /books: Menyimpan buku baru.
- GET /books: Menampilkan semua buku.
- GET /books/{bookId}: Menampilkan detail buku berdasarkan ID.
- PUT /books/{bookId}: Mengedit data buku berdasarkan ID.
- DELETE /books/{bookId}: Menghapus buku berdasarkan ID.
