---
id: 204
title: Menonaktifkan Fungsi USB Storage Device (Flashdisk)
date: 2008-11-28T16:33:17+07:00
author: Nana
layout: post
guid: https://www.tasikisme.com/?p=204
permalink: /menonaktifkan-dan-mengaktifkan-fungsi-usb-storage-device-flashdisk/
categories:
  - Komputer
tags:
  - Komputer
  - Tips
---
Komputer anda sering terserang virus yang berasal dari Flashdisk? Anda pasti kesal, meskipun anda telah berhati-hati dalam menggunakan Flashdisk di komputer, tapi teman-teman anda seenaknya aja mencolokan flashdisk ke komputer anda tak peduli apakah flashdisknya tersebut ada virusnya atau tidak.

Akibatnya sudah bisa ditebak, komputer andapun sering banget terserang virus.

Trik berikut akan menunjukkan kepada anda bagaimana menonaktifkan fungsi USB Storage Device pada komputer anda.

Bila suatu ketika ada teman anda iseng mencolokan Flashdisknya, komputer anda tidak akan meresponnya, alias flashdisknya tersebut tidak akan ke detect dan terbaca oleh komputer anda, sehingga komputer anda pun akan lebih aman dari penyebaran virus lewat Flashdisk.

Trik berikut akan berguna sekali terutama bagi anda yang selalu sharing komputer di kantor atau sekolah, dengan mendisable atau menonaktifkan fungsi USB Storage Device, tidak akan sembarang orang bisa mengcopy paste file dari maupun ke flashdisk.

Karena langkah berikut ini berkaitan dengan proses edting Registry Windows anda, ada baiknya sebelum melakukan trickini anda Back Up Dulu Registry Windows, sehingga bila nantinya terjadi kesalahan, anda bisa merestore registry anda ke posisi semula sebelum terjadinya proses editing.

**Menonaktifkan Fungsi USB di Laptop** 

  * Klik Start Menu &#8211;> RUN
  * Lalu masukan perintah berikut : regedit dan kemudian klik OK
  * Kemudian cari Key berikut ini :  HKEY\_LOCAL\_MACHINE/SYSTEM/CurrentControlSetServices/USBSTOR
  * Pada jendela sebelah kanan double klik Start
  * Pada Jendela Edit DWORD Value, masukan angka 4 padavalue data, pilih hexadecimal pada bagian base Terakhir klik OK, dan tutup Registry Editor anda

Kini Flashdisk apapun tidak akan terdetect dan terbaca oleh komputer, dan andapun bisa sedikit tenang karena teman-teman anda tidak akan sembarangan mencolokkan Flashdisk dan menyebarkan virus.

**Mengaktifkan Kembali USB Storage Device**  
Lalu bagaimana, untuk mengaktifkan kembali fungsi USB Storage Device ini? Caranya cukup anda tinggal mengganti angka 4 dengan angka 3 pada langkah diatas. Atau untuk lebih jelasnya seperti dibawah ini.

  * Klik Start Menu &#8211;> RUN
  * Lalu masukan perintah berikut : regedit dan kemudian klik OK
  * Kemudian cari Key berikut ini : HKEY\_LOCAL\_MACHINE/SYSTEM/CurrentControlSetServices/USBSTOR
  * Pada jendela sebelah kanan double klik Start
  * Pada Jendela Edit DWORD Value, masukan angka 3 padavalue data, pilih hexadecimal pada bagian base Terakhir klik OK, dan tutup Registry Editor anda

Selamat Mencoba