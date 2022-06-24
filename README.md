### Nama : Muhamad Wildan Septian
### Kelas : TI.20.D2
# Tugas-6-SBD-20.D2

# 1.Masuk ke database nama_nim !
![1](https://user-images.githubusercontent.com/106539745/175556634-ffd9e288-55fa-40c7-bf5e-8cb02e6fa6f3.JPG)
# 2.Lakukan proses backup dan recovery dengan sql dari database tugas sebelumnya !
### Proses Backup Database
![2](https://user-images.githubusercontent.com/106539745/175556774-e5f99c66-4f99-4722-9cdb-f63f39de0159.JPG)
### Contoh proses backup yang berhasil file otomatis akan masuk pada file direktori
### C:\xampp\mysql\data\nama database
![3](https://user-images.githubusercontent.com/106539745/175557004-8c82dd2d-0090-4bdd-9dff-af3f0f977de0.JPG)
### Proses Recovery
![4](https://user-images.githubusercontent.com/106539745/175557976-2797271d-2339-4c98-a072-32ccc34b933a.JPG)
# 3.Lakukan proses backup dan recovery dengan sqldump dari database tugas seblumnya !
![5](https://user-images.githubusercontent.com/106539745/175559109-f77b9321-3a8a-465a-b2a9-16ed7c69f0fc.JPG)
# 4.Tulisakan script cron job untuk melakukan backup otomatis setiap hari minggu jam 12 malam !
0 0 * * 7 mysqldump -u root –p imam_fauzi_312010220>imam_fauzi_312010220_backup.sql


