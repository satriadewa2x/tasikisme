---
id: 144
title: Cara mudah Memunculkan Kembali File yang ter-Hidden karena Virus
date: 2008-06-29T06:47:16+07:00
author: Nana
layout: post
guid: https://www.tasikisme.com/?p=144
permalink: /cara-mudah-memunculkan-kembali-file-yang-ter-hidden-karena-virus/
categories:
  - Komputer
tags:
  - Komputer
  - Tips
  - Windows
---
Bila komputer anda pernah terkena virus, tentu anda pernah mengalami dimana file-file asli anda jadi ter-Hidden (tersembunyi). Ketika anda akan merubah kembali attribut dari file tersebut, dengan cara klik kanan—Properties, anda tetap tidak bisa merubahnya karena anda tidak bisa merubah-rubah pada opsi Hidden.

Langkah berikut adalah cara mudah merubah attribut dari file yang tersembunyi dengan hanya menggunakan perintah di Command Prompt yang tersedia di Windows XP. Dengan begitu, di mana dan kapanpun anda berada anda bisa memunculkan file yang ter-Hidden dengan mudah, tanpa harus anda tergantung pada script atau program tertentu. Lebih praktis dan tentu lebih efisien.

1. Buka Command Prompt dengan cara Klik Start Menu – Accessories – Command Prompt

2. Tampilan pertama pada command prompt akan tampak seperti ini :

“C:Documents and SettingsUsername>” tanpa tanda kutip, dimana username merupakan profiles anda di komputer tersebut.

3. Setelah itu masuk ke Folder dimana file-file yang terhidden anda tersimpan. Misal kalau anda menyimpan file-file yang terhidden di folder document pada drive D maka anda masukan perintah berikut ini : “cd /d d:document” tanpa tanda kutip sehingga tampilan di command prompt akan tampak seperti ini : “D:document>”

Tips : sebaiknya anda kumpulkan file-file dan folder anda yang terHidden dalam satu folder, sehingga anda bisa menghemat waktu dan tidak harus melakukan langkah ini pada setiap file atau folder yang terhidden.

4. Waktunya anda merubah file-file anda tersebut menjadi visible atau tidak terhidden lagi, dengan memasukan perintah berikut : (tanpa tanda kutip)

“attrib -r -a -s -h /s /d” dengan perintah ini, maka semua file dan folder didalam folder tersebut (folder document di langkah 3) akan kembali muncul, dan tidak terhidden lagi.

Ket : r = read only,  
a=archive,  
s=system,  
h=hidden,  
tanda minus (-) untuk menghilangkan attribut pada suatu file, anda bisa menggantinya dengan tanda plus (+), untuk menambahkan attribut pada suatu file.

Bagaimana? Mudah bukan. Jadi bila suatu waktu anda berkunjung ke rumah teman anda, dan anda diminta untuk memunculkan kembali file-filenya yang terhidden, anda bisa menolongnya dengan segera, tanpa perlu anda tergantung pada script atau program tertentu.