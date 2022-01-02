---
id: 292
title: Mencegah Penyebaran Virus Lewat Flashdisk
date: 2009-04-02T10:22:23+07:00
author: Nana
layout: post
guid: https://www.tasikisme.com/?p=292
permalink: /mencegah-penyebaran-virus-lewat-flashdisk/
categories:
  - Komputer
  - Windows
tags:
  - Komputer
  - Windows
---
<div >
  <p>
    Ketika anda mencolokkan Flashdisk yang telah terinfeksi virus, misal virus Conficker/Downadup atau virus The Legend of Aang ke Laptop atau komputer anda, secara otomatis fitur AutoPlay yang secara default aktif di Sistem Operasi Windows, akan menjalankan virus tersebut dan menginfeksi laptop anda. Jadi, daripada anda terlanjur terinfeksi dan akhirnya harus susah payah mencari cara menghapus virus Conficker/Downadup atau cara menghapus virus the legend of aang, lebih baik anda lakukan pencegahan sed ini mungkin. Caranya sangat sederhana yaitu dengan menonaktifkan fitur AutoPlay di Laptop atau Komputer anda.
  </p>
  
  <p>
    Ada berbagai macam software yang bisa anda gunakan untuk menonaktifkan AutoPlay, tapi alangkahnya lebih baiknya bila anda mengetahui cara manual, untuk menonaktifkan AutoPlay, sehingga anda tidak terlalu tergantung pada software apapun.
  </p>
  
  <ol>
    <li>
      Bagi anda pengguna Windows XP, silahkan baca <strong>Menonaktifkan “AutoPlay” untuk Mencegah Virus</strong> untuk menonaktifkan fitur AutoPlay di Lappy anda.
    </li>
    <p>
    </p>
    
    <li>
      Kalau anda menggunakan Windows Vista, penjelasan tentang cara menonaktifkan AutoPlay bisa disimak di <strong>Menonaktifkan AutoPlay di Windows Vista </strong>
    </li>
    <p>
    </p>
    
    <li>
      Tapi, kalau anda menggunakan Windows lain, lakukan langkah sederhana berikut ini :
    </li>
  </ol>
  
  <ul>
    <li>
      Akses Registry Editor melalui menu <strong>(Start | RUN | regedit) </strong>
    </li>
    <li>
      Cari key berikut ini: <strong>HKEY_CURRENT_USERSoftwareMicrosoftWindowsCurrentVersionPoliciesExplorer</strong>
    </li>
    <li>
      Double klik <strong>NoDriveTypeAutoRun</strong> pada jendela sebelah kanan, dan masukkan nilai (Value data) Hexadecimal FF
    </li>
  </ul>
</div>