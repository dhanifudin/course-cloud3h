Oracle Cloud Infrastructure
2 jenis Instansi OCI :
1.	Bare Metal : instansi komputasi yang memberi akses ke server fisik khusus untuk kinerja tertinggi dan isolasi kuat.
2.	Virtual Machine : lingkungan komputasi independent secara virtual yang berjalan di atas perangkat keras fisik bare metal.
Jenis instansi yang dibutuhkan bisa dipilih sesuai kebutuhan Ketika membuat sebuah compute instance. Misalnya jumlah core CPU yang dibutuhkanm jumlah memori, dan sumber daya jaringan.
Shapes : sebuah templat yang menentukan kebutuhan jumlah CPU, volume memori, dan sumber daya lainnya yang dialokasikan untuk sebuah compute instance.
Jenis-jenis shape :
•	Standard shapes : untuk kebutuhan umum yang banyak digunakan pada aplikasi dan use case pada umumnya.
•	DenseIO shapes : untuk basis data yang besar, seperti big data dan aplikasi-aplikasi yang membutuhkan performa storage yang tinggi.
•	GPU shapes : untuk akselerasi pada hardware terutama kebutuhan GPU seperti Intel, AMD dan kartu grafis NVIDIA.
•	High performance computing (HPC) shapes : dirancang untuk komputasi performa tinggi yang membutuhkan frekuensi prosesor core yang tinggi.
•	Optimized shapes : untuk komputasi tingkat tinggi pada frekuensi core prosesor. Juga cocok untuk kebutuhan HPC dengan low latency.
Flexible Shapes : Merupakan sebuah templat yang dapat melakukan kustom sebuah OCPU dan memori Ketika melakukan launching atau mengubah VM. Pilihan jumlah OCPU dan volume memori yang dibutuhkan dapat disesuaikan.
Jenis-jenis Flexible shapes :
	VM.Standard.E3.Flex (AMD)
	VM.Standard.E4.Flex (AMD)
	VM.Optimized3.Flex (Intel)
	VM.Standard.A1.Flex (Arm processor dari Ampere)
Masing-masing memiliki perbedaan pada memory per OCPU, Minimum memory, dan maximum memory.
Jenis-jenis kapasitas tiap host :
o	On-demand capacity : cukup bayar sesuai dengan kapasitas yang digunakan.
o	Preemptible capacity : berguna Ketika membutuhkan sumber daya lebih dikala beban kerja meningkat.
o	Reserved capacity : kapasitas cadangan yang berguna untuk masa yang akan dating sesuai dengan kebutuhan.
o	Dedicated capacity : instansi VM pada dedicated server sehingga sumber daya tidak dibagi dengan yang lainnya.
Komponen ketika membuat VM :
	Availability domain
	Virtual cloud network
	Key pair (untuk Linux)
	Tags
	Password (untuk Windows)
	Image
	Shape
