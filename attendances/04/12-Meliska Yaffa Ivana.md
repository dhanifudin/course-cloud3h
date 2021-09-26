### A.	Layanan Networking
Komponen layanan networking adalah : 
1.	VIRTUAL CLOUD NETWORK (VCN)
Jaringan pribadi virtual yang disiapkan di pusat data Oracle. Dengan aturan firewall dan jenis gateway komunikasi tertentu yang dapat dipilih untuk digunakan. 
2.	SUBNETS
Subdivisi yang ditentukan dalam VCN (misalnya, 10.0.0.0/24, 10.0.1.0/24, atau 2001:DB8::/64). Subnet berisi Virtual Network Interface Cards (VNIC), yang ditautkan ke dalam instance. Setiap subnet terdiri dari rentang alamat IP yang berdekatan (untuk IPv4 dan IPv6, jika diaktifkan) yang tidak tumpang tindih dengan subnet lain dalam VCN.

3.	VNIC (Virtual Network Interface Cards)
VNIC melekat pada sebuah instance dan berada di subnet untuk mengaktifkan koneksi ke VCN subnet. VNIC menentukan bagaimana instances terhubung dengan endpoints di dalam dan di luar VCN. Setiap instans memiliki VNIC utama yang dibuat bersamaan dengan instance dan tidak dapat dihapus.

4.	PRIVATE IP
Alamat IPv4 pribadi dan informasi terkait untuk menangani instance (misalnya, nama host untuk DNS). Setiap VNIC memiliki IP pribadi primer, dan Anda dapat menambah dan menghapus IP pribadi sekunder. Alamat IP pribadi utama pada instance tidak akan berubah selama instance digunakan dan tidak dapat dihapus dari instance tersebut.

5.	PUBLIC IP
Alamat IPv4 publik dan informasi terkait. Anda dapat secara opsional menetapkan IP publik ke instances Anda atau sumber daya lain yang memiliki IP pribadi. IP publik dapat bersifat sementara atau dilindungi undang-undang.

6.	IPV6
7.	DYNAMIC ROUTING GATEWAY (DRG)
Router virtual (opsional) yang dapat Anda tambahkan ke VCN Anda. Menyediakan jalur lalu lintas jaringan pribadi antara VCN dan jaringan lokal. 

8.	INTERNET GATEWAY
Router virtual (opsional) yang dapat Anda tambahkan ke VCN. Ini menyediakan jalur untuk lalu lintas jaringan pribadi antara VCNAnda dan layanan yang didukung di Oracle Services Network.

9.	NETWORK ADDRESS TRANSLATION (NAT) GATEWAY
10.	SERVICE GATEWAY
Router virtual (opsional) yang dapat  ditambahkan ke VCN. Menyediakan jalur untuk lalu lintas jaringan pribadi antara VCN dan layanan yang didukung di Oracle Services Network.

11.	LOCAL PEERING GATEWAY (LPG)
Router virtual (opsional) yang dapat Anda tambahkan ke VCN Anda. Ini memungkinkan mengaitkan satu VCN dengan VCN lain di wilayah yang sama. Peering berarti VCN berkomunikasi menggunakan alamat IP pribadi, tanpa lalu lintas internet atau hanya melalui jaringan lokal di cloud.

12.	REMOTE PEERING CONNECTION (RPC)
Komponen yang dapat Anda tambahkan ke DRG. Ini memungkinkan mengaitkan satu VCN dengan VCN lain di wilayah yang berbeda.

13.	ROUTE TABLES
Virtual route tables untuk VCN Anda. Mereka memiliki aturan untuk merutekan lalu lintas dari subnet ke tujuan di luar VCN melalui gateway atau instance yang dikonfigurasi secara khusus. VCN Anda dilengkapi dengan tabel rute default yang kosong, dan Anda dapat menambahkan tabel rute kustom Anda sendiri.

14.	SECURITY RULES
Untuk aturan masuk dan keluar yang menentukan jenis lalu lintas (protokol dan port) yang diizinkan masuk dan keluar dari instance. Anda dapat memilih apakah aturan yang diberikan bersifat stateful atau stateless. 

15.	DHCP OPTIONS
Informasi konfigurasi yang secara otomatis diberikan ke instances saat dilakukan booting.


