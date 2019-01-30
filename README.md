#Latihan1


Apa Itu GIT ?


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

2. Buat Repository Local dengan mengetik "cd" & "mkdir" ("cd" untuk masuk ke folder & "mkdir" untuk membuat foldernya).

3. Mengkonfigurasikan e-mail dan user name kita di GIT.

4. Kita buat Repository Localnya menjadi master dengan melakukan inisialisai "git init".

5. Buat file project pada folder kita dengan mengetik "echo" dan cek apakah sudah ada filenya di dalam folder kita dengan mengetik "ls -l".

6. Siapkan file project kita yang akan di upload pada Repository Server dengan mengetik "git add".

7. Buatlah Repository Servernya pada https://github.com yang sudah di sign in oleh kita.

8. Update file project yang akan di upload ke Repository Online dengan mengetik "git commit".

9. Kemudian ketikkan alamat HTTPS Repository Online yang akan kita tuju dengan diawali "git remote add origin" & upload project filenya, untuk alamat HTTPS bisa dilihat pada tanda di gambar berikut.

10. Untuk mengisi teks pada file projectnya, kita bisa ketik "nano" lalu kalian masukkan teks yang kalian inginkan lalu simpan dengan cara "Ctrl + S".

11. Finally yaitu kita mengirim file project kita ke Repository Server di Github dengan mengetik "git push -u origin master" & jangan lupa untuk melakukan ini kita membutuhkan jaringan internet, pada proses ini kita juga akan diminta untuk memasukkan username dan password.

12. Dan inilah hasilnya.

Sekian dan Terima Kasih
Agus Saputra
311810946
TI.18.B.1
