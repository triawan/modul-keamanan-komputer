# Pengenalan Python

Python merupakan bahasa pemrograman yang populer khususnya pada bidang keamanan komputer. Pada modul ini, beberapa eksperimen dalam pembuatan program untuk mendukung proses keamanan komputer, ditulis menggunakan python versi 2. Apabila tidak ingin rumit, maka pakailah sistem operasi linux varian terbaru, misalnya : ubuntu, kali linux, dan lain sebagainya. Bahasa pemrograman python beserta modul-modulnya sudah terinstall otomatis di sistem operasi linux.


## Pengenalan Network Socket

Network socket merupakan alamat yang mengandung data alamat ip address dan nomor port. Singkatnya, socket merupakan cara yang mudah untuk berkomunikasi dengan komputer lain. Oleh karena itu, socket merupakan suatu proses yang dapat berkomunikasi dengan proses yang lain melalui jaringan.

Pada bahasa pemrograman python, untuk membuat socket menggunakan fungsi socket.socket() yang tersedia pada modul socket. Sintaks standar dari fungsi socket adalah:

```s = socket.socket(socket_family, socket_type, protocol=0)```

Deskripsi parameter dari fungsi socket diatas adalah sebagai berikut:

```socket_family: socket.AF_INET, PF_PACKET```

* AF_INET merupakan alamat untuk IPv4. 
* PF_PACKET merupakan device driver layer. Umumnya merupakan library pcap yang digunakan pada linux.


## Cara Kerja Method Socket Server 

Dalam konsep arsitektur client-server, terdapat dua layanan yang berbeda dari masing-masing perangkat. Server bertugas secara terpusat untuk memberikan service/layanan yang diminta oleh client. Sedangkan client bertugas untuk mengirimkan permintaan dan menerima layanan dari server.

Beberapa metode pada fungsi socket di python, yaitu:
* socket.bind(address): Method ini digunakan untuk menghubungkan alamat ip dengan nomor port ke socket. Socket harus dibuka dahulu sebelum terhubung dengan alamat tersebut.
* socket.listen(q): Method ini akan memulai fase mendengarkan koneksi TCP. Argumen q mendefinisikan jumlah koneksi maksimum yang dapat ditangani server.
* socket.accept(): Penggunaan method ini adalah untuk menerima koneksi yang dikirim dari client.



