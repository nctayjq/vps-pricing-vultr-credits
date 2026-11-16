# Sewa VPS Murah: Rp 10.000/Bulan Cukup untuk Apa, Kapan Perlu Naik ke $5, dan Bagaimana Kredit $300 Vultr Bekerja

VPS termurah yang bisa Anda sewa di Indonesia sekarang ada di angka **Rp 10.000 per bulan**, tapi itu paket NAT dengan IPv4 bersama dan jatah port forward terbatas. Kalau yang Anda butuhkan IP publik sendiri, harga mulai Rp 50.000. Di sisi lain, Vultr menjual Cloud Compute mulai **$5 per bulan** (sekitar Rp 80.000 dengan kurs Rp 16.000/USD) dan memberi kredit promosi $300 untuk akun baru, dengan masa pakai 30 hari.

Dua angka itu menjawab dua kebutuhan yang berbeda. Artikel ini memisahkan keduanya: berapa harga sewa bulanan terendah di pasar lokal, apa yang sebenarnya Anda dapat di harga itu, dan kapan cloud internasional seperti Vultr justru lebih masuk akal meski harga per bulannya lebih tinggi.

> **Ringkasan cepat:** untuk satu server kecil dengan IP publik, OS Linux bebas, dan kebutuhan mencoba beberapa region sebelum berkomitmen, mulai dari paket Cloud Compute $5–$6 per bulan di Vultr dan manfaatkan kredit $300 pada 30 hari pertama. 👉 [Lihat paket $5–$6 dan kredit $300 untuk akun baru Vultr](https://bit.ly/VuLtr)

## Harga sewa VPS murah di Indonesia ada di kisaran berapa?

Lima penyedia lokal yang kami periksa memakai patokan yang jauh berbeda, dari Rp 10.000 sampai Rp 100.000 per bulan. Selisih sepuluh kali itu bukan pertandingan harga yang setara, karena ujung termurahnya adalah VPS NAT, bukan VPS dengan IP sendiri.

| Penyedia | Paket termurah | Spesifikasi | Harga/bulan | Catatan |
| --- | --- | --- | --- | --- |
| Cloudra | NAT S1 | 2 core, 2 GB RAM, 30 GB SSD, 10 port forward | Rp 10.000 | IPv4 bersama, bukan IP sendiri |
| VPSIndonesia | Nano | 1 vCPU, 512 MB RAM, 20 GB NVMe, Jakarta | Rp 20.000 | QRIS, aktivasi otomatis |
| ProwCloud | RDP/VPS NAT | 1 core, 2 GB RAM, 15 GB SSD | Rp 25.000 | Setup 1–6 jam, dikerjakan manual |
| Rumahweb | XS | 1 vCPU, 512 MB RAM, 10 GB SSD | Rp 50.000 | IP publik, KVM, unmanaged |
| JagoanHosting | General Purpose | 2 vCPU, 2 GB RAM | Rp 100.000 | Halaman 2024, harga bisa sudah berubah |

Rp 10.000 di Cloudra memberi 2 core dan 2 GB RAM, spesifikasi yang di Vultr baru didapat di paket $20. Selisihnya ada di IP: paket NAT berbagi satu IPv4 publik dengan pelanggan lain, dan Anda hanya mendapat 10 sampai 15 port forward yang bisa dibuka. ProwCloud menyebut model ini bisa menekan biaya sampai 70% dibanding VPS ber-IP dedicated, dan angka itu masuk akal karena satu alamat IPv4 dipakai bersama.

Dua catatan sebelum Anda memegang angka di tabel. Halaman VPSIndonesia menampilkan dua harga berbeda untuk paket Mini, Rp 30.000 di judul dan Rp 40.000 di kartu harga, jadi jangan pakai salah satunya sebagai patokan. Halaman JagoanHosting yang kami baca bertanggal Mei 2024, sehingga harga Rp 100.000 itu adalah angka yang tampil saat itu, bukan harga hari ini.

## Paket Vultr dan harganya per November 2026

Vultr menjual beberapa lini Cloud Compute. Regular Performance memakai CPU Intel generasi sebelumnya dengan SSD standar. High Frequency dan High Performance memakai NVMe, dengan pilihan prosesor AMD EPYC atau Intel Xeon. Semua instance ditagih per jam dengan batas harga bulanan, jadi server yang dihapus di tengah bulan hanya kena biaya jam pemakaian.

| Lini | vCPU / RAM / Disk | Transfer | Harga/bulan | Cocok untuk |
| --- | --- | --- | --- | --- |
| IPv6-only | 0,5 GB RAM | – | **$2,50** | Uji coba, hanya tersedia di beberapa lokasi AS |
| Regular Performance | 1 vCPU / 1 GB / 25 GB SSD | 1 TB | **$5** | Bot, situs ringan, belajar Linux |
| Regular Performance | 2 vCPU / 4 GB | – | **$20** | WordPress plus WooCommerce kecil |
| High Frequency / High Performance | 1 vCPU / 1 GB / 25 GB NVMe | – | **mulai $6** | Produksi ringan, database kecil |
| High Performance | 4 vCPU / 8 GB | – | **$48** | Aplikasi, CI runner, staging |
| High Performance | 8 vCPU / 16 GB | – | **$96** | Uji beban sebelum migrasi |
| Paket terbesar yang dilacak | 12 vCPU / 24 GB | – | **$216** | Database, kompilasi, beban berat |

Harga di atas dicek 12 November 2026. Konfigurasi lain di lini yang sama (rentang 2 sampai 24 vCPU) tersedia di halaman resmi, dan semuanya memakai penyimpanan NVMe kecuali lini Regular Performance yang masih SSD.

Satu hal yang membedakan Vultr dari penyedia lokal: tidak ada harga perkenalan. Harga yang Anda lihat saat mendaftar adalah harga yang Anda bayar di bulan berikutnya, jadi tidak ada lonjakan saat perpanjangan.

## Kredit $300 Vultr: siapa yang dapat dan berapa lama berlaku

Kredit ini bukan diskon bulanan dan bukan saldo tunai. Ketentuannya:

- Hanya untuk akun baru, tidak bisa digabung dengan promo lain.
- Berlaku untuk produk tertentu (Cloud Compute, High Frequency, Optimized Cloud Compute), tidak untuk semua layanan.
- Anda harus memasang metode pembayaran lebih dulu, kartu kredit/debit atau PayPal minimal $1.
- Kode promo yang tercantum di halaman resmi adalah **FLY300VULTR**, dan kredit muncul di menu Billing setelah diterapkan.
- **Masa pakai 30 hari**, tidak bisa dicairkan, dan sisa saldo hangus setelah periode itu.

Karena tenggatnya 30 hari, cara membelanjakan kredit menentukan hasilnya. Satu instance $6 per bulan hanya memakai sekitar $6 dari $300 selama 30 hari, dan $294 sisanya menguap tanpa Anda rasakan. Kalau tujuannya mengukur performa, pakai paket yang benar-benar akan Anda beli setelah masa promo: satu instance 8 vCPU/16 GB di $96 memakai $96 dalam 30 hari, dan masih ada ruang untuk menguji beberapa region sekaligus. Alternatif lain, $300 cukup untuk menjalankan sekitar 50 server kecil $6 secara bersamaan selama sebulan penuh.

Yang perlu diingat, kredit ini berhenti otomatis setelah 30 hari. Setelah itu tagihan masuk ke metode pembayaran Anda dengan tarif normal.

👉 [Daftar akun baru dan terapkan kredit $300 sebelum masa berlakunya habis](https://bit.ly/VuLtr)

## Biaya tambahan yang tidak muncul di harga depan

Harga $5 atau $6 di tabel tadi adalah harga mesin kosong. Beberapa komponen di Vultr ditagih terpisah dan cukup mudah membuat perhitungan bulanan Anda meleset:

- Backup otomatis menambah **20%** dari harga instance.
- Snapshot $0,05 per GB per bulan.
- DDoS Protection tambahan $10 per bulan per instance.
- Kelebihan transfer $0,01 per GB, dan paket termurah hanya mendapat jatah 2 TB.
- Dukungan lewat tiket 24 jam, tanpa live chat atau telepon untuk akun standar.

Penyedia lokal punya kejutan sendiri, dan justru ini yang paling sering luput dari artikel perbandingan.

**Unmanaged adalah default.** Rumahweb hanya memastikan server menyala dan berjalan; isi dan konfigurasinya Anda kelola sendiri. Bantuan pengelolaan penuh dijual terpisah di Rp 250.000 per bulan, di luar lisensi cPanel.

**Tidak bisa turun paket.** Kalau kebutuhan Anda menyusut, satu-satunya jalan adalah membuat VPS baru dan memindahkan data sendiri. Penyedia tidak membantu proses migrasi.

**Port 25 ditutup.** Pengiriman email tidak jalan sampai Anda mengajukan whitelist dan lolos verifikasi.

**Backup resmi bukan untuk Anda.** Rumahweb menjalankan backup internal dua kali seminggu, tapi itu hanya dipakai memulihkan hardware yang rusak. Pelanggan tidak bisa mengaksesnya, jadi backup harian tetap tanggung jawab Anda.

**Aktivasi tidak selalu instan.** VPSIndonesia mengklaim di bawah 10 menit dan Rumahweb menyebut aktivasi instan, tapi ProwCloud butuh 1 sampai 6 jam, maksimal 1x24 jam, karena server dikonfigurasi manual oleh pemiliknya.

## NAT atau IP publik: ini yang menentukan paket murah Anda berguna atau tidak

VPS NAT memang jauh lebih murah, dengan konsekuensi yang jelas. Di Cloudra, paket NAT S1 hanya memberi 10 port forward dan S2 memberi 15, sementara paket VPS-nya memberi satu IPv4 dedicated plus satu IPv6. ProwCloud menulis hal yang sama: port publik dibatasi sesuai alokasi, bukan membuka seluruh port seperti IP dedicated.

Artinya, menjalankan VPN server, game server dengan banyak port, atau mail server di paket NAT akan menyiksa. Untuk bot Telegram, web portofolio, panel admin, atau server Minecraft dengan satu port, NAT sudah cukup.

Di Vultr, satu-satunya paket tanpa IPv4 publik adalah paket IPv6-only $2,50 yang juga hanya bisa dipasang di beberapa lokasi AS. Sisanya mendapat IPv4, dan tidak ada batasan port forward seperti di paket NAT lokal.

## Lokasi server: Singapura terdekat, tidak ada Jakarta

Dari 32 lokasi data center yang tercantum, Vultr tidak punya titik di Indonesia. Yang terdekat adalah Singapura, lalu Osaka, Tokyo, Seoul, Mumbai, Sydney, dan Melbourne.

Untuk pengunjung Indonesia, server Jakarta tetap lebih cepat. Rumahweb menyebut alasan yang masuk akal: latensi rendah ke ISP lokal membuat TTFB lebih baik, yang berpengaruh ke Core Web Vitals, dan data tetap berada di yurisdiksi Indonesia sesuai UU PDP.

Vultr menang di kebutuhan sebaliknya. Anda butuh satu server di Frankfurt untuk pengguna Eropa, satu di São Paulo untuk pasar Brasil, dan satu di Sydney untuk Australia, semua dari satu panel. Perlu dicatat, harga di sebagian besar region sama, tapi São Paulo sekitar 50% lebih mahal untuk paket yang identik.

## Cara memilih paket sesuai beban, bukan sesuai harga termurah

- **Belajar Linux, bot Telegram/WhatsApp, Uptime Kuma, Pi-hole.** Paket 1 GB sudah lebih dari cukup. Di Vultr itu $5 (Regular) atau $6 (NVMe). Di lokal, VPSIndonesia Nano Rp 20.000 untuk keperluan yang sama.
- **Satu WordPress dengan pengunjung di bawah 10.000 per bulan.** Rumahweb menyebut 1 core dan 1 GB RAM sudah memadai. Jangan bayar lebih untuk kasus ini.
- **WooCommerce atau situs dengan banyak plugin.** Minimal 2 core dan 2–4 GB RAM. Di Vultr lini Regular Performance 2 vCPU/4 GB ada di $20 per bulan.
- **Butuh IP publik dan audiens Anda di Indonesia.** VPS lokal Rp 50.000 dengan IP publik lebih masuk akal daripada $5 Vultr yang servernya di Singapura.
- **Butuh menguji banyak region atau beban produksi sebelum migrasi.** Kredit $300 Vultr dibuat untuk skenario ini.
- **Butuh server yang hidup hanya beberapa jam untuk testing.** Penagihan per jam Vultr membuat biayanya hampir nol, sementara paket lokal ditagih bulanan.

## Pertanyaan yang sering muncul

**Bisa bayar pakai QRIS?**
Di Vultr tidak. Metode pembayaran yang tersedia adalah kartu kredit/debit dan PayPal. QRIS justru standar di penyedia lokal seperti VPSIndonesia dan ProwCloud, dan itu alasan banyak orang memilih mereka meski spesifikasinya lebih kecil.

**Berapa lama server aktif setelah bayar?**
Di Vultr, deployment dilakukan dari panel setelah pembayaran terpasang, tanpa antre konfirmasi manual. Di lokal, VPSIndonesia menyebut di bawah 10 menit, Rumahweb menyebut instan, sementara ProwCloud 1–6 jam.

**Apakah harga perpanjangan naik?**
Vultr tidak memakai harga perkenalan, jadi tarif bulan kedua sama dengan bulan pertama. Penyedia lokal umumnya juga memakai harga tetap, tapi selalu cek halaman order sebelum membayar karena beberapa halaman lama masih beredar.

**Bisa berhenti kapan saja?**
Di Vultr ya, karena penagihan per jam dengan batas bulanan. Server yang dihapus menghentikan biaya. Di penyedia lokal, paket dibeli per bulan atau per beberapa bulan di muka.

**Boleh dipakai mining?**
Rumahweb melarang crypto mining, dan ProwCloud menyebutnya dilarang keras dengan sanksi suspend permanen tanpa pengembalian dana. Untuk Vultr, tidak ada informasi yang bisa kami verifikasi soal ini, jadi jangan menganggapnya diizinkan.

## Aturan akhir sebelum Anda checkout

Cocokkan dulu kebutuhan dengan tiga jalur ini. Butuh IP publik, latensi rendah untuk pengunjung Indonesia, dan harga di bawah Rp 100.000? Ambil VPS lokal Rp 50.000. Cuma butuh bot ringan atau server uji dan tidak peduli IP bersama? Paket NAT Rp 10.000–25.000 sudah cukup, dan Anda tidak perlu bayar lebih. Butuh banyak lokasi, NVMe di semua paket, penagihan per jam, dan ingin menguji beban nyata tanpa biaya selama sebulan? Kredit $300 Vultr menutupi hampir semua skenario uji yang masuk akal, asalkan Anda memakainya dalam 30 hari.

Dua hal yang wajib dicek sebelum membayar. Pertama, kurs yang Anda pakai saat mengonversi $5 atau $6 ke rupiah, karena angka Rp 80.000 di artikel ini memakai asumsi Rp 16.000/USD. Kedua, pastikan Anda tidak menghitung kredit $300 sebagai pengurang biaya jangka panjang; setelah 30 hari, tagihan kembali normal dan biaya tambahan seperti backup serta kelebihan transfer ikut dihitung.

👉 [Mulai dari paket $5 atau $6 di Vultr dan pakai kredit $300 untuk 30 hari pertama](https://bit.ly/VuLtr)
