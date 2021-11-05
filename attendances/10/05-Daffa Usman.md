Docker
Docker : 
	Mengemas aplikasi dengan semua dependensi yang dibutuhkannya ke dalam sebuah standar untuk deployment
	Docker membungkus semuanya menjadi sistem file lengkap yang berisi semuanya kebutuhan aplikasi dan yang menjalankan mesin virtual itu sendiri.
	Proses packaging tersebut ke dalam sebuah image lengkap dan menjamin bahwa itu portable, ketika menjalankan dilakukan dengan cara yang sama, tidak memperdulikan environment deployment yang digunakan.
Docker menggunakan Container Linux.
Linux container biasanya disebut LXC yang pada Agustus 2018.
Memanfaatkan fungsi cgroups kernel linux dari kernel linux versi 2.6.24
Linux container adalah sebuah virtualisasi sistem operasi yang dapat digunakan untuk menjalankan beberapa sistem Linux yang terisolasi pada satu host
Virtualisasi vs Container
	Docker adalah sebuah container management system yang membantu mengelola container lebih mudah dan universal.
	Memungkinkan membuat container pada virtual environment Mac/Windows di laptop dan menjalankan perintah atau mengoperasikannya.
	Perintah atau operasi yang dilakukan pada container yang dijalankan di local, akan sama seperti yang berjalan di production.
	Setiap membuat sebuah container, tidak membutuhan system operasi secara penuh
	Docker mengandalkan penggunaan kernel Linux Kernel
	Docker menghasilkan sebuah ukuran image yang kecil, compact, dan ringan untuk didistribusikan karena tidak terdapat kernel bahkan sistem operasi
Keuntungan Container
	Portability
	Quick deployment/teardown
	Managing infrastructure-like code
	Open source
	Consistency 
Produk Virtualisasi
	Berbasis hypervisor
	Oracle Virtualbox
	VMWare
	KVM
	Microsoft Hyper-V
	Berbasis container
	OpenVZ
	LXC

