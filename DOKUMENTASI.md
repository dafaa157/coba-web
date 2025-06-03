# Dokumentasi Website Sistem Informasi Nilai

## 1. Deskripsi Singkat
Website ini dibuat sebagai sarana pencatatan, pengelolaan, dan penampilan nilai mahasiswa.
Mendukung autentikasi dan akses terpisah untuk dosen, mahasiswa, dan admin.

## 2. Fitur-Fitur
-  **Login dan Logout**
-  **Navbar**
-  **Responsive**
-  **CRUD**

## 3. Screenshot Implementasi
### a. Halaman Login
<div style="display: flex; gap: 20px;">
  <div>
    <img src="assets/image/doc/login.png" width="100%">
    <p style="text-align: center;">Desktop</p>
  </div>
  <div>
    <img src="assets/image/doc/login2.png"width="100%">
    <p style="text-align: center;">Mobile</p>
  </div>
</div>


### b. Halaman Dashboard
- Admin
<div style="display: flex; gap: 20px;">
  <div>
    <img src="assets/image/doc/admin1.png" width="100%">
    <p style="text-align: center;">Desktop</p>
  </div>
  <div>
    <img src="assets/image/doc/admin2.png" width="100%">
    <p style="text-align: center;">Mobile</p>
  </div>
</div>

- Dosen
<div style="display: flex; gap: 20px;">
  <div>
    <img src="assets/image/doc/dosen1.png" width="100%">
    <p style="text-align: center;">Desktop</p>
  </div>
  <div>
    <img src="assets/image/doc/dosen2.png" width="100%">
    <p style="text-align: center;">Mobile</p>
  </div>
</div>

- Mahasiswa
<div style="display: flex; gap: 20px;">
  <div>
    <img src="assets/image/doc/murid1.png"width="100%">
    <p style="text-align: center;">Desktop</p>
  </div>
  <div>
    <img src="assets/image/doc/murid2.png" width="100%">
    <p style="text-align: center;">Mobile</p>
  </div>
</div>

### c. Fitur-Fitur
#### 1. Bagian Admin
1.1 Kelola Data Dosen 
- Tampilan Awal + Hasil Delete
<div style="gap: 20px;">
  <div>
  <img src="assets/image/doc/fit-adm-dd.png" width="100%">
  </div>
</div>

- Tampilan Form Edit 
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-adm-de.png" width="100%">
</div>

- Kelola Data Dosen (Tampilan Form Tambah)
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-adm-dt.png" width="100%">
</div>

1.2 Kelola Data Mahasiswa
<div style="gap: 20px;">
  <img src="assets/image/doc/adm-kel-dm.png" width="100%">
</div>

1.3 Kelola Data Mata Kuliah
<div style="gap: 20px;">
  <img src="assets/image/doc/adm-kel-dmatk.png" width="100%">
</div>

1.4 Kelola Data Semester
<div style="gap: 20px;">
  <img src="assets/image/doc/adm-kel-ds.png" width="100%">
</div>

1.5 Kelola Data Kelas 
- Tampilan Awal
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-adm-dkls.png" width="100%">
</div>

- Atur Dosen
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-adm-ad.png" width="100%">
</div>

- Atur Mahasiswa
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-adm-am.png" width="100%">
</div>


#### 2. Bagian Dosen
2.1 Kelola Jenis Penilaian
- Tampilan Awal
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-dos-tpjen.png"  width="100%">
</div>

- Edit Jenis Penilaian
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-dos-tpedjen.png"  width="100%">
</div>
2.2 Kelola Bobot Nilai
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-dos-tpbob.png" width="100%">
</div>
2.3 Kelola Nilai Mahasiswa
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-dos-tpnil.png" width="100%">
</div>

#### 3. Bagian Mahasiswa
3.1 Penampilan Transkrip Nilai
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-mhs-tptnil.png" width="100%">
</div>
3.2 Penampilan Kalkulator Nilai Akhir
<div style="gap: 20px;">
  <img src="assets/image/doc/fit-dos-tpnil.png"  width="100%">
</div>

## 4. Struktur Folder
```plaintext
pendataanNilai/
├── admin/
│   ├── atur_dosen_kelas.php
│   ├── atur_mahasiswa_kelas.php
│   ├── dashboard.php
│   ├── delete_data_dosen.php
│   ├── delete_data_kelas.php
│   ├── delete_data_mahasiswa.php
│   ├── delete_data_mata_kuliah.php
│   ├── delete_data_semester.php
│   ├── delete_dosen_kelas.php
│   ├── delete_mahasiswa_kelas.php
│   ├── edit_data_dosen.php
│   ├── edit_data_kelas.php
│   ├── edit_data_mahasiswa.php
│   ├── edit_data_mata_kuliah.php
│   ├── edit_data_semester.php
│   ├── kelola_dosen.php
│   ├── kelola_kelas.php
│   ├── kelola_mahasiswa.php
│   ├── kelola_mata_kuliah.php
│   ├── kelola_semester.php
│   ├── tambah_dosen.php
│   ├── tambah_kelas.php
│   ├── tambah_mahasiswa.php
│   ├── tambah_mata_kuliah.php
│   └── tambah_semester.php
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── image/
│   │   └── doc/
│   └── js/
│       └── script.js
├── database/
│   └── urp_nilai.sql
├── dosen/
│   ├── bobot_nilai.php
│   ├── dashboard.php
│   ├── edit_bobot.php
│   ├── edit_jenis_nilai.php
│   ├── edit_nilai.php
│   ├── hapus_bobot.php
│   ├── hapus_jenis_nilai.php
│   ├── hapus_nilai.php
│   ├── jenis_nilai.php
│   ├── nilai_mahasiswa.php
│   ├── tambah_bobot_nilai.php
│   ├── tambah_jenis_nilai.php
│   └── tambah_nilai.php
├── mahasiswa/
│    ├── dashboard.php
│    ├── hitung_nilai_akhir.php
│    └── lihat_nilai.php
├── DOKUMENTASI.md
├── config.php
├── login.php
└── logout.php
```

## 5. Teknologi yang Digunakan
- PHP 
- HTML5 
- CSS (Bootstrap, Font Awesome)
- JavaScript (Bootstrap, Popper)
- phpMyAdmin
- MySQL

## 6. Link Hosting
Website online bisa diakses melalui:  
🔗 [Link 🦅](https:hostingnyamanatangkas)

---

**Disusun oleh:**  
**Anomali Penyuka Taplak Meja**