# Internal cybersecurity audit analysis at Botium Toys

## 📌 Table of contents

1. [Overview](#overview)
2. [Background and audit scenario](#scenario)
3. [Audit objective and scope](#objective)
4. [Assessment of current security assets](#asset)
5. [Risk assessment summary](#risk)
6. [Control categories breakdown](#breakdown)
7. [Control and compliance evaluation](#evaluation)
8. [Key takeaways and insights](#insight)
9. [Conclusion](#conclusion)

---

## 📍 Overview <a name="introduction">

Studi kasus ini saya buat sebagai bagian portofolio cybersecurity dengan fokus audit keamanan internal. Proyek ini memakai skenario Botium Toys, perusahaan retail mainan fiktif, untuk menggambarkan proses audit keamanan yang mendekati kondisi nyata di industri. Pembahasan dimulai dari materi yang saya pelajari di program Google Cybersecurity Professional Certificate di Coursera, khususnya pada course Play It Safe: Manage Security Risks.

Audit dilakukan untuk melihat seberapa baik sistem keamanan siber Botium Toys berjalan dan sejalan dengan standar industri. Fokus utama ada pada risiko yang berdampak besar lalu diterjemahkan menjadi rekomendasi yang bisa langsung ditindaklanjuti. Hasil audit disusun dengan bahasa yang mudah dipahami, disertai rencana perbaikan supaya bisa disampaikan dengan jelas ke pihak terkait.

---

## 🧠 Background and audit scenario <a name="scenario">

Botium Toys merupakan perusahaan retail mainan yang sedang berkembang dengan penjualan melalui toko fisik dan platform online. Aktivitas transaksi digital yang semakin tinggi membuat perusahaan mengelola lebih banyak data pelanggan, termasuk data pribadi dan informasi pembayaran. Sistem TI menjadi bagian penting dalam operasional harian, seperti pengelolaan stok dan proses transaksi.

Pertumbuhan bisnis belum sepenuhnya diikuti dengan penguatan keamanan internal. Berbagai sistem digunakan bersama oleh karyawan lintas divisi, sementara pengaturan akses, pencatatan aset, dan perlindungan data masih belum memiliki struktur yang jelas. Kondisi ini memunculkan risiko seperti kebocoran data, gangguan layanan, dan potensi masalah kepatuhan regulasi.

Situasi tersebut mendorong manajemen untuk melakukan audit keamanan internal. Tujuan utamanya untuk memahami kondisi keamanan yang sedang berjalan. Audit difokuskan pada aset penting, mekanisme perlindungan sistem, serta risiko yang berdampak langsung pada operasional dan bisnis.

Audit ini dibuat untuk menilai kesesuaian praktik keamanan dengan standar industri. Setiap temuan dicatat secara jelas dan disertai saran perbaikan yang realistis. Hasil audit diharapkan menjadi langkah awal membangun sistem keamanan yang lebih kuat di masa depan.

---

## 🎯 Audit objectives and scope <a name="objective">

### a. Scope of the audit

Audit ini saya lakukan dengan melihat kondisi keamanan Botium Toys secara menyeluruh. Fokus tidak hanya ke satu sistem atau tools tertentu, tapi ke seluruh aset yang dikelola tim IT. Cakupan audit meliputi sistem harian, perangkat kerja karyawan, data perusahaan, serta proses internal yang berkaitan dengan keamanan dan kepatuhan standar.

Penilaian juga mencakup cara aset dikelola dan bagaimana pengaturan akses diterapkan. Penerapan kontrol keamanan dalam aktivitas sehari-hari ikut diperhatikan. Proses ini menunjukkan apakah keamanan benar-benar diterapkan secara konsisten atau hanya sebatas kebijakan di atas kertas.

### b. Goals of the audit

Audit ini saya lakukan untuk memahami seberapa kuat kondisi keamanan Botium Toys saat ini. Penilaian dimulai dengan melihat praktik yang sudah berjalan lalu dibandingkan dengan standar keamanan yang umum dipakai di industri.

Setiap aset ditinjau satu per satu dan dicocokkan dengan kontrol serta aturan yang relevan. Pendekatan ini membantu melihat bagian yang sudah aman dan bagian yang masih punya celah. Hasil akhirnya memberi gambaran langkah perbaikan yang perlu dilakukan supaya keamanan Botium Toys bisa lebih kuat.

---

## 🛠️ Assessment of current security assets <a name="asset">

Aset yang dikelola tim IT di Botium Toys cukup banyak dan saling terhubung. Seluruh aset ini punya peran penting dalam mendukung aktivitas bisnis harian dan operasional perusahaan.
- Perangkat kantor yang dipakai untuk kegiatan operasional sehari-hari
- Perangkat kerja karyawan seperti desktop, laptop, smartphone, workstation untuk kerja jarak jauh, serta perangkat pendukung lain
- Produk ritel yang dijual lewat toko fisik dan platform online, termasuk sistem penyimpanan dan pengelolaan gudang
- Sistem dan layanan bisnis yang digunakan setiap hari seperti keuangan, komunikasi, pengelolaan data, keamanan, platform penjualan online, dan manajemen inventori
- Akses internet serta infrastruktur jaringan internal yang menjadi dasar seluruh aktivitas digital perusahaan

---

## 🧮 Risk assessment summary <a name="risk">

Pengelolaan aset di Botium Toys masih belum optimal. Beberapa kontrol keamanan memang sudah ada, tapi penerapannya belum rapi dan belum mengacu ke standar yang jelas. Kondisi ini membuat celah keamanan masih terbuka.

Data sensitif punya peluang diakses oleh pihak yang tidak berwenang. Aktivitas bisnis juga berisiko terganggu saat terjadi insiden keamanan karena perlindungan yang ada belum benar-benar siap menghadapi risiko.

### a. Control best practices

Pendekatan yang digunakan dimulai dengan fungsi Identify pada NIST Cybersecurity Framework. Langkah awal dimulai dengan mengenali seluruh aset milik perusahaan. Setiap aset dicatat dan dikelompokkan supaya lebih mudah dipahami.

Proses ini membantu melihat aset mana yang paling krusial untuk bisnis. Prioritas perlindungan jadi lebih jelas. Dampak ke operasional bisa diperkirakan jika suatu aset bermasalah atau hilang.

### b. Risk score

Hasil penilaian menunjukkan skor 8 dari 10 yang menandakan tingkat risiko cukup tinggi. Perlindungan yang ada masih terbatas dan belum merata. Penerapan standar keamanan juga belum konsisten.

### c. Additional risk considerations

Dampak kehilangan aset berada di tingkat menengah. Aset paling penting belum dipetakan dengan jelas. Peluang kebocoran masih cukup besar. Risiko pelanggaran aturan juga tinggi karena perlindungan data belum kuat.

Beberapa temuan penting selama audit:
- Seluruh karyawan memiliki akses yang terlalu luas ke data internal, termasuk data pembayaran dan data pribadi pelanggan
- Data kartu kredit belum terlindungi dengan baik saat diproses maupun disimpan
- Prinsip pembatasan akses dan pemisahan tanggung jawab belum diterapkan
- Firewall sudah terpasang dan dikonfigurasi dengan aturan yang memadai
- Antivirus aktif dan dipantau secara rutin
- Sistem pendeteksian serangan belum tersedia
- Rencana pemulihan gangguan dan mekanisme pencadangan data belum disiapkan
- Prosedur pemberitahuan kebocoran data ke pelanggan Uni Eropa sudah mengikuti batas waktu 72 jam
- Aturan kata sandi sudah ada namun belum mengikuti standar kekuatan terbaru
- Sistem pengelolaan kata sandi terpusat belum digunakan

Gambaran ini menunjukkan area yang perlu diprioritaskan untuk meningkatkan keamanan Botium Toys secara bertahap.

---

## 🧩 Control categories breakdown <a name="breakdown">

Bagian ini saya gunakan sebagai titik awal untuk melihat kondisi keamanan Botium Toys secara keseluruhan. Gambaran keamanan dibagi ke tiga lapisan utama yaitu kebijakan, teknis, dan fisik. Pembagian ini membantu melihat keamanan tidak hanya lewat sistem, tapi juga kebiasaan kerja tim dan cara aset dijaga langsung di lingkungan kerja.

### a. Administrative/managerial Controls (kebijakan)

Bagian ini fokus ke aturan dan kebijakan yang mengatur cara orang bekerja dan menggunakan akses.

| Nama kontrol               | Tipe kontrol | Penjelasan singkat                                    |
| -------------------------- | ------------ | ----------------------------------------------------- |
| Least privilege            | Preventif    | Setiap orang hanya punya akses sesuai kebutuhan kerja |
| Rencana pemulihan bencana  | Korektif     | Aktivitas bisnis tetap bisa berjalan setelah gangguan |
| Kebijakan kata sandi       | Preventif    | Akun tidak mudah diakses sembarang orang              |
| Kebijakan kontrol akses    | Preventif    | Hak melihat dan mengubah data jadi lebih jelas        |
| Kebijakan pengelolaan akun | Preventif    | Akun lama dan akun bawaan tidak jadi celah keamanan   |
| Pemisahan tugas            | Preventif    | Tidak ada satu pihak yang memegang kendali penuh      |

### b. Technical controls (teknis)

Lapisan ini berkaitan langsung dengan sistem dan perlindungan digital yang digunakan sehari-hari.

| Nama kontrol                    | Tipe kontrol | Penjelasan singkat                                   |
| ------------------------------- | ------------ | ---------------------------------------------------- |
| Firewall                        | Preventif    | Jaringan terlindungi dari lalu lintas mencurigakan   |
| IDS / IPS                       | Detektif     | Aktivitas tidak wajar bisa terdeteksi lebih cepat    |
| Enkripsi                        | Preventif    | Data sensitif tetap aman saat disimpan dan digunakan |
| Cadangan data                   | Korektif     | Data bisa dipulihkan saat sistem bermasalah          |
| Manajemen kata sandi            | Preventif    | Penggunaan password lebih rapi dan konsisten         |
| Antivirus                       | Korektif     | Ancaman umum bisa langsung ditangani                 |
| Pemantauan dan perawatan manual | Preventif    | Sistem tetap aman lewat pengawasan rutin             |

### c. Physical/operational controls (fisik)

Lapisan ini melihat bagaimana aset dijaga secara langsung di lingkungan kerja.

| Nama kontrol                             | Tipe kontrol         | Penjelasan singkat                              |
| ---------------------------------------- | -------------------- | ----------------------------------------------- |
| Brankas dengan pengatur waktu            | Preventif            | Akses fisik ke aset penting dibatasi            |
| Penerangan yang memadai                  | Preventif            | Area rawan jadi lebih terbuka dan aman          |
| CCTV                                     | Preventif / detektif | Mencegah kejadian dan membantu investigasi      |
| Lemari terkunci untuk perangkat jaringan | Preventif            | Perangkat penting tidak mudah diakses           |
| Papan peringatan sistem alarm            | Preventif            | Memberi efek pencegahan ke pihak luar           |
| Kunci                                    | Preventif            | Akses fisik tetap terjaga                       |
| Sistem deteksi dan pencegahan kebakaran  | Detektif / preventif | Server dan inventori terlindungi dari kebakaran |

---

## 🔍 Control and compliance evaluation <a name="evaluation">
 
Tahap ini saya gunakan untuk membandingkan kontrol keamanan yang seharusnya ada dengan kondisi nyata di Botium Toys. Perbandingan ini memudahkan melihat bagian yang sudah berjalan dan bagian yang masih punya celah.

| Kontrol                                  | Sudah | Belum |
| ---------------------------------------- | ----- | ----- |
| Least privilege                          |       | x     |
| Rencana pemulihan bencana                |       | x     |
| Kebijakan kata sandi                     | x     |       |
| Kebijakan kontrol akses                  |       | x     |
| Kebijakan pengelolaan akun               |       | x     |
| Pemisahan tugas                          |       | x     |
| Firewall                                 | x     |       |
| IDS / IPS                                |       | x     |
| Enkripsi                                 |       | x     |
| Cadangan data                            |       | x     |
| Manajemen kata sandi                     |       | x     |
| Antivirus                                | x     |       |
| Pemantauan dan perawatan manual          | x     |       |
| Brankas dengan pengatur waktu            |       | x     |
| Penerangan yang memadai                  | x     |       |
| CCTV                                     | x     |       |
| Lemari terkunci untuk perangkat jaringan | x     |       |
| Papan peringatan sistem alarm            | x     |       |
| Kunci                                    | x     |       |
| Sistem deteksi dan pencegahan kebakaran  | x     |       |

Beberapa kontrol dasar sudah diterapkan dan berjalan cukup baik. Perlindungan jaringan dasar, antivirus, pemantauan sistem lama, serta keamanan fisik sudah memberi lapisan perlindungan awal.

Masalah mulai terlihat pada perlindungan data sensitif. Enkripsi belum diterapkan. Sistem pendeteksi serangan belum tersedia. Cadangan data belum disiapkan. Pengaturan akses pengguna belum berbasis peran. Kondisi ini membuat risiko kebocoran data dan gangguan operasional cukup tinggi.

Tahap selanjutnya dimulai dengan meninjau aspek kepatuhan. Fokus diarahkan ke standar yang paling relevan dengan aktivitas dan kebutuhan Botium Toys.

### a. PCI DSS

Penilaian ini dilakukan karena Botium Toys menyimpan dan mengelola data kartu pembayaran pelanggan di sistem internal. Kondisi ini membuat standar PCI DSS jadi cukup penting untuk diperhatikan.

| Praktik yang seharusnya diterapkan                       | Sudah | Belum |
| -------------------------------------------------------- | ----- | ----- |
| Akses data kartu dibatasi untuk pihak berwenang          |       | x     |
| Data kartu diproses dan disimpan di lingkungan yang aman |       | x     |
| Enkripsi transaksi kartu kredit diterapkan               |       | x     |
| Kebijakan pengelolaan kata sandi yang aman               |       | x     |

Hasil penilaian menunjukkan kondisi yang cukup berisiko. Sebagian besar praktik penting terkait PCI DSS belum diterapkan. Area pembayaran terlihat sebagai salah satu sumber risiko terbesar bagi perusahaan.

### b. GDPR

Bagian ini melihat bagaimana perusahaan melindungi data pribadi pelanggan dan kesiapan saat terjadi insiden.

| Praktik yang seharusnya diterapkan                  | Sudah | Belum |
| --------------------------------------------------- | ----- | ----- |
| Data pelanggan Uni Eropa dijaga keamanannya         |       | x     |
| Pemberitahuan kebocoran data dilakukan dalam 72 jam | x     |       |
| Data diklasifikasikan dan dicatat dengan jelas      |       | x     |
| Kebijakan privasi diterapkan                        | x     |       |

Beberapa hal sudah berjalan, terutama terkait prosedur pemberitahuan dan kebijakan tertulis. Pengelolaan data secara teknis masih perlu banyak perbaikan supaya lebih rapi dan terkendali.

### c. SOC type 1 and type 2

Acuan SOC digunakan untuk menilai pengelolaan akses serta perlindungan data dari sisi kerahasiaan, keutuhan, dan ketersediaan.

| Praktik yang seharusnya diterapkan             | Sudah | Belum |
| ---------------------------------------------- | ----- | ----- |
| Kebijakan pengaturan akses pengguna diterapkan |       | x     |
| Data sensitif terlindungi dengan baik          |       | x     |
| Keutuhan data tetap terjaga                    | x     |       |
| Data tersedia untuk pengguna berwenang         | x     |       |

Hasil penilaian menunjukkan keutuhan dan ketersediaan data mulai diperhatikan. Perlindungan kerahasiaan data masih perlu menjadi fokus utama perbaikan.

---

## 📌 Key takeaways and insights <a name="insight">

Hasil penilaian menunjukkan fokus utama perbaikan ada pada perlindungan data sensitif dan kesiapan operasional.
- Enkripsi perlu segera diterapkan
- Pengaturan akses berbasis peran perlu diterapkan secara jelas
- Sistem pendeteksi dini dibutuhkan supaya insiden bisa diketahui lebih cepat
- Cadangan data rutin perlu disiapkan
- Pengelolaan kata sandi terpusat bisa menutup banyak celah kecil yang berisiko

Langkah-langkah ini menjadi fondasi penting untuk menekan risiko kebocoran data, meningkatkan kesiapan audit kepatuhan, dan membangun kondisi keamanan yang lebih kuat ke depan.

---

## 📄 Conclusion <a name="conclusion">

Audit keamanan internal di Botium Toys menunjukkan adanya ketimpangan antara pertumbuhan bisnis dan kesiapan sistem keamanannya. Beberapa perlindungan dasar sudah tersedia, terutama di sisi teknis dan keamanan fisik. Pengelolaan akses, perlindungan data, pemantauan sistem, dan kesiapan menghadapi insiden masih belum berjalan optimal.

Hasil penilaian memperlihatkan risiko muncul karena banyak kontrol penting belum diterapkan secara menyeluruh. Pembatasan akses belum jelas. Data belum terlindungi dengan baik. Sistem pendeteksi serangan belum tersedia. Cadangan data dan rencana pemulihan juga belum disiapkan. Kondisi ini meningkatkan potensi kebocoran data dan gangguan operasional.

Temuan audit menegaskan perlunya pendekatan keamanan yang lebih terarah dan berbasis risiko. Penyesuaian kontrol keamanan dengan standar industri dan aturan yang berlaku membantu perusahaan bergerak menuju sistem keamanan yang lebih siap dan berkelanjutan.

Audit ini menjadi langkah awal dalam pengambilan keputusan strategis terkait keamanan informasi. Rekomendasi yang dihasilkan memberi panduan jelas untuk memperkuat perlindungan, menekan risiko, dan menjaga kelangsungan bisnis seiring pertumbuhan perusahaan.
