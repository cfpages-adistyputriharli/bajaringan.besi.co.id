---
article_id: LGS-15-01
title: "Apa yang Terjadi pada Baja Tipis saat Terpapar Api?"
slug: "baja-tipis-dalam-kebakaran"
description: "Mekanisme penurunan kekuatan baja ringan saat terpapar suhu tinggi dari api, faktor-faktor yang mempengaruhi, dan pertimbangan praktis untuk desain yang lebih aman."
status: draft
publication_date: "2026-05-21"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: LGS-15
primary_intent: "Understand mechanism"
reader_community: "Besi.co.id"
reader_address: "Teman Besi.co.id"
final_route: "/artikel/baja-tipis-dalam-kebakaran.html"
technical_review: required
writing_contract_version: native-id-v2
sources:
  - "https://peraturan.bpk.go.id/Home/Details/161846/pp-no-16-tahun-2021"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://pesta.bsn.go.id/produk/detail/12885-sni83692020"
  - "https://pesta.bsn.go.id/produk/detail/9714-sni79712013"
  - "https://www.iso.org/standard/64834.html"
  - "https://www.iso.org/standard/77795.html"
  - "https://www.nist.gov/publications/best-practice-guidelines-structural-fire-resistance-design-concrete-and-steel-buildings"
  - "https://www.nist.gov/publications/white-paper-fire-behavior-steel-structures"
---

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** LOCAL-002
- **Source type:** local
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi besi baja 1](/wp-content/uploads/2025/04/besi-baja-1.jpg)`
- **Caption/credit:** Aset lokal proyek; bukan dokumentasi proyek spesifik.
- **Selection basis:** filename/source metadata identifies besi baja 1 as relevant content media; no pixels were inspected.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert [NEEDS IMAGE REVIEW: LOCAL-002] and continue drafting the prose.
END MANAGED IMAGE PLAN -->

# Apa yang Terjadi pada Baja Tipis saat Terpapar Api?

Halo, Teman Besi.co.id!

Ketika baja ringan terpapar api, yang sebenarnya terjadi bukan sekadar "bajanya meleleh." Baja tetap padat pada suhu yang sangat tinggi, jauh di atas titik lelehnya. Yang berubah adalah kemampuan baja menahan beban: pada suhu sekitar 550–600 derajat Celsius, baja karbon kehilangan kira-kira setengah kekuatan tarik dan modulus elastisitasnya ([NIST, White Paper: Fire Behavior of Steel Structures](https://www.nist.gov/publications/white-paper-fire-behavior-steel-structures)). Dalam konteks rangka baja ringan—profil tipis yang dirancang dengan ketebalan dinding 0,40–1,00 mm—kehilangan kekuatan itu bukan sekadar angka teori. Profil tipis memiliki cadangan kompresi yang lebih kecil dibanding baja struktural berat, sehingga momen kritis dan buckling bisa terjadi lebih cepat pada suhu yang sama. Artinya, pertanyaan yang tepat bukan "apakah baja ringan bisa terbakar?" tetapi "seberapa cepat kapasitas strukturnya turun, dan apa yang menentukan batas waktu itu?"

Jawaban singkatnya: baja ringan tidak ikut menyala sebagai bahan bakar, tetapi kehilangan kekakuan dan kekuatan secara progresif seiring naiknya suhu. Seberapa cepat penurunan itu terjadi tergantung pada lima faktor utama: suhu dan durasi paparan, kondisi pengikatan profil, beban yang aktif saat kebakaran, perlindungan thermal yang dipasang, dan perilaku sistem atap secara keseluruhan. Memahami kelima faktor ini membantu Anda membuat keputusan desain dan proteksi yang realistis, bukan sekadar mengikuti rekomendasi vendor tanpa tahu mekanismenya.

![Ilustrasi besi baja 1](/wp-content/uploads/2025/04/besi-baja-1.jpg)

_Gambar ini bukan dokumentasi proyek tertentu; hanya ilustrasi untuk memperjelas konteks pembahasan._

## Apa saja yang dibahas dan apa yang tidak

Sebelum masuk lebih jauh, penting untuk menegaskan apa yang dibahas di halaman ini dan apa yang tidak. Artikel ini membahas apa yang terjadi pada baja tipis—khususnya profil cold-formed steel atau baja ringan—saat terpapar suhu tinggi dari api. Fokusnya adalah mekanisme material dan perilaku struktur, bukan rating ketahanan api suatu rangka atau sistem perlindungan lengkap. Topik rating ketahanan api assembly dimiliki oleh artikel terpisah dalam seri LGS-15.

Batas ini mengubah cara Anda membaca. Ketika Anda menemukan angka suhu atau waktu, itu adalah perilaku material pada kondisi tertentu, bukan jaminan bahwa rangka atap Anda akan bertahan selama durasi itu tanpa proteksi tambahan. Standar seperti SNI 1729:2020 tentang baja ringan ([BSN, SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020)) menetapkan syarat material dan geometri profil, tetapi tidak menentukan rating tahan api. SNI 8369:2020 tentang rangka atap baja ringan ([BSN, SNI 8369:2020](https://pesta.bsn.go.id/produk/detail/12885-sni83692020)) mengatur tata cara desain dan pemasangan, termasuk pertimbangan beban, tetapi aspek ketahanan api tetap bergantung pada evaluasi assembly secara keseluruhan. Standar lain yang relevan untuk karakteristik material baja ringan adalah SNI 7971:2013 ([BSN, SNI 7971:2013](https://pesta.bsn.go.id/produk/detail/9714-sni79712013)) yang memuat data sifat mekanis baja tipis. Jadi, ketika seseorang bertanya "apakah rangka baja ringan ini tahan api?", jawaban jujurnya adalah: itu tergantung pada banyak komponen selain baja itu sendiri.

## Mekanisme yang terjadi saat baja tipis terpapar api

Proses yang terjadi saat baja ringan terkena api bisa dijelaskan dalam beberapa tahap yang saling terkait. Pertama, panas dari api diserap oleh permukaan baja. Karena baja memiliki konduktivitas termal yang tinggi—sekitar 50 watt per meter-Kelvin pada suhu ruang—panas menyebar relatif cepat melalui penampang profil. Dalam hitungan menit, seluruh penampang bisa mencapai suhu yang merata, terutama pada profil tipis di mana ketebalan dinding hanya 0,4–1,0 mm. Berbeda dengan baja berat yang memiliki inersia termal lebih besar, baja ringan tidak memiliki "buffer" suhu yang signifikan.

Kedua, saat suhu naik, properti mekanis baja berubah. Kekuatan leleh dan modulus elastisitas menurun. Kurva penurunan ini bukan garis lurus; pada suhu rendah hingga sekitar 300°C, penurunannya masih moderat. Tetapi antara 400°C dan 600°C, penurunannya menjadi curam. Data dari NIST ([NIST, Best Practice Guidelines](https://www.nist.gov/publications/best-practice-guidelines-structural-fire-resistance-design-concrete-and-steel-buildings)) menunjukkan bahwa pada 500°C, kekuatan leleh baja karbon umumnya tersisa sekitar 60% dari nilai suhu ruang, dan pada 600°C bisa turun hingga 30–40%. Untuk profil tipis, penurunan ini lebih kritis karena desainnya sudah berada di tepi kapasitas—setiap pengurangan kekakuan bisa memicu buckling sebelum beban mencapai nilai nominal desain.

Ketiga, buckling adalah mekanisme kegagalan utama pada baja ringan dalam api. Buckling terjadi ketika kompresi atau lentur melebihi kapasitas stabilitas profil. Pada suhu tinggi, modulus elastisitas yang turun menurunkan momen inersia efektif, sehingga beban kritis buckling turun drastis. Profil C atau profil kanal yang biasa digunakan di rangka atap memiliki sumbu lemah yang rentan terhadap buckling lokal dan distorsi. Ketika kekakuan menurun karena panas, buckling lokal bisa muncul lebih dulu, diikuti oleh buckling global yang menyebabkan runtuhnya segmen rangka.

Keempat, kondisi pengikatan menentukan apakah profil akan mengembang bebas atau terjebak. Baja yang terikat pada kedua ujungnya akan mengalami tekanan termal tambahan saat memuai, yang bisa mempercepat buckling. Sebaliknya, profil yang memiliki sedikit kebebasan gerak mungkin mengalami distribusi tegangan yang lebih merata. Namun, dalam rangka atap yang kaku, pengikatan tinggi adalah norma, sehingga tekanan termal sering menjadi faktor tambahan yang mempercepat kegagalan. Standar internasional seperti ISO 899-1 ([ISO 899-1](https://www.iso.org/standard/64834.html)) dan ISO 6892-1 ([ISO 6892-1](https://www.iso.org/standard/77795.html)) memuat metode pengujian sifat mekanis baja yang bisa dijadikan referensi untuk memahami perilaku material pada kondisi normal, yang kemudian bisa diekstrapolasi untuk memahami perubahan pada suhu tinggi.

Kelima, durasi paparan sama pentingnya dengan suhu puncak. Api kebakaran tidak statis; kurva suhu-waktu bervariasi tergantung pada beban bakar, ventilasi, dan material yang terbakar. Standar ISO 834 mendefinisikan kurva uji standar yang mencapai sekitar 945°C pada 60 menit. Namun, kebakaran nyata bisa memiliki kurva yang berbeda—lebih cepat atau lebih lambat tergantung kondisi. Baja ringan yang terpapar suhu puncak hanya beberapa menit mungkin masih memiliki kapasitas tersisa, tetapi paparan berkepanjangan pada suhu 500–700°C akan menguras cadangan kekuatan secara bertahap.

## Kondisi proyek yang menentukan seberapa parah kerusakan

Lima mekanisme di atas tidak bekerja secara terisolasi. Dalam proyek nyata, faktor-faktor berikut menentukan bagaimana baja tipis benar-benar merespons api.

**Suhu dan kurva api aktual.** Kebakaran di ruangan dengan banyak furnitur kayu dan plastik akan menghasilkan kurva suhu yang berbeda dari kebakaran di gudang dengan beban bakar rendah. Suhu puncak dan durasi di atas 400°C adalah dua parameter yang paling menentukan seberapa cepat kekuatan baja turun. Tanpa data spesifik proyek, sulit memprediksi tepat, tetapi memahami prinsip ini membantu Anda menilai skenario secara realistis.

**Beban saat kebakaran.** Rangka atap yang sudah beban penuh—dengan penutup atap, insulasi, pendingin, dan beban sementara—akan memiliki cadangan lebih kecil dibanding rangka yang belum dimuat. Ketika suhu naik dan kekuatan turun, beban aktual yang sudah ada menjadi proporsi yang lebih besar dari kapasitas tersisa. Ini adalah momen kritis: beban yang aman pada suhu ruang bisa menjadi berlebihan pada 500°C.

**Perlindungan thermal.** Gypsum board, insulasi mineral, atau material pelindung lainnya bisa memperlambat kenaikan suhu baja secara signifikan. Ketebalan dan jenis material pelindung menentukan berapa lama baja tetap di bawah suhu kritis. Namun, perlu diingat bahwa proteksi ini bukan bagian dari baja ringan itu sendiri—ini ditambahkan sebagai bagian dari sistem. Tanpa proteksi, baja ringan akan mencapai suhu kritis lebih cepat dibanding baja berat karena rapian massanya yang lebih rendah.

**Ventilasi dan suplai oksigen.** Api membutuhkan oksigen. Ventilasi yang baik bisa memperparah kondisi dengan menyuplai udara segar, tetapi bisa juga membantu mengurangi suhu dengan mengeluarkan panas. Pola aliran udara dalam ruangan mempengaruhi distribusi suhu pada rangka atap, yang biasanya berada di zona terpanas karena panas naik.

**Kondisi awal material.** Baja ringan dengan lapisan galvanis atau galvalum memiliki ketahanan korosi yang baik pada kondisi normal, tetapi lapisan ini tidak dirancang untuk melindungi dari api. Pada suhu tinggi, lapisan seng atau aluminium-zinc bisa terdegradasi, yang mengubah penampilan permukaan tetapi tidak secara signifikan mempengaruhi kekuatan struktur pada tahap awal paparan api.

## Skenario untuk membantu Anda memutuskan

Pertanyaan yang sering muncul adalah: "Kalau begini, bagaimana saya harus merancang?" Berikut beberapa skenario bersyarat yang bisa membantu Anda membuat keputusan yang lebih terinformasi.

**Skenario 1: Rumah tinggal dua lantai dengan atap limasan.** Rangka atap baja ringan dengan profil C75 pada jarak 600 mm, ditutup dengan genteng metal. Beban hidup atap termasuk beban orang sesaat untuk pemeliharaan. Dalam kondisi ini, tidak ada perlindungan thermal tambahan. Jika terjadi kebakaran di lantai atas yang menjalar ke loteng, suhu di sekitar rangka atap bisa mencapai 500–700°C dalam 10–15 menit tergantung beban bakar. Keputusan: pastikan ada jalur evakuasi yang jelas dan sistem deteksi dini. Jangan mengandalkan baja ringan untuk mempertahankan struktur tanpa batas waktu.

**Skenario 2: Gudang dengan sistem sprinkler.** Rangka atap baja ringan dengan proteksi gypsum board di langit-langit. Sistem sprinkler aktif dan teruji sesuai standar. Dalam skenario ini, sprinkler berfungsi membatasi pertumbuhan api, menjaga suhu tetap lebih rendah lebih lama. Keputusan: proteksi thermal dari gypsum board memberikan waktu tambahan, tetapi pastikan sprinkler terpasang dan berfungsi. Tanpa sprinkler, asumsi proteksi ini runtuh.

**Skenario 3: Bangunan komersial tanpa proteksi tambahan.** Rangka atap baja ringan tanpa pelindung thermal, dengan beban atap termasuk unit AC outdoor. Dalam kebakaran, unit AC bisa menjadi sumber beban tambahan dan hambatan evakuasi. Keputusan: evaluasi apakah beban atap termasuk komponen yang bisa terlepas dan menjadi proyektil saat rangka mulai deformasi.

Kawan Besi.co.id, penting untuk diingat bahwa skenario di atas bersifat umum dan tidak menggantikan evaluasi oleh profesional yang memahami kondisi spesifik proyek Anda. Angka-angka suhu yang disebutkan adalah referensi umum dari literatur teknis, bukan batas pasti untuk setiap situasi.

## Mitos yang sering salah dipahami

Beberapa miskonsepsi yang sering ditemui dalam diskusi tentang baja ringan dan api:

**Miskonsepsi 1: "Baja ringan tidak tahan api, jadi tidak boleh digunakan."** Ini generalisasi yang keliru. Baja ringan, seperti baja struktural lainnya, memiliki perilaku yang bisa diprediksi dan dimanfaatkan dalam desain. Pertanyaannya bukan "apakah tahan api" tetapi "bagaimana mendesain sistem yang mempertimbangkan kondisi ini." Banyak bangunan di seluruh dunia menggunakan baja ringan dengan proteksi yang memadai.

**Miskonsepsi 2: "Kalau sudah pakai gypsum board, aman selamanya."** Gypsum board membantu, tetapi bukan solusi absolut. Kepadatan pemasangan, ketebalan, dan kondisi jangka panjang mempengaruhi efektivitasnya. Gypsum yang sudah retak, lembap, atau tidak terpasang rapat akan memberikan perlindungan yang lebih rendah.

**Miskonsepsi 3: "Baja ringan akan meleleh seperti lilin."** Seperti dijelaskan di awal, baja tidak meleleh pada suhu kebakaran biasa. Yang terjadi adalah penurunan kekakuan dan kekuatan yang menyebabkan deformasi dan buckling. Visual yang mungkin Anda lihat—baja yang bengkok, memutar, atau runtuh—adalah akibat buckling dan deformasi plastis, bukan pelelehan.

Untuk memeriksa asumsi Anda, tanyakan: Apakah saya memiliki data spesifik tentang beban bakar di ruangan ini? Apakah proteksi thermal yang ada sudah terpasang sesuai prosedur? Apakah ada sistem aktif seperti sprinkler yang bisa membatasi pertumbuhan api? Pertanyaan-pertanyaan ini membantu Anda berpindah dari asumsi umum ke evaluasi yang lebih dekat dengan kenyataan.

## Kecenderungan yang perlu Anda waspadai

Salah satu pendekatan yang sering diambil adalah mengabaikan pertimbangan api karena "ini hanya rumah tinggal" atau "risikonya kecil." Kecenderungan ini bisa gagal karena dua alasan. Pertama, kebakaran tidak memilih bangunan—data menunjukkan bahwa kebakaran terjadi di berbagai jenis bangunan, termasuk rumah tinggal, dengan frekuensi yang tidak bisa dianggap remeh ([PP 16/2021 tentang Perlindungan Kebakaran](https://peraturan.bpk.go.id/Home/Details/161846/pp-no-16-tahun-2021)). Kedua, ketika kecenderungan ini mengarah pada pengabaian proteksi dasar—seperti tidak memasang detektor asap atau tidak memiliki rencana evakuasi—konsekuensinya bukan hanya pada struktur, tetapi pada keselamatan penghuni.

Alternatif yang lebih andal adalah pendekatan bertingkat: pastikan deteksi dini berfungsi, pastikan jalur evakuasi jelas, dan evaluasi apakah proteksi thermal diperlukan berdasarkan beban bakar aktual. Tidak perlu proteksi berlebihan, tetapi juga tidak boleh mengabaikan prinsip dasar keselamatan kebakaran.

## Kesimpulan

Jadi, apa yang sebenarnya terjadi pada baja tipis saat terpapar api? Baja ringan tidak menyala atau meleleh dalam kondisi kebakaran biasa, tetapi kehilangan kekakuan dan kekuatan secara progresif seiring naiknya suhu. Pada 500–600°C, kekuatan bisa turun hingga setengah dari nilai suhu ruang, dan bagi profil tipis yang sudah dirancang dengan cadangan kompresi terbatas, penurunan ini bisa memicu buckling dan deformasi yang signifikan. Seberapa cepat dan parah penurunan itu tergantung pada suhu aktual, durasi paparan, beban saat kebakaran, dan keberadaan perlindungan thermal.

Langkah selanjutnya yang perlu Anda ambil: identifikasi beban bakar di ruangan di bawah atau di sekitar rangka atap, evaluasi apakah ada proteksi thermal yang sudah terpasang atau perlu ditambahkan, dan pastikan sistem deteksi serta evakuasi memadai. Untuk pertanyaan lebih spesifik tentang rating ketahanan api suatu assembly, konsultasikan dengan profesional yang bisa melakukan evaluasi berdasarkan standar yang berlaku. Dan untuk pemahaman lebih mendalam tentang komponen rangka atap lainnya, Anda bisa membaca tentang [fungsi bracing pada rangka atap baja ringan](/artikel/fungsi-bracing-baja-ringan.html) atau memahami [anatomi dimensi profil baja ringan](/artikel/anatomi-dimensi-profil-baja-ringan.html) yang menjadi dasar desain.

Ingat, Teman Besi.co.id: memahami mekanisme adalah langkah pertama, tetapi keputusan desain yang aman membutuhkan evaluasi konteks spesifik proyek Anda.
