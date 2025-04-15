
# 📘 Week 1 – Introduction to Enterprise Systems

## 🎯 Tujuan Pembelajaran
- Memahami peran Sistem Informasi (SI) dalam organisasi
- Mengenal sistem ERP (Enterprise Resource Planning)
- Mengetahui gambaran umum proses implementasi ERP

---

## 🌪️ Konteks VUCA & Strategi Digital
VUCA: Volatility, Uncertainty, Complexity, Ambiguity  
Organisasi perlu adaptif dan menjalankan strategi digital agar bisa bertahan dalam lingkungan VUCA.

---

## 🏢 Sistem Informasi dalam Organisasi
- SI mendukung fungsi bisnis: akuntansi, keuangan, HRM, pemasaran, layanan pelanggan, dan operasi.
- Masalah: sistem tidak terintegrasi → menciptakan bottleneck dan menurunkan produktivitas.
- Solusi: integrasi data, aplikasi, dan sumber daya lintas fungsi.

---

## 🧠 Apa itu Enterprise Systems?
- Perangkat lunak berskala besar untuk mengelola proses bisnis, alur informasi, pelaporan, dan analitik data.
- Mempermudah manajemen kinerja bisnis dengan berbasis data.

---

## 🧩 ERP – Enterprise Resource Planning
- Sistem yang mengintegrasikan berbagai fungsi dan departemen ke dalam satu infrastruktur tunggal.
- Mendukung otomatisasi dan efisiensi proses lintas departemen (keuangan, SDM, supply chain, dsb).

---

## 🏗️ Manfaat Sistem ERP
### Sistemik:
- Data terintegrasi
- Dukungan IT tersentralisasi
- Antarmuka pengguna konsisten
- Keamanan data meningkat

### Bisnis:
- Kolaborasi lebih baik
- Respons lebih cepat
- Layanan pelanggan lebih baik

### Tantangan:
- Kompleksitas tinggi
- Biaya dan proses konversi data
- Resisten terhadap perubahan

---

# 📘 Week 2 – System Integration & Enterprise System Architecture

## 🎯 Tujuan Pembelajaran
- Memahami silo fungsional dalam organisasi
- Mengetahui pentingnya integrasi sistem
- Mengenal arsitektur sistem enterprise dan modul-modul ERP

---

## 🧱 Silo Organisasi
- Horizontal: pembagian berdasarkan fungsi seperti HR, akuntansi.
- Vertical: pembagian berdasarkan level manajemen (atas-menengah-bawah).
- Efek negatif: fokus hanya pada departemen sendiri, bukan tujuan organisasi → butuh pendekatan lintas fungsi.

---

## 🔄 Business Process Reengineering (BPR)
- Pendekatan lintas departemen untuk menyatukan proses bisnis demi tujuan organisasi.
- Mengatasi masalah komunikasi & kolaborasi antar fungsi.

---

## 🧩 Sistem Informasi dalam Organisasi
- Sistem yang tidak terintegrasi → tidak efisien dan mahal.
- Dibutuhkan integrasi informasi dan fungsi di semua level organisasi.

---

## 🔌 System Integration

### Dua Jenis Integrasi:
1. Logical Integration: berbagi data secara aman dan sesuai kebutuhan organisasi.
2. Physical Integration: integrasi langsung antar sistem dengan middleware atau API.

### Langkah-langkah Integrasi Sistem:
1. Inventarisasi sumber daya TI
2. Pemeriksaan standar & compliance
3. Dukungan sistem lama (legacy)
4. Middleware
5. Kebijakan otentikasi & otorisasi
6. Dukungan IT terpusat
7. Backup & pemulihan
8. Standarisasi hardware/software

---

## 🧠 Peran ERP dalam Integrasi
- Logical: fokus ke proses bisnis, bukan fungsi.
- Physical: integrasi data, klien, aplikasi.

---

## 🏗️ Arsitektur Sistem Enterprise
### Definisi:
Representasi sistem (fungsi, perangkat keras, perangkat lunak, dan interaksi manusia).

### Dua Perspektif:
- Fungsional: Modul ERP seperti akuntansi, HR, SCM.
- Sistemik: Infrastruktur fisik seperti server, DB, dan jaringan.

---

## 🧩 Modul ERP Umum
- Self-service, performance management, keuangan, produksi, penjualan & layanan.

---

## 🖥️ Jenis Arsitektur ERP
1. Two-Tier: server menangani aplikasi & database
2. Three-Tier: web tier, application tier, data tier
3. Web-Based: pemisahan Web Services & Web Browser
4. Cloud: ERP sebagai layanan (SaaS)

---

## 📌 Implikasi untuk Manajemen
- Silo tidak efektif → perlu integrasi sistem
- Integrasi mendukung efisiensi dan kolaborasi
- Manajemen harus aktif dalam desain arsitektur sejak awal proyek

# 📘 Week 3 – ERP Life Cycle & Implementation Strategy

## 🎯 Tujuan Pembelajaran
- Memahami SDLC dan ERP Life Cycle
- Mengetahui komponen ERP
- Menyadari perlunya produk pihak ketiga
- Mengenal pendekatan implementasi ERP

---

## 🔁 SDLC (System Development Life Cycle)
- Proses sistematis untuk merancang, membangun, dan menjalankan sistem informasi.
- Digunakan untuk menghindari kegagalan proyek besar.

---

## 🌀 Perbedaan ERP vs Software Biasa
| ERP | Software Biasa |
|-----|----------------|
| Miliaran rupiah | Ratusan ribu - jutaan |
| Misi kritikal | Mendukung produktivitas |
| Butuh waktu tahunan | Bisa langsung digunakan |
| Perlu manajemen perubahan total | Hanya pelatihan dasar |
| Perlu vendor, konsultan, karyawan | Dukungan minimal |

---

## 📊 Tahapan Siklus Hidup ERP Tradisional
1. **Scope & Commitment**: studi kelayakan, rencana jangka pendek & panjang, komitmen top management.
2. **Analysis & Design**: analisis kebutuhan pengguna, perencanaan konversi data dan pelatihan.
3. **Acquisition & Development**: beli lisensi, konfigurasi sistem, konversi data, implementasi keamanan.
4. **Implementation**: sistem mulai digunakan, pendekatan konversi:
   - *Phased, Pilot, Parallel, Big Bang*
5. **Operation**: handover ke tim support, training lanjutan, patch & upgrade.

---

## 🛠️ Komponen ERP
- **Hardware**: server, client, jaringan, printer
- **Software**: OS, DBMS, software aplikasi (pengembangan, pemantauan)
- **People**: end-users, IT, project manager, konsultan

---

## 🔌 Produk Pihak Ketiga
- Software tambahan yang mendukung distribusi laporan, SSO, pemantauan, dll.
- Tidak terintegrasi langsung, tapi wajib berjalan lancar bersama ERP.

---

## 🧑‍💼 Organisasi Implementasi ERP
- **Pemilik Proyek**: senior management
- **Executive & Steering Committee**
- **Project Team**: fungsi, infrastruktur, pengembangan, konversi, reporting
- **Change Management Team**

---

## 🚦 Strategi Implementasi
1. **Comprehensive**: full fitur ERP, termasuk modul industri → perlu banyak BPR
2. **Middle-of-the-Road**: sebagian BPR dan kustomisasi
3. **Vanilla**: tanpa modifikasi sistem → ubah proses agar cocok dengan ERP

---

## 📌 Implikasi untuk Manajemen
- Komitmen top management sangat penting
- Minimalkan kustomisasi
- Fokus pada komunikasi, pelatihan, dan manajemen perubahan

---

# 📘 Week 4 – Software & Vendor Selection

## 🎯 Tujuan Pembelajaran
- Memahami proses pembelian sistem ERP
- Mengetahui langkah-langkah negosiasi kontrak vendor

---

## 🛒 Proses Pembelian ERP
1. **Vendor Research**: buat shortlist vendor, libatkan user dan SME
2. **Vendor Demonstrations & Evaluation**: gunakan "sandbox" demo
3. **Needs & Requirements Assessment**: buat flow dan tabel kebutuhan fungsional
4. **Request for Bid (RFB/RFP)**: minta proposal lengkap dari vendor
5. **Release RFB to Vendors**
6. **Vendor Analysis & Elimination**: analisa TCO, evaluasi kontrak, teknologi, fungsi
7. **Negotiation**: bahas lisensi, layanan, pihak yang bertanggung jawab
8. **Purchase System**

---

## 📝 Isi RFB/RFP
- Tipe ERP yang diinginkan
- Spesifikasi infrastruktur
- Kebutuhan pelatihan
- Isu kontrak khusus perusahaan

---

## 🤝 Negosiasi & Kontrak
- Fokus pada hak customer dalam otorisasi dan penerimaan
- Tunjuk *contract monitor* untuk jaga kepatuhan
- Perubahan kontrak hanya bila perlu dan disepakati bersama

---

## 📌 Implikasi untuk Manajemen
- Manajemen harus ikut evaluasi & demo sistem
- Wajib diskusi arah pengembangan sistem ke depan
- Negosiasi ke 2 vendor hasilkan harga lebih baik

---

## 🧾 Ringkasan
- Tahapan: riset → kebutuhan → RFI → RFB → seleksi → kontrak
- TCO jadi penilaian utama
- Dokumen, diskusi, dan demo penting untuk keputusan pembelian

# 📘 Week 5 – Blockchain Technology in Enterprise

## 🎯 Tujuan Pembelajaran
- Memahami kebutuhan dan definisi blockchain
- Menjelaskan fitur utama dan cara kerja blockchain
- Mengidentifikasi aplikasi blockchain di bisnis dan pemerintahan
- Mengenali tantangan dan keterbatasan teknologi blockchain

---

## 🔐 Apa itu Blockchain?
- Buku besar digital terdistribusi dan tidak dapat diubah
- Semua peserta jaringan memiliki salinan ledger
- Cocok untuk pencatatan aset, transaksi, dan kontrak

---

## 🧩 Konsep Utama
- **Participants**: pelanggan, regulator, pemerintah, dll
- **Transactions**: perpindahan aset (dihubungkan dengan kontrak)
- **Smart Contract**: otomatisasi kontrak tanpa perantara
- **Shared Ledger**: semua peserta bisa melihat data yang relevan

---

## ⚙️ Cara Kerja Blockchain
1. Transaksi dibuat dan ditandatangani digital
2. Diverifikasi oleh node → transaksi sah dikirim ke antrian
3. Mining node membentuk blok → disebar ke jaringan
4. Jika blok sah → ditambahkan ke rantai (blockchain)

---

## 💡 Kenapa Blockchain?
- Transparansi dan kepercayaan otomatis
- Data tidak dapat dimodifikasi (immutability)
- Riwayat lengkap transaksi → traceability
- Otomatisasi melalui smart contract

---

## 🛠️ Jenis Blockchain
| Tipe | Karakteristik |
|------|---------------|
| **Public** | Terbuka, semua orang bisa akses (Bitcoin, Ethereum) |
| **Private** | Diatur oleh entitas, terbatas (Supply Chain) |
| **Hybrid** | Kombinasi public dan private untuk fleksibilitas |

---

## 🏢 Penggunaan di Bisnis
- **Supply Chain**: transparansi, verifikasi asal barang
- **Identitas Digital**: kontrol data pribadi, aman & tanpa perantara
- **Aset Digital & NFT**: bukti kepemilikan, efisiensi transaksi
- **Data Sharing**: enkripsi dan pengelolaan akses
- **Smart Contract**: otomatisasi pembayaran, invoice, dsb

---

## 🏛️ Penggunaan di Pemerintahan
- Efisiensi layanan publik
- Transparansi dalam audit dan pengadaan
- Verifikasi dokumen secara otomatis dan aman

---

## ⚠️ Tantangan & Keterbatasan
- Skalabilitas dan performa transaksi
- Masalah privasi data dalam sistem terbuka
- Konsumsi energi tinggi (Proof of Work)
- Tidak cocok untuk sistem dengan update/delete rutin

---

# 📘 Week 6 – Artificial Intelligence in Enterprise

## 🎯 Tujuan Pembelajaran
- Pengenalan AI dan penerapannya dalam konteks bisnis
- Mengetahui aplikasi AI di berbagai bidang perusahaan
- Mengenal tantangan dan etika dalam penggunaan AI
- Studi kasus AI di perusahaan besar

---

## 🧠 Apa itu AI?
- Simulasi kecerdasan manusia oleh mesin
- Tujuan: membuat mesin yang bisa belajar, berpikir, dan mengambil keputusan

### Jenis AI:
- **ANI (Narrow AI)**: khusus tugas tertentu (chatbot, mesin pencari)
- **AGI (General AI)**: setara manusia, belum tercapai
- **Generative AI**: membuat konten baru (ChatGPT, Midjourney)

---

## 📊 Machine Learning: A → B Mapping
- Contoh: 
  - Email → spam/tidak
  - Gambar → ada cacat atau tidak
  - Kata → prediksi kata berikutnya

### LLM (Large Language Model)
- Dilatih dengan prediksi kata selanjutnya
- Contoh: "My favorite drink is..." → "lychee bubble tea"

---

## 🏢 Penerapan AI dalam Bisnis
- **Customer Service**: chatbot, prediksi kebutuhan
- **Data Analysis**: tren pasar real-time
- **Supply Chain**: prediksi kebutuhan, efisiensi pengiriman
- **Marketing & Sales**: personalisasi kampanye
- **HR**: seleksi kandidat, prediksi turnover

---

## 🧭 Transformasi AI dalam Perusahaan
- AI bukan sekadar tambahan → bagian inti bisnis modern
- Strategi meliputi:
  1. Pilot project
  2. Tim AI internal
  3. Pelatihan luas
  4. Strategi AI
  5. Komunikasi internal-eksternal

---

## ⚖️ Tantangan & Etika AI
- **Privasi Data**: penggunaan data sensitif
- **Bias Algoritma**: hasil diskriminatif jika datanya bias
- **Biaya Implementasi**: butuh investasi besar
- **Dampak Tenaga Kerja**: risiko kehilangan pekerjaan

---

## 🧪 Studi Kasus AI
- **Amazon**: otomatisasi gudang, rekomendasi, logistik
- **IBM Watson**: diagnosa medis
- **Coca-Cola**: analisis perilaku konsumen
- **Tesla**: sistem autopilot & manufaktur otomatis

---

## 🔍 Tren Mendatang: Explainable AI
- Fokus pada transparansi dalam pengambilan keputusan AI
