# Latihan

## Instalasi Git
Pertama-tama kita harus mendownload file Git untuk windows, silakan kunjungi website resminya di https://git-scm.com/downloads. 
Kemudian pilih versi 64-bit atau 32-bit sesuai arsitektur komputer kita.

<img width="341" alt="git-1" src="https://user-images.githubusercontent.com/115064323/224933358-76803fb3-14bd-4a90-aaba-7322eb928071.png">
<img width="343" alt="git-2" src="https://user-images.githubusercontent.com/115064323/224933410-5756b9f8-2a3a-42ea-b623-f9202dc8d0e7.png">
<img width="342" alt="git-4" src="https://user-images.githubusercontent.com/115064323/224933478-5ac87615-fdd2-40bb-a086-25603f115d10.png">

 Cek versi Git yang terinstall :
 Dengan cara git --version pada Git Bash atau di CMD, seperti berikut :
 
 ![alt text](gambar-01.jpg?raw=true)

## Konfigurasi Git
Berikut merupakan Screenshot untuk mengkonfigurasi Git dan mengkonfigurasi yang sudah ada :
Sebagaimana telah Anda lihat secara singkat di Memulai, Anda bisa menentukan pengaturan konfigurasi Git dengan perintah git config. Salah satu hal pertama yang harus Anda lakukan adalah menyiapkan nama dan alamat surel Anda.
 ![alt text](gambar-02.jpg?raw=true)
 
 Isian di atas harus disesuaikan dengan nama serta email yang digunakan untuk mendaftar di GitHub. Untuk melihat konfigurasi yang sudah ada.
 
 ## Mengelola Repo Sendiri
Berikut latihan untuk mengelola Repo : 
Setiap orang yang telah mempunyai account di GitHub bisa membuat repo dengan. Secara umum, langkah-langkahnya adalah sebagai berikut:

- Buat repo kosong di GitHub, bisa public maupun private.
- Cloe repo kosong tersebut di komputer lokal
- Perintah berikutnya terkait dengan perubahan repo serta sinkronisasi antara GitHub dengan lokal.

### Buat repositori baru
Secara umum repositori Github dibagi menjadi 2 yaitu Public dan Private
- repository Public : sebuah folder proyek yang dapat diakses secara public dan semua orang dapat mengakses folder tersebut
- repository Private : sebuah folder proyek yang dapat diakses secara Private/Pribadi 
![alt text](gambar-03.jpg?raw=true)

### Clone repositori yang baru dibuat
![alt text](gambar-04.jpg?raw=true)
 
### Jika ada perubahan pada file directory, langkah untuk push adalah = add - commit - push
![alt text](gambar-05.jpg?raw=true)

### Berikut preview perubahan dalam file
![alt text](gambar-06.jpg?raw=true)

### Checkout merupakan perintah untuk membuat / menukar branch atau cabang

### Langkah-langkah dalam melakukan checkout
![alt text](gambar-07.jpg?raw=true)

### Proses merge request branch
![alt text](gambar-08.jpg?raw=true)
![alt text](gambar-09.jpg?raw=true)


### Proses merge pada komputer lokal
![alt text](gambar-10.jpg?raw=true)
![alt text](gambar-11.jpg?raw=true)

Berikut Mengkonfigurasi Kembali :
![alt text](gambar-12.jpg?raw=true)

![alt text](gambar-13.jpg?raw=true)

- Git log -oneline adalah sebuah perintah untuk menampilkan log commit pada sebuah repository dengan format satu baris untuk setiap commit. Setiap baris menunjukkan informasi singkat mengenai commit tersebut, seperti hash commit, pesan commit, dan informasi lainnya yang terkait dengan commit.

- git revert adalah sebuah perintah pada Git yang digunakan untuk membatalkan perubahan yang ada pada sebuah commit. Perintah ini akan membuat sebuah commit baru yang akan mengembalikan codebase ke kondisi sebelum commit yang ingin dibatalkan dilakukan.
