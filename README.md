# Portfolio & Creative CV — B.J. Habibie

Praktikum Modul 1 (HTML & CSS) — Pemrograman Web 2026
Departemen Teknologi Informasi, Institut Teknologi Sepuluh Nopember
Kelompok **A01**

## Tentang

Website portofolio dan Creative CV untuk **Bacharuddin Jusuf Habibie** (1936–2019) —
insinyur penerbangan, ilmuwan, dan Presiden ke-3 Republik Indonesia.

## Anggota Kelompok

| Nama | NRP | Bagian yang dikerjakan |
|---|---|---|
| Kharisma Fahrun Nisa' | 5027231086 | Responsive & pengujian lintas ukuran layar, fitur tambahan |
| Ryan Adya Purwanto | 5027231046 | Landing page (`index.html`), styling (`style.css`), struktur repo |
| George David Nebore | 5027221043 | Halaman Creative CV (`cv.html`) |

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
| Call to action ke CV | Tombol "Lihat CV" di hero, menu navbar, dan section ajakan akhir |
| Creative CV | `cv.html` — foto, deskripsi karakter, karier, pendidikan, keahlian, penghargaan |
| Multi page | 2 halaman: `index.html` dan `cv.html` |
| Pseudo-class | `:hover`, `:focus`, `:active` |
| Position | `sticky` + `z-index` pada navbar |
| Display | `block`, `inline-block`, `flex`, `grid` |
| Flex | Navbar, menu, tombol hero, identitas CV, baris CV, footer |
| Grid | Hero, statistik, kerangka bagian, linimasa, kartu karya, kartu CV |
| Responsive | Media query `900px` (tablet) dan `600px` (HP) |

Setiap blok CSS yang memenuhi requirement di atas ditandai komentar `[REQ: ...]`
di dalam `style.css` agar mudah ditelusuri. Seluruh properti CSS yang dipakai
diambil dari materi Modul 1, tanpa custom property, gradien, atau efek di luar modul.

