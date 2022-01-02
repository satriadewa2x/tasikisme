---
id: 227
title: Percepat Windows dengan Disable Thumbnail Preview
date: 2009-01-13T12:37:00+07:00
author: Nana
layout: post
guid: https://localhost/wordpress/?p=227
permalink: /percepat-windows-dengan-disable-thumbnail-preview/
categories:
  - Komputer
  - Tips
  - Windows
tags:
  - Komputer
  - Tips
  - Windows
---
Suatu saat mungkin anda pernah mengalami, saat membuka sebuah folder yang berisi file gambar maupun video, komputer anda tiba-tiba jadi lemot karena harus meloading Thumbnail dari gambar dan video didalam folder tersebut.

Apalagi jika folder tersebut diisi dengan banyak sekali file gambar dan videodengan ukuran yang besar-besar, maka sudah bisa dipastikan proses thumbnail preview yang dilakukan oleh Windows XP ini akan sangat memperlambat kinerja komputer anda.

Dengan menonaktifkan proses thumbnail preview, paling tidak komputer anda akan lebih cepat dalam proses browsing file dari folder ke folder meskipun folder tersebut banyak diisi dengan file gambar dan video.

Karena dengan kondisi thumbnail preview tidak aktif, Windows XP anda tidak akan terus menerus berusaha untuk membuat thumbnail dari file gambar maupun video tersebut.

**Menonaktifkan Thumbnail Preview untuk File Gambar** 

Caranya sangat simple dan mudah.

Klik **[ Start Menu ]** &#8211;> **[ Run ]** 

Kemudian masukkan perintah berikut: **regsvr32 /u shimgvw.dll** untuk mendisable atau menonaktifkan proses thumbnail preview file gambar pada komputer anda.

<div style="text-align: center;">
  <img loading="lazy" title="Disable Thumbnail Preview untuk File Gambar" src="https://wisatacinta.files.wordpress.com/2009/01/disable_image_preview.gif" alt="Menonaktifkan Thumbnail Preview untuk File Gambar" width="344" height="184" border="0" />
</div>

**Menonaktifkan Thumbnail Preview untuk File Video/ Media** 

Klik **[ Start Menu ]** &#8211;> **[ Run ]** 

Kemudian masukkan perintah berikut: **regsvr32 /u shmedia.dll** untuk mendisable atau menonaktifkan proses thumbnail preview untuk file video/media anda.

<div style="text-align: center;">
  <img title="Disable Thumbnail Preview untuk File Video" src="https://wisatacinta.files.wordpress.com/2009/01/disable_video_preview.gif" alt="Menonaktifkan Thumbnail Preview untuk File Video" border="0" />
</div>

Setelah selesai melakukan langkah diatas, cobalah anda membuka sebuah folder yang berisi file gambar dan video, k ini komputer anda pun akan melakukan proses browsing file dengan lebih cepat karena Windows XP anda tidak akan berusaha terus menerus membuat thumbnail preview dari file gambar dan video anda.

Lalu, bagaimana kalau anda ingin mengaktifkan kembali fitur thumbnail preview ini. Caranya cukup mudah, masukkan perintah seperti diatas tapi dengan menghilangkan slash u ( /u), jadi kalau ingin mengaktifkan kembali thumbnail preview untuk file gambar tinggal masukkan perintah regsvr32 shimgvw.dll pada jendela command run dan regsvr32 shmedia.dll untuk mengaktifkan kembali proses thumbnail preview file video anda.

Selamat mencoba