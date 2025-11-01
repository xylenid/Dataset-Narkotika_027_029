# 📚 Dataset Putusan Narkotika – PN Balige  

Repository ini dibuat untuk memenuhi **Tugas 2 – Temu Kembali Informasi (SUBCPMK-2)**  
oleh:  
- 👩 **Faradhita Eka Septiana (027)**  
- 👨 **Febri Bagus Triwibowo (029)**  

---

## 🧾 Deskripsi  
Dataset ini berisi **50 dokumen putusan pengadilan** dari **Pengadilan Negeri Balige**  
dengan klasifikasi **Pidana Khusus – Narkotika dan Psikotropika**.  
Seluruh dokumen diunduh secara manual dari situs resmi  
[Direktori Putusan Mahkamah Agung RI](https://putusan3.mahkamahagung.go.id/direktori.html)  
untuk rentang tahun **2024 – 2025** dan **tidak berstatus Berkekuatan Hukum Tetap (BHT)**.  

Dataset ini bersifat **terbuka (open data)** dan dapat dimanfaatkan sebagai sumber data  
pada tugas **Temu Kembali Informasi** maupun riset hukum dan NLP.

---

## 📂 Struktur Repository

```
Dataset-Narkotika_027_029/
├── 📁 Dataset
│   └── 📦 Narkotika.zip
├── 📁 Overview
│   └── 📊 Overview.xlsx
└── 📄 README.md
```

---

## 🧩 Metadata `Overview.xlsx`
File `Overview.xlsx` berisi ringkasan 50 putusan dengan lima kolom utama:

| Kolom | Keterangan |
|:------|:------------|
| **No** | Nomor urutan 1-50 |
| **No Putusan** | Nomor putusan lengkap (contoh: 51/Pid.Sus/2025/PN Blg) |
| **Lembaga Peradilan** | Nama Pengadilan Negeri (contoh: PN Balige) |
| **Barang Bukti** | Rincian barang bukti yang disebut dalam amar putusan |
| **Amar Putusan** | Ringkasan isi putusan (hukuman, denda, penetapan barang bukti) |

**Contoh baris:**

| No | No Putusan | Lembaga Peradilan | Barang Bukti | Amar Putusan |
|----|-------------|-------------------|---------------|---------------|
| 1 | 51/Pid.Sus/2025/PN Blg | PN Balige | 1 (satu) paket sabu 1 gram + timbangan digital | Menyatakan Terdakwa RINCEN SARAGIH bersalah … |

---

## 📊 Informasi Teknis  
- Jumlah dokumen  : **50 PDF**  
- Tahun putusan    : **2024 – 2025**  
- Pengadilan        : **PN Balige**  
- Status putusan   : **Belum Berkekuatan Hukum Tetak**  
- Ukuran ZIP       : ± 7.8 MB  
- File ringkasan   : `Overview.xlsx`

---

## ⚖️ Sumber Data  
Direktori Putusan Mahkamah Agung Republik Indonesia  
🔗 <https://putusan3.mahkamahagung.go.id/direktori.html>

---

## 📜 Lisensi  
Dataset ini bersifat **terbuka (Open Data)** dan dapat digunakan kembali  
untuk tujuan akademik non-komersial.
