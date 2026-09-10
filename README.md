# MYTHIC SEASON 3 — Madiun Youth IT Competition

Landing page statis untuk Mythic Season 3, Madiun Youth IT Competition.

**Live:** https://akyssssf.github.io/mythic-s3/

## Isi

- `index.html` — seluruh halaman (markup + CSS inline + JS vanilla)
- `assets/` — logo, hero lockup, dan header tiap section

Tanpa build step dan tanpa dependency runtime. Font dimuat dari Google Fonts.

## Section

`#hero` · `#lomba` · `#timeline` · `#biaya` · `#syarat` · `#daftar`

## Jalankan lokal

```bash
python3 -m http.server 8000
```

Lalu buka http://localhost:8000

## Catatan

Halaman ini dikonversi dari kanvas Claude Design (`.dc.html`) menjadi HTML statis
biasa — runtime editor dan React dihapus, sementara countdown, scroll reveal, dan
parallax ditulis ulang sebagai JS vanilla.

Countdown menghitung mundur ke Technical Meeting: `2026-10-09T19:00:00+07:00`
(diatur di bagian atas blok `<script>` pada `index.html`).
