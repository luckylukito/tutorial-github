# tutorial-github
Cara Menggunakan Git & Github

A. Prosedur Awal
1. Pertama download github
https://git-scm.com/downloads
2. Membuat akun github
https://github.com/join
3. Melakukan setting pada Windows Powershell

   git config --global user.name (masukkan username)

   git config --global user.email (masukkan email)

4. Membuat SSH pada halaman Github
   Buka halaman github kemudian membuka halaman setting dilanjutkan dengan SSH dan GPH key dan copy new SSH Keys
5. Untuk key sendiri dapat dibuat dengan cara membuka Windows Powershell dan memasukkan command line berikut:

   ssh-keygen -t ed25519 -C (masukkan email) Kemudian pencet enter 2x
6. Copy clip SSH key yang telah dibuat dengan menggunakan command berikut:
   
   clip < ~/.ssh/id_ed25519.pub
7. Kemudian paste atau Ctrl+V ke bagian key pada setting New SSH Key di Github
