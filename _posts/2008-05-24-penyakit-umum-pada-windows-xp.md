---
id: 107
title: Penyakit Umum pada Windows XP
date: 2008-05-24T12:09:58+07:00
author: Nana
layout: post
guid: https://localhost/wordpress/?p=107
permalink: /penyakit-umum-pada-windows-xp/
categories:
  - Tips
  - Windows
tags:
  - Tips
  - Windows
---
Ternyata yang namanya penyakit tidak hanya menimpa manusia, Windows XP andapun bisa terkena “penyakit” yang bisa merepotkan anda. Anda pengguna setia Windows pasti pernah mengalami, dimana tiba-tiba Windows XP anda tidak mau boot, hingga akhirnya andapun terpaksa tidak bisa bekerja. Nah, biar anda tidak kelabakan saat Windows XP anda terkena “penyakit”, ada baiknya anda ketahui beberapa penyakit umum yang sering melanda Windows XP dan solusi untuk mengatasinya.

**>> NTLDR or NTDETECT.COM Not Found**

Jika pas booting Windows XP, anda hanya dikasih penjelasan dengan kata-kata seperti itu, langkah sederhana bisa anda lakukan untuk mengatasinya.

Jika anda menggunakan file sytem FAT32, anda tinggal boot dengan menggunakan WIN98Floppy/CD Boot, kemudian tinggal copy file NTLDR atau NTDETECT.COM yang ada di folder i386 dari CD Windows XP

Namun jika anda menggunakan file system NTFS :

  * Lakukan boot dari CD Windows XP anda
  * Pada pilihan pertama R=Repair option, tekan tombol R
  * Kemudian tekan nomor yang sesuai dengan posisi tempat instalasi Windows XP yang akan anda repair, biasanya angka 1.
  * Setelah itu anda akan diminta memasukan Password Adm inistrator, isilah sesuai dengan password yang anda buat pas pertama kali anda menginstalasi Windows XP.
  * Setelah itu copy file NTLDR atau NTDETECT.COM dengan perintah :
  * Copy X:i386NTLDR C: atau Copy X:i386NTDETECT.COM C: dimana X adalah CD Room anda.
  * Keluarkan CD Windows XP dan Restart komputer.

**>> NTOSKRNL Missing or Corrupt**

Kalau Windows XP anda tiba-tiba hanya memberikan kata-kata seperti ini pas booting,  
langkah yang bisa dilakukan oleh anda untuk mengatasinya antara lain :

  * Lakukan boot dari CD Windows XP anda
  * Pada pilihan pertama R=Repair option, tekan tombol R
  * Kemudian tekan nomor yang sesuai dengan posisi tempat instalasi Windows XP yang akan anda repair., biasanya angka 1.
  * Setelah itu anda akan diminta memasukan Password Adm inistrator, isilah sesuai dengan password yang anda buat pas pertama kali anda menginstalasi Windows XP.
  * Rubah posisi drive pada CD Room and CD i386
  * Expand ntkrnlmp.ex_C:WindowsSystems32ntoskrnl.exe
  * Restart komputer anda setelah sebelumnya anda mengeluarkan CD Windows XP

**>> HAL.DLL Missing or Corrupt**

  * Lakukan boot dari CD Windows XP anda Pada pilihan pertama R=Repair option tekan tombol R
  * Kemudian tekan nomor yang sesuai dengan posisi tempat instalasi Windows XP yang akan anda repair., biasanya angka 1.
  * Setelah itu anda akan diminta memasukan Password Adm inistrator, isilah sesuai dengan password yang anda buat pas pertama kali anda menginstalasi Windows XP.
  * Ketik bootcfg /list untuk melihat isi yang telah ada di file BOOT.INI
  * Kemudian ketik bootcfg /rebuild untuk proses perbaikan BOOT.INI tersebut.
  * Keluarkan CD Windows XP dan restart komputer anda

>> Reinstalling Windows XP

Jika anda merasa Windows XP anda telah banyak error atau ada beberapa bagian file system yang corrupt,  
tapi anda malas untuk melakukan Instalasi Windows secara full dan menginstalasi ulang program-program yang telah anda instal. Anda bisa kok melakukan langkah Reinstalling Windows XP anda secara “sederhana” dengan tetap mempertahankan program-program yang telah anda instal.

  * Start Windows XP anda
  * Browse source Windows XP
  * 
  * Run WINNT32 /unattend