---
title: "OpenClaw Jakarta Meetup #5: Beragam Praktik Terbaik Menggunakan OpenClaw"
description: "OpenClaw Jakarta Meetup #5 pertemukan developer dan pengguna agentic AI untuk membahas praktik membangun agen yang berguna, terukur, dan bertanggung jawab."
date: "2026-07-23"
thumbnail: "./assets/openclaw-jakarta-meetup-5-og.jpg"
thumbnailWidth: 1200
thumbnailHeight: 630
thumbnailType: image/jpeg
lang: id
translationKey: openclaw-jakarta-meetup-5
authors:
  - name: "IndopenSource Maintainers"
    github: "IndopenSource"
tags:
  - community
  - open-source
  - artificial-intelligence
  - openclaw
status: published
---

OpenClaw Jakarta Meetup #5 berlangsung di Jakarta Selatan pada Kamis, 23 Juli 2026. Dengan dukungan DANA Indonesia sebagai penyedia tempat dan konsumsi, acara ini mempertemukan developer, engineer, serta pengguna OpenClaw dan *agentic AI* untuk melihat penerapan agen AI dalam kasus nyata.

Para pembicara membawa pengalaman membangun produk: dari browser untuk agen AI, pencarian properti, sampai sistem penasihat keuangan. Namun, benang merah terkuat malam itu datang dari Hannes Rudolph, Community Manager OpenClaw: membangun agen yang dapat bekerja bukan berarti menyerahkan seluruh proses kepada AI.

## AI untuk Pekerjaan yang Memang Membutuhkannya

Vince Iswara, CEO DANA Indonesia, membuka acara dengan mengingatkan bahwa penggunaan AI membutuhkan tanggung jawab. Komputasi AI tidak murah, sehingga teknologi ini sebaiknya dipakai untuk persoalan yang memang membutuhkan kemampuan tersebut, bukan tugas sederhana yang dapat diselesaikan dengan cara lebih ringan.

Pesan itu juga terlihat dalam sesi Raden Muhammad Hadi, Senior Data Scientist DANA Indonesia, tentang *Financial Advisory Agent Stack*. Sistem ini menggunakan sejumlah subagen dengan peran berbeda, seperti menyusun rencana eksekusi, eksekusi task, memberi konteks literasi finansial, dan meninjau hasil melalui berbagai jenis model.

Hadi membandingkan beberapa model agar pemilihan model sesuai dengan tugasnya. Mereka juga memakai pendekatan statistik seperti TBATS untuk kebutuhan peramalan. Presentasi ini menunjukkan bahwa sistem agentic di sektor finansial tidak cukup hanya mengandalkan satu model dan satu instruksi.

## Hannes Rudolph: Mulai dari Loop Kecil

Dalam sesinya melalui Zoom Meeting, Hannes yang merupakan Community Manager Open Claw membuka sesi terbuka tanya jawab kepada audiens yang hadir, Menurut Hannes, Pendekatan yang lebih masuk akal dalam agentic adalah memulai dari *loop* kecil, memberi agen proses perencanaan dan pemeriksaan, lalu mempelajari hasil serta kesalahannya.

Evaluasi model menjadi bagian penting dari proses tersebut. Setiap perubahan model perlu dibandingkan melalui *benchmark* agar peningkatan pada satu sisi tidak diam-diam merusak kemampuan lain. Untuk pekerjaan yang dibuat dengan pendekatan *vibe coding*, developer tetap perlu memahami proses dan memeriksa kode baris demi baris.

Pesannya sederhana: fokus pada hal yang ingin diselesaikan, bangun mekanisme pengecekan, dan jangan memperluas otomatisasi sebelum hasil pada lingkup kecil cukup baik.

<div class="flex justify-center">
  <img src="https://raw.githubusercontent.com/IndopenSource/Blog-IndopenSource/main/content/2026/07/assets/openclaw-jakarta-meetup-5-body.jpg" alt="Peserta OpenClaw Jakarta Meetup #5" loading="lazy">
</div>

## Tiga Gambaran Agen AI di Dunia Nyata

Zen Aufa Bahalwan memperkenalkan Camoufox untuk menghadapi kendala browser seperti CAPTCHA, respons *forbidden*, dan sistem deteksi bot. Camoufox memberi agen kemampuan menjelajah web dengan pendekatan *anti-detect*. Penggunaannya tetap perlu ditempatkan dalam batas yang sah dan bertanggung jawab.

Okza Pradhana, dari komunitas Data Engineering Indonesia, membawa PropGen, sebuah orkestrasi agen untuk membantu pekerjaan pencarian properti. Demo ini menggambarkan bagaimana agen dapat dipekerjakan untuk mengumpulkan dan mengolah informasi yang biasanya tersebar di banyak sumber.

Sementara itu, sistem penasihat keuangan personal yang dibuat Hadi menunjukkan kebutuhan yang berbeda: basis pengetahuan yang kuat, pemilihan model berdasarkan kemampuan, dan lapisan peninjauan sebelum hasil sampai kepada pengguna.

Ketiga sesi tersebut memperlihatkan bahwa nilai agen AI tidak terletak pada banyaknya model atau panjangnya *workflow*. Nilainya muncul ketika sistem mampu menyelesaikan pekerjaan, dapat diperiksa, dan ditempatkan dalam batas tanggung jawab yang jelas.

OpenClaw Jakarta Meetup #5 akhirnya menjadi ruang untuk membandingkan apa yang sudah dibangun, apa yang masih bermasalah, dan apa yang perlu diperbaiki bersama. Dukungan DANA dan kehadiran tim komunitas OpenClaw mempertemukan perspektif perusahaan dengan semangat eksperimen *open source* dalam satu ruangan.
