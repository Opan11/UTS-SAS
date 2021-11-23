# Ujian Tengah Semester

### Sistem Administrasi Server

##### Novandy Prakoso (1202190057)



1. ##### Mendownload ISO installer Windows Server 2022

   - ###### Dengan mengklik link yang telah tersedia pada soal uts, maka akan dibawa ke link tersebut dengan tampilan seperti dibawah ini

      ![1](https://user-images.githubusercontent.com/94926477/143079867-a72a0cc1-8a8b-4423-bc3b-10d0f20aaf1e.png)
   - ###### Pilih Download the ISO kemudian ikutin sesuai step by stepnya. Jangan lupa centang yes kemudian continue

      ![2](https://user-images.githubusercontent.com/94926477/143079868-9d0c5f1c-017b-4c1c-b6ea-b3169ad73985.png)
   - ###### Pilih bahasa yang diinginkan dan klik download

      ![3](https://user-images.githubusercontent.com/94926477/143079871-57ba195a-b838-4de1-a26a-ce410c957a58.png)

2. ##### Instalasi-Instalasi

   - ###### Instalasi Windows Server 2022

     - Buka VirtualBox lalu klik "Machine-New" Menu
   
      ![4](https://user-images.githubusercontent.com/94926477/143079872-f8387a27-ea06-4e3c-a138-3fa12bca33a6.png)
   
     - Masukkan nama dari sistem yang ingin digunakan
   
      ![5](https://user-images.githubusercontent.com/94926477/143079875-df4e747a-04e5-46e9-be47-fd43aa76c9d8.png)   
     - Sesuaikan RAM dengan Laptop anda kemudian klik Next
   
      ![6](https://user-images.githubusercontent.com/94926477/143079876-055abeda-a691-44ac-a46e-6f9e23a6c8f9.png)
   
      ![7](https://user-images.githubusercontent.com/94926477/143079879-e4f0c445-5003-422c-b235-e7a6d2337672.png)
      
      ![8](https://user-images.githubusercontent.com/94926477/143079881-24e210af-4dac-4ca8-bdfa-5a7f60a6358e.png)

     - Sesuaikan size file sesuai dengan yang dari rekomendasi
   
      ![9](https://user-images.githubusercontent.com/94926477/143079884-2c517b77-9d67-4a5f-84ea-3e5308bfe7b0.png)
   
     - Setting konfigurasi "Network" dan set "Bridge adapter" pada VBox anda
   
      ![10](https://user-images.githubusercontent.com/94926477/143079888-190bcad7-bb10-4644-a0f2-82cd7b0daf97.png)
   
     - Klik "Start" kemudian pilih ISO yang sudah ter-unduh
   
      ![11](https://user-images.githubusercontent.com/94926477/143079891-cdfa3926-8697-417c-83b9-d016d34f7d8a.png)
   
     - Klik "Start" dan instalasi Windows Server 2022 Wizzard muncul
   
      ![12](https://user-images.githubusercontent.com/94926477/143079894-83eb487d-1ddd-4631-834f-4f8ce7b92402.png)
   
     - Klik Install Now
   
      ![13](https://user-images.githubusercontent.com/94926477/143079898-e7052769-0f23-4690-807f-b29bb53a2911.png)
   
     - Pilih lisensi Windows Server Datacenter Evolution(Dekstop Experience) lalu "Next"
     
      ![14](https://user-images.githubusercontent.com/94926477/143079901-c3708fcc-1101-4574-96d9-bcee60f96d46.png)
      
      ![15](https://user-images.githubusercontent.com/94926477/143079904-66bc4ab5-48dc-4704-8020-0e5e22a4400b.png)
      
      ![16](https://user-images.githubusercontent.com/94926477/143079907-cb5a5943-4daa-4ab9-9b37-d3eeeb70283f.png)
      
      ![17](https://user-images.githubusercontent.com/94926477/143079909-d1a36246-019c-4666-915e-b27871c9715a.png)

   
     - Apabila sudah ter-install sistem akan me-reboot ulang otomatis
   
      ![19](https://user-images.githubusercontent.com/94926477/143079916-edd98716-84a9-4b74-a0c5-38505d20adf8.png)   
     - klik menu "Input-keyboard-Insert Ctrl+Alt+Del" lalu masukkan password anda yang telah anda buat
   
      ![20](https://user-images.githubusercontent.com/94926477/143079919-957bc606-b0d8-4572-88b0-eace4f69aef8.png)
      
      ![21](https://user-images.githubusercontent.com/94926477/143079921-78d8ff31-a376-4ac8-9345-d541eacdfb7c.png)
   
     - lalu klik menu "Devices-Install Guest Additions CD Image" pada VBox
   
      ![22](https://user-images.githubusercontent.com/94926477/143079922-89f00518-4064-4e7b-836c-6abbeda34f69.png)
   
     - pada "file explorer", run berikut ini kemudian ikuti step nya
   
      ![24](https://user-images.githubusercontent.com/94926477/143079927-ac710f8c-e7d5-4826-a6ca-39640d6ba0b0.png)
      
      ![25](https://user-images.githubusercontent.com/94926477/143079929-825ef066-2cbe-4c7d-b730-c5d0cb3f014e.png)
      
      ![26](https://user-images.githubusercontent.com/94926477/143079930-bbe3063b-7594-48b1-9953-26038ade42a2.png)
      
      ![27](https://user-images.githubusercontent.com/94926477/143079931-8212cb1d-dd29-4c8d-b37e-7e74144b5217.png)
   
     - Setelah itu sistem akan me-reboot otomatis, lalu masukkan lagi password anda
   
      ![28](https://user-images.githubusercontent.com/94926477/143079932-b2437593-f99d-47b5-84da-edcae0a95225.png)
   
     
   
   - ###### Instalasi Active Directory Domain Services
   
     - Sebelum melakukan instalasi, kita merubah nama computer terlebih dahulu dengan masuk ke windows powershell. Kemudian ketikkan “rename-computer -Newname Server2022”
   
     ![29](https://user-images.githubusercontent.com/94926477/143079936-1290b0bb-5bcb-4b13-a4a8-197753b1ed22.png)
   
     - Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next"
   
      ![30](https://user-images.githubusercontent.com/94926477/143079938-88aa7886-706c-4eca-b3bb-ab63e3d79613.png)
      
      ![31](https://user-images.githubusercontent.com/94926477/143079942-952f5f76-ed1a-4143-88bb-58087c096e27.png)
   
     - Pilih opsi “Role-based or feature-based installation”. Lalu “Next”
    
      ![32](https://user-images.githubusercontent.com/94926477/143079944-d5f6fc04-682e-4cd9-856b-937b04d86c34.png)
   
     - Klik “Select a server from the server pool” untuk memilih direktori penyimpanan lokal. Lalu “Next”
   
      ![33](https://user-images.githubusercontent.com/94926477/143079947-f7e8a219-3008-465d-9af3-a3e4f5875600.png)
   
     - Selanjutnya, berikan tanda centang di kotak “Active Directory Domain Services”. Saat anda mencentang kotak, disebelah kanan muncul penjelasan singkat tentang ADDS dan cara kerjanya. Lalu klik “Add Features”
   
      ![34](https://user-images.githubusercontent.com/94926477/143079952-89c60246-f8b5-4a00-b0a9-512c9906ebdb.png)
   
     - Kemudian centang kotak “Group Policy Management” dan tekan tombol “Next”
   
      ![35](https://user-images.githubusercontent.com/94926477/143079955-0ce1a32d-255e-4949-bb32-fb1a7fcf7a1b.png)
   
     - Kik "Next"
   
      ![36](https://user-images.githubusercontent.com/94926477/143079960-649e9181-505e-4d9c-bd97-fcd95423c0d0.png)
   
     - Klik "Install" dan tunggu hingga selesai
   
      ![37](https://user-images.githubusercontent.com/94926477/143079963-8e81c98c-4b4f-4407-acec-2e02a8f7595f.png)
   
     
   
   - ###### Instalasi DNS server 
   
     - Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next”. Stepnya sama seperti instalasi active directory. Kita perlu menginstal dan mengonfigurasi peran Active Directory dan server DNS untuk bekerja bersama
   
      ![38](https://user-images.githubusercontent.com/94926477/143079965-89adc20e-028e-4250-8440-2675fe5ba659.png)
   
     
   
   - ###### Instalasi Net Framework 3.5
   
     - Centang "NET Framework 3.5 Features"
   
      ![39](https://user-images.githubusercontent.com/94926477/143079966-8e61d638-ad55-489d-98fa-b4fde2cce793.png)
   
     - Lalu Klik "Next"
   
      ![40](https://user-images.githubusercontent.com/94926477/143079969-fed7bb96-43de-4d32-bd69-964093d09f82.png)
   
     - Lalu Klik "Install"
   
      ![41](https://user-images.githubusercontent.com/94926477/143079970-e8875926-69ec-4959-89a8-310c903d3cd7.png)
   
     - Lalu tunggu hingga selesai
   
      ![42](https://user-images.githubusercontent.com/94926477/143079971-1155f308-ba29-44d8-a430-a319d4aff789.png)
   
     
   
   - ###### Promote Server to a Domain Controller
   
     Konfigurasi ADDS
   
     - Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan
     - Seting ke ip static menggunakan cmd, ketik "sconfig" - ketik "1"
   
      ![43](https://user-images.githubusercontent.com/94926477/143079973-3ceb7416-3abc-415c-bf20-07e4b7981001.png)
   
     - Kemudian setting network
   
      ![44](https://user-images.githubusercontent.com/94926477/143079976-f7ae77ff-ee50-4f5f-8bc3-7f7b82394133.png)
   
     - Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan
   
      ![45](https://user-images.githubusercontent.com/94926477/143079978-8c1925b6-a0ad-4ad8-9034-f967e08ac748.png)
   
     - Klik “Promote this server to a domain controller" untuk konfigurasi ADDS
   
      ![46](https://user-images.githubusercontent.com/94926477/143079982-d84e918f-0857-4d77-b113-c8ca99a2fd0a.png)
   
     - Pilih “Add a new forest” dan masukkan nama domain yang akan digunakan pada Root Domain Name. Misalnya disini saya menggunakan domain “Novan.com"
   
      ![47](https://user-images.githubusercontent.com/94926477/143079984-a2e58ed3-157d-4a3c-9801-adae29d0c6fc.png)
   
     - Pilih “Windows Server 2016” pada functional level, beri tanda centang pada “Domain Name System (DNS) server” dan ”Global Catalog (GC)”. Serta mengisi password Directory Services Restore Mode dengan kriteria strong password
   
      ![48](https://user-images.githubusercontent.com/94926477/143079988-042de6e3-3a82-46a6-b5fd-773c9787379f.png)
   
     - Lewati bagian DNS Options, lalu klik “Next”
   
      ![49](https://user-images.githubusercontent.com/94926477/143079991-767c5dd2-b103-42c5-aa9e-5aa30bf5d75f.png)
   
     - Mengisi “The NetBIOS domain name” sesuai dengan nama domain yang digunakan
   
      ![50](https://user-images.githubusercontent.com/94926477/143079996-3dfe1af6-db6e-4a8c-bde9-cad0eb1caf15.png)
   
     - Lewati bagian Paths, klik “Next”
   
      ![51](https://user-images.githubusercontent.com/94926477/143079847-5cfaee9f-db86-4267-929a-6e85a129f105.png)
   
     - Cek konfigurasi yang ditentukan pada Review Options, jika suda ok. Klik “Next”
     
      ![52](https://user-images.githubusercontent.com/94926477/143079856-73495ba0-837e-4979-80fb-6b3cfffa2008.png)
   
     - Jika sudah ada tulisan All prerequisite checks passed successfully. Klik “Install” untuk apply konfigurasi yang sudah ditentukan
   
      ![53](https://user-images.githubusercontent.com/94926477/143079858-f474ac9a-2afc-4c44-aa33-6302386eb30d.png)
   
     - Tunggu Instalasi hingga selesai
   
      ![54](https://user-images.githubusercontent.com/94926477/143079859-e3dc97cc-63d8-49bd-886c-d182063e4130.png)
   
     - Apabila sudah selesai sistem akan auto reboot, lalu cek hasil konfigurasi, buka cmd dan ketikkan “netdom query fsmo”
   
      ![55](https://user-images.githubusercontent.com/94926477/143079861-56e50dfd-cf96-42b1-a078-00e67a995fd1.png)
   
     - Setelah login dengan Active Directory Domain Controller Anda, buka properti TCP/IP koneksi jaringan Anda. Anda dapat melihat Alamat IP server DNS
   
      ![56](https://user-images.githubusercontent.com/94926477/143079862-ca931b04-e13c-4a87-9028-d94dc8df8032.png)
   
     - Kemudian ubah IP Address sesuai dengan awal tadi
   
      ![57](https://user-images.githubusercontent.com/94926477/143079866-c1b72d28-0bc9-4e84-9f4a-7fed9806d481.png)
   
     
   
     



