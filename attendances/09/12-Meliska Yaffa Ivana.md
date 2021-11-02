### Mid Exam TI-3H
Choose one:

1. Deploy a static web using object storage services. The web requires API integration which is deployed in the Compute and Database services provided by OCI.

2. Deploy a web application in Compute and Database. Integrate upload feature using Object Storage.

Create documentation all the steps needed in video format, and upload it to Youtube.

## Object Storage
Layanan Oracle Cloud Infrastructure Object Storage adalah platform penyimpanan yang memiliki performa yang tinggi dan scalable,  menawarkan ketahanan data yang andal dan hemat biaya. Layanan Object Storage dapat menyimpan data tidak terstruktur dalam jumlah tak terbatas dari jenis konten apa pun, termasuk data analitik dan konten (seperti gambar dan video).
Dengan Object Storage, Kita dapat menyimpan atau mengambil data langsung dari internet atau dari dalam platform cloud. Object Storage menawarkan beberapa interface yang memungkinkan Kita mengelola penyimpanan dalam skala besar dengan mudah.

## a. Object Storage Resource
1. Buckets
Bucket adalah logical container untuk menyimpan objek. Pengguna atau sistem membuat bucket sesuai kebutuhan dalam suatu wilayah. Bucket dikaitkan dengan kompartemen tunggal yang memiliki policies untuk menentukan tindakan apa yang dapat dilakukan pengguna pada bucket dan pada semua objek dalam bucket.

2. Objects
Semua tipe data, apa pun tipe kontennya, disimpan sebagai objek. Sebuah objek terdiri dari objek itu sendiri dan metadata tentang objek tersebut. Setiap objek disimpan dalam bucket.

3. Namespace
Namespace Object Storage berfungsi sebagai top-level container untuk semua bucket dan objek. Pada waktu pembuatan akun, setiap penyewa Oracle Cloud Infrastructure diberi satu nama namespase Object Storage unik yang dibuat oleh sistem dan tidak dapat diubah.

4. Compartment
Kompartemen adalah primary block building yang digunakan untuk mengatur sumber daya cloud. Saat sewa, kompartemen root dibuat untuk kemudian membuat kompartemen di bawah kompartemen root untuk mengatur sumber daya.

## b. Object Storage Characteristics
1. Strong Consistency
Saat ada read request, Object Storage akan membuat salinan terbaru dari data yang ditulis ke sistem.

2. Durability
Object Storage secara aktif memantau integritas data menggunakan checksum dan secara otomatis mendeteksi dan memperbaiki data yang rusak.
Object Storage secara aktif memantau dan memastikan redundansi data. Jika kehilangan redundansi terdeteksi, Object Storage secara otomatis membuat lebih banyak salinan data.

3. Custom Metadata
Dapat menentukan metadata ekstensif kita sendiri sebagai pasangan nilai kunci untuk tujuan apa pun dan menetapkan metadata khusus ke objek dan bucket menggunakan Oracle Cloud Infrastructure CLI atau SDK.

4. Security
Object Storage memastikan keamanan data yang disimpan menggunakan enkripsi data.Data dapat diakses menggunakan kunci dekripsi yang dibuat saat mengunggah objek ke bucket. Ini digunakan bersama dengan kebijakan IAM yang mengautentikasi pengguna yang melakukan tugas.

## c. Cara akses Object Storage
- Console
- CLI
- REST API
- OCI SDK
