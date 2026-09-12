# Portfolio & Creative CV — B.J. Habibie

Praktikum Modul 1 (HTML & CSS) — Pemrograman Web 2026
Departemen Teknologi Informasi, Institut Teknologi Sepuluh Nopember
Kelompok **A01**

## Tentang

Website portofolio dan Creative CV untuk **Bacharuddin Jusuf Habibie** (1936–2019) —
insinyur penerbangan, ilmuwan, dan Presiden ke-3 Republik Indonesia.

Dibangun **native from scratch** menggunakan HTML dan CSS saja, tanpa framework
(tanpa Bootstrap, Tailwind, atau sejenisnya) sesuai ketentuan modul.

## Anggota Kelompok

| Nama | NRP | Bagian yang dikerjakan |
|---|---|---|
| Ryan Adya Purwanto | 5027231046 | Landing page, struktur repo |
| _(isi nama)_ | _(isi NRP)_ | Halaman Creative CV |
| _(isi nama)_ | _(isi NRP)_ | Responsive & fitur tambahan |

## Cara Menjalankan

Tidak butuh instalasi apa pun.

1. Clone repository ini
2. Buka `index.html` di browser

Atau gunakan ekstensi **Live Server** di VS Code: klik kanan `index.html` →
_Open with Live Server_.

## Struktur File

```
.
├── index.html      # Landing page
├── cv.html         # Halaman Creative CV
├── style.css       # Seluruh styling (dipakai kedua halaman)
├── img/            # Aset gambar
```

## Pemenuhan Requirement

| Requirement | Di mana |
|---|---|
| Landing page | `index.html` |
| Call to action ke CV | Tombol "Lihat Curriculum Vitae" di hero, menu navbar, dan section ajakan akhir |
| Creative CV | `cv.html` — foto, deskripsi karakter, experience, education, skills |
| Multi page | 2 halaman: `index.html` dan `cv.html` |
| Pseudo-class | `:hover`, `:focus-visible`, `:active`, `:first-of-type`, `:first-child` |
| Position | `sticky` (navbar), `relative` + `absolute` (bingkai foto, garis bawah menu) |
| Display | `block`, `inline-block`, `flex`, `grid` |
| Flex | Navbar, menu, tombol hero, item linimasa, footer |
| Grid | Hero, statistik, paragraf tentang, linimasa, kartu karya |
| Responsive | Media query `900px` (tablet) dan `600px` (HP) |

Setiap blok CSS yang memenuhi requirement di atas ditandai komentar `[REQ: ...]`
di dalam `style.css` agar mudah ditelusuri.

