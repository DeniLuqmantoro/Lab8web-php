# Lab8web-php

<b>Nama	: Deni Luqmantoro

NIM		: 312010071

Kelas		: TI 20 D1

Matakuliah	: Pemrograman Web</b>

<b>Langkah-langkah praktikum</b>

1.	Menjalankan mysql server dengan aplikasi xampp, kemudian start apache dan mysql.
![image](https://user-images.githubusercontent.com/101716699/169769639-7ab3dc5e-d048-4bc8-b724-305acb762111.png) 

2.	Akses mysql Client menggunakan PHP MyAdmin melalui browser dengan link http://localhost/phpmyadmin/ 
 ![image](https://user-images.githubusercontent.com/101716699/169769673-7a5db61d-fc9e-422c-96fc-ed7f1dd7c18a.png)

3.	Membuat database dengan nama Latihan 1.
 
 ![image](https://user-images.githubusercontent.com/101716699/169769745-b63208ab-667b-4a10-b8c7-5daa885e80a4.png)

4.	Membuat tabel pada database Latihan 1 dengan syntax berikut.

CREATE TABLE data_barang (

id_barang int(10) auto_increment Primary Key,

kategori varchar(30),

nama varchar(30),

gambar varchar(100),

harga_beli decimal(10,0),

harga_jual decimal(10,0),

stok int(4)

);
 
 ![image](https://user-images.githubusercontent.com/101716699/169769983-506c78ab-d1b5-40e1-86cb-a351e4184ef9.png)

5.	Kemudian tambahkan data pada tabel data_barang.

 ![image](https://user-images.githubusercontent.com/101716699/169770321-22148faf-28d4-4018-957f-cec1f0b24708.png)

6.	Tampilkan field dan record tabel dengan query SELECT * FROM data_barang;

 ![image](https://user-images.githubusercontent.com/101716699/169770405-d7606bda-d421-4c04-aa91-ebf0a877f014.png)

7.	Membuat program CRUD (Create, Read, Update, Delete)
Buat folder lab8_php_database pada root directory web server (c:\xampp\htdocs)
 
![image](https://user-images.githubusercontent.com/101716699/169770513-949ce5aa-e913-404a-9b9d-127aa44159a5.png)

8.	Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:
http://localhost/lab8_php_database/ 
 
![image](https://user-images.githubusercontent.com/101716699/169770582-de0b3a6f-ad83-49c6-b85d-533fef7e4166.png)

9.	Membuat file koneksi dengan ekstension php dan beri nama dengan koneksi.php pada folder lab8_php_database.
 
![image](https://user-images.githubusercontent.com/101716699/169770625-24dafa46-53cc-4a45-b8c5-177d8e95d90f.png)

10.	Buka melalui browser untuk melakukan uji koneksi database, jika koneksi berhasil akan muncul pesan koneksi berhasil melalui perintah echo “koneksi berhasil”;
 
![image](https://user-images.githubusercontent.com/101716699/169770681-1814c74f-069f-4ef9-8901-4950dcead023.png)

11.	Disini saya akan mencoba dengan mengkombinasi antara CSS dan Bootstrap 5 yang telah saya simpan pada folder lab8_php_database
 
![image](https://user-images.githubusercontent.com/101716699/169770739-ff257973-d872-4adb-a9bb-654b1c7439dd.png)

12.	Membuat file Read dengan ekstension php dan beri nama dengan index.php pada folder lab8_php_database.
 
 ![image](https://user-images.githubusercontent.com/101716699/169770872-c017ced6-2666-47c6-aa8b-053e8aa52e3b.png)
 ![image](https://user-images.githubusercontent.com/101716699/169770897-319d18ba-9f06-4e09-b7ac-43a048ee19f7.png)
![image](https://user-images.githubusercontent.com/101716699/169770925-f78aa04a-b12d-46ab-9620-c01e2ccd4587.png)

Simpan dan buka pada browser dengan link localhost/lab8_php_database/index.php
 
![image](https://user-images.githubusercontent.com/101716699/169770973-67d43b73-eeca-4ff0-9013-1774dae4fb0b.png)

13.	Membuat file tambah data (create) dengan ekstension php dan beri nama dengan tambah.php pada folder lab8_php_database.
 
 ![image](https://user-images.githubusercontent.com/101716699/169771150-eaf54207-e79f-411f-88ba-25dafead60db.png)
 ![image](https://user-images.githubusercontent.com/101716699/169771174-40cacf23-ad1b-41b4-8565-fe4d06ee0d5c.png)
 ![image](https://user-images.githubusercontent.com/101716699/169771192-ba568b5b-2868-47de-b22e-53cd489e7868.png)
 ![image](https://user-images.githubusercontent.com/101716699/169771206-b676d714-3006-4158-a991-e17223315aef.png)

Simpan dan buka pada browser dengan klik tombol tambah barang atau dengan link localhost/lab8_php_database/tambah.php
 
![image](https://user-images.githubusercontent.com/101716699/169771447-127375f0-588e-4d07-8276-1a9973600f3a.png)

Saya mencoba melakukan penambahan barang seperti pada gambar diatas, kemudian simpan dan lihat hasilnya.
 
![image](https://user-images.githubusercontent.com/101716699/169771461-42938a84-7de8-4b19-bf60-1abecbf9e449.png)

14.	Membuat file ubah data (update) dengan ekstension php dan beri nama dengan ubah.php pada folder lab8_php_database.

![image](https://user-images.githubusercontent.com/101716699/169771957-32cd21e2-446f-4fb7-b91a-43e7505fb103.png)
 ![image](https://user-images.githubusercontent.com/101716699/169771979-81ce3d23-828e-47f4-be00-4b2b891af167.png)
 ![image](https://user-images.githubusercontent.com/101716699/169772000-0eb9fa71-0f5f-49ca-bf93-b13368ec73e5.png)
 ![image](https://user-images.githubusercontent.com/101716699/169772043-bdb5f60c-b1a2-48df-9e47-827c9a3cbd95.png)
![image](https://user-images.githubusercontent.com/101716699/169772079-ba6afdfe-70b3-4a51-85c1-247ca9185847.png)

Simpan dan buka pada browser dengan klik tombol ubah atau dengan link localhost/lab8_php_database/ubah.php
 
 ![image](https://user-images.githubusercontent.com/101716699/169772147-71893948-d958-4a61-aab5-e49574c05a53.png)

Disini saya melakukan perubahan data pada  harga barang dan stok barang, kemudian simpan dan lihat hasilnya.
 
![image](https://user-images.githubusercontent.com/101716699/169772208-c3d18cef-d3c5-4aef-beeb-0614af7f9155.png)

15.	Membuat file hapus data (delete) dengan ekstension php dan beri nama dengan hapus.php pada folder lab8_php_database.
 
![image](https://user-images.githubusercontent.com/101716699/169772260-58b0d5ff-ac66-4c7f-99b5-8165759b060a.png)

Simpan dan buka pada browser dengan klik tombol hapus atau dengan link localhost/lab8_php_database/hapus.php

![image](https://user-images.githubusercontent.com/101716699/169772378-69ed5baa-83cb-4d15-b689-d6d472d3e633.png)
 
Saya mencoba melakukan proses hapus pada data barang paling bawah, kemudian lihat hasilnya.
 
![image](https://user-images.githubusercontent.com/101716699/169772410-4bf66abb-df61-461d-b4c4-6f25385b4690.png)

