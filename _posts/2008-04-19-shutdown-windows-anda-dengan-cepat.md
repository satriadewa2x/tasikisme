---
id: 73
title: Shutdown Windows Anda dengan cepat!
date: 2008-04-19T14:20:21+07:00
author: Nana
layout: post
guid: https://localhost/wordpress/?p=73
permalink: /shutdown-windows-anda-dengan-cepat/
categories:
  - Tips
  - Windows
tags:
  - Tips
  - Windows
---
Anda pasti pernah mengalami, saat akan men-Shutdown Windows XP ternyata prosesnya lama sekali. Apalagi ketika anda se dang membuka beberapa aplikasi lalu anda ingin Shutdown Windows anda, maka sudah bisa dipastikan prosesnya bakal lama, sebab Windows akan meng-close dulu program-program yang se dang anda jalankan satu persatu satu.

Nah, trik berikut akan menunjukkan kepada anda, bagaimana menyiasiti biar Windows anda bisa di Shutdown dengan cepat kilat. Meskipun anda se dang menjalankan beberapa aplikasi/program, Anda bisa men-shutdown windows anda dengan instant alias dengan cepat tanpa harus menunggu aplikasi tersebut di-close satu per satu.

Sebelumnya pastikan dulu anda memback-up registry anda jadi dimana terjadi eror setelah melakukan trik ini  
anda bisa merestore registry anda dan komputer anda akan kembali normal seperti biasanya.

  * Dari Start Menu klik tombol Run dan ketik : REGEDIT
  * Kemudian cari path : HKEY\_CURRENT\_USERControl PanelDesktop
  * Setelah itu cari parameter berikut : WaitToKillAppTimeout
  * Double klik paramater tersebut terus ganti Value Datanya dengan 1200 atau tergantung selera anda. Perlu diketahui data tersebut dalam milidetik  
    jadi semakin kecil maka akan semakin cepat. Tapi penulis sarankan cukup 1200 saja.
  * Kemudian cari dan double klik juga paramater : HungAppTimeout parameter ini menunjukkan waktu yang dibutuhkan (dalam milidetik) oleh Windows untuk meng-close program yang hang jadi penulis sarankan isi Value Datanya dengan 2000 atau terserah anda.
  * Setelah selesai close Registry Editor kemudian restart dulu Windows anda  
    biar modifikasi tadi bisa mulai bekerja.

Selamat mencoba.