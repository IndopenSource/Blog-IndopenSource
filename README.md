# Blog IndopenSource

Repository artikel Markdown untuk blog IndopenSource.

Blog ini menyimpan tulisan komunitas dengan struktur sederhana dan mudah
ditinjau melalui pull request.

## Struktur Konten

```txt
content/
  2026/
    06/
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

Status yang didukung:

- `draft`: tulisan masih direview.
- `ready`: siap dipublikasikan.
- `published`: sudah dipublikasikan di website.

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
