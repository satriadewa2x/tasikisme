---
id: 43
title: Tips Mengatasi Error 734!
date: 2008-02-17T15:02:20+07:00
author: Nana
layout: post
guid: https://www.tasikisme.com/?p=18
permalink: /tips-mengatasi-error-734/
categories:
  - Tips
tags:
  - Tips
---
Bagi yang senang browsing dengan koneksi GPRS via Bluetooth mungkin pernah mengalami hal seperti ini : Error 734: The PPP link protokol was terminated. Untuk mengatasi masalah tersebut inilah langkah-langkahnya. Selamat mencoba.

  * Masuk ke Control Panel
  * Phone and Modem Option
  * Pilih modem yang anda pakai, dalam hal ini ponsel anda
  * Properties ( modem yang anda pakai)
  * Pilih advanced
  * Di Extra Initialization Command-> masukkan parameter : at+cgdcont=1, &#8220;ip&#8221;, &#8220;Acces Point Anda&#8221; misal kalau anda menggunakan koneksi pakai kartu mentari atau IM3 maka masukan parameter berikut at+cgdcont=1,  
    &#8220;ip&#8221;, &#8220;indosatgprs&#8221;

Pastikan Acces Point di ponsel anda telah benar, untuk memastikannya,  coba lakukan koneksi internet di ponsel anda. Pastikan juga driver untuk modem (dalam hal ini ponsel anda) telah terinstal dengan benar dan sesuai.