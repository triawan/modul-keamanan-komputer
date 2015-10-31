# Pengenalan Python

Python merupakan bahasa pemrograman yang populer khususnya pada bidang keamanan komputer. Pada modul ini, beberapa eksperimen dalam pembuatan program untuk mendukung proses keamanan komputer, ditulis menggunakan python versi 2. Apabila tidak ingin rumit, maka pakailah sistem operasi linux varian terbaru, misalnya : ubuntu, kali linux, dan lain sebagainya. Bahasa pemrograman python beserta modul-modulnya sudah terinstall otomatis di sistem operasi linux.


## Pengenalan Network Socket

Network socket merupakan alamat yang mengandung data alamat ip address dan nomor port. Singkatnya, socket merupakan cara yang mudah untuk berkomunikasi dengan komputer lain. Oleh karena itu, socket merupakan suatu proses yang dapat berkomunikasi dengan proses yang lain melalui jaringan.

Pada bahasa pemrograman python, untuk membuat socket menggunakan fungsi socket.socket() yang tersedia pada modul socket. Sintaks standar dari fungsi socket adalah:

```s = socket.socket(socket_family, socket_type, protocol=0)```

Deskripsi parameter dari fungsi socket diatas adalah sebagai berikut:

socket_family: socket.AF_INET, PF_PACKET