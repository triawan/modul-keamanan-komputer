# Bekerja Dengan Data Hasil Tangkapan

Data hasil tangkapan dari Wireshark dapat dimanfaatkan untuk kepentingan analisa data lebih lanjut. Umumnya data hasil tangkapan mempunyai ekstensi file (.pcap), namun Wireshark mendukung banyak format file sehingga apabila menemukan file paket data selain berformat .pcap tetap saja bisa dibuka dengan wireshark.


## Membuka File Hasil Tangkapan

Untuk membuka file paket data hasil tangkapan dilakukan dengan cara membuka menu File->Open. Kemudian akan tersaji data-data hasil tangkapan.


## Pemfilteran Paket Data


### Kenapa perlu difilter?

Bayangkan saja apabila dalam satu komputer yang menjalankan browser dengan banyak tab dan alamat web yang berbeda-beda. Kemudian, juga sambil membuat Email, Chatting, Skype, Facebook, Twitter, dll. Lalu menjalankan aplikasi wireshark, apa yang terjadi? Semua paket data akan masuk semua. 

Seperti yang sudah dijelaskan, paket-paket data jaringan dengan berbagai protokolnya kadang menyulitkan ketika akan melakukan analisa paket atau protokol tertentu. Atas dasar ini, maka dibutuhkan teknik filter data.


### Filter Paket Data Secara Langsung

Apabila ingin memfilter paket data secara langsung, Anda dapat melakukannya ketika membuka antarmuka yang akan digunakan. 

Pilih Interface -> Options -> Capture Filter , pilih salah satu filter di bagian kotak daftar Capture Filter, misalnya HTTP TCP port (80). Apabila sudah klik tombol OK kemudian klik Start untuk memulai proses sniffing.


# Tugas Praktikum

Berdasarkan data hasil tangkapan, silakan Anda lakukan filter paket berdasarkan parameter filter tertentu seperti tcp.ip, port, ip.src, ip.dst dan lain sebagainya. Sehingga mahasiswa dapat memahami apa fungsi dari filtering paket data.