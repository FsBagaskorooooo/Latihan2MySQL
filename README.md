# MySQL
# Praktikum 1

### Membuat DDL Script berdasarkan skema ERD tersebut diatas dan Jalankan script DDL tersebut pada DBMS MySQL

#
### Data Model Mapping
1. Mahasiswa (nim, nama, jenis_kelamin, tgl_lahir, jalan, kota, kodepos, no_hp, kd_ds)
2. Dosen (kd_ds, nama)
3. Matakuliah (kd_mk, nama, sks)
4. JadwalMengajar (kd_ds, kd_mk, hari, jam, ruang)
5. KRSMahasiswa (nim, kd_mk, kd_ds, semester, nilai)
# 

1. Membuat Database Latihan3

Pertama kita buat terlebih dahulu databasenya dengan perintah seperti dibawah

![s1](https://user-images.githubusercontent.com/130354090/232716201-000083d9-8b95-4589-93a7-2712b8725485.png)

Setelah kita buat lalu gunakan databasenya dengan perintah seperti dibawah

![s2](https://user-images.githubusercontent.com/130354090/232716653-587eddce-7894-4b58-861a-3d1853047a41.png)

2. Membuat Tabel dosen

Lalu kita membuat tabel dari entitas dosen dengan perintah seperti dibawah

![s3](https://user-images.githubusercontent.com/130354090/232718670-d569ee18-e927-41d6-8367-6a5340be94e2.png)

3. Membuat Tabel mahasiswa

Selanjutnya kita buat tabel dari entitas mahasiswa beserta atributnya dengan perintah seperti dibawah

![s4](https://user-images.githubusercontent.com/130354090/232719297-1d398c0c-82a0-4994-8804-7ce04223f878.png)

Dan Tabelnya akan seperti ini

![s5](https://user-images.githubusercontent.com/130354090/232719624-05a5a741-9fd1-427e-ba50-13997bda55df.png)

4. Membuat Tabel mata_kuliah

Kita buat lagi tabel dari entitas mata_kuliah dengan pertintah seperti dibawah

![s6](https://user-images.githubusercontent.com/130354090/232720311-70af07f6-fb54-491c-9ecd-4b9b82e79b28.png)

Maka outputnya akan seperti ini

![s7](https://user-images.githubusercontent.com/130354090/232720362-051444d4-70b9-4301-add9-3dbd9b264d31.png)

5. Membuat Tabel jadwal_mengajar

Selanjutnya kita akan membuat tabel dari jadwal_mengajar dengan perintah seperti dibawah

![s8](https://user-images.githubusercontent.com/130354090/232720693-e336a3cd-b6c1-4ea0-a9e5-5ecd635c6cc8.png)

Dan outputnya akan seperti dibawah ini

![s9](https://user-images.githubusercontent.com/130354090/232720792-79a4f214-60ef-4a35-abe9-9e25016c578e.png)

6. Membuat Tabel krs_mahasiswa

Dan yang terakhir kita akan membuat tabel untuk krs_mahasiswa dengan perintah seperti dibawah

![s10](https://user-images.githubusercontent.com/130354090/232721129-62a601e4-f0ec-4b76-8813-fea1d7ad0bb4.png)

Dan outputnya akan seperti ini

![s11](https://user-images.githubusercontent.com/130354090/232721230-a938be76-0916-486c-9df8-8a1e54e41b76.png)

## DDL Script

![code](https://user-images.githubusercontent.com/130354090/232725660-5b72f954-b486-4a2c-aa05-8f8a1849d87b.png)

# Praktikum 2

1. Isi Data Pada Table Tersebut Sebanyak Minimal 5 Record Data.

Petama-tama kita isi 5 data mahasiswa yang sudah ditentukan kedalam tabel dengan perintah seperti dibawah

![s12](https://user-images.githubusercontent.com/130354090/232726659-14d606a0-db2e-421e-96b6-21340c73c6fb.png)

Maka output tabelnya akan seperti dibawah ini

![s13](https://user-images.githubusercontent.com/130354090/232726812-04997012-bb90-45c5-875d-c41d66991217.png)

2. Mengubah Data Tanggal Lahir Mahasiswa

Selanjutnya kita akan mengubah tanggal lahir mahasiswa bernama ari menjadi 1979-08-31 dengan perintah seperti dibawah ini

![s14](https://user-images.githubusercontent.com/130354090/232727421-4ea64560-a273-4b5e-a529-e13b16ec0bbf.png)

Dan hasil outputnya bisa dilihat dibawah ini

![s15](https://user-images.githubusercontent.com/130354090/232727473-63b21095-33bb-4f5a-94bd-3db38942fa7b.png)

3. Menampilkan Satu Baris / Record Data Yang Telah Diubah Tadi Yaitu Record Dengan Nama Ari Saja

Lalu kita akan menampilkan hanya satu data mahasiswa saja dengan perintah dan output seperti dibawah

![s16](https://user-images.githubusercontent.com/130354090/232728235-64fc86c7-0593-4794-9998-6975d90668ef.png)

4. Menghapus Mahasiswa yang bernama Dina! 

Selanjutnya kita akan mencoba menghapus data mahasiswa bernama Dina dengan perintah seperti dibawah

![s17](https://user-images.githubusercontent.com/130354090/232728692-d40dbec4-0961-44c7-8276-93b33b3fb50d.png)

Bisa kita lihat output dibawah bahwa data mahasiswa bernama Dina berhasil dihapus

![s18](https://user-images.githubusercontent.com/130354090/232728724-9ac06836-6973-4cec-8bfa-eebf57cf6188.png)

5. Menampilkan Record Atau Data Yang Tanggal Kelahirannya Lebih Dari Atau Sama Dengan 1996-1-2

Selanjutnya kita akan mencoba menampilkan dengan tanggal lahir lebih atau sama dengan 1996-01-02 dengan perintah seperti dibawah

![s23](https://user-images.githubusercontent.com/130354090/232731191-51720650-3420-498c-8cdb-f9ac175bfd4c.png)

6. Menampilkan Semua Mahasiswa Yang Berasal Dari Bekasi Dan Berjenis Kelamin Perempuan 

Kali ini kita akan mencoba menampilkan data mahasiswa yang berasal dari bekasi dan berjenis kelamin perempuan dengan perintah
seperti dibawah

![s19](https://user-images.githubusercontent.com/130354090/232732100-c6fd82c5-e022-4130-8fc3-eec0dacbc638.png)

7. Menampilkan Semua Mahasiswa Yang Berasal Dari Bekasi Dengan Kelamin Laki-Laki Atau Mahasiswa Yang Berumur Lebih Dari 22 Tahun Dengan Kelamin Wanita

Lalu kita akan mencoba dengan perintah seperti dibawah ini

![s20](https://user-images.githubusercontent.com/130354090/232732945-8bbf0459-bf23-4a6b-855a-dcabcafeb768.png)

8. Menampilkan Data Nama Dan Alamat Mahasiswa Saja Dari Tabel

Selanjutnya kita akan menampilkan hanya nama dan alamat dari mahasiswa dengan perintah seperti dibawah 

![s21](https://user-images.githubusercontent.com/130354090/232733493-70bb2078-6a1c-4181-92ce-dada7ad7997a.png)

9. Menampilkan Data Mahasiswa Terurut Berdasarkan Nama

Dan terakhir kita akan mencoba menampilkan data mahasiswa berurut berdasarkan nama mahasiswanya dengan perintah seperti dibawah

![s22](https://user-images.githubusercontent.com/130354090/232734141-9ff54618-a65c-4a59-9ec7-49aad90186fa.png)

## Evaluasi Dan Pertanyaan

### 1.	Apa bedanya penggunaan BETWEEN dan penggunaan operator >= dan <= ? (misal: tgl_lahir BETWEEN '1990-10-10' AND '1992-10-11') (misal: tgl_lahir >= '1990-10-10' AND tgl_lahir <= '1992-10-11')

Penggunaan BETWEEN dan penggunaan operator >= dan <= pada umumnya memiliki hasil yang sama, yaitu menampilkan data yang memenuhi kondisi yang diberikan. Namun, ada beberapa perbedaan antara keduanya:

•	Penggunaan BETWEEN dapat membuat kode SQL lebih mudah dibaca, terutama jika kita ingin memeriksa rentang nilai. Sebaliknya, penggunaan operator >= dan <= dapat membuat kode SQL terlihat lebih rumit.

•	BETWEEN termasuk kedua nilai batas (termasuk nilai minimum dan maksimum), sedangkan operator >= dan <= hanya termasuk salah satu nilai batas. Dalam kasus tanggal, contohnya, BETWEEN '1990-10-10' AND '1992-10-11' akan mencakup data yang lahir pada tanggal 10 Oktober 1990 dan 11 Oktober 1992. Namun, jika kita menggunakan operator >= dan <=, maka data yang lahir pada tanggal 10 Oktober 1990 dan 11 Oktober 1992 tidak akan termasuk dalam hasil karena hanya memenuhi salah satu nilai batas.

Secara keseluruhan, penggunaan BETWEEN dan penggunaan operator >= dan <= dapat digunakan secara bergantian tergantung pada kebutuhan kita. Namun, dalam beberapa kasus, salah satu dari keduanya dapat lebih disukai dari yang lain tergantung pada preferensi dan kebutuhan kita.

### 2.	Berikan Kesimpulan Anda

DML (Data Manipulation Language) adalah bahasa SQL yang digunakan untuk memanipulasi data dalam sebuah basis data. DML digunakan untuk mengambil, menambahkan, memperbarui, dan menghapus data dalam tabel atau objek lain dalam basis data. DML juga menjadi salah satu bagian penting dalam manajemen basis data, dan merupakan bagian dari SQL (Structured Query Language) yang digunakan untuk mengelola basis data.

















