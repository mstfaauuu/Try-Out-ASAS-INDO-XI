# Ruang Bahasa — Template Try Out Bahasa Indonesia

Template try out berbasis teks bacaan dengan palet coffee editorial.

## Mulai
1. Ekstrak folder project.
2. Buka folder `template website` di VS Code.
3. Jalankan dengan Live Server (disarankan), karena project menggunakan `fetch()` untuk membaca JSON.

## Mengisi bank soal
Edit `bank-soal.json`. Setiap paket A–E berisi 40 nomor. Tiap nomor memiliki `reading` (teks bacaan), `question` (pertanyaan), dan `options` (opsi A–E).

Contoh nomor soal:
```json
{
  "number": 1,
  "reading": "Teks bacaan...",
  "question": "Gagasan utama teks tersebut adalah ...",
  "options": {"A":"...", "B":"...", "C":"...", "D":"...", "E":"..."}
}
```
Kunci jawaban tetap berada di `kunci-jawaban/paket-X/kunci.json`.
