---
article_id: LGS-06-02
title: "Data Geometri Atap sebelum Layout Kuda-Kuda"
slug: "data-geometri-atap-kuda-kuda"
description: "Menangkap data rentang, tumpuan, kemiringan, bubungan, pinggul, lembah, bukaan, tepi, dan overhang"
status: draft
publication_date: "2025-10-12"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: LGS-06
primary_intent: "Prepare layout input"
reader_community: "Besi.co.id"
reader_address: "Sobat Besi.co.id"
final_route: "/artikel/data-geometri-atap-kuda-kuda.html"
technical_review: required
writing_contract_version: native-id-v2
sources:
  - "https://www.aisc.org/aisc/solutions-center/hss/"
  - "https://www.aisc.org/globalassets/aisc/manual/v15.0-shapes-database/naming-convention-for-structural-steel-products-for-use-in-electronic-data-interchange-edi.pdf"
  - "https://peraturan.bpk.go.id/Home/Details/161846/pp-no-16-tahun-2021"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://pesta.bsn.go.id/produk/detail/12885-sni83692020"
  - "https://pesta.bsn.go.id/produk/detail/9714-sni79712013"
  - "https://www.iso.org/standard/46556.html"
  - "https://www.fhwa.dot.gov/bridge/steel/pubs/nhi16016.pdf"
  - "https://www.fhwa.dot.gov/bridge/inspection/"
  - "https://www.fhwa.dot.gov/publications/ndec/ndecnews.cfm"
---

# Data Geometri Atap sebelum Layout Kuda-Kuda

Halo, Sobat Besi.co.id!

Sebelum Anda mulai mendesain layout kuda-kuda baja ringan, ada satu langkah yang sering dianggap sepele tetapi bisa menyebabkan revisi besar di kemudian hari: mengumpulkan data geometri atap secara lengkap dan akurat. Tanpa data ini, desainer tidak bisa menentukan ukuran kuda-kuda yang tepat, posisi tumpuan yang benar, atau detail sambungan yang sesuai. Hasilnya? Revisi desain, penundaan fabrikasi, atau bahkan pemasangan yang tidak sesuai dengan kondisi aktual di lapangan.

Jawaban singkatnya: data geometri atap harus dikumpulkan sebelum layout kuda-kuda dimulai, mencakup rentang (span), tumpuan (supports), kemiringan (pitch), bubungan (ridge), pinggul (hips), lembah (valleys), bukaan (openings), tepi (edges), dan overhang. Data ini bukan sekadar dimensi kasar dari gambar arsitek, tetapi informasi detail yang memungkinkan desainer menentukan beban, titik tumpu, dan geometri kuda-kuda yang tepat. Tanpa data yang lengkap, Anda berisiko mendesain kuda-kuda yang tidak muat di lapangan atau tidak mampu menampung beban yang sebenarnya.

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** LOCAL-001
- **Source type:** local
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi Jual Baja Ringan](/wp-content/uploads/2025/04/Jual-Baja-Ringan.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies Jual Baja Ringan as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert [NEEDS IMAGE REVIEW: LOCAL-001] and continue drafting the prose.
END MANAGED IMAGE PLAN -->

![Ilustrasi Jual Baja Ringan](/wp-content/uploads/2025/04/Jual-Baja-Ringan.jpg)

_Gambar ilustrasi dari arsip proyek; bukan dokumentasi proyek spesifik._

## Mengapa data geometri harus dikumpulkan sebelum layout

Data geometri atap adalah input dasar untuk desain kuda-kuda. Tanpa data ini, desainer hanya bisa menebak—dan tebakan dalam desain struktural bisa berakibat fatal. Misalnya, jika rentang atap lebih besar dari yang diasumsikan, kuda-kuda yang didesain mungkin tidak cukup kuat. Jika posisi tumpuan berbeda dari yang diharapkan, sambungan yang dirancang mungkin tidak cocok.

SNI 1729:2020 tentang baja struktural ([SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)) menetapkan prinsip desain untuk elemen struktural baja, termasuk pertimbangan geometri. SNI 8369:2020 tentang rangka atap baja ringan ([SNI 8369:2020](https://pesta.bsn.go.id/produk/detail/12885-sni83692020)) memberikan panduan lebih spesifik tentang desain dan pemasangan, termasuk aspek geometri atap.

Sobat Besi.co.id, satu hal yang sering terlupakan: data geometri bukan hanya soal dimensi, tetapi juga soal kondisi aktual di lapangan. Dinding yang tidak rata, kolom yang bergeser, atau balok yang miring bisa mengubah geometri atap secara signifikan. Pengukuran di lapangan harus diverifikasi sebelum desain dimulai.

## Apa saja data yang harus dikumpulkan

Berikut data geometri atap yang harus dikumpulkan sebelum layout kuda-kuda:

**Rentang (span):** Jarak horizontal antara dua tumpuan utama kuda-kuda. Ini menentukan ukuran kuda-kuda dan kapasitas beban yang dibutuhkan. Pengukuran harus dilakukan di beberapa titik karena dinding mungkin tidak paralel.

**Tumpuan (supports):** Posisi dan jenis tumpuan kuda-kuda. Apakah kuda-kuda ditumpu pada dinding, balok, atau kolom? Apakah tumpuannya rata atau miring? Apakah ada tumpuan sementara yang perlu dipertimbangkan?

**Kemiringan (pitch):** Sudut kemiringan atap, biasanya dinyatakan dalam derajat atau rasio (misalnya, 30 derajat atau 1:4). Kemiringan menentukan tinggi kuda-kuda dan beban angin yang bekerja.

**Bubungan (ridge):** Garis puncak atap di mana dua bidang miring bertemu. Posisi bubungan menentukan geometri kuda-kuda dan sambungan di puncak.

**Pinggul (hips) dan lembah (valleys):** Pertemuan bidang atap yang membentuk sudut. Pinggul adalah pertemuan cembung, lembah adalah pertemuan cekung. Keduanya memerlukan kuda-kuda khusus dengan geometri yang berbeda.

**Bukaan (openings):** Lubang untuk skylight, ventilasi, tangki, atau akses. Ukuran dan posisi bukaan menentukan kebutuhan kuda-kuda penopang (trimming).

**Tepi (edges):** Batas atap di mana atap bertemu dinding, fascia, atau langit-langit. Detail tepi menentukan kebutuhan overhang dan flashing.

**Overhang:** Bagian atap yang menjulur di luar dinding luar. Overhang melindungi dinding dari hujan dan menentukan panjang ekor kuda-kuda.

ISO 46556 tentang manajemen aset ([ISO 46556](https://www.iso.org/standard/46556.html)) menekankan pentingnya data yang akurat untuk pengambilan keputusan. Prinsip yang sama berlaku untuk desain kuda-kuda.

## Bagaimana mengumpulkan dan memverifikasi data

Pengumpulan data geometri atap harus dilakukan secara sistematis:

**Dari gambar arsitek:** Mulailah dengan gambar denah, potongan, dan tampak yang disediakan arsitek. Ekstrak dimensi rentang, posisi tumpuan, kemiringan, dan bukaan. Namun, jangan hanya mengandalkan gambar—verifikasi di lapangan.

**Pengukuran di lapangan:** Lakukan pengukuran langsung di lokasi untuk memverifikasi data dari gambar. Gunakan water pass atau laser level untuk memeriksa level tumpuan. Gunakan theodolite atau aplikasi pengukuran sudut untuk memeriksa kemiringan. Ukur rentang di beberapa titik untuk memastikan konsistensi.

**Dokumentasi foto:** Ambil foto dari berbagai sudut untuk mendokumentasikan kondisi aktual. Foto ini berguna untuk referensi desainer dan untuk menyelesaikan sengketa jika ada perbedaan antara gambar dan kenyataan.

**Koordinasi dengan disiplin lain:** Pastikan data geometri dikumpulkan bersama dengan data dari disiplin lain—MEP (pipa, kabel, duct), struktur (kolom, balok), dan arsitek (finishing, langit-langit). Konflik antar disiplin harus diidentifikasi sebelum desain dimulai.

FHWA memberikan panduan tentang inspeksi dan verifikasi struktur baja ([FHWA bridge inspection](https://www.fhwa.dot.gov/bridge/inspection/)) yang bisa diterapkan untuk verifikasi data geometri. Publikasi FHWA tentang baja juga memberikan wawasan tentang perilaku struktural ([FHWA steel pubs](https://www.fhwa.dot.gov/bridge/steel/pubs/nhi16016.pdf)).

Teman Besi.co.id, satu kesalahan umum adalah menganggap gambar arsitek sebagai kebenaran mutlak. Gambar adalah representasi ideal; kenyataan di lapangan bisa berbeda. Selalu verifikasi.

## Faktor yang mengubah kebutuhan data

Beberapa faktor menentukan seberapa detail data geometri yang harus dikumpulkan:

**Kompleksitas atap:** Atap sederhana dengan satu bidang miring membutuhkan data yang lebih sedikit daripada atap dengan banyak pinggul, lembah, dan bukaan. Semakin kompleks atap, semakin detail data yang dibutuhkan.

**Ukuran bangunan:** Bangunan besar dengan rentang panjang membutuhkan data yang lebih akurat karena toleransi kesalahan lebih kecil. Kesalahan 10 mm pada rentang 6 m mungkin bisa ditolerir, tetapi pada rentang 18 m bisa menjadi masalah.

**Kondisi struktur pendukung:** Jika struktur pendukung (dinding, kolom, balok) sudah ada dan tidak bisa diubah, data geometri harus sangat akurat. Jika struktur masih bisa disesuaikan, toleransi bisa lebih longgar.

**Jenis kuda-kuda:** Kuda-kuda standar mungkin bisa menggunakan data kasar, tetapi kuda-kuda khusus dengan geometri kompleks membutuhkan data yang sangat detail.

AISC menyediakan panduan tentang profil baja struktural ([AISC HSS solutions](https://www.aisc.org/aisc/solutions-center/hss/)) yang bisa menjadi referensi untuk desain kuda-kuda. Konvensi penamaan produk baja struktural diatur dalam standar AISC ([AISC naming convention](https://www.aisc.org/globalassets/aisc/manual/v15.0-shapes-database/naming-convention-for-structural-steel-products-for-use-in-electronic-data-interchange-edi.pdf)).

## Contoh keputusan praktis

Berikut skenario untuk membantu keputusan Anda:

**Skenario 1: Atap pelana sederhana dengan rentang 8 m.** Keputusan: data yang dibutuhkan adalah rentang, kemiringan, posisi tumpuan, dan overhang. Verifikasi di lapangan cukup dengan pengukuran sederhana. Tidak ada bukaan atau pinggul yang perlu diperhatikan.

**Skenario 2: Atap dengan 3 bukaan skylight dan 2 lembah.** Keputusan: data yang dibutuhkan lebih detail—ukuran dan posisi setiap bukaan, geometri lembah, dan posisi kuda-kuda penopang. Verifikasi di lapangan harus lebih teliti karena toleransi kesalahan lebih kecil.

**Skenario 3: Bangunan lama yang akan dipasangi atap baru.** Keputusan: data geometri harus sangat akurat karena struktur pendukung sudah ada dan tidak bisa diubah. Pengukuran di lapangan harus menggunakan alat yang lebih presisi, dan perbedaan dengan gambar harus didokumentasikan.

SNI 7971:2013 tentang pengujian baja ([SNI 7971:2013](https://pesta.bsn.go.id/produk/detail/9714-sni79712013)) memberikan metode pengujian yang relevan jika material struktur pendukung perlu diverifikasi.

## Kesalahan umum dalam pengumpulan data

Beberapa kesalahan umum dalam pengumpulan data geometri atap:

**Hanya mengandalkan gambar arsitek.** Gambar adalah representasi ideal; kenyataan di lapangan bisa berbeda. Selalu verifikasi dengan pengukuran langsung. Pertanyaan verifikasi: Apakah Anda sudah melakukan pengukuran di lapangan dan membandingkannya dengan gambar?

**Tidak memeriksa level tumpuan.** Tumpuan yang tidak rata bisa mengubah geometri kuda-kuda secara signifikan. Gunakan water pass atau laser level untuk memeriksa level. Pertanyaan verifikasi: Apakah level tumpuan sudah diverifikasi?

**Mengabaikan bukaan dan penetrasi.** Bukaan untuk skylight, ventilasi, atau pipa sering terlupa dalam pengumpulan data. Padahal, bukaan ini membutuhkan kuda-kuda khusus. Pertanyaan verifikasi: Apakah semua bukaan sudah tercatat dengan ukuran dan posisi yang tepat?

**Tidak mendokumentasikan perbedaan.** Jika ada perbedaan antara gambar dan kenyataan, dokumentasikan perbedaan tersebut dan komunikasikan ke tim desain. Jangan biarkan perbedaan ini tidak tercatat. Pertanyaan verifikasi: Apakah perbedaan antara gambar dan kenyataan sudah didokumentasikan?

FHWA menekankan pentingnya dokumentasi dan verifikasi untuk menjaga kualitas ([FHWA NDEC news](https://www.fhwa.dot.gov/publications/ndec/ndecnews.cfm)).

## Mengapa "cukup dari gambar" bisa gagal

Salah satu kecenderungan yang sering muncul adalah mengandalkan data dari gambar arsitek tanpa verifikasi di lapangan dengan alasan "gambar sudah final, tidak mungkin salah." Mengapa ini bisa gagal?

Gambar arsitek adalah representasi ideal yang dibuat sebelum konstruksi dimulai. Selama konstruksi, banyak faktor yang bisa menyebabkan perbedaan: dinding yang tidak dibangun sesuai gambar, kolom yang bergeser beberapa sentimeter, atau balok yang tidak rata. Perbedaan kecil ini mungkin tidak signifikan untuk finishing, tetapi bisa kritis untuk desain kuda-kuda.

PP 16/2021 tentang Perlindungan Kebakaran ([PP 16/2021](https://peraturan.bpk.go.id/Home/Details/161846/pp-no-16-tahun-2021)) menetapkan persyaratan keselamatan yang juga relevan dengan akurasi desain struktural.

Alternatif yang lebih aman adalah melakukan pengukuran di lapangan meskipun gambar sudah final. Waktu yang dibutuhkan hanya beberapa jam, tetapi bisa menyelamatkan Anda dari revisi desain yang memakan waktu berminggu-minggu.

## Kesimpulan

Data geometri atap adalah input dasar yang harus dikumpulkan sebelum layout kuda-kuda dimulai. Data ini mencakup rentang, tumpuan, kemiringan, bubungan, pinggul, lembah, bukaan, tepi, dan overhang. Tanpa data yang lengkap dan akurat, desainer tidak bisa menentukan ukuran kuda-kuda yang tepat, posisi tumpuan yang benar, atau detail sambungan yang sesuai.

Langkah konkret yang harus Anda ambil sekarang: buat checklist data geometri atap yang harus dikumpulkan. Lakukan pengukuran di lapangan untuk memverifikasi data dari gambar. Dokumentasikan perbedaan antara gambar dan kenyataan. Koordinasikan dengan disiplin lain untuk mengidentifikasi konflik sebelum desain dimulai.

Ingat batasannya: artikel ini membahas pengumpulan data geometri, bukan desain kuda-kuda atau output layout. Untuk desain kuda-kuda, konsultasikan dengan insinyur struktur yang memahami kondisi proyek Anda. Untuk informasi lebih lanjut tentang koordinasi desain secara keseluruhan, kunjungi [panduan koordinasi geometri atap kompleks](/artikel/koordinasi-geometri-atap-kompleks.html) atau pelajari tentang [inspeksi rangka baja ringan terpasang](/artikel/inspeksi-rangka-baja-ringan-terpasang.html) untuk memahami apa yang diperiksa setelah pemasangan.
