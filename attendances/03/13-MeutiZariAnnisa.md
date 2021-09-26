# OCI

## Jenis Shape Pada Instance

1. Standard shape
<br>Untuk kebutuhan ummum yang banyak digunakan pada aplikasi aplikasi dan use cases yang umum. shape ini memnyediakan sumber daya yang seimbang pada core, memory, dan network. Standard shapes teersedia pada berbagai processor seperti processor Intel, AMD, dan Arm-based

2. DenseIO shapes
<br>Shape ini dirancang untuk basis data yang besar seperti contohnya saja big data lalu juga aplikasi aplikasi yang membutuhkan performa yang tinggi pada storage. Shape ini memiliki fitur NVMe berbasis SSD.

3. GPU shapes
<br>Shape ini dirancang untuk akselerasi pada hardware terutama kebutuhan GPU termasuk Intel, AMP CPU dan graphic processor NVIDIA.

4. High Performance Computing (HPC) shapes
<br>Shape ini dirancang untuk komputasi performa tinggi yang mmebutuhkan frekuensi processor core yang tinggi dan HPC dalam klaster jaringan yang diakses secara paralel.

5. Optimized shapes
<br> Shape ini dirancang untuk komputasi tingkat tinggi pada frekuensi core processor. Shape ini juga cocok untuk kebutuhan HPC dengan low latency. Shape ini juga mendukung cluster networking.

## Flexible shape
- Flexible shapes adalah sebuah tempate yang dapat melakukan custom sejumlah OCPU dan memori ketika melakukan launching atau mengubah VM.
- OCPU ekuivalen dengan satu core fisik dengan multithreading simultan (hyper-threading), di mana setiap OCPU merujuk pada dua hardware yang mengeksekusi threads (juga dikenal sebagai virtual CPUs atau vCPUs)

- Saat pembuatan Vitrtual machine menggunakan flexible shape, pilihan jumlah OCPU dan volume memroi yang dibutuhkan dapat disesuaikan.

- Terdapat beberapa jenis flexible shape yang tersedia:
    - VM.Standard.E3.Flex (AMD)
    - VM.Standard.E4.Flex (AMD)
    - VM.Optimized3.Flex (Intel)
    - VM.Standard.A1.Flex (arm Processor dari Ampere)

## Jenis-Jenis Kapasitas
Untuk kapasitas dari tiap jenis host yang digunakan dapat dikustomisasi pada VM. Secara default, kapasitas jenis on-demand sudah terpilih, tetapi juga memungkinkan untuk memilih jenis kapasitas lainnya.
- On-demand capacity
<br> Kita cukup membayar sesuai dengan kapasitas compute yang kita gunakan saja.

- Preemptible capacity
<br> Jenis kapasitas ini berguna saat membutuhkan sumber daya ketika beban kerja meningkat (autoscaling) pada periode waktu tertentu, sehingga lebih hemat biaya

- Reserved capacity
<br>Kapasitas cadangan yang berguna untuk masa yang akan datang sesuai dengan kebutuhan. Kapasitas cadangan yang tidak digunakan perhitungan biayanya berbeda dengan sumber daya yang sedang digunakan.

- Dedicated capacity
<br> Kapasitas ini menjalankan instance VM pada dedicated server, sehingga sumber daya tidak dibagi dengan client/suctomer lain.

## Komponen ketika membuat VM

- Availability domain (yang merupakan lokasi data center oracle secara geografis)
- Virtual cloud network (yang merupakan konfigurasi jaringan seprerti subnet, route table, gateway)
- Key pair (untuk Linux)(Mekanisme keamanan untuk keomunikasi Secure Shell (SSH) ke instance)
- Tags (untuk membantu mengolah instance menggunakan tag atau keyword tertentu agar mudah ditemukan)
- Password (Untuk Windows) (Mekanisme keamanan untuk mengakses instance yang menggunakan platform Windows)
- Image (template untuk virtual hard drive yang menentukan operation system dan software lainnya dalam sebuah instance)
- Shape (template untuk menentukan jumlah CPU, volume memory, dan alokasi sumber daya lainnya ketika membuat instance baru)

> Aplikasi yang digunakan bisa menggunakan Termius atau Putty