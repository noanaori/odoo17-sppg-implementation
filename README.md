# Master Data & Addons ERP Dapur SPPG Ekor Lubuk (Odoo 17)

Repositori ini secara khusus berisi modul pihak ketiga (*custom addons*) dan *Master Data* pendukung untuk pemenuhan Ujian Akhir Semester implementasi sistem *Enterprise Resource Planning* (ERP) pada studi kasus Dapur SPPG Ekor Lubuk. 

Sistem ini dibangun di atas **Odoo 17 Community Edition** menggunakan pendekatan *Fit-Gap Analysis* untuk mendukung rantai pasok dan operasional dapur berbasis *Make-to-Order* (MTO) dalam program Makan Bergizi.

## Struktur Repositori

* **`addons_accountant_module/`**
  Berisi modul pihak ketiga **Odoo Mates (om_account_accountant)**. Modul ini diimplementasikan untuk membuka kapabilitas pelaporan akuntansi penuh (*Full Accounting*) dan *Analytic Accounting* di versi Community guna memonitor penyerapan anggaran dana hibah/anggaran.

* **`addons_quality_module/`**
  Berisi modul pihak ketiga **Cybrosys Quality Assurance**. Modul ini diaktifkan untuk menjembatani *gap* pada fitur inspeksi logistik, memungkinkan dapur untuk melakukan *Quality Control* (seperti pengecekan suhu dan kesegaran) pada saat bahan baku tiba dari pemasok.

* **`data_master/`**
  Berisi seluruh *file* berekstensi `.csv` yang bertindak sebagai *Single Source of Truth* untuk inisialisasi basis data awal. Data ini mencakup:
  - Profil Pemasok dan Sekolah Penerima (Kontak)
  - Daftar Bahan Mentah & Produk Jadi (SKU)
  - Bill of Materials (BOM) / Resep
  - Work Center / Stasiun Kerja Dapur
  - Parameter Quality Measure
  - Reordering Rules (Batas Stok Otomatis)
  - Data SDM

## Tentang Proyek

Repositori ini merupakan lampiran teknis pendukung dari luaran perancangan arsitektur dan tata kelola sistem informasi.
* **Penulis:** Ayasha Zahwa
* **Institusi:** Program Studi S1 Sistem Informasi, UPN Veteran Jakarta
* **Fokus:** Supply Chain Management (SCM) & Enterprise Resource Planning (ERP)