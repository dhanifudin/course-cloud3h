#### Docker 2

## 1. Docker Network
    Tipe Docker network
# a. Bridge
Merupakan jenis network bawaan dari Docker. Ketika Docker service daemon berjalan, akan melakukan konfigurasi sebuah virtual bridge disebut dengan docker0.
Docker daemon akan terhubung secara default ke container menggunakan bridge network, jika network tidak dimasukkan secara spesifik.

# b. Host 
Docker network jenis ini yaitu meletakkan container di dalam stack hostnya network.
Semua antarmuka jaringan yang telah didefinisikan dapat diakses melalui container.
Ketika kita menjalankan container menggunakan parameter –net=host, sehingga container akan menggunakan network host. Ketika menggunakan host network akan secepat jaringan normal karena tidak ada menggunakan bridge ataupun translation


# c. None
Network None bertujuan untuk tidak mengkonfigurasi networking.
Tidak ada driver yang digunakan pada Network jenis ini.
Ketika kita tidak menginginkan container untuk dapat diakses. Perintah yang digunakan dengan menambahkan parameter –net=none

Perintah Networking Docker
Perintah yang dasar digunakan adalah docker network kemudian ditambahkan beberapa parameter setelah perintah dasar.
Docker network ls; untuk mengetahui network yang tersedia pada host docker
Docker network create; untuk membuat sebuah network pada host docker.
Docker network rm; untuk menghapus network yang terdapat pada host docker.
Docker network connect; untuk menghubungkan container pada spesifik network
Docker network disconnect; memutus network pada container
Docker network inspect; untuk mengetahui secara terperinci dari sebuah network, misalkan ip address dan informasi lain


## 2. Docker Volume 
Docker volume create; untuk membuat sebuah volume
Docker volume inspect; menampilkan detail informasi pada satu atau lebih dari satu volume.
Docker volume ls; menampilkan daftar volume.
Docker volume rm; menghapus satu atau lebih volume yang terdapat pada docker host.
Docker volume prune; menghapus semua volume yang tidak digunakan, semua volume yang sudah tidak digunakan oleh container akan dihapus.

Docker Volume Driver
Sama halnya dengan network yang memiliki driver, volume juga memiliki jenis-jenis volume agar mampu terintegrasi dengan jenis penyimpanan yang lain.
Docker volume driver for Azure file storage; sebuah driver docker volume yang digunakan Azure file storage untuk mount file yang dishare pada cloud ke Docker container sebagai volume.
IPFS(InterPlanetary File System); sebuah plugin volume open source yang mengizinkan menggunakan sebuah IPFS filesystem sebagai sebuah volume. IPFS adalah sebuah sistem storage yang sangat menarik dan menjanjikan, memungkinkan dalam mendistribusikan high volume data dengan efisiensi yang tinggi.

## 3. Docker Compose
Docker compose adalah sebuah tool untuk mendefiniskan, launching, dan mengelola service, dimana sebuah service adalah didefinisikan sebagai satu atau lebih dari sebuah docker container.
Service dan sistem service didefinisikan di dalam file YAML dan mengelolanya menggunakan perintah command-line docker-compose.
Beberapa hal yang bisa dilakukan menggunakan docker compose adalah build docker image, menjalankan aplikasi container sebagai service, menjalankan full system dari service, mengelola secara individu service pada sebuah sistem, melakukan scaling up atau down, dan melihat log dari kumpulan container yang berjalan sebagai service.

Perintah dasar Docker Compose :
Docker-compose up; membuat dan menjalankan container, ketika ditambakan parameter –d maka container akan berjalan sebagai daemon.
Docker-compose down; menghentikan dan menghapus semua resource
Docker-compose logs; melihat logging pada container
Docker-compose ps; melihat container yang sedang berjalan

