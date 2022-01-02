---
id: 259
title: Menonaktifkan AutoPlay di Windows Vista
date: 2009-02-14T18:09:59+07:00
author: Nana
layout: post
guid: https://www.tasikisme.com/?p=259
permalink: /menonaktifkan-autoplay-di-windows-vista/
categories:
  - Komputer
  - Windows
tags:
  - Komputer
  - Windows
---
Kita semua sudah mafhum bahwa salah satu cara penyebaran virus adalah dengan memanfaatkan fitur Autoplay yang secara default aktif di Windows anda.

Ketika anda memasukkan CD atau Flashdisk yang telah terkontaminasi oleh virus, maka secara otomatis virus yang ada dalam Flashdisk/CD tersebut akan aktif dengan adanya fitur autoplay ini, akibatnya sudah bisa ditebak komputer andapun terserang virus.

Untuk menonaktifkan/disable fitur Autoplay di Windows XP anda bisa membacanya di **[Menonaktifkan “AutoPlay” untuk Mencegah Virus](httpss://www.tasikisme.com/menonaktifkan-autoplay-untuk-mencegah-virus/){.contentpagetitle}**, Sedangkan untuk menonaktifkan /mendisable Autoplay di Windows Vista, ikutilah langkah-langkah berikut ini.

1. Cara pertama dan termudah adalah dengan mengakses **[Control Panel]** dan kemudian klik opsi “**Play CDs or other media automatically**”

<img  title="Disable Autoplay di Windows Vista 1" src="https://wisatacinta.files.wordpress.com/2009/02/autoplay_vista1.jpg" alt="Disable Autoplay di Windows Vista 1" border="0" /> 

Cara tercepat untuk menonaktifkan Autoplay adalah dengan menghilangkan tanda ceklist pada “**Use AutoPlay for all media and devices**”

<img  title="Disable AutoPlay pada Windows Vista 2" src="https://wisatacinta.files.wordpress.com/2009/02/autoplay_vista3.jpg" alt="Disable AutoPlay pada Windows Vista 2" border="0" /> 

2. Cara Kedua khusus bagi anda yang menggunakan Windows Vista versi **Business** dan **Ultimate**. Akses **gpedit.msc** melalu box search pada start menu kemudian arahkan ke **Windows Components Autoplay Policies** dan kemudian rubah opsinya menjadi enable.

<img  title="Disable AutoPlay pada Windows Vista 3" src="https://wisatacinta.files.wordpress.com/2009/02/autoplay_vista2.jpg" alt="Disable AutoPlay pada Windows Vista 3" border="0" /> 

3. Cara Ketiga adalah dengan melalui menu registry. Silahkan gunakan  **Registry** berikut ini.

  * **NonAktifkanAutoPlayAll.reg** = untuk menonaktifkan AutoPlay pada semua Device
  * **NonAktifkanAutoPlayRemovable.reg** = untuk menonaktifkan AutoPlay pada Removable Device (Flashdisk)