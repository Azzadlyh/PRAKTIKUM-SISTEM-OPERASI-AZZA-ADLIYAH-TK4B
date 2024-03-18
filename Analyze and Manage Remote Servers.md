# Remote SSH
Berikut adalah langkah-langkah untuk membuat penggunaan SSH remote ke VirtualBox Linux Ubuntu Desktop:  
1. `Persiapkan VirtualBox Ubuntu Desktop:`   
   Pastikan Anda memiliki VirtualBox diinstal dan sudah memiliki mesin virtual Ubuntu Desktop yang berjalan.   
   Pastikan mesin virtual Ubuntu Desktop memiliki koneksi internet yang baik.  
  ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/e9914412-a151-4c3d-a196-293e9bc55016)

2. `Buka Terminal di Ubuntu Desktop:`  
   Buka terminal di mesin virtual Ubuntu Desktop Anda. Anda dapat melakukannya dengan menekan Ctrl + Alt + T atau mencarinya dalam menu aplikasi.  
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/ba3899d1-0b93-4f8f-94f8-29d2920ba78e)  

3. `Periksa Alamat IP:`  
   Jalankan perintah ifconfig di terminal untuk mengetahui alamat IP mesin virtual Ubuntu Desktop.
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/38c0a6c5-670c-4af5-a1a5-7549a7639a4a)

   cek IP user lain untuk kita remote
   `contohnya :`  
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/de6a1fbb-3982-4c4d-a327-66de54f30337)

4. `Pastikan SSH Service Berjalan:`
   Pastikan layanan SSH (Secure Shell) aktif di mesin virtual Ubuntu Desktop. Jika belum aktif, Anda dapat mengaktifkannya dengan perintah :
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/ce0a4515-1864-45e0-8c20-2b149c99d5a0)

5. `Uji Koneksi SSH:`  
   Uji koneksi SSH ke mesin virtual Ubuntu Desktop dari komputer host Anda menggunakan alamat IP (user lain) yang telah Anda temukan sebelumnya.
   Gantilah username dengan nama pengguna Anda di mesin virtual Ubuntu Desktop dan <ip_address> dengan alamat IP mesin virtual Anda.
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/37fdb90f-c4ea-414e-a3d3-2669cc0ecb9d)

6. `Selesai:`
   Sekarang Anda telah berhasil melakukan koneksi SSH ke mesin virtual Ubuntu Desktop.
   Anda dapat melakukan operasi yang diperlukan melalui koneksi SSH ini.


   Pastikan untuk mengganti <ip_address> dengan alamat IP yang sesuai dari mesin virtual Anda dan <username> dengan nama pengguna yang ingin Anda gunakan.
   Juga, pastikan bahwa mesin virtual Anda memiliki pengaturan jaringan yang benar dan diakses dari komputer host Anda.

# Root IP 
  Ketik `sudo -1`    
  ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/28fd41a8-abc3-4a57-8c2b-ab915b5080db)


# Analyze and Manage Remote Servers  
"Selamat datang dalam tutorial tentang cara menganalisis dan mengelola server jarak jauh menggunakan Red Hat. Dalam sesi ini, kita akan melalui langkah-langkah penting untuk mengoptimalkan kinerja server Anda secara efisien."  

Dalam latihan ini, Anda mengaktifkan dan mengakses konsol web di server untuk mengelolanya dan untuk mendiagnosis serta menyelesaikan masalah.  
Gunakan konsol web untuk memantau fitur sistem, memeriksa file log, membuat akun pengguna, dan mengakses terminal.

Sebagai [student] pengguna mesin [workstation], gunakan lab perintah untuk mempersiapkan sistem Anda untuk latihan ini.

Perintah ini mempersiapkan lingkungan Anda dan memastikan bahwa semua sumber daya yang diperlukan tersedia.  
 ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/34f5a26a-293c-49e4-b97c-ac96f188da90)  
 
1. Masuk ke servera mesin sebagai student pengguna.  
![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/ec522d09-c94b-4a41-b0b5-aeef5fd9ac20)  

2. Aktifkan layanan konsol web.  
   password : student   
![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/3e581560-412f-49b2-8886-9ee18878081a)  
  
3. Di workstation mesin, buka browser web Firefox dan masuk ke antarmuka konsol web di servera.lab.example.com. Masuk sebagai studentpengguna.  
![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/c3a809bc-2f6a-47c9-854d-f7836106feff)

4. ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/8b83aaac-9dea-4af5-9d9f-207d641647a5)  ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/fa3da596-2dbe-48b0-ab6c-95e7416345fe)

5. ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/35c88b86-8722-4b45-984b-0da778949a6b)

6. ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/5bd6d144-1d03-4e03-bb24-60b3c1af88e1)  

7. ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/13f7b504-b66f-4557-b26f-4ffb92a185ee)

8. ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/91a815c4-f455-40e6-8cc7-7ce9562f1b42)

9. Isi Akun dengan :  
   - Full name : azza  
   - Username  : azza  
   - Password dan confirm : redhatazza  
![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/0e20a096-3156-4819-9b90-c497ce389190)  

10. ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/7527b7d5-0611-4dab-873a-edd503efd0a7)

11. ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/e0a0927b-9639-4d35-8f39-a9b4c68278e9)

12. ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/f073881d-bf0a-40f8-8315-7338e3bbca33)

13. ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/c3d1fde8-ea0d-42c4-bc20-cffeed8b7d7f)

14. ![image](https://github.com/Azzadlyh/PRAKTIKUM-SISTEM-OPERASI-AZZA-ADLIYAH-TK4B/assets/126213404/213f50f7-5ab7-47df-ac0e-d2e015888f25)  













