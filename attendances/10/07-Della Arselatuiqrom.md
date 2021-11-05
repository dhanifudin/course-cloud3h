Summary Week 10 :

Latar Belakang Docker :
- Mengemas aplikasi dengan semua dependensi yang dibutuhkannya ke dalam sebuah standar untuk deployment
- Docker membungkus semuanya menjadi sistem file lengkap yang berisi semuanya kebutuhan aplikasi dan yang menjalankan mesin virtual itu sendiri.
- Proses packaging tersebut ke dalam sebuah image lengkap dan menjamin bahwa itu portable, ketika menjalankan dilakukan dengan cara yang sama, tidak memperdulikan environment deployment yang digunakan.

Sejarah Docker :
- Dimulai sebagai project internal oleh dotCloud.
- 2013 menjadi sebuah project open source.
- dotCloud merupakan penyedia platform as as service yang mengizinkan menjalankan aplikasi tanpa khwatir masalah infrastruktur.
- Mereka membutuhkan sebuah lebih banyak virtual machine dan lebih cepat.

Containerization :
- Docker menggunakan Container Linux.
- Linux container biasanya disebut LXC yang pada Agustus 2018.
- Memanfaatkan fungsi cgroups kernel linux dari kernel linux versi 2.6.24
- Linux container adalah sebuah virtualisasi sistem operasi yang dapat digunakan untuk menjalankan beberapa sistem Linux yang terisolasi pada satu host

Apakah docker itu ?
- Docker adalah sebuah command-line program, sebuah background daemon dan serangkaian remote service dengan mengambil pendekatan logistic untuk memecahkan permasalahan umum perangkat lunak dan menyederhanakan pengalaman kita dalam installing, running, publishing, dan menghapus perangkat lunak.
- Docker bukan bahasa pemrograman dan bukan sebuah framework untuk membangun perangkat lunak

Perintah dasar docker :
- docker run: sebuah perintah untuk menjalankan container, ketika baru dijalankan pertama kali maka akan mencari/download image.
- docker build: digunakan untuk membuat sebuah docker image dari sebuah Dockerfile. Perintah ini secara default akan mencari di direktori saat ini tetapi dapat juga menggunakan spesifik PATH atau URL.
- docker images: perintah ini akan menampilkan semua image yang ada, informasi seperti tag dan ukuran akan ditampilkan.
