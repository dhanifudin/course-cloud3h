Object Storage
Object Storage adalah platform penyimpanan yang memiliki performa yang tinggi dan scalable,  menawarkan ketahanan data yang andal dan hemat biaya. Layanan Object Storage dapat menyimpan data tidak terstruktur dalam jumlah tak terbatas dari jenis konten apa pun, termasuk data analitik dan konten (seperti gambar dan video).
Object Storage Resource
•	Buckets
Logical container untuk menyimpan objek. Pengguna atau sistem membuat bucket sesuai kebutuhan dalam suatu wilayah.
•	Objects
Semua tipe data, apa pun tipe kontennya, disimpan sebagai objek. Sebuah objek terdiri dari objek itu sendiri dan metadata tentang objek tersebut. Setiap objek disimpan dalam bucket.
•	Namespace
Berfungsi sebagai top-level container untuk semua bucket dan objek. Pada waktu pembuatan akun, setiap penyewa Oracle Cloud Infrastructure diberi satu nama namespase Object Storage unik yang dibuat oleh sistem dan tidak dapat diubah.
•	Compartment
Primary block building yang digunakan untuk mengatur sumber daya cloud. Saat sewa, kompartemen root dibuat untuk kemudian membuat kompartemen di bawah kompartemen root untuk mengatur sumber daya Kita.

Object Storage Characteristics
•	Strong Constistency
Saat ada read request, Object Storage akan membuat salinan terbaru dari data yang ditulis ke sistem.
•	Durability
Object Storage secara aktif memantau dan memastikan redundansi data. Jika kehilangan redundansi terdeteksi, Object Storage secara otomatis membuat lebih banyak salinan data.
•	Custom Metadata
Kita dapat menentukan metadata ekstensif kita sendiri sebagai pasangan nilai kunci untuk tujuan apa pun.
•	Security
Object Storage memastikan keamanan data yang disimpan menggunakan enkripsi data.

Cara akses Object Storage
Kita dapat mengakses Object Storage menggunakan beberapa cara, OCI menyediakan sesuai dengan preferensi kita dan sesuai dengan kebutuhan.
•	Console
•	CLI
•	REST API
•	OCI SDK

