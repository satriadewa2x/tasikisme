---
id: 302
title: 'Solusi : Regedit Disable by Administrator'
date: 2009-04-29T17:35:27+07:00
author: Nana
layout: post
guid: https://www.tasikisme.com/?p=302
permalink: /solusi-regedit-disable-by-administrator/
categories:
  - Komputer
  - Windows
tags:
  - Komputer
  - Tips
  - Trick
  - Windows
---
<div>
  Saat kita akan mengedit registri, ada kalanya fungsi regedit di Windows tidak bisa diakses alias disable. Ini bisa dikarenakan oleh virus, atau juga memang oleh sang Adm inistrator telah di-disable untuk mencegah orang yang tidak berkepentingan mengutak-atik setting Windows. Kalau anda pernah mengalami kejadian seperti ini <strong>Registry Editing has been disable by your Adm inistrator</strong> ketika memasukkan perintah <strong>REGEDIT </strong>pada menu RUN</p> 
  
  <p>
    <img alt="solusi mengatasi registri disable by adm<mce:script mce_src=" src="https://1.bp.blogspot.com/-3FvXIr1vGns/Uq6KUy8wOmI/AAAAAAAACdE/R29jNRaHwGI/s1600/regedit_00.gif" border="0" /></div> 
    
    <p>
      Inilah solusi singkat yang mungkin bisa membantu anda mengatasi masalah seperti diatas.
    </p>
    
    <p>
      Klik Menu<strong> [Start] – [RUN] </strong> dan masukkan perintah : <strong>GPEdit.msc </strong><br /> <img title="GPEDIT" alt="GPEDIT" src="https://1.bp.blogspot.com/-tS0bOtrIA6A/Uq6KVPsOO3I/AAAAAAAACdI/qsWgc-KeHkM/s1600/regedit_01.gif" border="0" /></div> 
      
      <p>
        &nbsp;
      </p>
      
      <p>
        Akan muncul Windows Group Policy, selanjutnya arahkan ke <strong>[User Configuration] – [Adm inistrative Templates] – [System] </strong>.<br /> <img title="Group Policy" alt="Group Policy" src="https://1.bp.blogspot.com/-cw0TY8UELjw/Uq6KVCNVqaI/AAAAAAAACdM/jb2BJP2a1T0/s1600/regedit_02.gif" border="0" /></div> 
        
        <p>
          &nbsp;
        </p>
        
        <p>
          Setelah itu pada jendela sebelah kanan (panel setting) Double Klik Prevent Access to Registry Editing Tools<br /> <img title="disable registry tools" alt="disable registry tools" src="https://3.bp.blogspot.com/-oNzdNsy4qCk/Uq6KWLX1n1I/AAAAAAAACdc/FDDr9ESx5bE/s1600/regedit_03.gif" border="0" /></div> 
          
          <p>
            &nbsp;
          </p>
          
          <p>
            Pada jendela yang muncul pilih <strong>NOT CONFIGURED </strong> atau <strong>DISABLED </strong>, untuk mengaktifkan kembali fungsi regedit.<br /> <img title="Disable Regedit" alt="Disable Regedit" src="https://3.bp.blogspot.com/-gwizOE2AtYQ/Uq6KWSDaQaI/AAAAAAAACdg/na3DnBvGiOs/s1600/regedit_04.gif" border="0" /></div> 
            
            <p>
              Klik OK<br /> Sekarang coba anda akses registry editor lewat menu [RUN] &#8211; REGEDIT kalau masih belum berhasil, Restart Komputer anda dan coba akses lagi registry editor.
            </p>
            
            <p>
              Bila ternyata Solusi tersebut masih juga kurang ampuh, Tinggal Download REGTOOLS dari Doug Knox, Save dan kemudian jalankan regtools, ini berfungsi untuk meng-enable dan disable registry. Bila kondisi registry editor disable, maka regtool akan meng-enable-kannya, begitupun sebaliknya.
            </p>
            
            <p>
              Selamat mencoba dan jangan lupa untuk mendapatkan update dan informasi terbaru dari tasikisme.com secara langsung ke email, tinggal masukkan email anda di bawah ini dan klik subscribe!
            </p></div>