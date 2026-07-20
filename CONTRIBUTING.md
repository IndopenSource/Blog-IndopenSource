# Contributing

Terima kasih sudah ingin menulis untuk Blog IndopenSource.

## Alur Kontribusi

1. Buat artikel dari `templates/article.md`.
2. Simpan di `content/YYYY/MM/slug-artikel.md`.
3. Pastikan `status: draft` saat pertama submit.
4. Buka pull request dengan konteks tulisan.
5. Setelah tersinkron, buka `/blog/preview/slug-artikel/` untuk memeriksa hasilnya.
6. Maintainer akan memberi masukan editorial.

URL preview draf tidak muncul di daftar blog atau sitemap dan ditandai
`noindex, nofollow, noarchive`. URL publik `/blog/slug-artikel/` dipakai setelah
artikel diterbitkan.

## Checklist Artikel

- [ ] File berada di folder tahun dan bulan yang benar.
- [ ] Slug memakai huruf kecil dan tanda hubung.
- [ ] Frontmatter lengkap.
- [ ] Artikel punya ringkasan pembuka.
- [ ] Semua link sudah dicek.
- [ ] Gambar, jika ada, punya sumber dan izin pakai.
- [ ] Preview draf sudah diperiksa setelah konten tersinkron.

## Frontmatter Wajib

- `title`
- `description`
- `date`
- `authors`
- `tags`
- `status`

## Review Editorial

Maintainer dapat meminta perubahan untuk:

- Kejelasan struktur tulisan.
- Akurasi teknis.
- Sumber dan atribusi.
- Nada tulisan agar sesuai ruang komunitas.
