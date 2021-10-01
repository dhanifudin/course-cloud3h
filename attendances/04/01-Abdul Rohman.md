<H1>Virtual Cloud Network</H1> <br>
**Komponen-komponen Networking**<br>
	**VIRTUAL CLOUD NETWORK (VCN)**<br>
Jaringan pribadi virtual yang disiapkan di pusat data Oracle. Ini sangat mirip dengan jaringan konvensional, dengan aturan firewall dan jenis gateway komunikasi tertentu yang dapat dipilih untuk digunakan.<br>
	**SUBNETS**<br>
Subnet berisi Virtual Network Interface Cards (VNIC),<br>
	**VNIC (Virtual Network Interface Cards)**<br>
VNIC melekat pada sebuah instance dan berada di subnet untuk mengaktifkan koneksi ke VCN subnet.<br>
	**PRIVATE IP**<br>
Alamat IPv4 pribadi dan informasi terkait untuk menangani instance (misalnya, nama host untuk DNS).<br>
	**PUBLIC IP**<br>
Alamat IPv4 publik dan informasi terkait.<br>
	IPV6<br>
	**DYNAMIC ROUTING GATEWAY (DRG)**<br>
Router virtual (opsional) yang dapat Anda tambahkan ke VCN Anda. Ini menyediakan jalur lalu lintas jaringan pribadi antara VCN Anda dan jaringan lokal<br>
	**INTERNET GATEWAY**<br>
	**NETWORK ADDRESS TRANSLATION (NAT) GATEWAY**<br>
	**SERVICE GATEWAY**<br>
Ini menyediakan jalur untuk lalu lintas jaringan pribadi antara VCN Anda dan layanan yang didukung di Oracle Services Network<br>
	**LOCAL PEERING GATEWAY (LPG)**<br>
Ini memungkinkan mengaitkan satu VCN dengan VCN lain di wilayah yang sama.<br>
	**REMOTE PEERING CONNECTION (RPC)**<br>
Komponen yang dapat Anda tambahkan ke DRG. Ini memungkinkan mengaitkan satu VCN dengan VCN lain di wilayah yang berbeda.<br>
	**ROUTE TABLES**<br>
Mereka memiliki aturan untuk merutekan lalu lintas dari subnet ke tujuan di luar VCN melalui gateway atau instance yang dikonfigurasi secara khusus<br>
	**SECURITY RULES**<br>
Ini untuk aturan masuk dan keluar yang menentukan jenis lalu lintas (protokol dan port) yang diizinkan masuk dan keluar dari instance.<br>
	**DHCP OPTIONS**<br>
Informasi konfigurasi yang secara otomatis diberikan ke instances saat dilakukan booting.<br>

