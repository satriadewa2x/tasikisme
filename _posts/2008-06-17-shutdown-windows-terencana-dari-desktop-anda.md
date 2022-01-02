---
id: 130
title: Shutdown Windows Terencana dari Desktop Anda.
date: 2008-06-17T10:00:06+07:00
author: Nana
layout: post
guid: https://localhost/wordpress/?p=130
permalink: /shutdown-windows-terencana-dari-desktop-anda/
categories:
  - Komputer
  - Windows
tags:
  - Komputer
  - Tips
  - Windows
---
Biasanya kalau kita akan menShutdown komputer kita pada Windows XP, harus melalui langkah yang ‘biasa’ klik Start Menu kemudian klik Turn Off Computer dan klik lagi Turn Off. Jadi ada 3 langkah.

Padahal dengan menggunakan sebuah shortcut kita bisa menshutdown komputer kita hanya dalam 1 (satu) langkah saja, tinggal double klik shortcut shutdown di Desktop anda, maka komputer anda pun akan otomatis melakukan shutdown. Enaknya dengan shortcut ini, anda bisa merencanakan waktu untuk shutdown. Misalnya Anda ingin melakukan Shutdown Windows anda dalam waktu 10 menit ke depan. Lebih enak kan?

Caranya : klik kanan di Desktop anda (atau bisa juga didalam folder lain), New > Shortcut kemudian pada kolom Type The Location of The Item, anda masukkan parameter berikut ini : (tanpa tanda kutip)

“shutdown -s -t 00”

Setelah itu tekan Next pada isian Type a name for this Shortcut anda isikan sesuai dengan keinginan anda  
misal : Shutdown atau Matikan Komputer¸ sesuai dengan selera anda. Kemudian Finish

Keterangan :

  * -s singkatan dari shutdown anda bisa menggantinya dengan –r untuk = Restart jika anda menginginkan shortcut untuk melakukan Restart.
  * 00 = indikator waktu (dalam satuan detik) bila anda menginginkan melakukan shutdown dalam jangka waktu 1 menit ke depan maka ganti 00 dengan 60.  Untuk merubah parameter-parameter dari shortcut yang anda buat tadi misal ingin mengganti 00 jadi 60 atau dari –s menjadi –r tinggal anda klik kanan shortcut tersebut klik Properties dan anda bisa mengedit parameter tersebut pada kolom Target

Bagaimana, mudah bukan? K ini anda bisa melakukan shutdown terencana dari desktop anda.