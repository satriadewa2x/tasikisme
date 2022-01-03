---
id: 348
title: Cara Enable dan Disable Windows Task Manager
date: 2008-02-23T12:40:29+07:00
author: Nana
layout: post
guid: https://www.tasikisme.com/?p=25
permalink: /enable-disable-windows-task-manager/
categories:
  - Komputer
  - Laptop
  - Windows
tags:
  - Komputer
  - Laptop
  - Tips
  - Windows
---
Seperti kita ketahui Task Manager merupakan sebuah utility kecil bawaan Windows XP yang sangat berguna, terutama untuk menginformasikan kepada kita tentang proses dan program apa saja yang sedang berjalan di  komputer kita. Di Task Manager kita bisa melihat status dari program-program yang sedang berjalan, dan kita bisa menghentikan program tersebut disaat program tersebut Not Responding atau ngeHang.

Masalahnya, kadang di beberapa komputer terutama di rental-rental komputer, atau warnet atau malah di komputer kita sendiri, Task Manager ini di-Disable karena beberapa alasan (misalnya demi keamanan system), sehingga di saat kita perlu untuk meng End Task beberapa program yang hang, kita tidak bisa mengakses/membuka  Task Manager ini.

Bila kebetulan anda mengalami sendiri masalah seperti ini, tips berikut akan menjelaskan bagaimana kita bisa mengakses kembali Task Manager yang sudah di-disable. Caranya :

  * Dari Start Menu klik tombol Run
  * Ketik : REGEDIT
  * HKEY\_CURRENT\_USERSoftwareMicrosoftWindowsCurrentVersion
  * Buat Key baru dengan nama “System” Di key “System” yang baru saja dibuat, buat lagi DWORD value DisableTaskMgr
  * Set data value dengan angka 0 untuk enable Task Manager