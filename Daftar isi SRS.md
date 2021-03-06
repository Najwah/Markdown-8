﻿<h1>***Software Requirement Specification (SRS)***</h1>
<b>1. Pendahuluan</b><br>
&emsp;1.1 Tujuan<br>
&emsp;1.2 Lingkup<br>
&emsp;1.3 Definisi, Akronim, Singkatan<br>
&emsp;1.4 Referensi<br>
&emsp;1.5 Overview<br>
<b>2. Gambaran Umum</b><br>
&emsp;2.1 Perspektif produk<br>
&emsp;&emsp;2.1.1 Antarmuka sistem<br>
&emsp;&emsp;2.1.2 Antarmuka pengguna<br>
&emsp;&emsp;2.1.3 Antarmuka perangkat keras <br>
&emsp;&emsp;2.1.4 Antarmuka perangkat lunak<br>
&emsp;&emsp;2.1.5 Antarmuka komunikasi<br>
&emsp;&emsp;2.1.6 Batasan-batasan memori<br> 
&emsp;&emsp;2.1.7 Operasi-operasi<br>
&emsp;&emsp;2.1.8 Kebutuhan-kebutuhan dalam tahapan adaptasi<br>
&emsp;2.2 Fungsi-fungsi produk<br>
&emsp;2.3 Karakteristik pengguna<br>
&emsp;2.4 Batasan-batasan<br> 
&emsp;2.5 Asumsi-asumsi dan ketergantungan/keterkaitan<br>
&emsp;2.6 Kebutuhan-kebutuhan penyeimbang<br>
<b>3. Kebutuhan lain yang spesifik</b><br>
<b>4.  Informasi pendukung</b><br>
<br>
<br>
<br>

<b>1. Pendahuluan </b> <br>
&emsp;&emsp;Dokumen ini akan berisi Spesifikasi  Kebutuhan Perangkat Lunak<br>
(SKPL) atauSoftware RequirementSpecification (SRS) untuk sistem aplikasi<br>
Laundry. Untukpenamaan dokumen ini selanjutnya akan  digunakan istilah<br>
SKPL. Isi dari dokumen ini sebagian besar adalah terjemahan dari<br>
dokumen IEEE  Std 830-1993.<br>

&emsp;&emsp;&emsp;1.1 Tujuan<br>
&emsp;&emsp;&emsp;&emsp;&emsp; Dokumen spesifikasi kebutuhan perangkat lunak ini  merupakan<br>
&emsp;&emsp;&emsp;dokumen spesifikasi kebutuhan perangkat lunak yang akan<br>
&emsp;&emsp;&emsp;dikembangkan. Dokumen ini digunakan oleh pengembang perangkat<br>
&emsp;&emsp;&emsp;lunak sebagaiacuan teknis untuk pengembang perangkat lunak pada<br>
&emsp;&emsp;&emsp;tahap  selanjutnya.<br>

&emsp;&emsp;&emsp;1.2 Lingkup<br>
&emsp;&emsp;&emsp;&emsp;&emsp; Aplikasi laundry adalah perangkat lunak yang digunakan untuk<br>
&emsp;&emsp;&emsp;mengelola dan mengatur sistem informasi laundry. Usaha jasalaundry ini<br>
&emsp;&emsp;&emsp;menawarkan beragam layanan,  menggunakan jasa  antar jemput, ada juga<br>
&emsp;&emsp;&emsp;dengan perhitungan per kilogram. Kebanyakan usaha laundry<br>
&emsp;&emsp;&emsp;pengelolaannya dilakukan secara manual dansederhana. Hal ini tentunya<br>
&emsp;&emsp;&emsp;tidak praktis dan memakan banyak waktu. Sehingga dari permasalahan ini<br>
&emsp;&emsp;&emsp;dibuatlah sebuah aplikasi laundry yang dapat membantu jasa laundry<br>
&emsp;&emsp;&emsp;dalam meningkatkan pelayanannya. Maka dengan adanya aplikasi laundry<br>
&emsp;&emsp;&emsp;ini pihak jasa laundry dapat lebih praktis dan efektif dalam menyimpan<br>
&emsp;&emsp;&emsp;dan mengeloladata seputar usaha laundrynya, meliputi informasi<br>
&emsp;&emsp;&emsp;customer dan informasi transaksi. Sehingga kegiatan operasional usaha<br> 
&emsp;&emsp;&emsp;ini tetap dapat berjalan dengan lancar.<br>

&emsp;&emsp;&emsp;1.3 Definisi, Akronim, dan Singkatan<br>
&emsp;&emsp;&emsp;&emsp;&emsp; Definisi :<br>
&emsp;&emsp;&emsp;a.&emsp;Laundry adalah usaha yang bergerak dibidang  jasa cuci dan setrika,<br>
&emsp;&emsp;&emsp;&emsp;&emsp;secara umum sebenarnya sepertimencuci di rumah namun karena hasil<br>
&emsp;&emsp;&emsp;&emsp;&emsp;akhir dinilai oleh customer.<br>
&emsp;&emsp;&emsp;b.&emsp;Aplikasi adalah suatu subkelas  perangkat lunak komputer yang<br>
&emsp;&emsp;&emsp;&emsp;&emsp;memanfaatkan kemampuan komputerlangsung untuk melakukan<br>
&emsp;&emsp;&emsp;&emsp;&emsp;suatu tugas yang diinginkan customer<br>
&emsp;&emsp;&emsp;c. &emsp;Sistem Informasi adalah suatu sistem yang dibuat oleh manusia yang<br>
&emsp;&emsp;&emsp;&emsp;&emsp; terdiri dari komponen-komponendalam organisasi untuk mencapai<br>
&emsp;&emsp;&emsp;&emsp;&emsp; suatu tujuan yaitu penyajian informasi. (Leman. 1998, h.3)<br>
&emsp;&emsp;&emsp;d. &emsp;Use Case adalah urutan langkah-langkah yang secara  tindakan saling<br> 
&emsp;&emsp;&emsp;&emsp;&emsp; terkait, baik terotomatisasimaupun secara manual, untuk tujuan<br>
&emsp;&emsp;&emsp;&emsp;&emsp; melengkapi satu tugas bisnis tunggal. (Jeffery  L. Whitten. 2004,h.257)<br>

&emsp;&emsp;&emsp;&emsp;&emsp;Akronim dan Singkatan :<br>
&emsp;&emsp;&emsp;&emsp;a. &emsp;SKPL &emsp; : Spesifikasi  Kebutuhan  Perangkat  Lunak<br>
&emsp;&emsp;&emsp;&emsp;b. &emsp;SQL &emsp;&emsp;: Structure Query Language<br>
&emsp;&emsp;&emsp;&emsp;c. &emsp;SRS &emsp;&emsp; : Software Requirement Specification<br>

&emsp;&emsp;&emsp;1.4 Referensi<br>

&emsp;&emsp;&emsp;[https://klasiber.uii.ac.id/core/course/view.php?id=142717](https://klasiber.uii.ac.id/core/course/view.php?id=142717)<br>
&emsp;&emsp;&emsp;IEEE Std 830-1998, IEEE  Recommended Practice for Software <br>
&emsp;&emsp;&emsp;Requirements Specifications.<br>
&emsp;&emsp;&emsp;ISO/IEC/IEEE 29418-2011, System and software engineering<br>

&emsp;&emsp;&emsp;1.5 Overview<br>
&emsp;&emsp;&emsp;&emsp;&emsp; Dokumen SPL ini dibagi menjadi lima bagian utama, yaitu :<br>
&emsp;&emsp;&emsp; -&emsp;Bagian pertama berisi penjelasan tentang dokumen SPL yang<br>
&emsp;&emsp;&emsp;&emsp;&emsp;mencakup tujuan  pembuatan dokumenini, lingkup masalah yang<br>
&emsp;&emsp;&emsp;&emsp;&emsp;diselesaikan oleh  perangkat lunak yang dikembangkan, definisi,<br>
&emsp;&emsp;&emsp;&emsp;&emsp;referensi dan deskripsi umum.<br>
&emsp;&emsp;&emsp;-&emsp; Bagian kedua berisi penjelasan secara umum mengenai aplikasi laundry<br>
&emsp;&emsp;&emsp;&emsp;&emsp;yang akan dikembangkan,meliputi fungsi dari perangkat lunak,<br>
&emsp;&emsp;&emsp;&emsp;&emsp;karakteristik customer, batasan dan asumsi yang diambil dalam<br>
&emsp;&emsp;&emsp;&emsp;&emsp;pengembangan perangkat lunak.<br>
&emsp;&emsp;&emsp;-&emsp; Bagian ketiga berisi uraian kebutuhan perangkat lunak secara lebih<br>
&emsp;&emsp;&emsp;&emsp;&emsp;rinci.<br>
&emsp;&emsp;&emsp;-&emsp;Bagian keempat berisi model analisis dari perangkat lunak ini.<br>
&emsp;&emsp;&emsp;-&emsp;Bagian kelima merupakan bagian terakhir yang berisi  lampiran serta <br>
&emsp;&emsp;&emsp;&emsp; penjelasan dan penggambaran layarcustomer.<br>
**2.**	**Gamabaran Umum**<br>
	&emsp;**2.1**	**Perspektif produk**<br>
		&emsp;&emsp;Pendefinisian Aplikasi Random Grup ini yaitu untuk membagi list nama menjadi kelompok yang dilakukan secara acak. Pembuatan Aplikasi Random Grup bertujuan untuk membantu pengguna dalam menentukan pembagian sebuah kelompok yang mudah dan praktis tanpa harus menggunakan kertas secara manual. <br>
		&emsp;&emsp;**2.1.1**	**Antarmuka sistem**<br>
				&emsp;&emsp;&emsp;Dalam penggunaan, pengguna berinteraksi langsung dengan aplikasi melalui PC / Laptop.<br>
		&emsp;&emsp;**2.1.2**	**Antarmuka pengguna**<br>
				&emsp;&emsp;&emsp;Perangkat lunak untuk aplikasi ini dibuat dengan menggunkan aplikasi flash. Dimana tampilan didesain dengan menggunakan template yang ada. Perangkat lunak untuk layanan dalam aplikasi ini dilengkapi dengan menu untuk pengaksesan berbagai fungsi yang disediakan.<br>
		&emsp;&emsp;**2.1.3**	**Antarmuka perangkat keras**<br>
				&emsp;&emsp;&emsp;Perangkat keras yang dapat digunakan dalam perangkat lunak yang dibuat:<br>
				&emsp;&emsp;&emsp;1.	PC<br>
				&emsp;&emsp;&emsp;2.	Monitor VGA mempunyai resolusi minimal 8800 x 1200 pixel.<br>
			&emsp;&emsp;&emsp;3.	Keyboard dan mouse untuk kegiatan user.<br>
				&emsp;&emsp;&emsp;4.	Semua perangkat keras yang digunakan merupakan perangkat sttandar dalam sistem komputer.<br>
		&emsp;&emsp;**2.1.4**	**Antarmuka perangkat lunak**<br>
				&emsp;&emsp;&emsp;Perangkat lunak yang dibutuhkan untuk perpustakaan antara lain:<br>
				&emsp;&emsp;&emsp;1. Sistem Operasi Windows (10) dll<br>
				&emsp;&emsp;&emsp;2. Untuk pengolahan database : MySql<br>
				&emsp;&emsp;&emsp;3. Untuk koneksi Database digunakan ADOdB<br>
		&emsp;&emsp;**2.1.5**	**Antarmuka komunikasi**<br>
			&emsp;&emsp;&emsp;Proses komunikasi dalam sistem ini menggunakan jaringan lokal, dimana dikontrol oleh komputer server.<br>
		&emsp;&emsp;**2.1.6**	**Batasan – batasan memori**<br>
				&emsp;&emsp;&emsp;Perangkat lunak hanya dijalankan di Windows (7, 8,10 dll).
				&emsp;&emsp;&emsp;Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan. Pengembangan perangkat lunak tidak akan merubah file-file ataupun database yang ada pada saat ini tanpa adanya user.<br>
		&emsp;&emsp;**2.1.7**	**Operasi – operasi**<br>
				&emsp;&emsp;&emsp;Perangkat lunak dapat dijalankan di PC atau Laptop manapun. <br>
		&emsp;&emsp;**2.1.8**	**Kebutuhan – kebutuhan dalam tahapan adaptasi**<br>
	&emsp;**2.2**	**Fungsi – fungsi produk**<br>
		&emsp;&emsp;Fungsi dari Aplikasi Laundry berdasarkan pengguna sistem ini adalah sebagai berikut :
		&emsp;&emsp;	a.	Membantu pelanggan dalam memesan laundry dengan mudah dan cepat.<br>
	&emsp;**2.3**	**Karakteristik pengguna**<br>
		&emsp;&emsp;Karakterisitk pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses dan level autentifikasi.<br>
	&emsp;**2.4**	**Batasan – batasan**<br>
	&emsp;&emsp;	1.	Perangkat lunak hanya dijalankan di Windows (7, 8, 10 ).<br>
		&emsp;&emsp;2.	Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.<br>
		&emsp;&emsp;3.	Pengembangan perangkat lunak tidak akan merubah file-file ataupun database yang ada.<br>
	&emsp;**2.5**	**Asumsi – asumsi dan ketergantungan / keterkaitan**<br>
		&emsp;&emsp;Maksimal penginputan data atau memasukan nama pada aplikasi ini adalah 100, lebih dari itu program akan muncul peringatan “Anda melebihi batas maksimum penginputan nama”.<br>
	&emsp;**2.6**	**Kebutuhan – kebutuhan penyeimbang**<br>
**3. Kebutuhan lain yang lebih spesifik**<br>
&emsp;3.1 Database<br>
&emsp;Database yang terdapat dalam aplikasi Laundry terdiri dari:<br>
&emsp;&emsp;a. Data-data Laundry<br>
&emsp;&emsp;b. Data Anggota Laundry<br>
&emsp;&emsp;c. Database data pelanggan<br>
&emsp;&emsp;d. Database cetak nota<br>
&emsp;&emsp;e. Database paket cucian<br>
&emsp;3.2 Kebutuhan Fungsional adalah kebutuhan yang harus dipenuhi agar suatu sistem dapat berjalan atau dapat dikatakan kebutuhan tambahan yang memiliki input, proses, dan output. Kebutuhan fungsional yang harus ada dalam sistem yang akan dikembangkan ini adalah sebagai berikut:<br>
&emsp;&emsp;1.	Sistem harus dapat mempermudah pengguna / user dalam pembagian kelompok.<br>
&emsp;&emsp;2.	Sistem harus dapat mempermudah pengguna / user dalam menggunakan aplikasi ini.<br>

**4. Informasi Pendukung**

