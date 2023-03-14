# 04 Kolaborasi
# FORK
  Fork adalah membuat clone dari suatu repo di GitHub milik upstream author, diletakkan ke milik kontributor. Fork hanya dilakukan sekali saja. Pada dasarnya, proses untuk fork ini meliputi:
  1. Fork repo di web GitHub.
  2. Clone fork tersebut di komputer lokal.
  3. Kontributor harus mem-fork repo upstream author sehingga di repo kontributor muncul repo tersebut. Proses forking ini dijelaskan dengan langkah-langkah berikut:
    1. Login ke GitHub
    2. Akses repo yang akan di-fork: https://github.com/harry-prd/aksesoris-hp.git
    3. Pada sisi kanan atas, klik Fork:
<img width="915" alt="gambar2" src="https://user-images.githubusercontent.com/115064323/224923946-93bea927-f68c-45e7-9e87-7a419cba4d47.png">
<img width="923" alt="gambar1" src="https://user-images.githubusercontent.com/115064323/224923939-9549dd87-17a2-4e5d-8d00-b2dffe4ef352.png">

4. Setelah proses tersebut, clone di komputer lokal, Setelah itu, konfigurasikan repo lokal kontributor. Pada kondisi saat ini, di komputer lokal sudah terdapat repo playground-1 yang berada pada direktori dengan nama yang sama. Untuk keperluan berkontribusi, ada 2 nama repo yang harus diatur:

<img width="398" alt="1" src="https://user-images.githubusercontent.com/115064323/224924153-76a16bf2-04b7-45d1-b26f-5d6a1c035e07.png">

origin: menunjuk ke repo milik kontributor di GitHub, hasil dari fork.
upstream: menunjuk ke repo milik upstream author (repo asli) di account oldstager. Repo origin sudah dituliskan konfigurasinya pada saat melakukan proses clone dari repo kontributor. Konfigurasi repo upstream harus dibuat.

<img width="412" alt="2" src="https://user-images.githubusercontent.com/115064323/224925683-45188718-25b1-4629-a903-873fd8021fa2.png">

Lakukan perubahan-perubahan, setelah itu push ke origin (milik kontributor)
 5. Setelah itu, buka halaman Web dari repo kontributor [https://github.com/Afifa9/tekn-cloud-computing-1](https://github.com/krishnaokvan/aksesoris-hp.git). Pada halaman tersebut akan ditampilkan isi yang kita push.
<img width="421" alt="3" src="https://user-images.githubusercontent.com/115064323/224926060-f47d30a0-5133-4808-a919-7d0c9338e479.png">

 6. Pilih ```Compare and pull request```, kemudian isikan deskripsi PR dan klik pada ```Create pull request```:
<img width="451" alt="4" src="https://user-images.githubusercontent.com/115064323/224926137-faa601d1-2f09-4c84-847c-84dd77c8249a.png">
<img width="902" alt="5" src="https://user-images.githubusercontent.com/115064323/224926139-208e2db6-3fe9-4cd5-bfd5-cd44267a9620.png">


 7. Pada repo upstream author, muncul angka 1 (artinya jumlahnya 1) pada Pull requests di bagian atas.
 8. Upstream author bisa menyetujui setelah melakukan review: klik pada Pull requests, akan muncul PR dengan message seperti yang ditulis oleh kontributor     (Add: contributor). Klik pada PR tersebut, review kemudian klik Merge pull request diikuti dengan Confirm merge. Setelah itu, status akan berubah menjadi   Merged.
 9. Sinkronkan semua repo (lokal maupun GitHub kontributor)
<img width="907" alt="6" src="https://user-images.githubusercontent.com/115064323/224926144-1adc8c70-f3a6-4a53-9f93-613e4cd2e1d0.png">
Jika dijalankan ulang hasilnya :
<img width="361" alt="7" src="https://user-images.githubusercontent.com/115064323/224926149-257565a5-1ec2-4689-a853-05ac34c97b29.png">
