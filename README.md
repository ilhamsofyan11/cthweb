Menginstal Git
    1. Unduh Git di website (git-scm.com).
    2. Lalu unduh git sesuai dengan kompatibel komputer 32 bit atau 64 bit.
    3. Kemudian Install


Menambah Global Config
    1. Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi "user.name" dan "user.email"
    2. konfigurasi inin bisa dilakukan untuk global reposity atau individual repository
    3. Apabila belum dilakukan konfigurasi , akan mengakibatkan terjadi kegagalan saat menjadikan perintah git commit
      Config Global Repository 
      git config --global user.name “name_user”
        
     
git config --global user.email "email_anda"

Membuat Reposiory Local
    1. Buka direktory aktif misal " D:/Labs1 " buka menggunakan Windows Explorer
    2. Klik kanan pada direktory aktif tersebut , dan pilih menu " Git Bash " , sehingga muncul git bash command





Membuat Repository Local
    1. Jalankan perintah $ git init, untuk membuat repository local.
    2. Repository baru berhasil di inisialisasi,akan terbentuk satu direktori dengan nama .git
    3. Pada direktori itu, semua perubahan working directory akan disimpan.

Membuat File Baru di repository
    1. Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository)
    2. Contoh file bernama README.md menggunakan echo "#lab1" >> README.md
    3. File README.md berhasil dibuat


Commit ( Menyimpan perubahan ke database)
    1. untuk menyimpan perubahan kedalam data repository local,gunakan perintah git commit -m " Komentar commit”

Membuat Reposity Server
    1. Server reopsitory yang akan kita gunakan adalah " https://github.com "
    2. Anda harus membuat akun terlebih dahulu
    3. Pada website github, kilik tomboh start project, atau Dari menu (icon + ) klik New repository 
    4. Isi nama repository, misal :user
    5. Lalu klik tombol Create repository 

Push (Mengirim Perubahan ke server)
    1. Untuk mengirim perubahan pada local repository ke server gunakan perintah git push. git push -u origin master
    2. Perintah ini akan meminta memasukkan username dan password pada akun github.com
    3. Buka laman github.com arahkan pada repositori
    4. Pembaruan akan terlihat pada halaman 



# VCS
