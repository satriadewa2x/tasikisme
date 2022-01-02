---
id: 177
title: Menonaktifkan System Restore untuk Memusnahkan Virus
date: 2008-09-03T13:09:53+07:00
author: Nana
layout: post
guid: https://localhost/wordpress/?p=177
permalink: /menonaktifkan-system-restore-untuk-memusnahkan-virus/
categories:
  - Komputer
  - Tips
  - Windows
tags:
  - Komputer
  - Tips
  - Windows
---
System Restore pertama kali diperkenalkan pada Windows ME, fitur ini sangat bermanfaat terutama bila anda sering melakukan perubahan-perubahan pada komputer anda. Dengan fitur ini bila suatu saat terjadi masalah atau eror dengan komputer anda ketika anda selesai menginstal sebuah software atau driver, anda bisa mengembalikan keadaan Windows XP pada kondisi normal sebelum terjadinya eror masalah tersebut.

Namun fitur yang sangat bermanfaat ini justru seringkali dimanfaatkan virus untuk tetap berdiam diri pada komputer anda. Saat anda akan merestore komputer anda, maka si virus pun ikut merestore diri, dan kembali menyerang komputer anda.

Anda pasti pernah mengalami ketika antivirus anda menemukan virus di folder System Volume Information,  
tapi antivirus anda tidak bisa berbuat banyak dan tidak bisa memusnahkan virus tersebut, karena folder System Volume Information merupakan folder yang dilindungi oleh Windows Xp anda.

Untuk mengatasi permasalahan seperti ini, langkah berikut mungkin layak anda coba, Menonaktifkan System Restore untuk Memusnahkan Virus.

> Untuk memusnahkan virus tersebut yang anda perlukan adalah Antivirus dengan Update terakhir (yang sudah mengenali virus yang akan dimusnahkan)

> Non Aktifkan dulu System Restore, karena kalau dalam System Restore masih aktif, antivirus anda tetap tidak akan bisa menghilangkan virus tersebut. Untuk menonaktifkan System Restore inilah langkah-langkahnya :

Default Control Panel

Klik Start Menu | Control Panel | Performance and Maintenance | System kemudian pada jendela System Properties pilih tab System Restore dan beri tanda ceklis pada pilihan : Turn Off System Restore

Control Panel dengan Classic View

Klik Start Menu | Control Panel | System kemudian pada jendela System Properties pilih tab System Restore dan beri tanda ceklis pada pilihan : Turn Off System Restore

> Setelah anda menonaktifkan System Restore,  restart komputer anda untuk memberikan effek

> Setelah itu, scan kembali folder System Volume Information dengan antivirus anda dan kali ini Antivirus anda seharusnya bisa menghilangkan virus tersebut.

> Setelah folder System Volume Information terbebas dari virus, ada baiknya anda kembali mengaktifkan system dengan mengulangi langkah kedua diatas tapi kali ini hilangkan tanda ceklis pada opsi Turn Off System Restore

Selamat mencoba!