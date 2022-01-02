---
id: 41
title: Windows XP…. wush….. wush……..!
date: 2008-02-16T13:44:49+07:00
author: Nana
layout: post
guid: https://localhost/wordpress/?p=15
permalink: /windows-xp-wush-wush/
categories:
  - Komputer
tags:
  - Komputer
  - Tips
  - Trick
---
<p style="text-align: justify;">
  Windows anda semakin lambat dari hari ke hari? Tip-tips berikut akan menjadikan Windows anda lebih cepat daripada yang anda rasakan selama ini. Satu hal yang mesti diperhatikan, tips yang akan dikemukan di bawah ini mengakses jauh ke sistem windows sehingga mengandung resiko. Jadi demi mendapatkan hasil yang maksimal disarankan anda untuk berhati-hati.
</p>

### Mempercepat Booting Windows

Pada menu RUN ketika msconfig,  
pada tab start up, hilangkan tanda centang pada program-program yang tidak ingin anda jalankan pada saat Windows dijalankan.

**Matikan layanan yang tidak perlu**

Klik [Start] > [Run] dan buka jendela Services dengan mengetikan perintah berikut : services.msc klik kanan pada layanan yang tidak anda perlukan misal pada ‘Wireless Zero Configuration’, klik Propertis, klik Stop (bila layanan ini emang se dang berjalan), terus pada Start Up ubah menjadi Disable atau Manual sesuai kebutuhan anda.

**Bersih-bersih registry**

Bila registry tersumbat,  Windows tidak berfungsi dengan lancar dan mulai merayap. Saatnya untuk bersih-bersih. Separah apa registry Anda terbebani dengan yang tidak perlu, tergantung jumlah program yang terinstalasi. Entri-entri mana saja yang membengkakkan registry dan melumpuhkan Windows XP?

Baca penjelasan berikut. Nilai dalam kunci-kunci Autoexec: Program-program yang dijalankan saat start tercantum dalam subkey ‘Run’ dan ‘Run Once’ di lokasi ‘HKEY\_LOCAL\_MACHINE SoftwareMicrosoftWindowsCurrentVersion’. Terlalu banyak entri akan memperlambat start Windows.

Tipe file yang tak digunakan: Semua akhiran file terkait dengan aplikasi tertentu. Sebagai contoh, ‘acw’ terkait dengan wizard Help (accwiz.exe). Jika Anda tidak membutuhkannya, singkirkan akhiran ini.

Entri yang tidak berlaku: Anda dapat melacak entri-entri yang tidak berlaku dengan RegSeeker. Saat tool memberi laporan, biasanya ia menemukan trojan atau spyware.  Links yatim-piatu: Bila program tidak menyingkirkan entri-entri dalam registry saat uninstall,  Anda memiliki file-path yang tidak mengantar ke mana pun. Link semacam ini juga ditemukan oleh RegSeeker.

Singkirkan entri-entri tersembunyi dalam registry Entri-entri tersembunyi tidak dapat ditampilkan dengan regedit maupun disingkirkan dengan cleaning-tool seperti RegSeeker. Kabarnya, tool anti-spyware yang canggih seperti ‘Hijack this’ juga gagal pada entri-entri registry yang lebih panjang dari 256 karakter dan rangkaian karakter ANSI 8 bit yang berakhiran 0.

Untuk membersihkan folder Autoexec dengan tuntas, Anda membutuhkan baris perintah internal Windows. Jalankan regedit atau tool seperti RegSeeker dan bersihkan kunci :

> ‘HKEY\_LOCAL\_MACHINE/Software/Microsoft/Windows/CurrentVersionRun’

dari semua entri yang tidak diperlukan seperti biasa.

Selanjutnya, klik [Start] > [Run] dan buka DOS-box dengan perintah berikut : cmd untuk menemukan entri-entri tersembunyi, ketikkan perintah berikut. reg•query•HKLM/Software/Microsoft/Windows/CurrentVersion Jika Anda menemukannya, hapus dengan perintah berikut.

> reg•delete•HKLM/Software/Microsoft/Windows/CurrentVersion/Run Nilai•tersembunyi

Catatan: Perintah ‘Reg’ menawarkan banyak fungsi yang penjelasannya dapat Anda baca dengan mengetikkan perintah berikut. reg/?

### Percepat download

Dengan SP2, Microsoft telah membatasi jumlah koneksi paralel TCP/IP menjadi 10 buah. Ini memberikan keamanan, tetapi menghambat kerja bursa-tukar. Singkirkan pembatasan ini dengan sebuah patch yang memodifikasi file ‘tcpip.sys’ dan sebuah registry-hack.

Pertama, download EvID4226Patch dan ekstrak file ZIP-nya. Setelah mengklik ganda file EXE yang ada, akan tampak sebuah jendela DOS yang menanyakan apakah Anda ingin meningkatkan batas menjadi 50.

Konfirmasikan dengan menekan tombol [Y] dua kali untuk menjalankan patch. Berikutnya, jawab jendela keamanan Windows dengan mengklik ‘Stop’ dan ‘OK’. Kemungkinan besar, virus-scanner Anda akan melaporkan a danya bahaya karena trojan juga menggunakan teknik yang sama seperti patch ini untuk menyebarkan diri lebih cepat. Abaikan laporan yang muncul dan matikan sementara virus-scanner Anda.

Patch hanya meningkatkan jumlah koneksi yang setengah terbuka (ada dalam waiting-list). Karena jumlah koneksi TCP/IP biasa dibatasi 10,  Anda perlu mengubah satu nilai dalam registry. Windows XP memungkinkan penggunaan sampai 16.777.214 koneksi paralel. Jalankan registry-editor, masuk ke kunci:

> ‘HKEY\_LOCAL\_MACHINE/System/CurrentControl/SetServicesTcpip Parameters’.

Buat sebuah nilai DWORD dengan nama ‘TcpNumConnections’ dan beri nilai ‘00fffffe’ (hexadecimal) atau ‘16777214’ (decimal). Setelah restart, tidak ada lagi pembatasan jumlah koneksi.

Matikan fungsi POSIX Posix

memungkinkan penggunaan fungsi-fungsi Unix di bawah Windows—menurut Microsoft tidak lagi didukung sejak Windows XP digunakan. Namun, para pembuat Windows merahasiakan bahwa sebenarnya Posix masih berfungsi di latar belakang. Ia mengkonsumsi resource sistem dan membuka celah keamanan. Melalui registry Anda dapat mematikan Posix. Jalankan registry-editor dan masuk ke kunci:

> ‘HKEY\_LOCAL\_MACHINE/ System/CurrentControl/SetControl Session/Manager/SubSystems’.

Di sana Anda akan menemukan entri ‘Optional’. Di bawah ‘Value’ tercantum teks ‘Posix’ yang berarti layanan ini aktif. Untuk mematikannya, klik ganda entri ‘Optional’ dan hapus kata ‘Posix’. Setelah restart,  
layanan Posix akan dimatikan.

### Optimalkan Autoexec

Misalkan Anda ingin menjalankan aplikasi Word bersama Windows. Namun, bila Anda sekadar memindahkan shortcut ‘Word.exe’ ke dalam folder Autoexec, start Windows akan menjadi lambat. Masalah ini dapat diatasi dengan sebuah script VBS yang akan menjalankan aplikasi setelah Windows start.

Nilai ‘WaktuTunggu’ menentukan kapan aplikasi akan dijalankan. Dalam contoh, Word akan dijalankan setelah 30.000 milidetik atau 30 detik. Pada sistem yang di-setting dengan benar, semua layanan Windows yang relevan akan dijalankan setelahnya. Masukkan path ke ‘Word.exe’ setelah ‘objshell.exec’ dengan tepat dan simpan dengan nama ‘start.vbs’.

Tentu saja Anda dapat memasukkan aplikasi selain Word. Jika Anda ingin menjalankan beberapa aplikasi, tambahkan saja perintah objshell.exec lain di bawahnya. Kebanyakan virus-scanner menunjukkan reaksi alergi terhadap VBS-script.

Coba klik ganda script yang baru dibuat tadi. Bila Anda mendapatkan laporan dari virus-scanner, ijinkan script untuk dijalankan. Selanjutnya, copy ‘start.vbs’ ke folder ‘Autoexec’. Setelah restart, aplikasi akan dijalankan setelah Waktu Tunggu terlewati, sementara Windows XP dapat langsung digunakan

### Matikan layanan Indeks File

Klik [Start] > [Run] dan masukan perintah: services.msc Klik kanan Indexing Service dan pilih Stop. Anda masih perlu mematikan indeksasi pada setiap partisi. Untuk itu, klik kanan salah satu partisi, misalnya ‘c:’, lalu buka ‘Properties’. Matikan ‘Index drive for quick file-search’. Dalam dialog berikutnya, beritahu Windows bahwa setting ini berlakun untuk subfolder.

Tergantung ukuran hard disknya, proses ini bisa berlangsung cukup lama. Setelah selesai, restart PC. Untuk pencarian file di komputer anda pergunakan Google Desktop Search yang lebih powerfull dibandingkan dengan tool pencari bawaan windows.