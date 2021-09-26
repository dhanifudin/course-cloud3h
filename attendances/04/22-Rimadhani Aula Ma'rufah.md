VIRTUAL CLOUD NETWORK
KOMPONEN-KOMPONEN NETWORKING
  1. VIRTUAL CLOUD NETWORK (VCN)
     Jaringan pribadi virtual yang disiapkan pada pusat data Oracle, VCN berada di satu region Oracle Cloud Infrastructure dan mencakup satu atau beberapa blok CIDR(IPv4 dan IPv6, jika diaktifkan)
  2. SUBNET 
     Subnet berisi Virtual Network Interface Cards(VNIC), yang ditautkan ke dalam instance. Setiap subnet terdiri dari rentang alamat IP yang berdekatan (untuk IPv4 dan IPv6, jika diaktifkan) yang tidak tumpang tindih dengan subnet lain dalan VCN.
  3. VIRTUAL NETWORK INTERFACE CARDS (VNIC)
     VNIC melekat pada sebuah instance dan berada di subnet untuk mengaktifkan koneksi ke VCN subnet. VNIC menentukan bagaimana instance terhubung dengan endpoints di dalam dan di luar VCN.
  4. PRIVATE IP
     Alamat IPv4 pribadi dan informasi terkait untuk menangani instance. Setiap VNIC memiliki IP pribadi primer, dan anda dapat menambah dan menghapus IP pribadi sekunder.
  5. PUBLIC IP 
     IP publik dapat bersifat sementara dan dilindungi undang-undang.
  6. DYNAMIC ROUTING GATEWAY (DRG) 
     Router virtual (opsional) dapat di tambahkan kepada VCN user, router juga menyediakan jalur lintas jaringan pribadi antara VCN user dengan jaringan lokal. 
  7. SERVICE GATEWAY 
     Sistem DB di subnet pribadi di VCN Anda dapat mencadangkan data ke Object Storage tanpa memerlukan alamat IP publik atau akses ke internet.
  8. LOCAL PEERING GATEWAY (LPG)
     Peering berarti VCN berkomunikasi menggunakan alamat IP pribadi, tanpa lalu lintas internet atau hanya melalui jaringan lokal di cloud. VCN tertentu harus memiliki LPG terpisah untuk setiap peering yang dibuatnya.
  9. REMOTE PEERING CONNECTION (RPC) 
     Komponen yang dapat di tambahkan ke dalam DRG, komponen ini memungkinkan mengaitkan satu VCN dengan VCN lain di wilayah yang berbeda.
 10. ROUTE TABLES 
     Virtual route tables memiliki aturan untuk merutekan lalu lintas dari subnet ke tujuan di luar VCN melalui gateway atau instance yang dikonfigurasikan secara khusus. 
 11. SECURITY RULES 
     Grup keamanan jaringan terdiri dari seperangkat aturan keamanan yang hanya berlaku untuk sumber daya dalam grup tersebut.
 12. DHCP OPTION
     Informasi konfigurasi yang secara otomatis diberikan ke instances saat dilakukan booting.

