<H2>Jenis-jenis Compute<H2><br>
	Bare Metal: merupakan instances komputasi bare metal yang memberi Anda akses ke server fisik khusus untuk kinerja tertinggi dan isolasi yang kuat.<br>
	Virtual Machine: (VM) adalah lingkungan komputasi independen secara virtual yang berjalan di atas perangkat keras fisik bare metal. Virtualisasi memungkinkan untuk menjalankan beberapa VM yang terisolasi satu sama lain.<br>
<H2>Jenis-jenis Instance</H2><br>
Ketika membuat sebuah compute instance, Anda dapat memilih jenis instance yang sesuai kebutuhan berdasarkan karakteristik sumber daya misalnya jumlah core CPU yang dibutuhkan, jumlah memori, dan sumber daya jaringan.<br>
<H2>Jenis shapes</H2><br>
 Standard shapes: untuk kebutuhan umum yang banyak digunakan pada aplikasi-aplikasi dan use cases pada umumnya. <br>
 DenseIO shapes: untuk basis data yang besar, seperti big data dan aplikasi-aplikasi yang membutuhkan performa storage yang tinggi<br>
 GPU shapes: untuk akselerasi pada hardware terutama kebutuhan GPU termasuk Inter, AMD CPU dan prosesor grafis NVIDIA.<br>
 High performance computing (HPC) shapes: untuk komputasi performa tinggi yang membutuhkan frekuensi prosesor core yang tinggi dan HPC dalam klaster jaringan yang diakses secara paralel.<br>
 Optimized shapes: untuk komputasi tingkat tinggi pada frekuensi core prosesor. Shape ini juga cocok untuk kebutuhan HPC dengan low latency. Shape ini juga mendukung cluster networking.<br>
 Flexible shapes adalah sebuah tempat yang dapat melakukan kustom sejumlah OCPU dan memori ketika melakukan launching atau mengubah VM.<br>
<H2>Jenis-jenis Kapasitas</H2><br>
	On-demand capacity: cukup bayar sesuai dengan kapasitas compute yang kita gunakan saja.<br>
	Preemptible capacity: berguna saat membutuhkan sumber daya ketika beban kerja meningkat (autoscaling) pada periode waktu tertentu, sehingga lebih hemat biaya.<br>
	Reserved capacity: kapasitas cadangan yang berguna untuk masa yang akan datang sesuai dengan kebutuhan. Kapasitas cadangan yang tidak digunakan perhitungan biayanya berbeda dengan sumber daya yang sedang digunakan.<br>
	Dedicated capacity: menjalankan instance VM pada dedicated server, sehingga sumber daya tidak dibagi dengan client/customer lain.<br>
<H2>Komponen ketika membuat VM</H2><br>
	Availability domain<br>
	Virtual cloud network<br>
	Key pair (untuk Linux)<br>
	Tags<br>
	Password (untuk Windows)<br>
	Image<br>
  Shape<br>
