# Writing-Week-6
Writing Test Week 2 Back End


# Writing-Week-6 / Writing-Week-2-BackEnd
**Senin, 31 Oktober 2022**


### BackEnd Development

#### Introduction
- BackEnd adalah bagian belakang layar dari sebuah website atau aplikasi, yang secara teknologi backend merupakan sisi server dari sebuah website atau aplikasi
- Back-End Developers dapat memilih banyak bahasa pemrograman dan framework, tergantung jenis aplikasi apa yang akan dibuat. 
Contoh dari bahasa pemrogramannya :
C
Java
C++
Python
Javascript
Rust
Golang

#### Servers : The Machinery
- Server adalah sebuah jaringan komputer yang menyediakan jenis layanan/service tertentu pada komputer lain. yang biasanya didukung dengan prosesor yang bersifat scalable dan RAM yang besar
- Server dilengkapi dengan sistem operasi khusus yang disebut sebagai Sistem Operasi Jaringan
- Server bekerja atas permintaan dari sebuah klien


#### Databases
- Database adalah kumpulan data yang disimpan secara sistematis di dalam komputer yang dapat diolah dan dimanipulasi atau sebagai gudang penyimpanan data untuk diolah lebih lanjut
Relational
Non-Relational


#### API
- API adalah sekumpulan intruksi program dan protokol yang digunakan untuk membangun aplikasi perangkat lunak
- Rest API sebagai penghubung/perantara antara Front End dengan Back End untuk saling bertukar informasi(request dan response)


#### MERN Stack
- MERN adalah salah satu kombinasi teknologi antara Front End dan Back End untuk membuat aplikasi website
- MERN adalah singkatan dari MongoDB, Express, React, dan NodeJS. Teknologi Full-stack yang menggunakan 1 bahasa yaitu Javascript
- Beberapa alasan mengapa menggunakan MERN stack :
Segala kegiatan pengembangan menggunakan bahasa Javascript
Mendukung arsitektur MVC (Model View Controller) untuk membuat proses pengembangan lebih lancar dan terstruktur
Dengan menggunakan Javascript, maka developer hanya perlu menguasai Javascript dan JSON
Open source framework dengan dukungan komunitas yang besar dan baik

- Beberapa perusahaan yang menggunakan MERN Stack
ebay
Trello
PayPal
UBER
Netflix
Walmart
Linkedin
Medium




### Database

#### Introduction
- Database adalah kumpulan informasi yang disimpan dalam komputer secara sistematik dan saling berelasi
- Database merupakan sekumpulan tabel yang berisikan informasi untuk diolah yang kemudian data tersebut bisa digunakan didalam sebuah sistem
- Membuat database diperlukan software DBMS(Databases Management System)

#### Database Management System
- DBMS adalah software yang dapat digunakan oleh user untuk berkomunikasi dengan data yang ada dalam media penyimpanan
- Tipe utama pada Database management system antara lain Hierarchical Network, Relational, Non Relational, dan Object Oriented


#### Istilah pada Database
Table
- Table adalah kumpulan value yang dibangun oleh baris dan kolom, yang didalamnya berisikan atribut dari sebuah data
Field
- Field adalah kolom dari sebuah tabel dimana masing-masing field memiliki tipe data masing-masing
Record
- Record merupakan kumpulan nilai yang saling terkait, yang merupakan isi dari sebuah tabel
SQL
- SQL atau Structured Query Language merupakan suatu bahasa yang digunakan untuk mengakses databases
- Membuat, menampilkan, dan menghapus data didalam database
- Mengatur “Permission” (siapa saja yang bisa mengakses data)
- Membuat dan menghapus database
DDL
- DDL merupakan kumpulan perintah SQL yang digunakan untuk membuat, mengubah, dan menghapus struktur dan definisi metadata dari objek-objek database
‘CREATE TABLE “nama tabel’
ALTER
- Alter digunakan untuk mengubah struktur dari tabel yang ada, seperti untuk menambahkan atau menghapus kolom
- Membuat atau menghapus primary key, mengubah jenis kolom yang ada, juga mengubah kolom atau nama tabel
‘ALTER TABLE nama_table ADD Primary key(nama_field)’
DROP
- Drop digunakan untuk menghapus database, tabel, dan view atau index
‘DROP DATABASE Nama_Database’
DML (Data Manipulation Language)
SELECT
Perintah SELECT digunakan untuk menyeleksi data berdasarkan syarat yang diberikan. Dengan menggunakan SELECT record dalam tabel tertentu yang berjumlah ribuan bahkan jutaan dapat ditampilkan
‘SELECT * FROM nama_tabel’
INSERT
Insert digunakan untuk memasukkan data ke kolom-kolom yang terdapat pada tabel/view
‘INSERT INTO nama_table VALUES (value1, value2,... , valueN)’
Where, And, Or, Not, Like
‘WHERE condition1 AND condition2 OR condition3 NOT condition4’
UPDATE
Update digunakan untuk melakukan editing pada isi dari kolom yang dipilih untuk memperbaiki data lama/terjadi kesalahan
‘UPDATE nama_table SET nama_kolom = “data baru” WHERE id = 1;’
DELETE
Delete digunakan untuk menghapus data dalam tabel yang menjadi target
‘DELETE FROM nama_tabel WHERE condition;’
DCL (Data Control Language)
GRANT
Grant digunakan untuk memberikan hak akses pada user
REVOKE
Revoke digunakan untuk mencabut hak akses yang telah diberikan pada user
Database Relationships
- Database relationships adalah relasi atau hubungan antara beberapa tabel dalam bahasa yang kita miliki
- Relasi antar tabel dihubungkan oleh Primary Key dan Foreign Key
- Primary Key adalah atribut yang tidak hanya mengidentifikasi secara unik suatu kejadian, tetapi juga mewakili setiap kejadian suatu entitas (NIM Mahasiswa)
- Foreign Key adalah atribut yang melengkapi relationship dan menunjukan hubungan antara tabel induk dengan tabel anak
##### Tipe Database 
One to One Relationship adalah hanya satu dari masing-masing entity yang saling berhubungan atau berelasi
One to Many and Many to One Relationship adalah dimana satu atribut dari satu entity bisa berhubungan dengan dua atau lebih atribut dari entity yang lain
Many to Many Relationship adalah relasi antar table dimana banyak dari masing-masing record tersebut memiliki banyak relasi ke tabel lainnya
SQL Table Join
Join adalah penggabungan tabel yang dilakukan melalui kolom tertentu yang memiliki nilai terkait untuk mendapatkan satu set data dengan informasi lengkap
- Inner Join adalah menampilkan data hanya yang sesuai di kedua tabe;
- Left Join adalah menampilkan semua data sebelah kiri dari tabel yang di joinkan dan menampilkan data sebelah kanan yang cocok dengan kondisi join
- Right Join adalah menampilkan semua data sebelah kanan dari tabel yang di joinkan dan menampilkan data sebelah kiri yang cocok dengan kondisi join
No SQL
- Database NoSQL adalah database yang tidak memiliki perintah SQL. Konsep penyimpanannya semi struktural atau tidak struktural dan tidak harus memiliki relasi seperti pada tabel di MySQL
- Tujuan dari NoSQL adalah untuk model data spesifik dan memiliki skema fleksibel dalam mengembangkan aplikasi modern seperti aplikasi yang bersifat real time
##### Kelebihan NoSQL dibandingkan Relasional Database
NoSQL bisa menampung data yang terstruktur, semi terstruktur dan tidak terstruktur
Menggunakan OOP dalam pengaksesan/manipulasi data
NoSQL tidak mengenal skema tabel yang kaku
Document Database
- Document adalah salah satu dari beberapa model database NoSQL yang artinya penyimpanan data dan proses manipulasinya dalam bentuk objek dokumen seperti penerapan pada pemrograman format JSON
### MySQL - Basic


#### Database
- Database adalah kumpulan terorganisir dari informasi terstruktur, atau data, biasanya disimpan secara elektronik dalam sistem komputer. 
- Sebuah database biasanya dikendalikan oleh sistem manajemen database (DBMS). Bersama-sama, data dan DBMS, bersama dengan aplikasi yang terkait dengannya, disebut sebagai sistem basis data, sering disingkat menjadi basis data saja.

#### DBMS (Database Management System)
- Sebuah database biasanya memerlukan program perangkat lunak database yang komprehensif yang dikenal sebagai sistem manajemen database (DBMS). 
- Sebuah DBMS berfungsi sebagai antarmuka antara database dan pengguna akhir atau program, memungkinkan pengguna untuk mengambil, memperbarui, dan mengelola bagaimana informasi diatur dan dioptimalkan. 
- DBMS juga memfasilitasi pengawasan dan pengendalian basis data, memungkinkan berbagai operasi administratif seperti pemantauan kinerja, penyetelan, serta pencadangan dan pemulihan.

#### MySQL
- MySQL adalah sistem manajemen basis data relasional open source berbasis SQL. Itu dirancang dan dioptimalkan untuk aplikasi web dan dapat berjalan di platform apa pun. 
- Sebagai persyaratan baru dan berbeda muncul dengan internet, MySQL menjadi platform pilihan untuk pengembang web dan aplikasi berbasis web.


#### Tipe Data SQL
Number : data yang berisi kumpulan karakter angka
Int : Tipe data untuk angka bulat (1, 66, 33)
Float : Tipe data untuk angka menggunakan koma (3,41)
Decimal : Tipe data angka pecahan(desimal), dimana jumlah angka pecahan (angka dibelakang koma) sudah ditentukan dari awal (decimal (4,1) = -999,9)
String : tipe data berupa kumpulan karakter termasuk karakter simbol
Char : tipe data string dengan panjang yang sudah ditentukan dan memori sesuai panjang yang didefinisikan (char(5), char(17))
Varchar : Tipe data string dengan penyimpanan karakter yang fleksibel maksimal 255 (varchar(80), varchar (150), varchar(255))
Text : Tipe data string dengan penyimpanan yang lebih panjang dari varchar (text)
Enum : Tipe data yang khusus untuk kolom dimana nilai datanya sudah ditentukan sebelumnya (enum(‘aku’,’mereka’)
Boolean : Tipe data ini hanya menyimpan 2 tipe data yaitu TRUE dan FALSE, dan dapat di convert menjadi int dengan representasi TRUE = 1, dan FALSE = 0
Data Time : Tipe ini merupakan tipe data untuk menyimpan tanggal dan waktu
Date : tipe data untuk menyimpan tanggal (‘CCYY-MM-DD’)
Datetime : tipe data untuk menyimpan tanggal dan waktu (‘CCYY-MM-DD hh-mm-ss’)
Time : tipe data untuk menyimpan waktu (‘hh-mm-ss’)
Timestamp : tipe data untuk menyimpan tanggal dan waktu dan juga UTC nya atau timezone (‘CCYY-MM-DD hh:mm:ss +00:00')
Tipe data lainnya
Default : Tipe data untuk set default value jika tidak di assign dengan value
NULL : tipe data kosong atau tipe data yang belum di assign dengan value/data





**Selasa, 1 November 2022**
### MySQL Lanjutan

#### Relations di SQL
One to Many
- Paling sering digunakan
- Satu baris dalam tabel dapat memiliki beberapa baris di table relasinya
Many to Many
- Digunakan ketika kedua tabel yang berelasi dapat memiliki beberapa baris ditabel relasinya
One to One
- Sangat jarang digunakan 
- Diimplementasikan dengan cara yang sama seperti One to Many tetapi dengan kondisi tambahan(foreign key merupakan primary key)


#### Database Normalization
Pengertian Database Normalization
- Merupakan teknik analisis data yang mengorganisasikan atribut-atribut data dengan cara mengelompokkan sehingga terbentuk entitas yang non-redundant, stabil, dan fleksibel
Tujuan Database Normalization
Menghilangkan redudansi data pada database
Memudahkan jika ada perubahan struktur table database
Memperkecil pengaruh jika ada perubahan dari stuktur table database
Efek jika tidak melakukan Database Normalization
INSERT Anomali : Situasi dimana tidak memungkinkan memasukkan beberapa jenis data secara langsung di database.


DELETE Anomali : Penghapusan data yang tidak sesuai dengan yang diharapkan, artinya data yang harusnya tidak terhapus mungkin ikut terhapus.


UPDATE Anomali : Situasi dimana nilai yang diubah menyebabkan inkonsistensi database, dalam artian data yang diubah tidak sesuai dengan yang diperintahkan atau yang diinginkan.

Bentuk Database Normalization
First Normal Form (1NF)
Menghilangkan multiple value pada sebuah kolom table database
Sebuah table memenuhi kaidah 1NF jika :
Setiap kolom bernilai tunggal (single value)
Setiap kolom memiliki nama yang unik
Urutan penyimpanan data tidak menjadi masalah
Second Normal Form (2NF)
Harus sudah dalam bentuk 1NF untuk mendapatkan 2NF
Menghapus beberapa subset data yang ada pada tabel dan menempatkan mereka pada tabel terpisah.
Third Normal Form (3NF)
Menghilangkan seluruh atribut atau field yang tidak berhubungan dengan primary key. Dengan demikian tidak ada ketergantungan transitif pada setiap kandidat key.
	Masih ada banyak bentuk database normalisasi, diantaranya :
EKNF
BCNF
4NF
5NF
DKNF
6NF


#### Keys di SQL
Super Key 
- Kumpulan dari satu atau lebih dari satu key yang dapat digunakan untuk mengidentifikasi record secara unik dalam sebuah tabel.
- Super Key adalah superset dari Candidate Key.

Candidate Key
- kumpulan satu atau lebih fields/columns yang dapat mengidentifikasi record secara unik dalam tabel.
- Bisa jadi ada beberapa Candidate Keys di dalam satu tabel
- Setiap Candidate Key bisa digunakan sebagai Primary Key.
- Candidate Key adalah super key yang tidak mempunyai value yang berulang
Primary Key
- kumpulan satu atau lebih fields/columns dari sebuah tabel yang secara unik mengidentifikasi sebuah record dalam tabel database.
- Valuenya tidak boleh berupa null ataupun duplicate value.
- Hanya boleh salah satu Candidate Key yang bisa menjadi Primary Key.

Alternate Key
- key yang bisa digunakan menjadi primary key.
- Pada dasarnya, Key ini merupakan candidate key yang tidak dijadikan  primary key.

Unique Key
- Kumpulan dari satu atau lebih fields/columns di sebuah table database yang secara unik mengidentifikasi sebuah record dalam table database tersebut.
- Hampir sama dengan Primary key, namun value dari Unique Key bisa berupa satu buah null value di dalam sebuah table database, dan Unique Key tidak bisa memiliki duplicate values

Foreign Key
- Field di sebuah table database yang menjadi Primary Key di table database lain.
- Value dari Foreign key bisa menerima multiple null dan duplicate values.


#### Join Multiple Tables
Inner Join
- Semua baris akan diambil dari kedua table yang akan di JOIN, selama columns cocok dengan kondisi yang sudah di tentukan.
- Memungkinkan baris dari salah satu tabel muncul di hasil jika dan hanya jika kedua tabel memenuhi kondisi yang ditentukan dalam klausa ON.

Left Join
- Pada JOIN ini, semua records dari table di sisi kiri JOIN statement akan di pilih.
- Jika record yang di pilih dari table kiri tidak memiliki record yang cocok pada table JOIN yang kanan, maka record tersebut masih dipilih, dan kolom pada table yang kanan akan bernilai NULL. 

Right Join
- Pada JOIN ini, semua records dari table di sisi kiri JOIN statement akan di pilih, bahkan jika table di sebelah kiri tidak memiliki record yang cocok.


#### Aggregate Functions
Max
- fungsi mengembalikan nilai terbesar dari kolom yang dipilih.
Min
- fungsi mengembalikan nilai terkecil dari kolom yang dipilih.

SUM
- fungsi mengembalikan jumlah total kolom numerik.

Count
- fungsi mengembalikan jumlah baris yang cocok dengan kriteria yang ditentukan.

AVG
- fungsi mengembalikan nilai rata-rata kolom numerik

UNION
- Digunakan untuk menggabungkan kumpulan hasil dari dua atau lebih pernyataan SELECT.
- Setiap pernyataan SELECT dalam UNION harus memiliki jumlah kolom yang sama
- Kolom juga harus memiliki tipe data yang serupa
- Kolom dalam setiap pernyataan SELECT juga harus dalam urutan yang sama

GROUP BY
- Mengelompokkan baris yang memiliki nilai yang sama ke dalam baris ringkasan
- Sering digunakan dengan fungsi agregat untuk mengelompokkan kumpulan hasil dengan satu atau lebih kolom.

Having
- HAVING ditambahkan ke SQL karena kata kunci WHERE tidak dapat digunakan dengan aggregate functions.

LIKE & Wildcards
- Operator LIKE digunakan dalam klausa WHERE untuk mencari pola tertentu dalam kolom.
- Karakter wildcard digunakan untuk menggantikan satu atau lebih karakter dalam sebuah string.












**Rabu, 2 November 2022**
### Authentication & Authorization in Express


#### Authentication
- Otentikasi bergantung pada satu atau lebih faktor untuk memverifikasi identitas, dan faktor-faktor ini datang dalam tiga jenis utama:
Pengetahuan adalah sesuatu yang Anda ketahui, seperti nama pengguna dan kata sandi.
Kepemilikan adalah sesuatu yang Anda miliki, seperti kartu keamanan atau perangkat seluler
Inheren adalah sesuatu tentang Anda, yang umumnya mengacu pada data biometrik seperti sidik jari.

#### Authorization
- Otorisasi sangat penting untuk keamanan web, dan bertanggung jawab atas segala hal mulai dari mencegah pengguna memodifikasi akun satu sama lain, melindungi aset back-end dari penyerang, hingga memberikan akses terbatas ke layanan eksternal.
- Otorisasi yang baik akan memungkinkan Anda membatasi pengguna dan layanan untuk hak istimewa yang mereka butuhkan; hanya karena seorang pengguna berwenang untuk mengelola satu grup tidak berarti mereka harus dapat mengelola semua grup, misalnya.


#### Encryption
- Salah satu alat inti untuk menegakkan otentikasi dan otorisasi adalah enkripsi. Enkripsi adalah proses mengubah data menjadi format yang tidak dapat dibaca kecuali Anda memiliki kunci yang benar untuk mendekripsinya. Enkripsi datang dalam dua jenis utama:
Enkripsi simetris
Enkripsi asimetris


#### Authentication Details
- Tanggapan terhadap perintah autentikasi dapat dikategorikan ke dalam:
Berbasis Pengetahuan: “Sesuatu yang Anda Ketahui”
Berbasis Kepemilikan: “Sesuatu yang Anda Miliki”
Berbasis Inheren: "Sesuatu Anda"


#### Session VS Cookie VS LocalStorage
Web Session
- Sesi web mengacu pada serangkaian interaksi pengguna selama jangka waktu tertentu. Data sesi disimpan di sisi server dan dikaitkan dengan ID sesi.
- Pikirkan sesi sebagai memori jangka pendek untuk aplikasi web. Pada latihan berikutnya, kami akan menjelaskan di mana pengidentifikasi sesi ini disimpan sehingga browser (klien) dapat terus mengambil data sesi yang sama di antara pemuatan halaman yang berbeda.


#### Session & Cookie
- Agak kikuk bagi klien untuk mengingat untuk menempelkan ID sesi ke setiap permintaan. Karena itu, ID sesi sering disimpan di sisi klien dalam bentuk cookie sesi.
- Cookie adalah potongan kecil data — file teks berukuran maksimal 4kb — browser menyimpan yang secara otomatis dikirim dengan permintaan HTTP ke aplikasi web. Cookie disetel oleh header respons HTTP dalam pasangan nilai kunci:


#### Cookie Security
- Cookie sering kali menyimpan informasi sensitif, terutama saat digunakan dalam manajemen sesi. Cookie juga digunakan untuk menyimpan preferensi atau riwayat pribadi pengguna, yang juga harus tetap aman.
- Atribut HttpOnly untuk header Set-Cookie memastikan bahwa data cookie tidak dapat diakses oleh skrip yang menjalankan sisi klien. Ini membantu mencegah serangan Cross-Site Scripting (XSS) yang mencoba mencuri cookie sesi dan mengambil alih sesi korban, yang sangat umum.
























**Jum’at, 4 November 2022**
### Sequelize


#### Pengertian Sequelize
- Sequelize adalah ORM (Object Relational Mapping) Node JS yang berbasis promise. Sequelize mendukung sebagian besar relational Database seperti MySQL, PostgresQL, MariaDB, SQLite dan Miscrosoft SQL Server.
- Dengan fitur fitur di Sequelize, kita bisa mengelola dan mengatur data di database kita dengan cepat, dan efisien.


#### ORM
- ORM adalah suatu metode/teknik pemrograman yang digunakan untuk mengkonversi data dari lingkungan bahasa pemrograman berorientasi objek (OOP) dengan lingkungan database relational. 


#### Generate Sequelize
Sequelize init
- Pertama kita perlu melakukan inisialisasi di project kita terlebih dahulu agar dapat melakukan generate code
Setting Database
Generate Model
Generate Seed


#### Membuat CRUD dengan Express dan Sequelize
- Setelah Model tersedia, maka model tersebut bisa kita gunakan untuk membuat CRUD.
- Beberapa endpoint RESTFul :
Get All Todos
Get Todo Detail By Id
Create New Todo
Update Todo By Id
Delete Todo


