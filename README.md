# BABI — Gemini Canvas Text-to-Image Studio

Repository ini berisi instruksi dan requirement untuk membangun aplikasi **Text-to-Image Studio** menggunakan Gemini Canvas.

Repository ini menggunakan pendekatan prompt-driven development. File `prompt.md` berfungsi sebagai instruksi utama untuk AI dalam memahami, merancang, dan membangun aplikasi.

## Repository Structure

```text
babi/
├── README.md
├── AI_WORKFLOW.md
└── prompt.md
```

| File | Responsibility |
|---|---|
| `README.md` | Repository overview dan entry point untuk AI. |
| `AI_WORKFLOW.md` | Aturan kolaborasi, tahapan kerja, dan otorisasi pengguna. |
| `prompt.md` | Master prompt dan requirement aplikasi Text-to-Image Studio. |

## Mandatory Instructions for AI

**Sebelum melakukan pekerjaan apa pun di repository ini, AI WAJIB:**

1. Membaca seluruh isi `AI_WORKFLOW.md`.
2. Memahami dan mengikuti aturan kolaborasi, workflow, dan ketentuan otorisasi yang ditetapkan di dalamnya.
3. Membaca `prompt.md` ketika pekerjaan berkaitan dengan requirement, audit, evaluasi, desain, atau pengembangan aplikasi.
4. Melakukan audit terhadap kondisi aktual repository sebelum memberikan rekomendasi atau merencanakan perubahan.
5. Tidak melewati tahapan diskusi dan persetujuan requirement.
6. Tidak mengubah file repository tanpa persetujuan implementasi yang eksplisit dari pengguna.
7. Mengklarifikasi instruksi yang bertentangan sebelum melanjutkan pekerjaan.

Instruksi tersebut berlaku untuk seluruh pekerjaan, termasuk audit, evaluasi, perencanaan, perubahan prompt, dan implementasi.

## Source of Truth

Gunakan pembagian sumber kebenaran berikut:

- `AI_WORKFLOW.md` adalah sumber utama untuk aturan kolaborasi dan otorisasi.
- `prompt.md` adalah sumber utama untuk requirement dan instruksi aplikasi.
- Kondisi aktual repository adalah sumber utama untuk mengetahui implementasi dan perubahan yang sudah tersedia.

Jangan menganggap rekomendasi, asumsi, atau percakapan sebelumnya sebagai requirement yang sudah disetujui apabila belum dikonfirmasi pengguna.

## Important Rules

- Jangan mengarang kemampuan Gemini Canvas, API, SDK, atau runtime.
- Jangan menambahkan fitur di luar scope yang disetujui.
- Jangan mengubah requirement yang sudah dikunci tanpa persetujuan pengguna.
- Jangan melakukan implementasi sebelum mendapatkan persetujuan eksplisit.
- Jangan menyatakan implementasi berhasil tanpa verifikasi.

## Project Scope

Project ini berfokus pada aplikasi **Text-to-Image Studio** yang dibangun menggunakan Gemini Canvas, sesuai requirement yang didefinisikan di `prompt.md`.

Untuk memahami detail aplikasi, baca `prompt.md` setelah membaca `AI_WORKFLOW.md`.

---

**Starting Point:** Read `AI_WORKFLOW.md` completely before starting any task in this repository.
