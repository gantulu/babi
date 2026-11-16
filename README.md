# BABI

Repository ini merupakan source project aplikasi web yang dirancang untuk dijalankan melalui **Gemini Canvas**.

## Gambaran Umum

Aplikasi menggunakan pendekatan sederhana dengan `index.html` sebagai entry point utama. File tersebut menjadi tempat struktur halaman, tampilan, dan kode aplikasi yang diperlukan oleh Gemini Canvas.

Project ini mengandalkan runtime yang telah disediakan oleh aplikasi Gemini Canvas untuk integrasi AI.

## Teknologi dan Runtime

- **HTML** — struktur dan entry point aplikasi melalui `index.html`.
- **Gemini Canvas Runtime** — lingkungan eksekusi dan integrasi AI yang disediakan oleh Gemini Canvas.
- **Client-side application** — kode aplikasi dijalankan di lingkungan frontend.

## Integrasi AI dan API Key

Project ini **tidak memerlukan API key Gemini yang ditulis atau disimpan di dalam repository**.

Alasannya:
- Gemini Canvas telah menyediakan runtime dan integrasi AI yang diperlukan.
- Aplikasi menggunakan fasilitas yang tersedia dari runtime Gemini Canvas.
- Tidak perlu menambahkan API key ke `index.html`, file konfigurasi, atau environment variable untuk penggunaan di Gemini Canvas.

> **Catatan:** Ketergantungan pada runtime Gemini Canvas berarti fitur integrasi AI dapat tidak berjalan jika `index.html` dibuka di browser biasa atau lingkungan hosting lain yang tidak menyediakan runtime tersebut.

## Struktur Repository

```text
babi/
└── index.html    # Entry point aplikasi untuk Gemini Canvas
```

Struktur dapat berkembang sesuai kebutuhan aplikasi. Dokumentasi ini tidak mengasumsikan adanya framework, backend, database, atau layanan eksternal yang belum ditambahkan ke repository.

## Menjalankan Aplikasi

1. Buka project melalui Gemini Canvas.
2. Gunakan `index.html` sebagai entry point.
3. Jalankan aplikasi di dalam runtime Gemini Canvas agar integrasi AI yang disediakan platform tersedia.

## Prinsip Pengembangan

- Utamakan kompatibilitas dengan runtime Gemini Canvas.
- Jangan meminta pengguna memasukkan API key Gemini untuk penggunaan di Gemini Canvas.
- Jangan menanamkan API key atau kredensial rahasia ke source code.
- Pertahankan implementasi sesederhana mungkin sesuai kebutuhan aplikasi.
- Perbarui README ini apabila struktur, dependensi, atau cara menjalankan aplikasi berubah.

---

**Runtime utama:** Gemini Canvas  
**Entry point:** `index.html`  
**API key Gemini:** Tidak diperlukan di repository untuk penggunaan melalui Gemini Canvas.
