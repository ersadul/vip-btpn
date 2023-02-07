# Week-1
### Introduction to T-SQL
[![youtube](http://img.youtube.com/vi/YVwjBNV10K4/0.jpg)](http://www.youtube.com/watch?v=YVwjBNV10K4 "Virtual Internship Experience BTPN Syariah - Data Engineer - Video Learning 1")  
TSQL merupakan singkatan dari Transact-SQL yang merupakan extension dari SQL sendiri. Pada Data Engineer BTPNS salah satu teknik yang digunakan adalah TSQL. Maka dari itu pemahaman dasar dari teknologi ini adalah ilmu yang wajib dimiliki oleh peserta VIX BTPNS  
[Slide](files/slide_1.pdf)

### T-SQL Datatypes
Datatypes pada T-SQL tidak jauh berbeda dengan datatypes pada sql, pada modul ini, dijelaskan bahwa terdapat tiga tipe data yaitu: Numerik, Datetime, dan String.  
[PDF](files/Reading_1_TSQL_Data_Types.pdf)

### T-SQL Statement
Macam-macam statement, penjelasan mengenai setiap statement dan contoh implementasi statement:
<details>
<summary>Statement</summary>

- SELECT: menampilkan maupun mengambil sebuah data pada tabel.
	```  
	SELECT * FROM Customers;
	```  
- WHERE: memfilter hasil SELECT dengan mengekstrak record yang memenuhi persyaratan tertentu
	```
    SELECT kolom1, kolom2, … FROM nama_tabel WHERE kondisi;
    ```
- ORDER BY: mengurutkan result-set dalam pengurutan ‘ascending’ atau ‘descending
	```
    SELECT kolom1, kolom2, … FROM nama_tabel ORDER BY column ASC;
	SELECT nis, nama FROM siswa ORDER BY tahun_lahir DESC;
    ```
- INSERT INTO: menambahkan record baru ke dalam tabel.
	```
    INSERT INTO nama_tabel VALUES (nilai1, nilai2, nilai3, …)
    INSERT INTO nama_tabel (kolom1, kolom2) VALUES (nilai1, nilai2);
    ```
- UPDATE: memperbarui atau mengubah nilai suatu record berdasarkan kriteria tertentu.
	```
    UPDATE nama_tabel SET kolom1 = nilai1, kolom2 = nilai2, … WHERE kondisi;
    ```
- CREATE: membuat database atau tabel.
	```
    CREATE DATABASE namadatabase;
    ```
- DELETE: menghapus nilai suatu record berdasarkan kriteria tertentu.
	```
    DELETE FROM table_name WHERE condition;
    ```
- MIN: mendapatkan nilai terkecil dari suatu kolom.
	```
    SELECT MIN(nama_kolom) FROM nama_tabel WHERE kondisi;
    ```
- MAX: mendapatkan nilai terbesar dari suatu kolom.
	```
    SELECT MAX(nama_kolom) FROM nama_tabel WHERE kondisi;
    ```
- COUNT: mendapatkan jumlah hitungan record yang memenuhi suatu kriteria.
	```
    SELECT COUNT(nama_kolom) FROM nama_tabel WHERE kondisi;
    ```
</details>  

[PDF](files/Reading_2_TSQL_Statements.pdf)

### T-SQL Clause
Clause membantu untuk memfilter dan menganalisis data dengan cepat. Ketika kita memiliki sejumlah besar data yang disimpan dalam database, kita menggunakan clause untuk melakukan kueri dan mendapatkan data yang dibutuhkan oleh pengguna.  
[PDF](files/Reading_3_TSQL_Clause.pdf)

### Transaction Control
[![youtube](http://img.youtube.com/vi/U1iCOYASCFc/0.jpg)](http://www.youtube.com/watch?v=U1iCOYASCFc "Virtual Internship Experience BTPN Syariah - Data Engineer - Video Learning 2")  
Untuk menutup minggu pertama, peserta akan diperkenalkan dengan tools yang membedakan TSQL dan SQL yaitu Transaction Control. Transaction Control merupakan salah satu teknologi Data Engineering yang kerap digunakan untuk proses transaksi. Melacak, memperlihatkan, menghilangkan, dan menambahkan transaksi pada suatu tabel. Maka teknologi ini merupakan hal yang perlu diketahui oleh role expert Data Engineering BTPNS.  
[Slide](files/slide_2.pdf)

### Task week-1
[![youtube](http://img.youtube.com/vi/3KMjc3Y0lZc/0.jpg)](http://www.youtube.com/watch?v=3KMjc3Y0lZc "Virtual Internship Experience BTPN Syariah - Data Engineer - Task 1")  
Pada Task pertama ini, pengetahuan kalian akan diuji mengenai dasar dasar operasi database yaitu SQL seperti table operation, expressions, operators, dan CRUD table. Selain itu, kalian juga akan diuji mengenai pegetahuan dasar dari T-SQL seperti dasar dasar T-SQL dan Transaction Control.
