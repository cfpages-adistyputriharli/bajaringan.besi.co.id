---
article_id: LGS-06-04
title: "Hip, Valley, Overhang, dan Atap Bertingkat: Titik Koordinasi"
slug: "koordinasi-geometri-atap-kompleks"
description: "Panduan praktis mengoordinasikan jalur beban, tumpuan, aliran air, pemotongan, dan lapisan atap pada geometri yang kompleks."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-10-22"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: LGS-06
primary_intent: "Coordinate complexity"
reader_community: "Besi.co.id"
reader_address: "Kawan Besi.co.id"
final_route: "/artikel/koordinasi-geometri-atap-kompleks.html"
technical_review: required
sources:
  - "https://www.aisc.org/aisc/solutions-center/hss/"
  - "https://peraturan.bpk.go.id/Home/Details/161846/pp-no-16-tahun-2021"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://pesta.bsn.go.id/produk/detail/12885-sni83692020"
  - "https://pesta.bsn.go.id/produk/detail/9714-sni79712013"
  - "https://www.iso.org/standard/46556.html"
---

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-001
Source type: local
Placement: setelah jawaban pembuka, sebelum H2 pertama
**Exact Markdown to insert:** `![Ilustrasi Jual Baja Ringan](/wp-content/uploads/2025/04/Jual-Baja-Ringan.jpg)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata identifies Jual Baja Ringan as relevant content media; no pixels were inspected.
Hard boundary: jangan menebak isi visual, kepemilikan proyek, lokasi, orang, merek, kondisi, performa, atau hasil.
Substitution rule: jika aset tidak tersedia atau asalnya tidak lengkap, gunakan [NEEDS IMAGE REVIEW: LOCAL-001].
END MANAGED IMAGE PLAN -->

# Hip, Valley, Overhang, dan Atap Bertingkat: Titik Koordinasi

Halo, Kawan Besi.co.id! Pada atap dengan pertemuan hip (jurai luar), valley (jurai dalam), overhang (teritisan), dan beberapa tingkat, masalah paling mahal biasanya bukan satu batang yang kurang kuat. Masalahnya adalah garis pertemuan yang tidak pernah disepakati: beban turun ke mana, ujung rangka bertumpu di mana, air mengalir lewat jalur apa, dan lapisan atap harus dipotong sejauh apa.

Jawaban singkatnya: koordinasikan geometri kompleks sebagai satu rangkaian antarmuka, bukan sebagai empat bentuk terpisah. Bekukan garis acuan dan elevasi, teruskan jalur beban hingga tumpuan, cocokkan detail pembuangan air dengan posisi rangka, lalu tandai semua pemotongan dan perubahan lapisan sebelum material dipotong. Kesimpulan itu dapat berubah setelah data lokasi, beban, profil, sambungan, dan gambar yang disetujui diperiksa oleh perancang berwenang; tanpa data tersebut, artikel ini bukan detail desain.

![Ilustrasi Jual Baja Ringan](/wp-content/uploads/2025/04/Jual-Baja-Ringan.jpg)

*Ilustrasi material baja ringan dari aset lokal situs, bukan dokumentasi proyek tertentu.*

## Jawaban singkat dan salah paham utama

Nama bentuk sering membuat orang mengira setiap garis atap dapat dikerjakan sendiri. Hip terlihat seperti dua bidang bertemu di sudut, valley seperti saluran di cekungan, overhang seperti ujung yang tinggal dipanjangkan, dan atap bertingkat seperti dua atap yang hanya berbeda tinggi. Padahal, satu perubahan pada garis pertemuan menggeser panjang batang, posisi tumpuan, arah gaya, dan ruang untuk talang sekaligus.

Salah paham kedua adalah menganggap ukuran luar yang sama berarti profilnya dapat saling menggantikan. Label penampang perlu dibaca bersama bentuk, sumbu, dimensi, tebal, massa, material, dan dokumen produknya. AISC menjelaskan anatomi HSS (penampang berongga struktural) sebagai informasi geometri dan produk yang harus dibaca utuh, bukan sekadar nama singkat ([AISC HSS](https://www.aisc.org/aisc/solutions-center/hss/)). Untuk proyek di Indonesia, tabel profil dan sertifikat yang berlaku tetap menjadi rujukan proyek, bukan contoh penamaan dari luar negeri.

Jadi, sebelum bertanya “batangnya cukup kuat atau tidak?”, ajukan pertanyaan yang lebih awal: “garis ini membawa beban ke tumpuan yang mana, dan apakah detail air, penutup, serta sambungannya masih muat di sana?”

## Definisi dan batas objek

Di artikel ini, hip adalah garis menonjol tempat dua bidang atap bertemu; valley adalah garis cekung yang mengumpulkan aliran dari dua bidang; overhang adalah bagian penutup atau rangka yang melewati garis tumpuan; sedangkan atap bertingkat memiliki bidang dengan elevasi berbeda yang harus dihubungkan atau dipisahkan dengan sengaja. Istilah tersebut dipakai untuk membaca koordinasi, bukan untuk menetapkan ukuran batang atau jenis sambungan.

Batasnya penting. Bukaan untuk tangki, skylight, atau akses yang menembus bidang atap masuk ke pembahasan penetrasi tersendiri, bukan detail di sini. Demikian juga pemilihan kapasitas anggota, pemeriksaan stabilitas, desain sambungan, ketahanan api, keadaan sementara, dan keputusan retrofit memerlukan data proyek serta perhitungan dan review kompeten. Catatan status standar atau halaman produk tidak menggantikan desain struktur; rekaman PP 16/2021 dan katalog SNI justru perlu dibaca sebagai lapisan aturan dan standar yang berbeda ([PP 16/2021](https://peraturan.bpk.go.id/Home/Details/161846/pp-no-16-tahun-2021), [SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020), [SNI 8369:2020](https://pesta.bsn.go.id/produk/detail/12885-sni83692020), [SNI 7971:2013](https://pesta.bsn.go.id/produk/detail/9714-sni79712013)).

## Cara kerjanya

Mulai dari satu gambar koordinasi yang memiliki garis grid, elevasi, kemiringan, garis tumpuan, dan arah aliran air. Jangan memulai dari daftar batang. Tandai puncak, lembah, tepi overhang, dan titik pertemuan tingkat sebagai titik kontrol. Setiap titik kontrol harus punya identitas yang sama pada gambar arsitektur, rangka, penutup, dan talang; perbedaan satu nama atau satu elevasi saja dapat membuat tukang bekerja dengan referensi yang berbeda.

Setelah geometri dibekukan, telusuri jalur beban. Beban penutup dan rangka sekunder mengalir ke anggota utama, lalu ke tumpuan dan struktur di bawahnya. Pada hip, periksa bagaimana ujung-ujung bidang bertemu dan apakah ada anggota yang menerima reaksi dari lebih dari satu arah. Pada valley, jangan menyamakan garis air dengan garis struktur secara otomatis; saluran perlu ruang, kemiringan, dan detail kedap yang mungkin mengubah posisi rangka. Pada overhang, garis ujung bukan tumpuan baru kecuali memang dirancang demikian.

Atap bertingkat menambah satu pertanyaan: apakah beda elevasi itu diselesaikan sebagai sambungan yang menerus, atau sebagai dua sistem yang masing-masing memiliki tumpuan? Jawabannya memengaruhi balok tepi, dinding parapet, flashing (lembar penutup sambungan), dan akses pemasangan. Jika keputusan belum ada di gambar yang disetujui, tandai sebagai [NEEDS GATE-01: klasifikasi sistem dan jalur beban harus dikonfirmasi perancang proyek].

Berikutnya, cocokkan lapisan dari atas ke bawah: penutup, lapisan kedap atau underlay, reng, rangka, dan elemen tumpuan. Setiap lapisan memiliki garis akhir yang mungkin berbeda. Potongan pada penutup tidak otomatis berarti batang di bawahnya boleh dipotong. Sebaliknya, menambah batang untuk mengejar tepi penutup tanpa memeriksa aliran air dapat menciptakan kantong air dan sambungan yang sulit dirawat.

Terakhir, buat urutan kerja. Titik yang belum memiliki ukuran, elevasi, arah air, dan detail sambungan adalah hold point (titik berhenti sementara), bukan ruang untuk improvisasi. Kawan Besi.co.id, keputusan kecil di meja gambar jauh lebih murah daripada memindahkan talang setelah penutup terpasang.

## Faktor yang mengubah hasil

Kemiringan dan panjang bidang menentukan kecepatan serta volume aliran air. Valley yang menerima dua bidang luas memerlukan koordinasi lebih ketat daripada lembah pendek yang hanya menerima satu limpasan kecil. Namun, jangan mengubah pengamatan ini menjadi ukuran talang atau kapasitas tanpa data hujan, detail penutup, dan ketentuan proyek; tandai kebutuhan itu sebagai [NEEDS GATE-02: verifikasi drainase dan limpasan berdasarkan lokasi serta sistem penutup].

Beban dan penggunaan juga mengubah jalur. Perubahan penutup, pemasangan panel, plafon tambahan, atau peralatan di atas atap dapat menambah beban dan mengubah akses pemeliharaan. Data produk atau lembar profil menunjukkan identitas material, bukan kapasitas struktur terpasang. Karena itu, cocokkan kode profil, tebal, mutu, dan sertifikat dengan gambar serta daftar material sebelum mengganti barang.

Kondisi pelaksanaan sering menjadi sumber selisih. Rangka prefabrikasi, rakitan di lokasi, toleransi dinding, dan urutan pemasangan dapat membuat titik hip atau valley bergeser. Ukur kondisi nyata dan catat perubahan sebelum melakukan pemotongan ulang. Untuk bangunan yang sudah ada, proses penilaian sebaiknya mencakup tujuan pemeriksaan, dokumen, survei, identitas material, geometri, riwayat perubahan, kerusakan, dan keputusan sementara; prinsip ini sejalan dengan kerangka penilaian struktur eksisting ISO 13822 ([ISO 13822:2010](https://www.iso.org/standard/46556.html)).

Lingkungan dan perawatan pun berpengaruh. Sambungan di valley lebih mudah terpapar air tertahan, sementara ujung overhang lebih mudah terkena angin dan akses luar. Jangan menetapkan umur layanan atau interval inspeksi dari artikel umum. Jika ada karat, deformasi, kebocoran berulang, atau perubahan fungsi, mintalah pemeriksaan dan keputusan teknis khusus proyek.

## Contoh keputusan praktis

Bayangkan denah memiliki dua sayap bangunan yang bertemu membentuk valley, lalu satu sayap lebih tinggi dan memiliki overhang panjang. Langkah pertama bukan memilih batang tambahan, melainkan menandai empat hal: garis pertemuan bidang, elevasi tiap sayap, tumpuan yang benar-benar tersedia, dan jalur air dari titik tertinggi ke pembuangan.

Jika garis air melewati tepat di atas titik tumpuan, koordinasikan ruang untuk flashing dan talang tanpa memotong anggota utama. Jika garis air bergeser karena kemiringan atau toleransi lapangan, tahan pekerjaan pada titik itu dan keluarkan revisi gambar; jangan memaksa penutup mengikuti rangka yang salah posisi. Jika overhang bertemu ujung dinding tanpa tumpuan, minta perancang menjelaskan jalur gaya dan detail pengaku sebelum pemasangan.

Untuk atap bertingkat, buat tabel kecil yang menghubungkan setiap elevasi dengan garis dinding, balok tepi, dan lapisan kedapnya. Tabel ini bukan perhitungan kapasitas, tetapi alat untuk menemukan siapa yang harus menjawab ketika satu angka berubah. Bila profil hendak diganti karena stok, cocokkan seluruh identitas penampang dan dokumen material; [NEEDS GATE-03: persetujuan substitusi profil dan sambungan harus tertulis pada dokumen proyek].

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah mengukur dari tepi penutup, lalu menganggapnya sebagai garis struktur. Periksa kembali jarak dari grid ke sumbu tumpuan pada semua gambar. Kesalahan kedua adalah menggambar valley sebagai satu garis tanpa menunjukkan arah air dan detail tepi. Tambahkan panah aliran, garis akhir lapisan, serta akses pembersihan agar tim lain dapat membaca maksudnya.

Kesalahan ketiga adalah memotong batang di lapangan untuk mengatasi benturan tanpa catatan perubahan. Foto dan ukur kondisi, beri tanda lokasi, lalu minta keputusan revisi. Kesalahan keempat adalah mengandalkan nama profil dari katalog luar negeri sebagai bukti kesetaraan. Cocokkan profil yang tersedia di proyek, standar yang ditetapkan, dan sertifikatnya; [NEEDS GATE-04: kecocokan material, toleransi, dan sambungan perlu review teknis].

Sebelum serah-terima, lakukan pemeriksaan berurutan: geometri dan elevasi, jalur beban, tumpuan, arah air, kesinambungan lapisan, detail pemotongan, identitas material, lalu daftar perubahan. Jika salah satu jawaban masih “nanti di lapangan”, statusnya belum siap dirilis.

## Jalan pintas yang sering dipilih

Jalan pintas yang menggoda adalah membuat satu detail standar untuk semua hip, valley, overhang, dan tingkat, lalu menyesuaikan dengan potongan di lokasi. Cara ini tampak cepat karena gambar lebih sedikit, tetapi menyembunyikan perbedaan tumpuan, arah air, dan ruang sambungan. Ketika kondisi nyata berbeda, pemotongan berantai dapat memindahkan masalah ke anggota lain.

Alternatif yang lebih aman adalah membuat detail tipikal hanya untuk bagian yang benar-benar sama, kemudian memberi lembar koordinasi khusus pada setiap titik pertemuan. Detail khusus tidak harus panjang; yang penting ia menunjukkan garis acuan, elevasi, jalur beban, arah air, lapisan yang berakhir, dan pihak yang menyetujui perubahan. Sobat Besi.co.id, sedikit lebih banyak kejelasan di awal biasanya mengurangi pekerjaan bongkar-pasang yang tidak tercatat.

## Kesimpulan dan langkah berikutnya

Hip, valley, overhang, dan atap bertingkat tidak boleh diperlakukan sebagai bentuk terpisah. Koordinasikan semuanya melalui garis acuan dan elevasi yang sama, telusuri beban sampai tumpuan, pisahkan jalur air dari asumsi garis struktur, dan tandai setiap pemotongan serta perubahan lapisan sebelum pekerjaan berjalan.

Langkah berikutnya adalah mengumpulkan gambar arsitektur dan struktur yang disetujui, daftar profil dan sertifikat, data kondisi lapangan, serta detail penutup dan drainase. Minta perancang atau pemeriksa kompeten menutup [NEEDS GATE-06: beban, stabilitas, dan sambungan proyek] dan [NEEDS GATE-07: keputusan perubahan atau kondisi eksisting] sebelum rilis pekerjaan. Untuk konteks profil atau produk, Anda dapat mulai dari [hub Kanal C Galvalum](/kanal-c-galvalum) atau [hub Reng Galvalum](/reng-galvalum); bila spesifikasi belum jelas, gunakan [halaman kontak](/kontak) untuk menyampaikan data yang tersedia, bukan meminta tebakan kapasitas.

Aturan operasionalnya sederhana: bila satu titik pertemuan belum memiliki garis, elevasi, jalur beban, jalur air, dan penanggung jawab persetujuan yang jelas, jangan potong material dan jangan anggap detailnya selesai.
