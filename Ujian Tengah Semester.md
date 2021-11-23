# Ujian Tengah Semester

#### Sistem Administrasi Server

##### Novandy Prakoso (1202190057)



1. ##### Mendownload ISO installer Windows Server 2022

   - ###### Dengan mengklik link yang telah tersedia pada soal uts, maka akan dibawa ke link tersebut dengan tampilan seperti dibawah ini

     <img src="C:\Users\Novandy\OneDrive\Pictures\1.png" alt="1" style="zoom:50%;" />

   - ###### Pilih Download the ISO kemudian ikutin sesuai step by stepnya. Jangan lupa centang yes kemudian continue

     <img src="C:\Users\Novandy\OneDrive\Pictures\2.png" alt="2" style="zoom:50%;" />

   - ###### Pilih bahasa yang diinginkan dan klik download

     <img src="C:\Users\Novandy\OneDrive\Pictures\3.png" alt="3" style="zoom: 50%;" />

2. ##### Instalasi-Instalasi

   - ###### Instalasi Windows Server 2022

     - Buka VirtualBox lalu klik "Machine-New" Menu
   
     ![4](C:\Users\Novandy\OneDrive\Pictures\4.png)
   
     - Masukkan nama dari sistem yang ingin digunakan
   
     ![5](C:\Users\Novandy\OneDrive\Pictures\5.png)
   
     - Sesuaikan RAM dengan Laptop anda kemudian klik Next
   
     ![6](C:\Users\Novandy\OneDrive\Pictures\6.png)
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\7.png" alt="7" style="zoom: 67%;" />
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\8.png" alt="8" style="zoom:67%;" />
   
     - Sesuaikan Size File sesuai dengan yang dr rekomendasi
   
     ![9](C:\Users\Novandy\OneDrive\Pictures\9.png)
   
     - Setting konfigurasi "Network" dan set "Bridge adapter" pada VBox anda
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\10.png" alt="10" style="zoom:67%;" />
   
     - Klik "Start" kemudian pilih ISO yang sudah ter-unduh
   
     ![11](C:\Users\Novandy\OneDrive\Pictures\11.png)
   
     - Klik "Start" dan instalasi Windows Server 2022 Wizzard muncul
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\12.png" alt="12" style="zoom:50%;" />
   
     - Klik Install Now
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\13.png" alt="13" style="zoom: 50%;" />
   
     - Pilih lisensi Windows Server Datacenter Evolution(Dekstop Experience) lalu "Next"
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\14.png" alt="14" style="zoom:67%;" />
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\15.png" alt="15" style="zoom:50%;" />
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\16.png" alt="16" style="zoom:50%;" />
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\17.png" alt="17" style="zoom: 67%;" />
   
     - Apabila sudah ter-install sistem akan me-reboot ulang otomatis
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\19.png" alt="19" style="zoom:50%;" />
   
     - klik menu "Input-keyboard-Insert Ctrl+Alt+Del" lalu masukkan password anda yang telah anda buat
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\20.png" alt="20" style="zoom:50%;" />
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\21.png" alt="21" style="zoom:50%;" />
   
     - lalu klik menu "Devices-Install Guest Additions CD Image" pada VBox
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\22.png" alt="22" style="zoom:50%;" />
   
     - pada "file explorer", run berikut ini kemudian ikuti step nya
   
     ![24](C:\Users\Novandy\OneDrive\Pictures\24.png)
   
     ![25](C:\Users\Novandy\OneDrive\Pictures\25.png)
   
     ![26](C:\Users\Novandy\OneDrive\Pictures\26.png)
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\27.png" alt="27" style="zoom:50%;" />
   
     - Setelah itu sistem akan me-reboot otomatis, lalu masukkan lagi password anda
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\28.png" alt="28" style="zoom:50%;" />
   
     
   
   - ###### Instalasi Active Directory Domain Services
   
     - Sebelum melakukan instalasi, kita merubah nama computer terlebih dahulu dengan masuk ke windows powershell. Kemudian ketikkan “rename-computer -Newname Server2022”
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\29.png" alt="29" style="zoom:67%;" />
   
     - Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next"
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\30.png" alt="30" style="zoom: 50%;" />
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\31.png" alt="31" style="zoom:50%;" />
   
     - Pilih opsi “Role-based or feature-based installation”. Lalu “Next”
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\32.png" alt="32" style="zoom:50%;" />
   
     - Klik “Select a server from the server pool” untuk memilih direktori penyimpanan lokal. Lalu “Next”
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\33.png" alt="33" style="zoom:50%;" />
   
     - Selanjutnya, berikan tanda centang di kotak “Active Directory Domain Services”. Saat anda mencentang kotak, disebelah kanan muncul penjelasan singkat tentang ADDS dan cara kerjanya. Lalu klik “Add Features”
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\34.png" alt="34" style="zoom:50%;" />
   
     - Kemudian centang kotak “Group Policy Management” dan tekan tombol “Next”
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\35.png" alt="35" style="zoom:50%;" />
   
     - Kik "Next"
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\36.png" alt="36" style="zoom:50%;" />
   
     - Klik "Install" dan tunggu hingga selesai
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\37.png" alt="37" style="zoom:50%;" />
   
     
   
   - ###### Instalasi DNS server 
   
     - Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next”. Stepnya sama seperti instalasi active directory. Kita perlu menginstal dan mengonfigurasi peran Active Directory dan server DNS untuk bekerja bersama
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\38.png" alt="38" style="zoom:50%;" />
   
     
   
   - ###### Instalasi Net Framework 3.5
   
     - Centang "NET Framework 3.5 Features"
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\39.png" alt="39" style="zoom:50%;" />
   
     - Lalu Klik "Next"
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\40.png" alt="40" style="zoom:50%;" />
   
     - Lalu Klik "Install"
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\41.png" alt="41" style="zoom:50%;" />
   
     - Lalu tunggu hingga selesai
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\42.png" alt="42" style="zoom:50%;" />
   
     
   
   - ###### Promote Server to a Domain Controller
   
     Konfigurasi ADDS
   
     - Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan
     - Seting ke ip static menggunakan cmd, ketik "sconfig" - ketik "1"
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\43.png" alt="43" style="zoom: 67%;" />
   
     - Kemudian setting network
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\44.png" alt="44" style="zoom: 67%;" />
   
     - Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\45.png" alt="45" style="zoom: 67%;" />
   
     - Klik “Promote this server to a domain controller" untuk konfigurasi ADDS
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\46.png" alt="46" style="zoom:50%;" />
   
     - Pilih “Add a new forest” dan masukkan nama domain yang akan digunakan pada Root Domain Name. Misalnya disini saya menggunakan domain “Novan.com"
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\47.png" alt="47" style="zoom: 67%;" />
   
     - Pilih “Windows Server 2016” pada functional level, beri tanda centang pada “Domain Name System (DNS) server” dan ”Global Catalog (GC)”. Serta mengisi password Directory Services Restore Mode dengan kriteria strong password
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\48.png" alt="48" style="zoom: 67%;" />
   
     - Lewati bagian DNS Options, lalu klik “Next”
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\49.png" alt="49" style="zoom:67%;" />
   
     - Mengisi “The NetBIOS domain name” sesuai dengan nama domain yang digunakan
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\50.png" alt="50" style="zoom:67%;" />
   
     - Lewati bagian Paths, klik “Next”
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\51.png" alt="51" style="zoom:67%;" />
   
     - Cek konfigurasi yang ditentukan pada Review Options, jika suda ok. Klik “Next”
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\52.png" alt="52" style="zoom:67%;" />
   
     - Jika sudah ada tulisan All prerequisite checks passed successfully. Klik “Install” untuk apply konfigurasi yang sudah ditentukan
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\53.png" alt="53" style="zoom:67%;" />
   
     - Tunggu Instalasi hingga selesai
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\54.png" alt="54" style="zoom:67%;" />
   
     - Apabila sudah selesai sistem akan auto reboot, lalu cek hasil konfigurasi, buka cmd dan ketikkan “netdom query fsmo”
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\55.png" alt="55" style="zoom:67%;" />
   
     - Setelah login dengan Active Directory Domain Controller Anda, buka properti TCP/IP koneksi jaringan Anda. Anda dapat melihat Alamat IP server DNS
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\56.png" alt="56" style="zoom:67%;" />
   
     - Kemudian ubah IP Address sesuai dengan awal tadi
   
     <img src="C:\Users\Novandy\OneDrive\Pictures\57.png" alt="57" style="zoom:67%;" />
   
     
   
     



