# latihan 1 #

Langsung saja pada tutorialnya:

1.  Buat akun pada https://github.com/

2.  Setelah selesai, lalu download Git, download disini https://git-scm.com/downloads

    ![image](pg/sc1.PNG)
     

3.  Instal seperti biasa

4.  Lalu login ke akun github dan buat repository baru, klik link https://github.com/new 

    ![image](pg/sc6.png)

    ![image](pg/sc7.PNG)

    ![image](pg/sc8.PNG)

    ![image](pg/sc9.PNG)
  

 lakukan seperti gambar diatas: Repository name: (Diisi nama repositorya) Desciption: (Diisi deskripsi repositorynya (tidak wajib)) lalu set Public, Private, default Public, lalu klik tombol berwarna hijau Create Repository.

5.  Setelah Create Repository muncul halaman seperti ini:

    ![image](pg/sc10.PNG)

ini berfungsi sebagai perintah command line\

6.  Setelah itu buka project yang akan dimasukkan ke Github,



caranya klik kanan pada folder project 

 dan pilih Git Bash Here Image dan muncul command line

![image](pg/sc3.png)

7.  Ketikkan perintah seperti di step 5:

    echo "# Repository-Baru" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/brianetlab/Repository-Baru.git
    git push -u origin master

 Penjelasan:
    git add = untuk memiliih file yang akan dimasukan ke github (kalau pilih semua: “ git add . “ )
    git commit = untuk memberi commit/pesan git remote = alamat untuk memasukan ke github
    git push = untuk ngepush semuanya ke github klik enter dan lihat project kamu sudah terupload ke Github

8.  Selamat Project kamu sudah masuk ke Github! Image

            Selesai sekarang

                







            


