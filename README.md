<h1 align="center">Rangga Maulana Ramadhan Wiharto</h1>
<h3 align="center"><em>(a.k.a Bos Rabeg)</em></h3>

<p align="center">
  <strong>🎯 High-Level Analyst | Information Systems Student @ UNPAM Serang | Full-Stack Entrepreneur</strong>
</p>

<p align="center">
  <em>"Menganalisis dengan tajam, mengeksekusi tanpa ragu. <strong>70% Eksekusi</strong> hari ini jauh lebih bernilai daripada terjebak dalam Kemandekan Sempurna."</em><br>
  <sub>— Filosofi yang mendorong lahirnya solusi terukur, bukan menunggu kesempurnaan.</sub>
</p>

<p align="center">
  <a href="https://desa.ranggamrw.my.id"><img src="https://img.shields.io/badge/DEMO_LANGSUNG-Prodesa-00C7B7?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Prodesa Live" /></a>
  <a href="https://billing.alkonek.online"><img src="https://img.shields.io/badge/DEMO_LANGSUNG-Alkonek_Billing-007ACC?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Alkonek Live" /></a>
  <a href="https://ranggamrw.my.id"><img src="https://img.shields.io/badge/PORTOFOLIO-ranggamrw.my.id-FF6B6B?style=for-the-badge&logo=globe&logoColor=white" alt="Portofolio" /></a>
</p>

---

## 🏛️ Sistem Produksi & Penggelaran (Deployment)

### **1. Prodesa — Portal Desa Digital** `AKTIF` 
**Tautan Langsung:** https://desa.ranggamrw.my.id

Platform **administrasi & tata kelola desa digital** komprehensif yang melayani masyarakat pedesaan di Indonesia dengan operasional berbasis digital.

| Aspek | Detail |
| :--- | :--- |
| **Stack Teknologi** | Laravel 11 • PHP 8.2 • MySQL 8 • Tailwind CSS • Alpine.js • Telegram Bot API |
| **Fitur Utama** | • Enkripsi AES-256-CBC untuk data sensitif<br>• Kontrol Akses Berbasis Peran (RBAC) dengan 30+ lapisan hak akses<br>• Integrasi notifikasi Telegram untuk peringatan *real-time*<br>• Manajemen dokumen multi-otoritas (surat-menyurat)<br>• Manajemen data kependudukan & data pemilih<br>• Dashboard pelaporan keuangan<br>• Antarmuka web responsif seluler dengan formulir dinamis |
| **Arsitektur** | Pola MVC dengan pemisahan *service layer* • Antrean pekerjaan (*job queuing*) untuk tugas asinkron • Otentikasi & pemantauan berbasis *middleware* • Berbasis *API-first* |
| **Performa** | Waktu respons di bawah 500ms • Kueri basis data teroptimasi dengan pengindeksan • *Lazy-load* untuk aset & gambar |
| **Keamanan** | Proteksi CSRF • Pencegahan SQL Injection • Pembatasan laju kueri (*Rate limiting*) • Validasi & sanitasi input |
| **Pengguna Dilayani** | 10+ administrasi desa di wilayah Kabupaten/Kota Serang |

---

### **2. Alkonek Billing — Mesin Billing Multi-Tenant ISP** `AKTIF`
**Tautan Langsung:** https://billing.alkonek.online

**Sistem manajemen jaringan & penagihan (*billing*)** kelas enterprise untuk Penyedia Jasa Internet (ISP), mengelola seluruh siklus pelanggan dari pendaftaran hingga penerbitan faktur.

| Aspek | Detail |
| :--- | :--- |
| **Stack Teknologi** | PHP • Laravel • MySQL • REST API • MikroTik RouterOS API • Redis Caching |
| **Modul Utama** | • **Mesin Billing**: Pembuatan faktur otomatis, pemrosesan pembayaran, kalkulasi denda keterlambatan<br>• **Integrasi Jaringan**: Sinkronisasi status koneksi *real-time* dari MikroTik<br>• **Manajemen Pelanggan**: Tingkat paket bertingkat, pembatasan *bandwidth*, pembaruan paket<br>• **Otomatisasi**: Isolasi otomatis saat menunggak, manajemen antrean, alur kerja koneksi ulang<br>• **Pelaporan**: Analitik pendapatan, analisis rasio kehilangan pelanggan (*churn*), visualisasi topologi jaringan |
| **Arsitektur** | Pemrosesan asinkron berbasis antrean (Laravel Horizon) • Manajemen status pelanggan berbasis *event* • Listener *webhook real-time* untuk *event* MikroTik |
| **Performa** | Menangani 100+ siklus *billing* secara bersamaan • Sinkronisasi MikroTik di bawah 1 detik • Operasi massal (*batch*) |
| **Keunggulan Utama** | • Dukungan *multi-tenant* (beberapa operator ISP dalam satu platform)<br>• Konfigurasi struktur tarif kustom per *tenant*<br>• Pemeriksaan redundansi jaringan & mekanisme *failover* |
| **Klien** | Alkonek ISP • Mitra telekomunikasi regional |

---

## 🛠️ Stack Teknologi & Kompetensi Inti

<table>
  <tr>
    <td width="30%"><strong>🔧 Backend & Basis Data</strong></td>
    <td>
      <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
      <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>🎨 Frontend & Mobile</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />
      <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" />
      <img src="https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
      <img src="https://img.shields.io/badge/Alpine.js-8BC0D0?style=flat-square&logo=alpine.js&logoColor=black" />
      <img src="https://img.shields.io/badge/HTML5-E34C26?style=flat-square&logo=html5&logoColor=white" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>🔐 Infrastruktur & DevOps</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" />
      <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=white" />
      <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" />
      <img src="https://img.shields.io/badge/MikroTik-000000?style=flat-square&logo=mikrotik&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/cPanel-FF6B35?style=flat-square&logo=cpanel&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>🔗 Integrasi & API</strong></td>
    <td>
      <img src="https://img.shields.io/badge/REST_API-4285F4?style=flat-square" />
      <img src="https://img.shields.io/badge/Telegram_Bot-0088cc?style=flat-square&logo=telegram&logoColor=white" />
      <img src="https://img.shields.io/badge/MikroTik_API-FF8C00?style=flat-square&logo=mikrotik&logoColor=white" />
      <img src="https://img.shields.io/badge/Webhooks-9B59B6?style=flat-square" />
    </td>
  </tr>
</table>

---

## 📱 Aplikasi Mobile & Utilitas

| Proyek | Tujuan | Stack | Status |
| :--- | :--- | :--- | :--- |
| 🍕 **FoodMate** | POS & manajemen pesanan untuk bisnis kuliner | Flutter • Dart • Firebase | Aktif |
| 🛍️ **Kasir** | Sistem Point-of-Sale dengan pelacakan inventaris | Flutter • Dart • SQLite | Produksi |
| ✈️ **Aplikasi Travel List** | Perencana rencana perjalanan & agregator pemesanan | Flutter • Dart | Pemeliharaan |
| 🏥 **AntrianRS** | Sistem manajemen antrean rumah sakit | Flutter • Dart • REST API | Aktif |
| ☕ **Kopken** | Manajemen kedai kopi (inventaris + penjualan) | Flutter • Dart | Aktif |

---

## 🌐 Sistem Web & Enterprise

| Repositori | Tujuan | Teknologi | Skala |
| :--- | :--- | :--- | :--- |
| **desamoderen** | Dashboard admin desa modern (iterasi awal Prodesa) | Laravel • MySQL • Bootstrap | 5+ desa |
| **billing** | Mesin *billing* inti (pondasi sistem Alkonek) | PHP • Laravel • MySQL | 100+ pelanggan |
| **rabegnet-billing** | Modul *billing* ISP terspesialisasi | Laravel • MikroTik API | Multi-tenant |

---

## 🖥️ Infrastruktur & Jaringan

**Keahlian:** Pemantauan jaringan, pengujian latensi, administrasi server, konfigurasi MikroTik RouterOS

| Domain | Proyek | Fokus |
| :--- | :--- | :--- |
| **Homelab** | Lingkungan server pribadi | Ubuntu • Docker • Orkestrasi Layanan |
| **Speedtest** | Pemantauan performa jaringan | Analisis Latensi • Pengujian Bandwidth • Visualisasi Topologi |
| **Admin Jaringan** | Setup & pemeliharaan infrastruktur ISP | Konfigurasi MikroTik • DHCP/DNS • Setup VPN |

---

## ✨ Pencapaian Utama & Sorotan

### **🎯 Dampak Bisnis**
- ✅ Membangun **2 sistem produksi** yang melayani **10+ organisasi** dengan **100+ pengguna aktif bersamaan**
- ✅ Mengurangi birokrasi kertas administrasi desa hingga **80%** melalui digitalisasi Prodesa
- ✅ Mengotomatiskan alur kerja *billing* ISP, menghemat **20+ jam/bulan** per operator

### **🏗️ Pencapaian Teknis**
- ✅ Menerapkan **keamanan kelas enterprise** (enkripsi AES-256, RBAC, *rate limiting*)
- ✅ Merancang **arsitektur terukur** yang menangani lonjakan beban dengan *Redis caching* & antrean pekerjaan
- ✅ Mengintegrasikan **MikroTik RouterOS API** untuk manajemen status jaringan secara *real-time*
- ✅ Membangun **otomatisasi Bot Telegram** untuk notifikasi instan di 10+ desa

### **📦 Penguasaan Full-Stack**
- ✅ **Arsitektur**: Desain skema, kontrak API, model keamanan
- ✅ **Backend**: Layanan PHP/Laravel, optimasi basis data, sistem antrean
- ✅ **Frontend**: UI responsif dengan Alpine.js & Tailwind CSS
- ✅ **Mobile**: Aplikasi Flutter lintas platform untuk iOS & Android
- ✅ **DevOps**: Manajemen server Linux, Docker, hosting cPanel
- ✅ **Jaringan**: Administrasi MikroTik, infrastruktur ISP

---

## 📊 Aktivitas & Kontribusi GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ranggamaulana111111-bit&show_icons=true&theme=radical&hide_border=true&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ranggamaulana111111-bit&layout=compact&theme=radical&hide_border=true" width="48%" alt="Top Languages" />
</p>

**Bahasa Berdasarkan Tingkat Penguasaan:**
- **PHP** — Lanjutan (*enterprise systems*, desain *framework*)
- **Dart** — Menengah (aplikasi Flutter, desain berfokus *mobile*)
- **MySQL/SQL** — Lanjutan (optimasi, normalisasi, migrasi)
- **Bash/Linux** — Menengah (admin server, skrip otomatisasi)

---

## 🎓 Pendidikan & Pembelajaran Berkelanjutan

- 🎓 **Mahasiswa Sistem Informasi** @ UNPAM Serang
- 📚 Pengembang *full-stack* otodidak melalui proyek-proyek produksi nyata
- 🔍 Pembelajar aktif: Ekosistem Laravel, *framework* Flutter, protokol jaringan

---

## 🚀 Bidang Keahlian

| Kategori | Keahlian |
| :--- | :--- |
| **Pengembangan Web** | Full-stack Laravel/PHP • Desain REST API • Skema basis data • Praktik terbaik keamanan |
| **Pengembangan Mobile** | Flutter lintas platform • Pengetahuan native Android/iOS • Desain *offline-first* |
| **Desain Sistem** | Arsitektur terukur • Sistem *multi-tenant* • Pemrosesan berbasis *event* • Strategi *caching* |
| **Infrastruktur** | Admin Ubuntu/Linux • Setup MikroTik • Dasar-dasar Docker • Pengerasan & keamanan server |
| **ISP/Telekomunikasi** | Logika *billing* • Pemantauan jaringan • Manajemen siklus hidup pelanggan • Otomatisasi pelanggan |

---

## 📬 Mari Terhubung

<p align="left">
  <a href="https://ranggamrw.my.id"><img src="https://img.shields.io/badge/Portofolio-ranggamrw.my.id-1f6feb?style=for-the-badge&logo=globe&logoColor=white" alt="Portofolio" /></a>
  <a href="https://instagram.com/rangga.mrw"><img src="https://img.shields.io/badge/Instagram-@rangga.mrw-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
  <a href="https://wa.me/6285176922584"><img src="https://img.shields.io/badge/WhatsApp-%2B62_851_769_22584-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
  <a href="mailto:hey@ranggamrw.my.id"><img src="https://img.shields.io/badge/Email-hey@ranggamrw.my.id-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

<h3 align="center">💭 <em>Selalu mengeksekusi. Selalu belajar. Selalu berkembang.</em></h3>

<p align="center">
  <strong>"70% eksekusi hari ini adalah prioritas kami — sempurna adalah musuh dari progress."</strong>
</p>
