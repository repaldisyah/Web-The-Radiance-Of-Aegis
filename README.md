# The Radiance of Aegis

Website worldbuilding fantasi untuk OC **The Radiance of Aegis**. Proyek ini diarahkan sebagai **interactive fantasy codex**: arsip dunia berisi cerita, karakter, ras, wilayah, prophecy, timeline, gallery, dokumen pendukung, dan aset visual.

Lokasi proyek lokal:

```txt
D:\web oc\Web The Radiance Of Aegis
```

---

## Status Saat Ini

- File halaman di `pages/` sudah dibuat, tetapi masih kosong.
- File CSS di `css/` sudah dibuat, tetapi masih kosong.
- File JavaScript di `js/` sudah dibuat, tetapi masih kosong.
- Aset visual, dokumen karakter, PDF cerita, dan video opening sudah tersedia di `assets/`.
- File referensi lama berada di luar folder proyek utama: `D:\web oc\Reference Home.html`.
- PDF gabungan character sheet sudah dibuat di folder character sheet.

---

## Arah Desain

Tema utama web: **Ancient Fantasy Archive / Interactive Fantasy Codex**.

Nuansa desain yang dituju:

- Parchment manuscript untuk halaman lore, cerita, ras, dan timeline.
- Dark divine fantasy untuk villain, corruption, prophecy, dan Naraka Gate.
- Gold ornament untuk border, divider, tombol, ikon, dan hover state.
- World map archive untuk wilayah dan perjalanan cerita.
- Character codex untuk halaman karakter seperti database pahlawan, support, villain, dan ancient divine beings.

Palet warna awal:

```txt
Dark base        #120F0C / #1A1410
Parchment        #E8D8B5 / #C9AD76
Gold accent      #C9A23A / #F0D77A
Dark brown text  #2A1A10
Corruption red   #7A1E24 / #B53A3A
Forest green     #1F3A2E
Moon silver      #BFC7D5 / #5E6F8C
```

Font yang disarankan:

- Heading: `Cinzel`, `Cinzel Decorative`, atau `Cormorant Garamond`
- Body: `Merriweather`, `Lora`, atau `Libre Baskerville`
- UI kecil: `Inter` atau `Source Sans 3`

---

## Struktur Folder

```txt
Web The Radiance Of Aegis/
|
|-- README.md
|
|-- pages/
|   |-- 01_homepage.html
|   |-- 02_story.html
|   |-- 03_characters.html
|   |-- 04_races.html
|   |-- 05_regions.html
|   |-- 06_prophecy.html
|   |-- 07_timeline.html
|   `-- 08_gallery.html
|
|-- css/
|   |-- 00_global.css
|   |-- 01_homepage.css
|   |-- 02_story.css
|   |-- 03_characters.css
|   |-- 04_races.css
|   |-- 05_regions.css
|   |-- 06_prophecy.css
|   |-- 07_timeline.css
|   `-- 08_gallery.css
|
|-- js/
|   |-- 00_data.js
|   |-- 00_global.js
|   |-- 01_homepage.js
|   |-- 02_story.js
|   |-- 03_characters.js
|   |-- 04_races.js
|   |-- 05_regions.js
|   |-- 06_prophecy.js
|   |-- 07_timeline.js
|   `-- 08_gallery.js
|
`-- assets/
    |-- audio/
    |-- video/
    |   `-- aegis_opening_final_compatible.mp4
    |
    |-- documents/
    |   |-- Character sheet/
    |   |-- Folder Bab/
    |   `-- structure arc/
    |
    `-- image/
        |-- background/
        |-- decoration/
        |-- gallery/
        |-- icon/
        |-- karakter/
        |   |-- divine ancient/
        |   |-- heroes/
        |   |-- support/
        |   `-- villain/
        |-- maps/
        |-- races/
        |-- region/
        |-- story_card/
        `-- ui/
```

---

## Daftar Halaman

| File | Fungsi | Arah visual |
|---|---|---|
| `pages/01_homepage.html` | Halaman utama | Hero fantasy dengan `bg_homepage_lumina_night.png` dan akses ke semua arsip |
| `pages/02_story.html` | Arsip cerita | Story arc cards memakai aset `assets/image/story_card/` |
| `pages/03_characters.html` | Codex karakter | Grid karakter dari heroes, support, villain, dan divine ancient |
| `pages/04_races.html` | Ensiklopedia ras | Katalog ras memakai aset `assets/image/races/` |
| `pages/05_regions.html` | Wilayah dan peta | Map/archive style memakai `assets/image/maps/` dan `assets/image/region/` |
| `pages/06_prophecy.html` | Prophecy dan divine lore | Dark moon temple style dengan aksen corruption |
| `pages/07_timeline.html` | Kronologi sejarah | Old chronicle / scroll timeline |
| `pages/08_gallery.html` | Galeri visual | Archive gallery untuk background, region, dan scene |

---

## Aset Penting

### Background

Folder: `assets/image/background/`

Berisi background untuk homepage, story archive, characters hall, races manuscript, regions world map, prophecy moon temple, timeline chronicle, gallery archive, market, villain section, footer night forest, dan parchment global.

### Karakter

Folder: `assets/image/karakter/`

Kategori:

- `heroes/`
- `support/`
- `villain/`
- `divine ancient/`

### Dokumen Character Sheet

Folder: `assets/documents/Character sheet/`

File DOCX:

- `Character_Sheet_Ashura.docx`
- `Character_Sheet_lyra_Everwood.docx`
- `Character_Sheet_aelia_Avariel.docx`
- `Character_Sheet_Coralina_Syrene.docx`
- `Character_Sheet_Darius.docx`
- `Character_Sheet_Indra.docx`
- `Character_Sheet_Magnus.docx`
- `Character_Sheet_Orion_Silverfield.docx`
- `Character_Sheet_Solara.docx`
- `Character_Sheet_Syrus_Leonin.docx`
- `Character_Sheet_Thrain Ironvein.docx`
- `Character_Sheet_Umbra_Noctis.docx`

File PDF gabungan:

```txt
assets/documents/Character sheet/Character_Sheets_All_Ashura_to_Umbra_Noctis.pdf
```

### Cerita dan Arc

Folder: `assets/documents/Folder Bab/`

- `The Radiance of Aegis bab 1-20.pdf`
- `The Radiance of Aegis bab 21-40.pdf`
- `The Radiance of Aegis bab 41-60.pdf`
- `The Radiance of Aegis bab 61-80.pdf`
- `The Radiance of Aegis bab 81-96 Finish.pdf`

Folder: `assets/documents/structure arc/`

- `Struktur Arc_ The Radiance of Aegis (1).pdf`

### Video

Folder: `assets/video/`

- `aegis_opening_final_compatible.mp4`

---

## Catatan Implementasi

- Gunakan `00_global.css` untuk reset, font, warna global, layout dasar, nav, footer, modal, tombol, dan komponen umum.
- Gunakan file CSS per halaman untuk style yang spesifik.
- Gunakan `00_data.js` sebagai pusat data karakter, ras, region, story arc, dokumen, dan gallery.
- Gunakan `00_global.js` untuk navigasi, modal, audio/video, lazy loading, dan helper umum.
- Path aset harus mengikuti struktur saat ini, misalnya `../assets/video/aegis_opening_final_compatible.mp4` dari dalam folder `pages/`.
- Jangan merujuk `global.css` atau `global.js`; nama file aktual adalah `00_global.css` dan `00_global.js`.

---

## Cara Menjalankan

Karena ini website statis, buka file berikut di browser atau melalui Live Server VS Code:

```txt
pages/01_homepage.html
```

Jika memakai Live Server, jalankan dari root proyek:

```txt
D:\web oc\Web The Radiance Of Aegis
```

---

## Rencana Pengerjaan

1. Isi `00_data.js` dengan data terstruktur dari aset yang tersedia.
2. Buat fondasi visual di `00_global.css`.
3. Bangun `01_homepage.html` sebagai entry utama codex.
4. Lanjutkan halaman Story, Characters, Races, Regions, Prophecy, Timeline, dan Gallery.
5. Tambahkan interaksi JavaScript untuk filter, modal detail, preview dokumen, dan navigasi antar halaman.
6. Uji di desktop dan mobile.

---

## Made By

**Repaldisyah Ahmad**
