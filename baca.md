# Web Aplikasi Pelayanan Keluhan Pelanggan

Layanan keluhan pelanggan berbasis web. Pelanggan dapat memberikan keluhan mereka terkait pelayanan, dan juga melacak status keluhan yang telah mereka laporkan dengan mencantumkan ID Complaint (ID Keluhan).

# Instalasi

1. Buka localhost/phpmyadmin
2. Buat database dengan nama 'customer_service'
3. 	Pastikan username dan password DB Anda adalah.  
	Username DB : root  
	Password DB :   
	*Jika Anda tidak mengubah konfigurasi default phpMyAdmin pengaturan ini tidak diperlukan.  
	**Jika Anda username dan Password phpMyAdmin telah dikonfigurasi / diubah, Anda perlu mengubah file customer_service/application/database.php  
	Kemudian ubah pada kolom 'username' dan 'password' sesuai dengan username dan password pada phpMyAdmin.  
4. Export database 'customer_service' ke dalam database phpMyAdmin yang telah dibuat.
5. Copy - Paste folder 'customer_service' yang telah Anda dapatkan dari Github ini ke dalam folder C:/xampp/htdocs
6. Buka localhost/customer_service melalui web browser Anda.

# Username & Password Admin

Pada database yang telah disediakan di Github ini, terdapat akun admin yang dapat Anda lakukan untuk login ke sistem aplikasi web.

Username : admin  
Password : admin

## Konfigurasi
Untuk dapat menggunakan layanan auto email. Anda harus mengganti   
* $config['smtp_user']        = 'iwan.bazz@gmail.com'; 	/*Masukkan nama email Anda*/
* $config['smtp_pass']        = '********';	/*Masukkan password email Anda*/
Pada file 'application/config/email.php'
Saya sangat merekomendasikan untuk menggunakan email dari Google (Gmail)