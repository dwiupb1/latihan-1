# latihan 1 #

Langsung saja pada tutorialnya:

# LANGKAH-LANGKAH MENGGUNAKAN GITHUB
• Download Git, buka website resminya Git (git-scm.com).

• Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.

![sc1](https://user-images.githubusercontent.com/115912116/198843484-0d304e5f-da42-4d44-b4f1-fcee31f36116.PNG)
• setelah terinstall,Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah

git --version.

![sc2](https://user-images.githubusercontent.com/115912116/198843627-6279cbf6-4cee-4f44-bedb-8dc620d1dab8.PNG)

# MENAMBAHKAN GLOBAL CONFIG

• Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email

• konfigurasi ini bisa dilakukan untuk global repository atau individual repository.

apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi kegagalan saat menjalankan perintah git commit

# CONFIG GLOBAL Repository

$ git config --global user.name “nama_user”

$ git config --global user.email “nama_user”


# Membuat Reposiory Local


• Buka direktory aktif, misal: /d/Latihan VCS

• klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash here

• Buat direktory project praktikum pertama dengan nama Latihan_1

• Sehingga terbentuk satu direktori baru dibawahnya, selanjutnya masuk kedalam direktori tersebut dengan perintah cd (change directory)

• direktory aktif menjadi: /d/Latihan VCS/Latihan_1

![sc3](https://user-images.githubusercontent.com/115912116/198843929-e98fc484-39d4-45d6-952f-69002a21fd38.png)



# Membuat Repository github

![sc6](https://user-images.githubusercontent.com/115912116/198844044-00a059ac-1538-450f-a7e7-d37b5b332652.png)

# Menambahkan File baru pada repository

• Jalankan git status, lalu jalan perintah git add .

• Jalankan perintah git commit -m "Update Tugas"

• git remote add origin https://github.com/dwiupb1/latihan-1.git

• git push -u origin master/main

 # Ketikkan perintah seperti di step

    echo "# Repository-Baru" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/brianetlab/Repository-Baru.git
    git push -u origin master

 . Penjelasannya :

    > git add = untuk memiliih file yang akan dimasukan ke github (kalau pilih semua: “ git add . “ )
    > git commit = untuk memberi commit/pesan git remote = alamat untuk memasukan ke github
    > git push = untuk ngepush semuanya ke github klik enter dan lihat project kamu sudah terupload ke Github


![sc5](https://user-images.githubusercontent.com/115912116/198844117-8f58ba5c-716e-4d3b-b543-60047ebcb2b5.PNG)

• Maka Hasilnya akan seperti ini

![image_2022-10-30_001003743](https://user-images.githubusercontent.com/115912116/198844308-69cebf40-6b3a-4bd4-bc2c-15249293ecb7.png)

> Selamat projek kamu sudah masuk ke Github! 

Setelah selesai tinggal upload link ke e-campus atau tugas yang akan dikirim.

# SEKIAN DAN TERIMA KASIH #





            


