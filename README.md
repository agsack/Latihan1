#Latihan1


Apa Itu GIT ?

![51690083-90b4e400-202a-11e9-8c54-d9586558eb8b](https://user-images.githubusercontent.com/46734315/51964724-f4f7fd80-2499-11e9-884e-f24891b38164.png)

GIT adalah pengontrol versi yang bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri. GIT dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database GIT tidak hanya berada dalam satu tempat saja.

Install GIT di Windows

Menginstall GIT di Windows sangat mudah, cukup dengan mendownload dan menjalankan instalasinya. Ikuti langkah berikut ini untuk meng-install GIT di Windows:

Buka https://gitforwindows.org/ dan download installer GIT untuk Windows.
Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.

Beberapa Perintah Dasar Pada GIT

git init, perintah untuk membuat repository local.
git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
git commit, perintah untuk menyimpan perubahan kedalam database git.
git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.
git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory).
Langkah-Langkah Menggunakan GIT

1. Jalankan software GIT pada Desktop dengan cara klik kanan > Git Bash Here.
![as](https://user-images.githubusercontent.com/46734315/51964826-4a340f00-249a-11e9-8e45-ec0d5b7f8f39.jpg)

2. Buat Repository Local dengan mengetik "cd" & "mkdir" ("cd" untuk masuk ke folder & "mkdir" untuk membuat foldernya).
![1 - copy 2](https://user-images.githubusercontent.com/46734315/51965742-13abc380-249d-11e9-92ad-9da9c05a218c.png)

3. Kita buat Repository Localnya menjadi master dengan melakukan inisialisai "git init".
![1 - copy 3](https://user-images.githubusercontent.com/46734315/51965744-15758700-249d-11e9-8c66-8139f5e4e686.png)

4. Buat file project pada folder kita dengan mengetik "echo" dan cek apakah sudah ada filenya di dalam folder kita dengan mengetik "ls -l".
![1 - copy 4](https://user-images.githubusercontent.com/46734315/51965749-17d7e100-249d-11e9-9ec9-87df7198418d.png)

5. Siapkan file project kita yang akan di upload pada Repository Server dengan mengetik "git add".
![1 - copy 5](https://user-images.githubusercontent.com/46734315/51965757-1a3a3b00-249d-11e9-99d5-f25d7c04a16f.png)

6. Buatlah Repository Servernya pada https://github.com yang sudah di sign in oleh kita.
![2](https://user-images.githubusercontent.com/46734315/51966226-85d0d800-249e-11e9-9de8-6b3874d87b25.png)

7. Update file project yang akan di upload ke Repository Online dengan mengetik "git commit".
![1 - copy 6](https://user-images.githubusercontent.com/46734315/51965772-21f9df80-249d-11e9-83e5-6d5464b02a96.png)

8. Kemudian ketikkan alamat HTTPS Repository Online yang akan kita tuju dengan diawali "git remote add origin" & upload project filenya, untuk alamat HTTPS bisa dilihat pada tanda di gambar berikut.

![3](https://user-images.githubusercontent.com/46734315/51965779-258d6680-249d-11e9-8b71-b40acf0b536b.png)
![4 - copy 2](https://user-images.githubusercontent.com/46734315/51965786-28885700-249d-11e9-8334-d4251546a3fe.png)

9. Untuk mengisi teks pada file projectnya, kita bisa ketik "nano" lalu kalian masukkan teks yang kalian inginkan lalu simpan dengan cara "Ctrl + S".
![51695852-a16b5700-2036-11e9-9d34-d0c875aba2a9](https://user-images.githubusercontent.com/46734315/51965795-30e09200-249d-11e9-8a16-19b93b8db41e.jpg)

10. Finally yaitu kita mengirim file project kita ke Repository Server di Github dengan mengetik "git push -u origin master" & jangan lupa untuk melakukan ini kita membutuhkan jaringan internet, pada proses ini kita juga akan diminta untuk memasukkan username dan password.
![4 - copy 3](https://user-images.githubusercontent.com/46734315/51965789-2b834780-249d-11e9-9314-5ec61384ea03.png)

11. Dan inilah hasilnya.

Sekian dan Terima Kasih
Agus Saputra
311810946
TI.18.B.1
