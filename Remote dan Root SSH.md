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





   

   
