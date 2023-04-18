# MySQL
# Praktikum 1

### Membuat DDL Script berdasarkan skema ERD tersebut diatas dan Jalankan script DDL tersebut pada DBMS MySQL
### Data Model Mapping
1. Mahasiswa (nim, nama, jenis_kelamin, tgl_lahir, jalan, kota, kodepos, no_hp, kd_ds)
2. Dosen (kd_ds, nama)
3. Matakuliah (kd_mk, nama, sks)
4. JadwalMengajar (kd_ds, kd_mk, hari, jam, ruang)
5. KRSMahasiswa (nim, kd_mk, kd_ds, semester, nilai)



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






















