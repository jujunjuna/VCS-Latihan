# VCS-Latihan
## cara menggunakan git hub
1. Login Git
Untuk login ke Git, Anda bisa menggunakan akun GitHub, Gitlab, atau Bitbucket. Jika belum memiliki akun dari ketiga platform tersebut, Anda bisa mendaftarkan diri terlebih dahulu. Selanjutnya Anda bisa melakukan login awal pada Git  menggunakan Command Prompt  (Windows) atau Command Line (Linux) . Kemudian masukkan perintah-perintah yang akan kami jelaskan di bawah ini.

Selanjutnya, masukkan username GitHub Anda menggunakan perintah di bawah ini. Lalu tekan ENTER jika sudah benar.
$ git config --global user.name "UsernameAnda"
Kemudian masukkan email yang terdaftar di GitHub Anda menggunakan perintah di bawah  ini. Lalu tekan ENTER jika sudah benar.

$ git config --global user.email IsiDenganEmailAnda@gmail.com
Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.

$ git config --list
2. Login Github
Langkah kedua dalam belajar menggunakan Git adalah Anda harus login ke dalam website GitHub. Github dan Git memiliki hubungan khusus, yaitu Git yang berperan sebagai version control system dan Github menjadi hosting atau sebagai penyimpan kode pemrograman.

Setelah Anda login, akan muncul tampilan dashboard dari GitHub seperti  gambar di bawah ini.
![gambar 1](sreenshot/gambar1.png)

3. Buat Repository
Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.
4. Buat Folder pada Windows
Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.
5. Buka Folder Menggunakan Git Bash
![gambar2](sreenshot/gambar2.png)
6. Ubah Folder Menjadi Repository
Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:

$ git init
7. Tambahkan File ke Repository
Untuk bisa menambahkan file ke repository GitHub, Anda perlu menerapkan langkah-langkah di bawah ini:

Buat file di folder yang sudah dibuat (Test Git). Contohnya, di sini kami membuat file index.php
Buka GitBash lalu masukkan perintah berikut:
$ git add index.php
Perintah tersebut tidak akan menghasilkan output apa pun.
8. Buat Commit 
Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit:

$ git commit -m "first commit"
Pada tutorial ini kami membuat first commit sebagai Commit pertama kami. Anda bebas membuat membuat nama Commit apa saja.
9. Remote Repository Github
Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository:

$ git remote add origin git@github.com:UserNameGit/NamaRepository.git
Perintah di atas tidak akan menghasilkan output apa pun.
10. Push ke GitHub 
Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub:

git push -u origin master
Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub. 
![gambar3](sreenshot/gambar3.png)

Jika proses login berhasil, akan muncul tampilan Command Prompt seperti di bawah:
![gambar4](gambar4.png)