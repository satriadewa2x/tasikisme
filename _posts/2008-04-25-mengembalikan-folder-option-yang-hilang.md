---
id: 78
title: Mengembalikan “Folder Option” yang hilang?
date: 2008-04-25T10:17:46+07:00
author: Nana
layout: post
guid: https://www.tasikisme.com/?p=78
permalink: /mengembalikan-folder-option-yang-hilang/
categories:
  - Komputer
  - Tips
  - Windows
tags:
  - Komputer
  - Tips
---
Virus-virus zaman sekarang memang makin ganas, selain itu makin bervariasi dan tingkat penyebarannya pun semakin mudah aja. Satu kali anda salah klik, maka komputer Anda pun terinfeksi. Salah satu yang sering dilakukan sang virus adalah menghilangkan “Folder Option” di menu Tools pada Explorer anda, sehingga salah satu akibatnya anda tidak bisa merubah option untuk view/ show hidden file, hingga akhirnya anda tidak bisa mengakses folder yang anda hidden. Nah bila anda mengalami seperti ini, “Folder Option” anda hilang cobalah satu dari dua langkah berikut ini :

Langkah Satu :

  * Klik menu Start > Run
  * Ketik : “gpedit.msc” tanpa tanda kutip untuk membuka Group Policy Windows
  * Setelah itu masuk ke :User Configuration >Administrative Templates >Windows Component > Windows Explorer.
  * Di Panel sebelah kanan, carilah “Remove the Folder Option menu item from the Tools Menu” kemudian double klik dan set value ke “Disabled”

Langkah Dua :

Bukan Registry Editor dengan mengetikan “Regedit” pada menu Run, Kemudian carilah key berikut : HKEY\_CURRENT\_USER/Software/Microsoft/Windows/CurrentVersion/Policies/Explorer dan pada panel sebelah kanan cari : NoFolderOptions dan set value menjadi 0

jika anda tidak menemukan NoFolderOptions, tinggal anda buat sendiri dan masukkan valuenya dengan 0.