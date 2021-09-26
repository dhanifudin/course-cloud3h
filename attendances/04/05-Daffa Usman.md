Virtual Cloud Network
Komponen-komponen Networking :
	Virtual Cloud Network (VCM)
Jaringan pribadi virtual yang disiapkan di pusat data Oracle. Ini sangat mirip dengan jaringan konvensional, dengan aturan firewall dan jenis gateway komunikasi tertentu yang dapat dipilih untuk digunakan.
	Subnets
Subdivisi yang ditentukan dalam VCN (misalnya, 10.0.0.0/24, 10.0.1.0/24, atau 2001:DB8::/64). Subnet berisi Virtual Network Interface Cards (VNIC), yang ditautkan ke dalam instance.
	VNIC (Virtual Network Interface Cards)
VNIC melekat pada sebuah instance dan berada di subnet untuk mengaktifkan koneksi ke VCN subnet. VNIC menentukan bagaimana instances terhubung dengan endpoints di dalam dan di luar VCN.
	Private IP
Alamat IPv4 pribadi dan informasi terkait untuk menangani instance (misalnya, nama host untuk DNS). Setiap VNIC memiliki IP pribadi primer, dan Anda dapat menambah dan menghapus IP pribadi sekunder.
	Public IP
Alamat IPv4 publik dan informasi terkait. Anda dapat secara opsional menetapkan IP publik ke instances Anda atau sumber daya lain yang memiliki IP pribadi.
	IPV3
	Dynamic Routing Gateway (DRG)
Router virtual (opsional) yang dapat Anda tambahkan ke VCN Anda. Ini menyediakan jalur lalu lintas jaringan pribadi antara VCN Anda dan jaringan lokal.
	Internet Gateway
	Network Address Translation (NAT) Gateway
	Service Gateway
Router virtual (opsional) yang dapat Anda tambahkan ke VCN Anda. Ini menyediakan jalur untuk lalu lintas jaringan pribadi antara VCN Anda dan layanan yang didukung di Oracle Services Network (contoh: Oracle Cloud Infrastructure Object Storage dan Autonomous Database).
	Local Peering Gateway (LPG)
Router virtual (opsional) yang dapat Anda tambahkan ke VCN Anda. Ini memungkinkan mengaitkan satu VCN dengan VCN lain di wilayah yang sama. Peering berarti VCN berkomunikasi menggunakan alamat IP pribadi, tanpa lalu lintas internet atau hanya melalui jaringan lokal di cloud.
	Remote Peering Connection (RPC)
Komponen yang dapat Anda tambahkan ke DRG. Ini memungkinkan mengaitkan satu VCN dengan VCN lain di wilayah yang berbeda.
	Route Tables
Virtual route tables untuk VCN Anda. Mereka memiliki aturan untuk merutekan lalu lintas dari subnet ke tujuan di luar VCN melalui gateway atau instance yang dikonfigurasi secara khusus.
	Security Rules
Aturan firewall virtual untuk VCN Anda. Ini untuk aturan masuk dan keluar yang menentukan jenis lalu lintas (protokol dan port) yang diizinkan masuk dan keluar dari instance.
	DHCP Options
Informasi konfigurasi yang secara otomatis diberikan ke instances saat dilakukan booting.
