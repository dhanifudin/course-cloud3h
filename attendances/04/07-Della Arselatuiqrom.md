Summary Week 4 about Virtual Cloud Network :

- Komponen-komponen Networking : 

1.	VIRTUAL CLOUD NETWORK (VCN)
Jaringan pribadi virtual yang disiapkan di pusat data Oracle. Ini sangat mirip dengan jaringan konvensional, dengan aturan firewall dan jenis gateway komunikasi tertentu yang dapat dipilih untuk digunakan. 

2.	SUBNETS
Subdivisi yang ditentukan dalam VCN (misalnya, 10.0.0.0/24, 10.0.1.0/24, atau 2001:DB8::/64). Subnet berisi Virtual Network Interface Cards (VNIC), yang ditautkan ke dalam instance. Setiap subnet terdiri dari rentang alamat IP yang berdekatan (untuk IPv4 dan IPv6, jika diaktifkan) yang tidak tumpang tindih dengan subnet lain dalam VCN.

3.	VNIC (Virtual Network Interface Cards)
VNIC melekat pada sebuah instance dan berada di subnet untuk mengaktifkan koneksi ke VCN subnet. 

4.	PRIVATE IP
Alamat IPv4 pribadi dan informasi terkait untuk menangani instance (misalnya, nama host untuk DNS). 

5.	PUBLIC IP
Alamat IPv4 publik dan informasi terkait. Anda dapat secara opsional menetapkan IP publik ke instances Anda atau sumber daya lain yang memiliki IP pribadi. 

6.	DYNAMIC ROUTING GATEWAY (DRG)
Router virtual (opsional) yang dapat Anda tambahkan ke VCN Anda. Ini menyediakan jalur lalu lintas jaringan pribadi antara VCN Anda dan jaringan lokal. Anda dapat menggunakannya dengan komponen Jaringan lain dan router di jaringan lokal Anda untuk membuat koneksi melalui Site-to-Site VPN atau OCI FastConnect.


7.	SERVICE GATEWAY
Router virtual (opsional) yang dapat Anda tambahkan ke VCN Anda. Ini menyediakan jalur untuk lalu lintas jaringan pribadi antara VCN Anda dan layanan yang didukung di Oracle Services Network (contoh: Oracle Cloud Infrastructure Object Storage dan Autonomous Database). 

8.	LOCAL PEERING GATEWAY (LPG)
Router virtual (opsional) yang dapat Anda tambahkan ke VCN Anda. Ini memungkinkan mengaitkan satu VCN dengan VCN lain di wilayah yang sama. Peering berarti VCN berkomunikasi menggunakan alamat IP pribadi, tanpa lalu lintas internet atau hanya melalui jaringan lokal di cloud.

9.	REMOTE PEERING CONNECTION (RPC)
Komponen yang dapat Anda tambahkan ke DRG. Ini memungkinkan mengaitkan satu VCN dengan VCN lain di wilayah yang berbeda.

10.	ROUTE TABLES
Virtual route tables untuk VCN Anda. Mereka memiliki aturan untuk merutekan lalu lintas dari subnet ke tujuan di luar VCN melalui gateway atau instance yang dikonfigurasi secara khusus.

11.	SECURITY RULES
Aturan firewall virtual untuk VCN Anda. Ini untuk aturan masuk dan keluar yang menentukan jenis lalu lintas (protokol dan port) yang diizinkan masuk dan keluar dari instance. Anda dapat memilih apakah aturan yang diberikan bersifat stateful atau stateless. 

12.	DHCP OPTIONS
Informasi konfigurasi yang secara otomatis diberikan ke instances saat dilakukan booting.

