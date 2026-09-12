# Portofolio & Creative CV — Prof. Dr.-Ing. B.J. Habibie

Praktikum Modul 1 (HTML & CSS Native) &mdash; Pemrograman Web 2026  
Departemen Teknologi Informasi, Institut Teknologi Sepuluh Nopember (ITS)  
Kelompok **A01**

---

## Tentang Proyek

Website portofolio interaktif dan **Creative CV** untuk mengenang serta mempelajari rekam jejak **Bacharuddin Jusuf Habibie** (1936–2019) &mdash; ilmuwan aeronautika penemu *Habibie Factor*, teknokrat perintis kedirgantaraan Indonesia, dan Presiden ke-3 Republik Indonesia.

---

## Anggota Kelompok A01

| Nama | NRP | Peran & Bagian yang Dikerjakan |
|---|---|---|
| Ryan Adya Purwanto | 5027231046 | Landing page, struktur repo & rancangan arsitektur CSS |
| George David Nebore | 5027221043 | Desain & implementasi Creative CV (`cv.html`), deskripsi karakter & portofolio |
| Kharisma Fahrun Nisa' | 5027231086 | Optimasi Responsive (PC/Tab/HP), fitur tambahan |

---

##  Fitur Tambahan

1. **Fitur Unik 1**:
   - Toggle di navbar untuk berpindah antara tema terang dan tema gelap.
   - Tersimpan otomatis di `localStorage` peramban.
2. **Fitur Unik 2**:
   - Modul interaktif di landing page untuk membandingkan mahakarya pesawat IPTN: **N-250 Gatotkaca** dan **CN-235 Nusantara**.
   - Menampilkan spesifikasi teknis lengkap: kapasitas, kecepatan jelajah, jangkauan terbang, dan mesin.
3. **Creative CV Siap Ekspor PDF**:
   - Dilengkapi tombol *"Cetak / Simpan PDF CV"* dengan stylesheet `@media print` khusus yang otomatis merapikan tata letak menjadi dokumen CV profesional bebas elemen navigasi web.
4. **Visual Skill Proficiency Meters**:
   - Indikator persentase keahlian dinamis berbasis CSS untuk keahlian aeronautika, kepemimpinan publik, dan kemampuan multibahasa (Indonesia, Jerman, Inggris, Belanda).
5. **Floating Back-to-Top**:
   - Tombol mengambang di pojok kanan bawah (`position: fixed`) dengan transisi pudar dan luncur otomatis saat halaman digulir.

---

## Struktur Direktori

```text
.
├── index.html       # Landing page profil & portofolio utama
├── cv.html          # Halaman Creative CV B.J. Habibie
├── style.css        # Seluruh styling native (dipakai kedua halaman)
├── README.md        # Dokumentasi praktikum kelompok A01
└── img/
    ├── habibie.jpg  # Foto resmi B.J. Habibie resolusi tinggi
    └── habibie.svg  # Cadangan vektor ikon
```

---

##  Cara Menjalankan

Proyek ini tidak memerlukan instalasi dependensi, compiler, maupun server backend:

1. Buka folder proyek di teks editor.
2. Buka berkas `index.html` langsung dengan klik dua kali untuk membukanya di peramban favorit Anda.
3. Atau gunakan ekstensi **Live Server** di VS Code: klik kanan `index.html` &rarr; *Open with Live Server*.
