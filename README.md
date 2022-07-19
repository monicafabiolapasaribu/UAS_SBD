# UAS_SBD

### Nama  : Monica Fabiola Pasaribu
### Kelas : TI.20.D1
### NIM   : 312010083

### Membuat Sistem Informasi Klinik.
### Tampilan Login.
![image](https://user-images.githubusercontent.com/101724604/179496454-438340a0-8f39-49a7-ba1c-b3b8c3e86808.png)

### Tampilan Data Pasien.
![image](https://user-images.githubusercontent.com/101724604/179496787-53ce9913-20ff-45fb-9b9d-f10b2c6ce914.png)

Dalam tabel pasien saya bisa menambahkan, mengedit dan menghapus data. Contohnya sebagai berikut :

### Tampilan Menambah Pasien.
![image](https://user-images.githubusercontent.com/101724604/179678831-0484e241-d5f1-4abf-94ae-101bddc96d07.png)

![image](https://user-images.githubusercontent.com/101724604/179678492-0c101272-cfe5-46f9-8b1e-7ff9ba475aa3.png)

### Tampilan Edit Pasien
![image](https://user-images.githubusercontent.com/101724604/179679432-8bc34d12-1f6e-4db6-bed0-d60f94d0e874.png)

![image](https://user-images.githubusercontent.com/101724604/179679924-81df9f09-59e0-44d5-9e5e-b4aa8e261da0.png)

### Tampilan ubah pasien
![image](https://user-images.githubusercontent.com/101724604/179680323-4a9ad776-bfcd-4a03-a6de-5f3670c88d32.png)

![image](https://user-images.githubusercontent.com/101724604/179680594-969790b1-2cb0-4b14-b357-02a645d3f7eb.png)

### Tampilan Data Dokter
![image](https://user-images.githubusercontent.com/101724604/179681024-13107bca-2466-4096-954f-3982caa71916.png)

Data Dokter juga diberikan perintah tambah,hapus dan juga edit

### Tampilan Data Obat
![image](https://user-images.githubusercontent.com/101724604/179681584-cb62c2f6-523d-4665-b5ae-58b089a91390.png)

Didalam modul data obat saya memberikan Trigger create table log_obat(id_log int(100) auto_increment primary key, id_obat int(10), nama_obat_lama varchar(100), nama_obat_baru varchar(100), waktu date not null)

create trigger update_nama_obat before update on obat for each row insert into log_obat set id_obat=old.id_obat, nama_obat_lama = old.nama_obat, nama_obat_baru=new.nama_obat, waktu = now();

![image](https://user-images.githubusercontent.com/101724604/179682146-c6d9e622-4abf-417c-8d5c-3f5a0d0937db.png)





