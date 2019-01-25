#latihan1


## Langkah - Langkah cara penggunaan Git Hub

Apa itu Git ?
Git adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

# Langkah-langkah Install GIT di berbagai jenis sistem

# Install GIT di Windows

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

  1. Buka website ini dan download installer GIT untuk Windows.
    
  2. Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.

# PERINTAH DASAR GIT

   1. git init, perintah untuk membuat repository local
   2. git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
   3. git commit, perintah untuk menyimpan perubahan kedalam database git.
   4. git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
   5. git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
   6. git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).

# Langkah-Langkah Menggunakan Git

   1. Klik kanan pada monitor Klik " Git Bash Here"
  
   ![langkah 1](https://user-images.githubusercontent.com/47028610/51748250-acd37800-2060-11e9-81d3-637941c7ef39.jpg)

   2. Maka akan ada tampilan command prompt seperti dibawah ini
 
   ![langkah 2](https://user-images.githubusercontent.com/47028610/51748332-f58b3100-2060-11e9-962c-665fa2da2223.jpg)

   3. Buka Drive yang ingin dipakai, semisal Drive D jalankan dengan perintah cd /d
  
   ![langkah 3](https://user-images.githubusercontent.com/47028610/51748387-223f4880-2061-11e9-8b6f-80e33fbf8365.jpg)
  
   4. Buat directory dengan printah "mkdir" sebagai contoh : directory Pemograman1
  
   ![langkah 4](https://user-images.githubusercontent.com/47028610/51748402-2ec3a100-2061-11e9-9705-e7fd6c902965.jpg)

   5. Buka directory Pemograman1 dengan perintah cd Pemograman1
   
   ![langkah 5](https://user-images.githubusercontent.com/47028610/51748454-5450aa80-2061-11e9-9924-d42601b68ca8.jpg)

   6. Buat directory latihan1 dan buka directory latihan1.
 
   ![langkah 6](https://user-images.githubusercontent.com/47028610/51748539-9548bf00-2061-11e9-9331-857680989f9b.jpg)

   7. Menambahkan file baru pada repository dengan perintah echo "#latihan1" >> README.md 

   ![langkah 7](https://user-images.githubusercontent.com/47028610/51748572-b7dad800-2061-11e9-99de-bf5a83dc579b.jpg)

   8. Jalankan perintah git init untuk menjalankan repository local

   ![langkah 8](https://user-images.githubusercontent.com/47028610/51748608-cc1ed500-2061-11e9-8d23-6f0a1d12491a.jpg)

   9. Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add README.md

   ![langkah 9](https://user-images.githubusercontent.com/47028610/51748621-d640d380-2061-11e9-8f2f-5577655f7a23.jpg)

   10. Untuk menyimpan perubahaan yang ada kedalam database repository local, gunakan perintah git commit -m "File pertama saya"
    
   ![langkah 10](https://user-images.githubusercontent.com/47028610/51748641-e789e000-2061-11e9-837b-a94c4bb399fa.jpg)

   11. Buat repository server, isi nama repositorynya semisal : latihan1 ,kemudian klik tombol Creat repository

   ![langkah 11](https://user-images.githubusercontent.com/47028610/51748706-199b4200-2062-11e9-90f3-6d5280a0f2c5.jpg)

   12. Menambahkan remote repository. remote repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan sehingga dapat diakses oleh banyak user
    
   ![langkah 12](https://user-images.githubusercontent.com/47028610/51748736-3172c600-2062-11e9-81d3-ea54130ef449.jpg)

   13. Mengirim perubahan ke server dengan perintah git push -u origin master

   ![langkah 13](https://user-images.githubusercontent.com/47028610/51748847-844c7d80-2062-11e9-892a-b5d335748a53.jpg)

   14. Melihat hasil pada repository, buka laman github.com arahkan pada repositorynya. Maka perubahan akan terlihat pada laman tersebut
   
   ![langkah 14](https://user-images.githubusercontent.com/47028610/51748865-90383f80-2062-11e9-8fcd-4ccc291656a0.jpg)


   15. Buka drive D kemudian klik Pemograman1, klik latihan1 
    
   ![langkah 15](https://user-images.githubusercontent.com/47028610/51748924-b362ef00-2062-11e9-8d38-fc7df9849b0e.jpg)

   16. Klik kanan pada file Readme.md kemudian pilih aplikasi untuk mengubah file, semisal dibawah ini dengan aplikasi notepad 
    
   ![langkah 16](https://user-images.githubusercontent.com/47028610/51748939-c4abfb80-2062-11e9-87b2-01ba7ca78798.jpg)

   17. Untuk mengirim perubahan jalan perinta git push -u origin master, kemudian git add README.md dan git commit -m "latihan1"
    
   ![langkah 17 a](https://user-images.githubusercontent.com/47028610/51748953-d392ae00-2062-11e9-9c2b-b51c41f422c1.jpg)
    
   ![langkah 17 b](https://user-images.githubusercontent.com/47028610/51748961-de4d4300-2062-11e9-96f8-e0dbb3bfac05.jpg)
    
   ![langkah 17 c](https://user-images.githubusercontent.com/47028610/51748975-ee652280-2062-11e9-9cb0-469dd66f79ee.jpg)


   18. Kemuidan lihat perubahannya pada laman github.com 
    
   ![langkah 18](https://user-images.githubusercontent.com/47028610/51749001-ffae2f00-2062-11e9-9bf3-f34ece751fd4.jpg)


   ![terimakasih](https://user-images.githubusercontent.com/47028610/51749091-4b60d880-2063-11e9-93bf-4e98696c3668.jpg)

# BAGUS DWI SAPUTRO
# 311810029
# TI 18 B.1
Sekian dan terima kasih
