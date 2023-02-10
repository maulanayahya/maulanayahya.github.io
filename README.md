# SELAMAT DATANG DI DOCS SEJARAH CODINGKU
#### Dokumentasi ini bertujuan sebagai catatan teknik coding agar tidak lupa  
---
### DAFTAR ISI
* [CATATAN PENGALAMAN CODING EROR](#CATATAN-PENGALAMAN-CODING-EROR)
* [PHP](#PHP-1)  
* [NODE JS](#NODEJS-1)
* TEKNOLOGI
  * HTTP
  * WEB SERVER SENT
  * WEB SOCKET
  * API
---  
## CATATAN PENGALAMAN CODING EROR
 *  #### Pastikan tipe data variabel benar

 ```
 Contoh dalam php :
 ```
 ```php
 <?php
 
 //VARIABEL INI
 $data = 1;
 
 //DENGAN INI
 $data = "1";
 
 //TIDAK SAMA KARNA VARIABEL AWAL TIPE DATA INTEGER (ANGKA) DAN KEDUA STRING (DENGAN KUTIP)
  ```
  * Catatan penting :
    > Tipe data ini juga berlaku pada teknologi API, jika tipe data pada api berbeda dengan script kita maka eror
    > Tipe data ini juga berlaku dalam penggunaan database terutama Mysql jika tipe data db dan script berbeda maka eror
    
 * #### Pastikan variabel bukan variabel bawaan
 >Variabel yang ada di script kita tidak boleh sama dengan variabel bawaan yang biasa di sebut `variabel global`
 >jika sama itu akan memunculkan eror

 * #### Pastikan menulis script dengan benar
 >Pastikan anda menulis script dengan benar, cek kembali format penulisan nya, cek juga parameter seperti fungsi dll di script apakah
 >sesuai, jika tidak maka akan eror meskipun itu sekecil apapun hal nya, karena programming adalah ilmu 100% pasti akurat
 >artinya jika anda lupa memasukkan sintak dll itu akan di anggap tidak akurat (harus sangat fokus)
 
 * #### Cek versi dari script :
 >Terkadang kita lupa bahwa ada perbedaan versi dari script dan itu sangat berpengaruh terhadap jalannya program.

 * #### Cek versi library script :
 >Jika memakai library pihak ketiga untuk script anda atau biasa di sebut `dependency` segera cek versi nya support atau tidak
 >untuk script anda, ini juga berpengaruh dan amat sering memusingkan programmer, solusi nya kurangi memakai library atau jika
 >anda masih membutuhkan library silakan ubah versi library itu ke versi lama yang support script anda (cek di website nya)
 
 * #### Jika program itu menerapkan simantik versi maka format nya akan seperti `1.4.5` artinya :
 >Angka `1` menjelaskan `major update` dimana perubahan besar terjadi mulai dari versi teknologi dan membuat versi lama tidak support lagi.
 >Angka `4` menjelaskan `minor update` dimana perubahan menengah seperti penambahan fitur dan tetap support versi lama.
 >Angka `5` menjelaskan `patch update` dimana perubahan kecil terhadap script seperti fix bug dan tetap support versi lama.
 
 * #### Jika program itu tipe nya saling berkomunikasi :
 > Jika program anda adalah program yang selalu berkomunikasi antar server, maka cek IP anda apakah di blokir oleh penyedia layanan
 > sehingga script anda tidak bisa melakukan `request`, ini biasanya terjadi pada teknologi API, cek juga regulasi atau `peraturan request`
 > apakah ada syarat khusus, salahsatu contoh nya seperti `CORS` pada website global yang membatasi permintaan secara default untuk alasan keamanan 
 
 * #### Jika semua sudah dilakukan namun tetap eror :
 > Solusi terakhir adalah dengan cara browsing eror yang muncul, usahakan browsing dengan bahasa inggris jika pada website bahasa indonesia belum ada solusi
 
---
  
## PHP
 - Membuat script wajib mencantumkan `<?php` di paling awal script dan di akhiri `?>`
 - Sintak dasar php selalu di awali tanda `$` (dolar) dan di akhiri `;` (titik koma)
 - Bahasa pemrograman yang `case sensitif` artinya huruf besar dan kecil tidak sama


