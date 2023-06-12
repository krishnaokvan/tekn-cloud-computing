# Diagram - Docker Compose

Diagram:<br>
<div align="center"><img src="gambar/tugas/diagram.jpg"></div>

Penjelasan:<br>
- Docker image : sebuah file yang terdiri dari beberapa lapisan (layers) yang saling terkait. Setiap lapisan mewakili perubahan yang dilakukan terhadap image dasar sebelumnya. Lapisan-lapisan ini dibangun secara bertahap saat Dockerfile, yang berisi instruksi-instruksi untuk membangun image, dieksekusi.
- Container: Container dapat membawa image tadi dan digunakan untuk membantu development. Satu Image dapat digunakan banyak Container.
- Dockerd: Yang Berisikan Images serta Container.
- docker client : Berfungsi untuk Menjalankan dan mengelola container, Membangun dan mengelola image, dan Mengelola Volume.
- Docker Compose: Digunakan untuk mengelola dan menjalankan aplikasi multi-container dengan menggunakan sebuah file konfigurasi YAML.
- Docker Swarm: Digunakan untuk mengelola dan menjalankan aplikasi yang terdiri dari beberapa kontainer di lingkungan Docker yang terdistribusi.

