<div align="center">

# 🏪 Digital Twin Warung Kak Ros

### Sistem Informasi dan Statistik Penjualan UMKM

<p>
  <strong>📊 Project Charter</strong>
  <br>
  <em>Mengubah data operasional menjadi informasi yang mudah dipantau.</em>
</p>

[📋 Trello Project Board](https://trello.com/b/uidA3Hw4/digital-twin-warung-kak-ros)

</div>

---

## 📑 Daftar Isi

- [A. Informasi Proyek](#a--informasi-proyek)
- [B. Latar Belakang](#b--latar-belakang)
- [C. Ide Proyek](#c--ide-proyek)
- [D. Kondisi, Kebutuhan, dan Solusi](#d--kondisi-kebutuhan-dan-solusi)
- [E. Tujuan Proyek](#e--tujuan-proyek)
- [F. Solusi yang Diusulkan](#f--solusi-yang-diusulkan)
- [G. Ruang Lingkup](#g--ruang-lingkup)
- [H. Jadwal Proyek](#h--jadwal-proyek)
- [I. Batasan dan Asumsi](#i--batasan-dan-asumsi)
- [J. Stakeholder](#j--stakeholder)
- [K. Klasifikasi Stakeholder](#k--klasifikasi-stakeholder)
- [L. Work Breakdown Structure](#l--work-breakdown-structure-wbs)
- [M. Project Management](#m--project-management)
- [Ringkasan Proyek](#-ringkasan-proyek)

---

## A. 📌 Informasi Proyek

<table>
<tr><td><strong>📛 Nama Proyek</strong></td><td>Pengembangan Sistem Informasi dan Statistik Penjualan UMKM Kak Ros</td></tr>
<tr><td><strong>🏪 Konsep</strong></td><td>Digital Twin Warung Kak Ros</td></tr>
<tr><td><strong>👤 Sponsor / Pemilik</strong></td><td>Kak Ros</td></tr>
<tr><td><strong>🧑‍💼 Manajer Proyek</strong></td><td>Hamdani</td></tr>
<tr><td><strong>👨‍💻 Tim Pengembang</strong></td><td>Unedo Hesekiel Clinton Sirait &amp; Mustaqim</td></tr>
</table>

---

## B. 📝 Latar Belakang

Warung Kak Ros merupakan usaha mikro yang bergerak di bidang penjualan makanan dan minuman. Dalam kegiatan operasionalnya, beberapa proses seperti pencatatan pesanan, pemeriksaan stok, serta pencatatan pemasukan dan pengeluaran masih dilakukan secara manual.

Kondisi tersebut dapat menyulitkan pemantauan ketika jumlah pelanggan meningkat, terutama pada jam ramai. Pemilik juga membutuhkan informasi yang lebih mudah untuk melihat kondisi stok, pesanan, pemasukan, pengeluaran, rekap usaha, serta perkembangan usaha.

> 💡 **Permasalahan utama:** data operasional masih tersebar dalam proses manual sehingga membutuhkan media terpusat untuk membantu pemantauan usaha.

Berdasarkan hasil observasi tersebut, diperlukan sebuah sistem yang dapat merepresentasikan kondisi operasional Warung Kak Ros secara digital dan menyajikan informasi tersebut dalam satu tempat.

---

## C. 💡 Ide Proyek

Proyek ini mengusulkan **Digital Twin Warung Kak Ros**, yaitu representasi digital dari kondisi operasional warung yang memanfaatkan data kegiatan usaha untuk membantu proses pemantauan.

### 🔄 Konsep Digital Twin

```text
┌──────────────────────────────┐
│     OPERASIONAL WARUNG       │
│  Pesanan • Stok • Keuangan   │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│       DATA SISTEM            │
│ Input & Pengelolaan Data     │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│       DIGITAL TWIN           │
│ Representasi Kondisi Usaha   │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│          DASHBOARD           │
│ Rekap • Grafik • Monitoring  │
└──────────────────────────────┘
```

### 📦 Informasi yang Dipusatkan

| Modul | Informasi |
|---|---|
| 🧾 **Pesanan** | Data dan status pesanan |
| 📦 **Stok** | Ketersediaan bahan/barang |
| 💰 **Pemasukan** | Data pemasukan dan penjualan |
| 💸 **Pengeluaran** | Data pengeluaran |
| 📋 **Rekap** | Ringkasan kegiatan usaha |
| 📈 **Perkembangan** | Visualisasi perkembangan usaha |

---

## D. 🔍 Kondisi, Kebutuhan, dan Solusi

| 🔴 Kondisi Saat Ini | 🟡 Kebutuhan | 🟢 Solusi yang Diusulkan |
|---|---|---|
| Pesanan masih dipantau secara manual | Pemantauan pesanan lebih terstruktur | 🧾 Pencatatan dan pemantauan pesanan |
| Stok diperiksa secara manual | Informasi stok mudah dipantau | 📦 Monitoring stok |
| Pemasukan dan pengeluaran dicatat manual | Pencatatan keuangan lebih terstruktur | 💰 Pencatatan pemasukan & pengeluaran |
| Rekap usaha masih dilakukan secara manual | Rekap mudah dilihat | 📋 Dashboard rekap usaha |
| Perkembangan usaha belum divisualisasikan | Informasi perkembangan dalam bentuk visual | 📈 Grafik perkembangan usaha |

---

## E. 🎯 Tujuan Proyek

Membangun sebuah **Digital Twin** yang dapat merepresentasikan kondisi operasional Warung Kak Ros secara digital sehingga informasi mengenai:

**Pesanan • Stok • Pemasukan • Pengeluaran • Rekap • Perkembangan Usaha**

dapat dipantau dalam **satu sistem terintegrasi**.

### 🎯 Target Utama

- 🧾 Memusatkan data pesanan.
- 📦 Memudahkan pemantauan stok.
- 💰 Menyediakan pencatatan pemasukan.
- 💸 Menyediakan pencatatan pengeluaran.
- 📋 Menyediakan rekap kegiatan usaha.
- 📊 Menampilkan perkembangan usaha secara visual.

---

## F. 🚀 Solusi yang Diusulkan

Mengembangkan sistem **Digital Twin berbasis dashboard** yang merepresentasikan kondisi operasional Warung Kak Ros berdasarkan data yang dimasukkan ke dalam sistem.

### ✨ Fitur Utama

| # | Fitur | Fungsi |
|---:|---|---|
| 01 | 🧾 **Pesanan** | Pencatatan dan pemantauan pesanan |
| 02 | 📦 **Stok** | Monitoring stok bahan |
| 03 | 💰 **Pemasukan** | Pencatatan pemasukan |
| 04 | 💸 **Pengeluaran** | Pencatatan pengeluaran |
| 05 | 📋 **Rekap** | Rekap kegiatan usaha |
| 06 | 📊 **Dashboard** | Ringkasan kondisi operasional |
| 07 | 📈 **Grafik** | Visualisasi perkembangan usaha |

---

## G. 📐 Ruang Lingkup

### ✅ Termasuk dalam Proyek

- [x] Pengelolaan data pesanan
- [x] Pengelolaan data stok
- [x] Pengelolaan pemasukan dan penjualan
- [x] Pengelolaan pengeluaran
- [x] Rekap data operasional
- [x] Dashboard dan visualisasi data
- [x] Representasi kondisi operasional Warung Kak Ros secara digital

### ❌ Tidak Termasuk dalam Proyek

- [ ] Penggunaan sensor atau perangkat IoT
- [ ] Otomatisasi pengukuran stok secara fisik
- [ ] Pemodelan 3D warung
- [ ] Integrasi dengan sistem eksternal

---

## H. 🗓️ Jadwal Proyek

| Tahap | Kegiatan Utama | Waktu |
|:---:|---|:---:|
| **01** | 🔎 **Inisiasi & Perencanaan** — observasi, wawancara, Project Charter, stakeholder, WBS, pembagian tugas | **Minggu 1** |
| **02** | 🧠 **Analisis Kebutuhan** — analisis proses operasional dan kebutuhan sistem | **Minggu 1–2** |
| **03** | 🛠️ **Perancangan & Pengembangan** — database, antarmuka, dan fitur utama | **Minggu 2–3** |
| **04** | 🧪 **Pengujian & Finalisasi** — pengujian, perbaikan, dokumentasi, presentasi | **Minggu 4** |

### 🛣️ Timeline

```text
Minggu 1          Minggu 2          Minggu 3          Minggu 4
   │                 │                 │                 │
   ▼                 ▼                 ▼                 ▼
┌─────────┐      ┌────────────┐    ┌──────────────┐   ┌───────────┐
│ Inisiasi│ ───► │  Analisis  │ ─► │ Development │ ─►│ Testing   │
│ & Plan  │      │ Kebutuhan  │    │ & Design    │   │ & Final   │
└─────────┘      └────────────┘    └──────────────┘   └───────────┘
```

---

## I. ⚙️ Batasan dan Asumsi

| # | Batasan / Asumsi |
|---:|---|
| 01 | Data sistem diperoleh dari kegiatan operasional Warung Kak Ros. |
| 02 | Sistem tidak menggunakan IoT atau sensor. |
| 03 | Pencatatan penggunaan bahan per pesanan masih berdasarkan data yang tersedia dari pemilik. |
| 04 | Sistem berfokus pada pemantauan dan representasi kondisi operasional, bukan otomatisasi seluruh kegiatan warung. |

---

## J. 👥 Stakeholder

| No. | Stakeholder | Peran | Kepentingan | Keterlibatan |
|---:|---|---|---|---|
| 01 | **Kak Ros** | Pemilik UMKM | Memantau kondisi operasional warung | Memberikan kebutuhan, masukan, dan menjadi pengguna utama |
| 02 | **Bang Amat** | Pengelola Operasional | Mendukung kegiatan operasional warung | Memberikan informasi proses operasional dan dapat menggunakan sistem |
| 03 | **Hamdani** | Project Manager UMKM | Menghasilkan sistem sesuai kebutuhan proyek | Analisis, perancangan, pengembangan, pengujian, dokumentasi |
| 04 | **Unedo Hesekiel Clinton Sirait** | Developer | Menghasilkan sistem sesuai kebutuhan proyek | Analisis, perancangan, pengembangan, pengujian, dokumentasi |
| 05 | **Mustaqim** | Developer | Menghasilkan sistem sesuai kebutuhan proyek | Analisis, perancangan, pengembangan, pengujian, dokumentasi |
| 06 | **Ibu Cut Alna Fadila** | Dosen / Supervisor | Memastikan proyek sesuai tujuan dan ketentuan tugas | Arahan, evaluasi, dan masukan |

---

## K. 📊 Klasifikasi Stakeholder

| Stakeholder | Pengaruh | Kepentingan |
|---|:---:|:---:|
| Kak Ros | 🔴 Tinggi | 🔴 Tinggi |
| Bang Amat | 🔴 Tinggi | 🔴 Tinggi |
| Hamdani | 🔴 Tinggi | 🔴 Tinggi |
| Unedo Hesekiel Clinton Sirait | 🔴 Tinggi | 🔴 Tinggi |
| Mustaqim | 🔴 Tinggi | 🔴 Tinggi |
| Ibu Cut Alna Fadila | 🔴 Tinggi | 🔴 Tinggi |

> 📌 **Catatan:** Seluruh stakeholder utama berada pada tingkat **pengaruh tinggi** dan **kepentingan tinggi**, sehingga komunikasi dan koordinasi perlu dilakukan secara aktif selama proyek berlangsung.

---

# L. 🧩 Work Breakdown Structure (WBS)

## 1. Struktur Pekerjaan Proyek

```text
🏪 1. DIGITAL TWIN WARUNG KAK ROS
│
├── 📌 1.1 INISIASI PROYEK
│   ├── 1.1.1 Identifikasi objek UMKM
│   ├── 1.1.2 Observasi dan wawancara
│   ├── 1.1.3 Penyusunan Latar Belakang & Ide Proyek
│   ├── 1.1.4 Penyusunan Project Charter
│   └── 1.1.5 Identifikasi Stakeholder
│
├── 📋 1.2 PERENCANAAN PROYEK
│   ├── 1.2.1 Penyusunan WBS
│   ├── 1.2.2 Identifikasi kebutuhan sistem
│   ├── 1.2.3 Perhitungan Function Point
│   ├── 1.2.4 Pembagian tugas tim
│   ├── 1.2.5 Penyusunan jadwal proyek
│   └── 1.2.6 Pengelolaan tugas menggunakan Trello
│
├── 🔎 1.3 ANALISIS KEBUTUHAN
│   ├── 1.3.1 Analisis proses operasional warung
│   ├── 1.3.2 Analisis kebutuhan pesanan
│   ├── 1.3.3 Analisis kebutuhan stok
│   ├── 1.3.4 Analisis kebutuhan pemasukan dan pengeluaran
│   ├── 1.3.5 Analisis kebutuhan rekap
│   └── 1.3.6 Analisis kebutuhan dashboard
│
├── 🎨 1.4 PERANCANGAN SISTEM
│   ├── 1.4.1 Perancangan alur sistem
│   ├── 1.4.2 Perancangan database
│   ├── 1.4.3 Perancangan antarmuka
│   └── 1.4.4 Perancangan dashboard Digital Twin
│
├── 💻 1.5 PENGEMBANGAN SISTEM
│   ├── 1.5.1 Pengembangan modul pesanan
│   ├── 1.5.2 Pengembangan modul stok
│   ├── 1.5.3 Pengembangan modul pemasukan
│   ├── 1.5.4 Pengembangan modul pengeluaran
│   ├── 1.5.5 Pengembangan rekap
│   └── 1.5.6 Pengembangan dashboard dan grafik
│
├── 🧪 1.6 PENGUJIAN SISTEM
│   ├── 1.6.1 Pengujian fitur pesanan
│   ├── 1.6.2 Pengujian fitur stok
│   ├── 1.6.3 Pengujian fitur keuangan
│   ├── 1.6.4 Pengujian dashboard
│   └── 1.6.5 Evaluasi bersama pemilik
│
└── 📚 1.7 DOKUMENTASI & PENYELESAIAN
    ├── 1.7.1 Dokumentasi proses pengembangan
    ├── 1.7.2 Dokumentasi hasil pengujian
    ├── 1.7.3 Penyusunan laporan proyek
    └── 1.7.4 Finalisasi dan presentasi
```

---

# M. 🔗 Project Management

## 🗂️ Trello Board

Pengelolaan task, pembagian pekerjaan, dan pemantauan progres proyek dilakukan menggunakan **Trello**.

<div align="center">

### 📋 Digital Twin Warung Kak Ros

[**👉 Buka Trello Project Board**](https://trello.com/b/uidA3Hw4/digital-twin-warung-kak-ros)

</div>

### 🎯 Fungsi Trello dalam Proyek

| Aktivitas | Penggunaan |
|---|---|
| 📋 **Task Management** | Mencatat pekerjaan yang harus dilakukan |
| 👥 **Task Assignment** | Membagi pekerjaan kepada anggota tim |
| 🔄 **Progress Tracking** | Memantau status pekerjaan |
| 📅 **Project Planning** | Mengorganisasi pekerjaan berdasarkan tahapan |
| 📝 **Documentation** | Menyimpan informasi pendukung pekerjaan |

> 💡 Trello menjadi media pendukung WBS untuk memvisualisasikan pekerjaan proyek, status tugas, pembagian tugas anggota, serta progres pengembangan.

---

# 📊 Ringkasan Proyek

<table>
<tr><td><strong>🏪 Proyek</strong></td><td>Digital Twin Warung Kak Ros</td></tr>
<tr><td><strong>🎯 Fokus</strong></td><td>Sistem informasi dan statistik penjualan UMKM</td></tr>
<tr><td><strong>📍 Objek</strong></td><td>Warung Kak Ros</td></tr>
<tr><td><strong>🔄 Konsep</strong></td><td>Representasi digital kondisi operasional warung</td></tr>
<tr><td><strong>📦 Data Utama</strong></td><td>Pesanan, stok, pemasukan, pengeluaran, dan rekap</td></tr>
<tr><td><strong>📊 Output</strong></td><td>Dashboard dan visualisasi perkembangan usaha</td></tr>
<tr><td><strong>📋 Manajemen Tugas</strong></td><td>Trello</td></tr>
<tr><td><strong>🗓️ Durasi</strong></td><td>4 Minggu</td></tr>
<tr><td><strong>👤 Pengguna Utama</strong></td><td>Kak Ros dan pengelola operasional</td></tr>
<tr><td><strong>🚫 Batasan</strong></td><td>Tanpa IoT, sensor, pemodelan 3D, dan integrasi sistem eksternal</td></tr>
</table>

---

## 🔗 Referensi Proyek

- 📋 [**Trello — Digital Twin Warung Kak Ros**](https://trello.com/b/uidA3Hw4/digital-twin-warung-kak-ros)

---

<div align="center">

## 🏪 Digital Twin Warung Kak Ros

**Sistem Informasi dan Statistik Penjualan UMKM**

`Project Charter • WBS • Stakeholder • Timeline • Project Management`

<br>

*Built with teamwork, planning, and data-driven thinking.*

</div>
