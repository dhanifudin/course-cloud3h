### Komputasi Awan dan Sistem Terdistribusi
## IaaS (Compute)
A.	Jenis Jenis instances :	
	Ada 2 jenis instance yaitu bare metal dan virtual machine(VM) :
1.	Bare metal : Yang memberi akses ke server fisik khusus untuk kinerja  tertinggi dan isolasi yang kuat.
2.	Virtual machine : adalah lingkungan komlutasi independent secara virtual yang berjalan diatas perangkat keras fisik bare metal. Virtualisasi memungkinkan untuk menjalankan beberapa VM yang terisolasi satu sama lain. VM ideal untuk menjalankan aplikasi yang tidak memerlukan kinerja dan sumber daya (CPU, memori, bandwidth jaringan, penyimpanan) dari keseluruhan mesin fisik.

Untuk membuat compute instance, kita dapat memilih jenis instance berdasarkan karakteristik sumber daya misalnya jumlah core CPU yang dibutuhkan, jumlah memori dan sumber daya jaringan.

B. Jenis Jenis Shape
OCI menawarkan berbagai variasi shape. Shape adalah sebuah template yang menentukan kebutuhan jumalh CPU, volume memori dan sumber daya lain nya yang dialokasikan untuk sebuah compute instance. Jenis jenis instance yaitu : 
a.	Standard shapes: dirancang untuk kebutuhan umum yang banyak digunakan pada aplikasi-aplikasi dan use cases pada umumnya. Standard shapes menyediakan sumber daya yang seimbang pada core, memori, dan jaringan. Standard shapes tersedia dengan prosesor Intel, AMD, dan Arm-based.
b.	DenseIO shapes: dirancang untuk basis data yang besar, seperti big data dan aplikasi-aplikasi yang membutuhkan performa storage yang tinggi. Shapes ini mendapat fitur NVMe berbasis SSD.
c.	GPU shapes: dirancang untuk akselerasi pada hardware terutama kebutuhan GPU termasuk Inter, AMD CPU dan prosesor grafis NVIDIA.
d.	High performance computing (HPC) shapes: dirancang untuk komputasi performa tinggi yang membutuhkan frekuensi prosesor core yang tinggi dan HPC dalam klaster jaringan yang diakses secara paralel.
e.	Optimized shapes: dirancang untuk komputasi tingkat tinggi pada frekuensi core prosesor. Shape ini juga cocok untuk kebutuhan HPC dengan low latency. Shape ini juga mendukung cluster networking.
f.	Flexible shapes : template yang dapat melakukan sejumlah OCPU dan memori Ketika melakukan launching yang membutuhkan  satu core fisik dengan multithreading simultan. Jenis jenis flexible shapes:
    •	VM.Standard.E3.Flex (AMD)
    •	VM.Standard.E4.Flex (AMD)
    •	VM.Optimized3.Flex (Intel)
    •	VM.Standard.A1.Flex (Arm processor dari Ampere)

C.	Jenis Jenis Kapasitas : 
    a.	On-demand capacity : Membayar sesuai dengan kapasitas compute yang  gunakan saja
    b.	Preemptible capacity : Saat membutuhkan sumber daya Ketika beban kerja meningkat (autoscaling) pada periode waktu tertentu, sehingga lebih hemat biaya.
    c.	Reserved capacity : Kapasitas cadangan untuk digunakan dimasa yang akan datang sesuai dengan kebutuhan. Perhitungan biaya nya berbeda dengan sumber daya yang sedang digunakan.
    d.	Dedicated capacity : menjalankan instance VM pada dedicated server sehingga sumber daya tidak dibagi dengan client/customer lain.

D.	Komponen dalam membuat VM:
    a.	Availability domain
    b.	Virtual cloud network
    c.	Key pair (untuk Linux)
    d.	Tags
    e.	Password (untuk Windows)
    f.	Image
    g.	Shape
