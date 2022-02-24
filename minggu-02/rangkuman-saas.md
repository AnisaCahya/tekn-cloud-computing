## Latihan
### 1. Membuat rangkuman
### What is the difference between IaaS, SaaS, and PaaS?
#### a. IaaS: Infrastruktur sebagai Layanan
- Menyediakan lingkungan bagi pengembang untuk membangun aplikasi yang dapat digunakan pengguna. IaaS termasuk: Pengguna membuat mesin virtual (VM) sesuai permintaan, dan dari perpustakaan gambar VM.
- Infrastruktur sebagai Layanan adalah tingkat komputasi awan yang paling dasar dan paling tidak dapat dikontrol karena menyediakan sumber daya komputasi mentah seperti server virtual, volume penyimpanan, dan komponen jaringan.
- Pelanggan tidak memiliki kendali atas sistem operasi, volume penyimpanan, atau kemampuan aplikasi individual, tetapi mengontrol pengaturan jaringan (misalnya penetapan alamat IP), aplikasi yang diterapkan, modul server web (misalnya mod_perl) dan kemungkinan kontrol terbatas atas pengaturan mesin virtual individual (misalnya memori dialokasikan ke VM).
Contoh aplikasi Iaas adalah Amazon (AWS), Digital Ocean, Microsoft Azure.
#### b. SaaS: Perangkat Lunak sebagai Layanan
- Perangkat Lunak sebagai Layanan didasarkan pada aplikasi yang dijalankan dari jarak jauh oleh vendor, dan tersedia untuk pelanggan melalui web atau intranet.
- Pelanggan tidak mengelola atau mengontrol infrastruktur cloud yang mendasarinya termasuk jaringan, server, sistem operasi, penyimpanan, atau bahkan kemampuan aplikasi individual, dengan kemungkinan pengecualian dari pengaturan konfigurasi aplikasi khusus pengguna yang terbatas.
- Menjalankan aplikasi di cloud publik. Pengguna menggunakan aplikasi ini melalui Internet. Aplikasi ini dikelola oleh Penyedia Layanan. 
Beberapa Penyedia Layanan adalah SalesForce, Microsoft (Office 365), Oracle, Google (Google Apps), dll.
#### c. PaaS: Platform sebagai Layanan
- Platform as a Service naik satu tingkat dari SaaS karena memungkinkan pelanggan untuk menyebarkan perangkat lunak mereka sendiri ke infrastruktur cloud.
- Pelanggan memiliki kendali atas sistem operasi, penyimpanan, aplikasi yang digunakan, dan kemungkinan modul server web (mis. mod_perl). Mereka tidak mengontrol infrastruktur cloud yang mendasarinya tetapi mereka memiliki kontrol lebih besar daripada dalam model SaaS.
- Hampir sama dengan IaaS tetapi perbedaannya adalah: Pengembang menyediakan aplikasi yang dijalankan oleh platform, dan PaaS tidak secara langsung membuat VM.
Contoh aplikasi PaaS adalah Heroku, salesforce, google app engine, openshift.

### SaaS Platform Architecture (Perangkat Lunak sebagai Layanan)
SaaS adalah model pengiriman umum untuk banyak aplikasi bisnis, termasuk perangkat lunak perkantoran dan perpesanan, perangkat lunak manajemen, virtualisasi, dll. Ini adalah bagian dari nomenklatur komputasi awan, bersama dengan infrastructure as a service(IaaS), platform as a service(PaaS), desktop as a service(DaaS).
#### a. Arsitektur SaaS
Dengan model ini, satu versi aplikasi, dengan konfigurasi tunggal digunakan untuk semua pelanggan. Aplikasi diinstal pada beberapa mesin untuk mendukung skalabilitas (disebut penskalaan horizontal).
Ada dua jenis utama SaaS:
- SaaS Vertikal
Perangkat Lunak yang menjawab kebutuhan industri tertentu (misalnya, perangkat lunak untuk perawatan kesehatan, pertanian, real estat, industri keuangan).
- SaaS Horizontal
Produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.
#### b. Manfaat SaaS bagi Perusahaan
- Menghemat biaya operasional dan biaya modal
- Meningkatkan efisiensi perusahaan
- Meningkatkan produktivitas karyawan
- Mempermudah analisis data
- Mempermudah akses dan mendukung fleksibilitas kerja

### SaaS (Software as a Service) Platform itecture
SaaS adalah cara untuk memberikan perangkat lunak, penyedia perangkat lunak secara terpusat menghosting satu atau lebih aplikasi dan membuatnya tersedia untuk pelanggan melalui internet.
#### a. Manfaat Platfrom SaaS
- Kesederhanaan
Aplikasi perangkat lunak yang dirancang sebagai solusi SaaS biasanya diakses melalui web melalui berbagai jenis perangkat.
- Ekonomis
Model pembayaran biaya berlangganan bulanan atau tahunan memudahkan bisnis untuk menganggarkan, memasangkan ini dengan nol biaya penyiapan infrastruktur, mudah untuk melihat bagaimana memilih untuk menggunakan solusi SaaS dapat menghemat uang bisnis.
- Keamanan
Sebagai konsumen aplikasi yang dirancang menggunakan SaaS, Anda tidak perlu khawatir dengan bagaimana data Anda dikunci. Itu disimpan dengan aman di cloud!
- Kesesuaian
Dengan instalasi perangkat lunak tradisional, pembaruan dan tambalan terkadang membutuhkan banyak waktu dan uang. Hal ini terutama berlaku di perusahaan. Namun, dengan SaaS, pelanggan cukup masuk ke layanan yang sudah ditingkatkan.
#### b. Kemampuan Solusi SaaS
Teknologi cloud seperti Microsoft Azure memungkinkan Anda menyediakan server yang dapat meng-host situs web, database, dan banyak lagi.
Solusi SaaS dapat digunakan untuk lingkungan ini dan, secara teori, menawarkan semua jenis layanan yang dapat dikembangkan sebagai aplikasi perangkat lunak yang dapat mencakup, namun tidak terbatas pada:
- Aplikasi kantor
- Email dan pesan instan
- Media sosial
- Layanan fintech
- Mengekspos  API Pihak Ketiga
- Keamanan dan otentikasi
- Pembelajaran mesin
- Kecerdasan buatan
- Layanan Lokasi
- Layanan streaming dan pencarian data
#### c. Kekurangan Platform SaaS
- Kurang kontrol
Karena aplikasi SaaS dihosting di lingkungan SaaS vendor, Anda hanya memiliki sedikit atau tidak ada kendali atas perangkat lunak yang Anda gunakan
- Ekosistem terbatas
SaaS adalah tren yang berkembang sebagai saluran distribusi perangkat lunak. Meskipun demikian, masih banyak aplikasi yang tidak menawarkan versi yang dihosting.
- Performa
Aplikasi in-house, tebal atau on-premise akan selalu berjalan lebih cepat daripada produk yang dikirim melalui internet.
- Masalah Data
Saat memilih produk SaaS, dan misalnya, dengan munculnya GDPR, bisnis harus memberikan perhatian khusus dalam hal di mana implementasi SaaS menyimpan data di cloud.  Setiap yurisdiksi memiliki kebijakan dan tindakan legislatifnya sendiri ketika data sensitif sedang diproses atau disimpan.
#### d. Komponen Utama Platform SaaS
- Keamanan
Melindungi data pelanggan di platform SaaS Anda adalah yang paling penting, dengan demikian, produk SaaS Anda kemungkinan besar akan melayani ratusan, jika tidak ribuan pengguna.  Pastikan arsitektur SaaS Anda memperhitungkan hal ini.
- Privasi
Sementara keamanan berkaitan dengan penguncian pengguna dan data sensitif, privasi merupakan komponen penting untuk dipertimbangkan ketika merancang produk SaaS Anda sendiri.
- Kustomisasi dan Konfigurasi
Meskipun Anda mungkin dapat memberikan solusi SaaS out-of-the-box untuk sebagian besar konsumen yang dikirimkan dengan serangkaian fitur standar, antarmuka pengguna, dan fungsionalitas, perusahaan sering mengharapkan penyesuaian tambahan untuk menangani kasus penggunaan khusus untuk domain masalah spesifik mereka. Anjak dalam ekstensibilitas untuk arsitektur SaaS Anda adalah komponen penting lain yang perlu Anda pertimbangkan.

### How to build a cloud-based SaaS Application
a. Memilih bahasa pemrograman
b. Memilih database berorientasi dokumen
c. Memilih sistem antrian
d. Membangun aplikasi web yang dapat diskalakan menggunakan AWS & EC2
e. Layanan penyimpanan web dengan Amazon S3
f. Membuat jaringan Pengiriman konten
g. Rekap: pengaturan aplikasi SaaS
h. Menguji Perangkat lunak

### 2. Layanan SaaS dan Non Cloud
Contoh 2 layanan SaaS adalah Canva dan Google Suite.
Sedangkan layanan non cloud yaitu CorelDRAW Graphic Suite yang mirip dengan Canva dan Microsoft Office yang mirip dengan Google Suite.