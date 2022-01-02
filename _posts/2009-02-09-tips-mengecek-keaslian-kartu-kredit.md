---
id: 254
title: Tips Mengecek Keaslian Kartu Kredit
date: 2009-02-09T17:08:03+07:00
author: Nana
layout: post
guid: https://www.tasikisme.com/?p=254
permalink: /tips-mengecek-keaslian-kartu-kredit/
categories:
  - Informasi
  - Tips
tags:
  - Informasi
  - Tips
---
Langkah berikut ini adalah sebuah langkah kecil untuk mengecek keaslian sebuah kartu kredit dengan mempergunakan Logaritma Luhn yang ditemukan oleh Hans Peter Luhn. Dengan memakai Logaritma Luhn kita bisa mengetahui apakah sebuah Kartu itu Valid atau tidak, dalam waktu yang singkat (hanya perlu waktu kurang dari lima menit).

Seperti kita ketahui, umumnya sebuah kredit mempunyai 16 digit number meski dalam beberapa kasus ada juga yang digitnya sampai 19. Sebelum mulai mempergunakan Logaritma Luhn yang pertama kali kita perlukan adalah sebuah tabel dengan jumlah baris empat buah, dan jumlah kolom disesuaikan dengan banyak digit kartu kredit yang akan kita cek.

1. Misal kita akan mengecek sebuah kartu kredit (credit card) dengan nomor **7563 8924 1329 5497** , apakah merupakan sebuah kartu kredit yang valid atau tidak. Pertama tuliskan semua nomor tersebut pada baris pertama.

<table border="0" align="center">
  <tr id="www.tasikisme.com" align="center">
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong> 7 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>5<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>6<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>3<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>8<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>9<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>2<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>4<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>1<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>3 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>2 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>9 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>5<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>4 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>9 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff; width: 12px;" align="center">
      <strong>7<br /> </strong>
    </td>
  </tr>
  
  <tr style="background-color: #008080;" align="center">
    <td style="border: 1px solid #ffffff;" align="center">
      <strong> 7&#215;2=14 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>5 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>6&#215;2=12 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>3 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>8&#215;2=16 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>9 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>2&#215;2=4 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>4 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>1&#215;2=2 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>3 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>2&#215;2=4 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>9 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>5&#215;2=10 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>4<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>9&#215;2=18 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>7<br /> </strong>
    </td>
  </tr>
  
  <tr align="center">
    <td style="border: 1px solid #ffffff;" align="center">
      <strong> 14-9=5 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>5<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>12-9=3<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>3<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>16-9=7<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>9<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>4<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>4 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>2<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>3 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>4<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>9 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>10-9=1<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>4 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>18-9=9<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>7<br /> </strong>
    </td>
  </tr>
  
  <tr style="background-color: #708090;" align="center">
    <td style="border: 1px solid #ffffff;" align="center">
      <strong> 5 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>5 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>3<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>3<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>7<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>9 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>4<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>4 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>2<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>3<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>4<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>9 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>1<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>4 </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>9<br /> </strong>
    </td>
    
    <td style="border: 1px solid #ffffff;" align="center">
      <strong>7<br /> </strong>
    </td>
  </tr>
</table>

<div>
  <p>
    2. Pada baris kedua tabel tersebut, kalikan dengan 2.
  </p>
  
  <p>
    3. Pada baris ketiga, jadikan semua nomor pada baris kedua menjadi kurang dari 10, jika perlu kurangi dengan 9 supaya menjadi kurang dari 10
  </p>
  
  <p>
    4. Masukan hasil dari baris ketiga ke baris keempat.
  </p>
  
  <p>
    5. Terakhir jumlah semua angka yang didapat pada baris keempat.
  </p>
  
  <p>
    6. Untuk mengetahui valid atau tidaknya sebuah kartu kredit, hasil dari langkah ke-5 harus habis dibagi 10 (tanpa tanda koma dibelakang) dalam arti lain merupakan kelipatan 10. Pada contoh diatas hasil penjumlahan dari baris keempat adalah sebanyak 79 yang tidak habis dibagi 10, jadi bisa dipastikan bahwa kartu kredit tersebut tidak valid alias palsu.
  </p>
</div>