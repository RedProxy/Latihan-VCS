# Latihan-VCS
## Tutorial Penggunaan Git

![Gif 1](screenshot/gif1.gif)

### Menginstall Git
- Buka [Github](https://Github.com)
- Jika Belum mendaftar klik Register/Sign up
- Jika sudah mendaftar silahkan klik Masuk/Sign in

![Gambar 1](screenshot/Ss1.png)

- Jika sudah Sign in muncul tampilan seperti tampilan dibawah ini
- Kemudian klik Create repository
![Gambar 2](screenshot/Ss2.jpg)

- kemudian isi Repository name
- deskripsi (optional) boleh di isi boleh tidak
- Ceklist Add a README file
- kemudian klik Create repository seperti gambar dibawah

![Gambar 3](screenshot/Ss3.png)

![Gambar 4](screenshot/Ss4.png)

- Setelah muncul tampilan seperti gambar dibawah
- Klik Kode kemudian Anda bisa memilih HTTPS, SSH, Github, atau CLI. Lalu copy link yang tersedia

![Gambar 5](screenshot/Ss5.jpg)

- Jika Anda belum menginstal git-scm silahkan, instal terlebih dahulu (lewati saja jika sudah instal)
- [Git-scm](https://git-scm.com) klik Unduh untuk Windows
- Jika sudah didownload silahkan instal seperti biasa, klik next saja

![Gambar 6](screenshot/Ss6.png)

- Buat satu folder kosong untuk directory kerja
- Kemudian klik kanan pada mouse pilih "Git Bash Here"

![Gambar 7](screenshot/Ss7.png)

- Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut :

> $ git config --global user.name "username"

> $ git config --global user.email "email"

![Gambar 7](screenshot/Screenshot51.png)

- Kemudian Masukan Perintah :

> $ pwd

![Gambar 8](screenshot/Screenshot56.png)

> $ cd /d/VCS/

![Gambar 9](screenshot/Screenshot57.png)

> $ ls

![Gambar 10](screenshot/Screenshot58.png)

> $ ls -l

![Gambar 11](screenshot/Screenshot65.png)

- Kemudian copy link HTTPS Github kalian

> $ git clone 'link Github'

- Tekan Enter pada keyboard

![Gambar 12](screenshot/Screenshot70.png)

- Kemudian muncul file README.md di file kalian

- Klik kanan pada mouse, lalu pilih open with pilih "Visual Studio Code"

- Jika kalian belum instal "Visual Studio Code" kalian bisa download [VCS](https://code.visualstudio.com/)

- Tutorial cara instal [Video instalasi VCS](https://www.youtube.com/watch?v=OSmaWPSgvTQ)

![Gambar 13](screenshot/Screenshot71.png)

- Setelah terbuka Visual Code Studio, pastikan kalian koding di file README.md

- Edit file README.md, lalu jangan lupa di save (ctrl+s)

- Setelah itu buka Git Bash yang sebelumnya

> git add README.md
> git commit -m "Descrption"
> git push -u origin master

- Selesai terupload dan di push Ke GitHub

![Gambar 14](screenshot/Screenshot82.png)

- SELESAI