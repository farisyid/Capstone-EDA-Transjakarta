# Capstone-Module-2-DataSet-TransJakarta

TransJakarta adalah sebuah sistem transportasi Bus Rapid Transit (BRT) pertama di Asia Tenggara dan Selatan dengan jalur lintasan terpanjang di dunia (208 km). Sistem BRT ini didesain berdasarkan sistem TransMilenio di Bogota, Kolombia. Terhitung sejak 1 Februari 2004, TransJakarta resmi beroperasi. 

Pada tahun 2011, TransJakarta menenerapkan sistem manajemen armada terpadu. Salah satunya, melakukan integrasi dengan operator bus untuk menyediakan layanan feeder Busway bagi para pelanggannya. Di tahun ini juga TransJakarta mulai melakukan persiapan pembukaan layanan koridor 11 & 12 serta mengganti bus koridor 1 dengan bus articulated.

TransJakarta mempersiapkan pembukaan koridor - koridor baru seperti, persiapan tender operator, pembangunan jalur Busway, ramp, halte dan infrastruktur pendukung lainnya. Di tahun 2013, TransJakarta juga mulai menerapkan sistem e-ticketing untuk seluruh koridor serta integrasi sistem e-ticketing dengan feeder Busway dan angkutan umum lainnya.

Pada 27 Maret 2014, TransJakarta berubah status menjadi bentuk BUMD (Badan Usaha Milik Daerah) dan resmi berganti nama menjadi PT. Transportasi Jakarta. Rencana pembukaan layanan koridor-koridor baru terus berjalan, inovasi-inovasi pun diluncurkan demi kenyamanan para pelanggan.

Pada April 2016, Transjakarta resmi mengoperasikan bus khusus wanita yang berwarna pink dalam rangka memperingati hari kartini. Bus khusus wanita ini dapat ditemui di koridor 1 (Blok M - Kota). Transjakarta juga akan menambah bus khusus wanita di koridor - koridor lainnya.

Site Visit Transjakarta: Senior Traveler pertama kali diadakan. Peserta untuk kegiatan pertama kali diikuti oleh 40 lansia dari Panti Werdha Sasana Bina Mulya. Kegiatan ini berjalan rutin setiap minggunya dan diikuti oleh peserta yang berumur 60-70 tahun dari berbagai panti sosial. Harapannya ke depan, Transjakarta tidak hanya nyaman dan aman bagi pelanggan pada umumnya tetapi juga menjadi angkutan umum yang ramah dan mudah bagi anak-anak kecil maupun pelanggan Lansia.

### **Permasalahan**
Dalam konsistensi perusahaan untuk **mengatasi kemacetan lalu lintas**, perusahaan akan terus **berinovasi dengan meningkatkan pelayanan pada halte-halte yang membutuhkan pengembangan**. Dengan demikian, masyarakat pengguna Transjakarta bisa dengan nyaman menggunakan fasilitas Transjakarta dan bisa bertambah penggunanya agar mengurai kemacetan di Jakarta.

Untuk menjawab permasalahan tersebut saya akan memberikan referensi sebagai berikut :
1. Koridor mana saja yang menjadi koridor tersibuk
2. Koridor mana saja yang banyak di kunjungi oleh wanita
3. Koridor mana saja yang banyak di kunjungi oleh lansia

### **StakeHolder**
PT. Transjakarta Bussiness and Development Team.

Dataset ini berisi informasi terkait umur, jenis kelamin, asal, tujuan, dan jenis moda transportasi pengguna layanan PT. TransJakarta. Ada 22 kolom di dalam dataset Transjakarta, yaitu:
|No. | Nama Kolom | Keterangan |
|----|------------|------------|
|1.	|transID| Unique transaction id for every transaction|
|2.	|payCardID| Customers main identifier. The card customers use as a ticket for entrance and exit.|
|3.	|payCardBank| Customers card bank issuer name|
|4.	|payCardName| Customers name that is embedded in the card.|
|5.	|payCardSex| Customers sex that is embedded in the card|
|6.	|payCardBirthDate| Customers birth year|
|7.	|corridorID| Corridor ID / Route ID as key for route grouping.|
|8.	|corridorName| Corridor Name / Route Name contains Start and Finish for each route.|
|9.	|direction| 0 for Go, 1 for Back. Direction of the route.|
|10.|tapInStops| Tap In (entrance) Stops ID for identifying stops name|
|11.|tapInStopsName| Tap In (entrance) Stops Name where customers tap in.|
|12.|tapInStopsLat| Latitude of Tap In Stops|
|13.|tapInStopsLon| Longitude of Tap In Stops|
|14.|stopStartSeq| Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.|
|15.|tapInTime| Time of tap in. Date and time|
|16.|tapOutStops| Tap Out (Exit) Stops ID for identifying stops name|
|17.|tapOutStopsName| Tap out (exit) Stops Name where customers tap out.|
|18.|tapOutStopsLat| Latitude of Tap Out Stops|
|19.|tapOutStopsLon| Longitude of Tap Out Stops|
|20.|stopEndSeq| Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.|
|21.|tapOutTime| Time of tap out. Date and time|
|22.|payAmount| The number of what customers pay. Some are free. Some not.|
