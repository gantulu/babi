# BABI

BABI adalah repository source code aplikasi web yang ditujukan untuk dikembangkan dan dijalankan melalui **Gemini Canvas**.

Repository ini menggunakan pendekatan sederhana: `index.html` sebagai entry point aplikasi, `prompt.md` sebagai panduan instruksi pengembangan untuk AI, dan `README.md` sebagai dokumentasi repository.

## Struktur Repository

```text
babi/
├── index.html   # Entry point dan implementasi aplikasi
├── prompt.md    # Instruksi pengembangan aplikasi melalui Gemini Canvas
└── README.md    # Dokumentasi repository
```

> Struktur di atas menjelaskan file utama yang direncanakan. File aplikasi seperti `index.html` dapat ditambahkan atau dikembangkan sesuai kebutuhan.

## Runtime

Aplikasi ditujukan untuk berjalan di lingkungan **Gemini Canvas**. Gemini Canvas menyediakan runtime dan integrasi AI yang digunakan oleh aplikasi.

### API Key

Untuk penggunaan melalui Gemini Canvas:

- Tidak perlu meminta pengguna menyediakan Gemini API key.
- Jangan menambahkan API key ke `index.html` atau file source lainnya.
- Gunakan runtime dan kapabilitas AI yang memang disediakan oleh Gemini Canvas.
- Jangan mengasumsikan integrasi runtime tersebut tersedia ketika aplikasi dijalankan di browser atau hosting lain.

## Panduan Pengembangan

1. Baca `prompt.md` sebelum mengembangkan atau mengubah aplikasi.
2. Gunakan kebutuhan dan instruksi pengguna sebagai sumber utama ruang lingkup fitur.
3. Implementasikan aplikasi melalui `index.html`, kecuali ada kebutuhan struktur lain yang telah disetujui.
4. Prioritaskan antarmuka yang responsif, mudah digunakan, dan mudah dipelihara.
5. Jangan menambahkan framework, backend, database, atau layanan eksternal tanpa kebutuhan yang jelas.
6. Uji hasil perubahan di Gemini Canvas.

## Batasan dan Asumsi

- Gemini Canvas adalah target runtime utama.
- Repository tidak mengasumsikan adanya backend atau database.
- Integrasi AI bergantung pada fasilitas runtime Gemini Canvas.
- Menjalankan file di luar Gemini Canvas mungkin tidak menyediakan kapabilitas runtime yang sama.

## Status

Repository ini merupakan basis pengembangan aplikasi. Detail fitur dan kebutuhan produk mengikuti instruksi yang diberikan pada sesi pengembangan.

---

**Runtime utama:** Gemini Canvas  
**Entry point aplikasi:** `index.html`  
**Panduan AI:** `prompt.md`  
**Kebutuhan Gemini API key di repository:** Tidak diperlukan untuk penggunaan melalui runtime Gemini Canvas.
