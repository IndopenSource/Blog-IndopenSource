# Blog IndopenSource

Repository artikel Markdown untuk blog IndopenSource.

Blog ini menyimpan tulisan komunitas dengan struktur sederhana dan mudah
ditinjau melalui pull request.

## Struktur Konten

```txt
content/
  2026/
    06/
      assets/
        memperkenalkan-blog-indopensource.jpg
      memperkenalkan-blog-indopensource.md
templates/
  article.md
```

Gunakan format path:

```txt
content/YYYY/MM/slug-artikel.md
```

Contoh:

```txt
content/2026/06/project-spotlight-opensid.md
```

## Format Artikel

Setiap artikel memakai frontmatter YAML:

```md
---
title: "Judul artikel"
description: "Ringkasan singkat artikel."
date: "2026-06-14"
thumbnail: "./assets/cover.jpg"
thumbnailWidth: 1200
thumbnailHeight: 630
thumbnailType: image/jpeg
lang: id
translationKey: project-spotlight-opensid
authors:
  - name: "Nama Penulis"
    github: "username"
tags:
  - project-spotlight
  - komunitas
status: draft
---

Isi artikel ditulis dengan Markdown yang bersih.
```

`thumbnail` bersifat opsional. Nilainya bisa URL penuh `https://...` atau path
relatif dari file artikel, misalnya `./assets/cover.jpg`. Jika memakai path
relatif, simpan gambar di folder artikel yang sama, biasanya
`content/YYYY/MM/assets/`.

Untuk hasil Open Graph yang konsisten, gunakan gambar 1200×630 dan isi
`thumbnailWidth`, `thumbnailHeight`, serta `thumbnailType`. JPG berukuran di
bawah 500 KB lebih kompatibel untuk preview media sosial.

Status yang didukung:

- `draft`: tulisan masih direview.
- `ready`: siap dipublikasikan.
- `published`: sudah dipublikasikan di website.

## Artikel Multibahasa

Bahasa Indonesia adalah bahasa default. Gunakan `lang: id` untuk artikel
Indonesia dan `lang: en` untuk edisi Inggris. Artikel terjemahan disimpan
sebagai file Markdown terpisah dan dihubungkan memakai `translationKey` yang
sama.

Artikel Indonesia tersedia di `/blog/slug/`, sedangkan artikel Inggris tersedia
di `/en/blog/slug/`. Website menampilkan tombol pergantian bahasa ketika dua
artikel memiliki `translationKey` dan status publikasi yang sama.

Setelah konten tersinkron ke website, artikel `draft` dapat dipreview melalui
URL khusus:

```txt
https://indopensource.org/blog/preview/slug-artikel/
```

Preview draf tidak ditampilkan di daftar blog atau sitemap dan memakai
`noindex, nofollow, noarchive`. Setelah status artikel diterbitkan, URL publiknya
menjadi `https://indopensource.org/blog/slug-artikel/`.

## Cara Submit Artikel

1. Buat branch baru dari `main`.
2. Salin `templates/article.md` ke `content/YYYY/MM/slug-artikel.md`.
3. Isi frontmatter dan konten artikel.
4. Buka pull request.
5. Tunggu review editorial dari maintainer.

## Gaya Penulisan

- Gunakan Bahasa Indonesia yang jelas dan langsung.
- Tulis paragraf pendek.
- Pakai heading berurutan mulai dari `##`.
- Hindari promosi berlebihan.
- Sertakan link sumber jika menyebut data, klaim, atau proyek tertentu.
- Untuk project spotlight, jelaskan manfaat, cara mencoba, dan peluang kontribusi.

## Kategori Awal

- `project-spotlight`
- `learning-notes`
- `release-notes`
- `community`
- `maintenance`

## License

Konten artikel menggunakan lisensi Creative Commons Attribution 4.0 International
sebagaimana dijelaskan di `LICENSE`.
