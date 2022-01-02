---
id: 428
title: Cara Install Windows XP dan Windows 7 di Laptop
date: 2010-06-29T11:46:07+07:00
author: Nana
layout: post
guid: https://www.tasikisme.com/?p=403
permalink: /cara-install-windows-xp-dan-windows-7-di-laptop/
categories:
  - Komputer
  - Windows
tags:
  - Komputer
  - Tips
  - Windows
---
Laptop keluaran terbaru saat ini telah banyak yang dibundel dengan sistem operasi Windows 7. Dari segi performa dan tampilan Windows 7 memang layak diacungi jempol, belum lagi dengan kemudahan dalam mengoperasikannya. Namun dari segi kompabilitas atau dukungan terhadap software-software lama, Windows 7 seringkali menghadapi kendala dimana software-software lama tidak bisa berjalan dengan mulus bahkan tak bisa dijalankan sama sekali di Windows 7.

Solusi terbaik dari  masalah tersebut, mungkin Anda berencana untuk menginstall Windows XP disamping Windows 7 di Laptop Anda atau istilahnya Dual Boot antara Windows 7 dan Windows XP di Laptop Anda. Ada dua cara untuk proses dual boot ini.

Pertama, Anda menginstall dulu Windows XP (misal di drive C) setelah selesai baru Anda menginstall Windows 7 (Drive D). Cara seperti ini memang sangat dianjurkan karena nantinya Anda tidak akan menemukan masalah dalam Bootloader. Anda bisa mengcopy file Instalasi Windows 7 ke Hard Drive dan kemudian melakukan Instalasi Windows 7 langsung dari Windows XP sebagaimana layaknya menginstall program biasa. Anda tenang saja meski Windows 7 menreplace bootloader Windows XP, namun pada saat booting, akan ada dua opsi pilihan yakni Windows 7 atau Earlier Version of Windows (Windows XP)

Kedua, Anda menginstal Windows XP setelah menginstal Windows 7. Dalam kasus ini tentunya saja akan menimbulkan masalah dalam bootloader, dimana Windows XP mereplace Bootloader Windows 7 dan tentunya tidak ada opsi pilihan saat boot karena akan langsung masuk ke Windows XP. Untuk mengatasi masa seperti ini ikuti langkah sederhana di bawah ini.

Lakukan Repair terhadap Windows 7, boot Laptop Anda menggunakan DVD Instalasi (Flashdisk) Windows 7, ikuti setiap langkah-langkah setelah ada pilihan Install Now (seperti gambar di bawah), Anda jangan mengklik Install Now tapi pilihlah “Repair Your Computer” ikuti langkah selanjutnya sampai selesai.

Setelah Windows 7 anda berhasil di repair, sekarang saatnya booting dan masuk ke Windows 7, setelah itu Anda bisa menggunakan program EasyBCD untuk mengkonfigurasi dan menambahkan boot entry untuk Windows XP dan Windows 7.

EasyBCD

Untuk selalu uptodate dengan info terbaru seputar komputer dari blog Tasikisme jangan pernah lupa, masukan email Anda di bawah ini atau jadilah Follower Blog Tasikisme di Twitter dan Fans Tasikisme di Facebook.