# Week-4
### SQL Server
[![youtube](http://img.youtube.com/vi/GCJezx1LMkM/0.jpg)](http://www.youtube.com/watch?v=GCJezx1LMkM "Virtual Internship Experience BTPN Syariah - Data Engineer - Video Learning 7")  
Salah satu tools yang digunakan oleh BTPNS adalah Microsoft SQL Server. Pada materi ini, peserta akan diperkenalkan pada konsep SQL dan database yang ada. Selain itu, peserta akan diberikan pengetahuan mengenai fitur dan tools yang ada pada Microsoft SQL Server. Hal ini dilakukan agar peserta familiar dengan Microsoft SQL server sebelum memahami lebih dalam konsep SSIS.
[Slide](files/slide_7.pdf)

### Microsoft SQL Server
Sebagai bentuk pemahaman lebih dalam mengenai Microsoft SQL server, peserta akan diberikan pengetahuan mengenai tools dan fitur yang ada pada Microsoft SQL server. Hal ini dilakukan agar peserta familiar dengan salah satu tools yang digunakan oleh BTPNS.  
[PDF](files/Reading_12_Microsoft_SQL_Server.pdf)

### SSIS Concept
[![youtube](http://img.youtube.com/vi/pIbMBt4i4cw/0.jpg)](http://www.youtube.com/watch?v=pIbMBt4i4cw "Virtual Internship Experience BTPN Syariah - Data Engineer - Video Learning 8")  
Peserta akan diperkenalkan dengan salah satu keunggulan dari Microsoft SQL server yaitu fitur SSIS dan ETL. Pada Video Learning ini peserta akan diberikan pengetahuan mengenai konsep SSIS dan menerapkan package ETL pada project Microsoft SQL Server. Hal ini dilakukan agar peserta memiliki pengetahuan lebih dalam mengenai Microsoft SQL Server.  
[Slide](files/slide_8.pdf)

### Final Task
[![youtube](http://img.youtube.com/vi/ULkCQgb7EJA/0.jpg)](http://www.youtube.com/watch?v=ULkCQgb7EJA "Virtual Internship Experience BTPN Syariah - Data Engineer - Task 5")   
Pada task ini kalian akan diuji pengetahuannya mengenai data engineer dengan cara membentuk sebuah laporan pengolahan data yang berbentuk PPT dari data yang telah disediakan. Kalian harus membuat power point yang memiliki 3 komponen yang diuji yaitu Objective, Eksplorasi data, membentuk Insight.

[Case](files/final_task.pdf):  
Seorang manajer di bank merasa terganggu dengan semakin banyak pelanggan yang meninggalkan layanan kartu kredit mereka. Mereka akan sangat menghargai jika seseorang dapat mengetahui profil pelanggan sehingga mereka dapat mengetahui pelanggan mana yang akan pergi sehingga mereka dapat secara proaktif mendatangi pelanggan untuk memberikan layanan yang lebih baik dan mengubah keputusan pelanggan ke arah yang berlawanan.

Dari Study Case diatas, bentuklah tiga jenis olahan data dalam bentuk power point:  
1. Business Objective  
2. Data Exploration
3. Insight Presentation
4. Kesimpulan dan Saran

Keterangan:  
Schema data: [Link](data/schema.csv)  
Data: [Link](data/)  
Source code: [Link](./ingest_data.ipynb)  
PPT Final Task: [Link](https://docs.google.com/presentation/d/16j7dSE3-BWhM5xaA3orOINfU6HHE68vEIU01xBjSMjk/edit?usp=sharing)  
PPT Comparison: [Link](files/comparison_document.pdf)




<details>
<summary>Tahapan Pengerjaan Final Task</summary>

**HINT Task 5**  
Pada task 5, kalian ditugaskan untuk membentuk power point Insight Presentation yang setidaknya memiliki 4 komponen yaitu Business Objective, Data Exploration, Insight Visualization, dan Kesimpulan dan Saran.
- Kalian akan dinilai berdasarkan Kesimpulan dan Saran dan data yang kalian olah untuk mendukung kesimpulan dan saran yang kalian bentuk.
- Format dan keterangan poin tugas yang harus kalian bentuk : [Link](https://docs.google.com/presentation/d/1nJ3eB9ufZHbpk_DzTpvuJrTApsB8Qrrl/edit?usp=sharing&ouid=101984988987283973706&rtpof=true&sd=true)
- Keterangan data yang akan kalian akses :  

Database Customer data history = data historical customer sampai saat ini
Keterangan kolom:
Clientnum : nomor id client  
Idstatus   : keterangan status customer  
Customer_age : umur customer  
Gender : jenis kelamin customer  
Dependent count : yang menjadi tanggungan customer  
Educationid : keterangan jenjang Pendidikan customer  
Maritalid : status pernikahan customer  
Income_category : ketgori penghasilan customer  
Card_categoryid : jenis kartu kredit customer  
Month_on_book : periode berhubungan dengan bank  
Relationship_in_count : total product yang dipegang customer  
Months_inactive_in_12_month : jumlah bulan tidak aktif selama 12 bulan terakhir  
Contacts_Count_12_mon : total dihubungi bank dalam 12 bulan terakhir  
Credit limit : limit credit  
Total Revolving Balance on the Credit Card : total saldo bergulir pada kartu kredit  
Avg_open_to_buy : membeli dengan kartu kredit dalam 12 bulan terakhir  
Total_trans_amt : jumlah transaksi  
Total_trans_ct : frekuensi transaksi  
Avg_utilization_ratio : rata rata rasio penggunaan kartu kredit  
Database Category_db = data category dari layanan kartu kredit yang digunakan  
Database Education_db = data tingkat Pendidikan customer  
Database Marital_db = data status pernikahan customer  
Database Status_db = data keterangan status customer existing / attired  

- Untuk pengolahan data, gunakan software open source seperti Microsoft SQL Server Developer, MySQL, atau PostgreSQL.
- submit tugas dalam bentuk power point dengan format penamaan : [NAMA]_TASK_5_DATA_ENGINEER_VIX_BTPNS
</details>
