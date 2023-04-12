# Apache OFBiz Installation

### Install Packet yang dibutuhkan
Install paket Java dan Gradle
```bash
krishnaokvan@ubuntu:~$ sudo apt-get install apt-transport-https ca-certificates wget dirmngr gnupg software-properties-common unzip -y
krishnaokvan@ubuntu:~$ sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 8AC3B29174885C03
krishnaokvan@ubuntu:~$ sudo add-apt-repository --yes https://adoptopenjdk.jfrog.io/adoptopenjdk/deb/
krishnaokvan@ubuntu:~$ sudo apt-get install adoptopenjdk-8-hotspot -y
krishnaokvan@ubuntu:~$ sudo apt-get install gradle
```

Setelah itu cek apakah sudah terinstall dengan baik.<br>
![1](gambar/instalasi/Installation_1.jpg)<br>

### Instalasi OFBiz
Download OFBiz, kemudian extract file yang telah didownload.
```bash
krishnaokvan@ubuntu:~$ wget https://archive.apache.org/dist/ofbiz/apache-ofbiz-16.11.05.zip
krishnaokvan@ubuntu:~$ unzip apache-ofbiz-16.11.05
krishnaokvan@ubuntu:~$ cd apache-ofbiz-16.11.05
krishnaokvan@ubuntu:~/apache-ofbiz-16.11.05$ sudo ./gradlew cleanAll loadDefault
```

Tunggu sampai proses instalasi selesai.<br>
![2](gambar/instalasi/Installation_2.jpg)<br>

### Akses OFBiz 
Jalankan service OFBiz, kemudian akses melalui browser. 
```bash
krishnaokvan@ubuntu:~/apache-ofbiz-16.11.05$ sudo ./gradlew "ofbiz --load-data readers=seed"
krishnaokvan@ubuntu:~/apache-ofbiz-16.11.05$ sudo ./gradlew "ofbiz --load-data readers=seed,seed-initial,ext"
krishnaokvan@ubuntu:~/apache-ofbiz-16.11.05$ sudo ./gradlew ofbiz
```

Untuk login, user/password: admin/ofbiz<br>
Default dashboard: https://SERVER_IP:8443/ordermgr/control/main<br>
Catalog Manager: https://SERVER_IP:8443/catalog<br>
E-Commerce: https://SERVER_IP:8443/ecommerce<br>
WebTools: https://SERVER_IP:8443/webtools<br>

![3](gambar/instalasi/AksesOfbiz_1.jpg)<br>
![4](gambar/instalasi/AksesOfbiz_2.jpg)<br><br>
![5](gambar/instalasi/AksesOfbiz_3.jpg)<br>
![6](gambar/instalasi/AksesOfbiz_4.jpg)<br>
