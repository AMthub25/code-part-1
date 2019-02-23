Membuat database =>
	create database latihan;
Perintah USE, untuk masuk kedalam database yang dibuat=>
	USE latihan;
Menampilkan basisdata yang ada pada server database MySQL;
	show databases;
Menghapus database=>
	DROP DATABASE latihan;
Membuat table =>
	CREATE TABLE biodata (nama VARCHAR(50), alamat TEXT);
Menampilkan struktur table yang dibuat =>
	desc biodata;
Menambah Field =>
	ALTER TABLE biodata ADD COLUMN id int(10) FIRST;
Mengubah namma Field =>
	ALTER TABLE biodata CHANGE alamat alamat_jalan VARCHAR(200);
Mengubah Tipe Data =>
	ALTER TABLE biodata MODIFY alamat_jalan TINYTEXT;
Menghapus Field =>
	ALTER TABLE biodata DROP alamat_jalan;
Menambah index atau key =>
	ALTER TABLE biodata ADD PRIMARY KEY(id);
Menghapus Primery Key =>
	ALTER TABLE biodata DROP PRIMARY KEY;

