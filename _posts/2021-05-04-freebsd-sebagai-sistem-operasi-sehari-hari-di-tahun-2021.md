---
layout: post
published: false
title: "FreeBSD Sebagai Sistem Operasi Sehari-hari di Tahun 2021"
date: 2021-05-04 21:19:23 +0700
category: linux
tags: ["freebsd desktop", "sistem operasi freebsd", "freebsd sehari-hari"]
excerpt_separator: <!--more-->
comment: false
---

<!--screenshot freebsd-->

Apabila berbicara sistem operasi (OS) yang biasa digunakan dalam keseharian, saya yakin banyak orang menggunakan dan familiar dengan Windows. Selain itu ada pula yang menggunakan macOS. Sayangnya macOS pada dasarnya hanya bisa digunakan di perangkat besutan Apple saja. Lalu bagi yang antusias terhadap teknologi, pasti sudah tidak asing dengan GNU/Linux. Namun bagaimana dengan FreeBSD?
<!--more-->

Secara silsilah, macOS, Linux dan BSD berasal dari satu rumpun yang sama. Perbedaannya, macOS sukses di ranah desktop sementara Linux dan BSD lebih banyak digunakan di server. Meski begitu, tak sedikit orang yang menggunakan Linux dan BSD sebagai sistem operasi desktop sehari-hari.

Di artikel saya kali ini, kita akan membahas kemungkinan digunakannya FreeBSD sebagai sistem operasi desktop sehari-hari. Perlu dicatat bahwa artikel ini bukanlah tutorial *step-by-step*, namun lebih ke *proof of concept*. Sehingga apabila kamu ingin mencobanya juga, Google dan YouTube menyediakan banyak sekali tutorial yang bisa kamu ikuti.

Langsung saja kita masuk ke poin utama. Kita akan menggunakan FreeBSD 13.0. Sistem operasi desktop yang ideal di tahun 2021 harus bisa digunakan untuk hal-hal berikut ini:

- [x] Tampilan GUI dan aksesoris bawaan sistem operasi
- [x] Terhubung ke internet dan membuka situs media sosial
- [x] Konsumsi multimedia (memutar video, YouTube, Netflix, Spotify, dsb.)
- [x] Manipulasi dokumen dan *spreadsheet*
- [x] Editing foto dan atau video secara sederhana

Yuk mari kita kupas satu per satu!

## GUI dan Aksesoris Bawaan Sistem Operasi

FreeBSD secara bawaan tidak menawarkan opsi GUI *out of the box*. Pengguna harus mengunduh dan memasangnya sendiri. Pilihannya ada GNOME, KDE, Xfce maupun MATE, sama seperti distro Linux kebanyakan. Namun karena saya suka tampilan yang minimalis dan juga ringan, saya pilih MATE.

Agar proses lebih mudah dan simpel, saya gunakan *installation script* buatan Felix Caffier yang bisa kalian akses di link [Github ini](https://github.com/broozar/installDesktopFreeBSD/tree/DarkMate12).