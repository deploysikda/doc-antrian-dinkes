# [HOME](README.md)
# CHANGELOG | PEMBARUAN APLIKASI ANTRIAN DINKES

<!-- ![logo-antrian](media/logo-antrian-transparent.png) -->

## 1.1.2 - 15-12-25

Version: 1.1.2 |
Tanggal: 15 Desember 2025

### CHANGED
---
#### [ AKUN ADMIN PUSKESMAS ]
- [ AKSES PUBLIK BISA LANGSUNG ONLINE TANPA SERVER LOCAL YANG DI INSTALL DI PUSKESMAS ] -> Jika menggunakan [__Link Akses Aplikasi - Akses Publik__](README.md#link-akses-aplikasi) dan mengosongkan ip pada bagian edit puskesmas maka akan secara default akan menembak server yang berada di dinkes, sehingga tidak perlu lagi untuk install / set / menjalankan server antrian secara local di puskesmas.
  
![cara-bayar-pasien-anjungan](media/changelog-1-1-2-default-akses-publik-ke-server.png)

Secara default jika tidak menggunakan server antrian local di puskesmas maka akan langsung online.

![langsung-online](media/changelog-1-1-3-semua-akan-langsung-online.png)


---


## 1.1.1 - 10-12-25

Version: 1.1.1 |
Tanggal: 10 Desember 2025

### ADDED
---

#### [ AKUN ADMIN PUSKESMAS ]
- [ AKUN ADMIN ] -> Suara Pemanggilan antrian di bagian Poli bisa di rubah menjadi "Ruangan".
  
![suara-panggilan-poli](media/changelog-1-1-1-1-atur-suara-panggil-poli.png)

- [ AKUN ADMIN ] -> Jika ip server tidak di set di bagian admin puskesmas, maka secara default akan terhubung dengan server yang berada di Dinas.
  
![default-server](media/changelog-1-1-1-3-ip-kosong-akan-konek-ke-server-dinas.png)

- [ AKUN ADMIN ] [ MODE BRIDGING SIKDA PASIEN UMUM ] -> Terdapat 2 Mode Bridging SIKDA, silahkan disesuaikan dengan kondisi alur di puskesmas masing-masing.
  
![default-server](media/changelog-1-1-1-7-mode-bridging-sikda.png)
![default-server](media/changelog-1-1-1-8-pilih-mode-bridging-sikda.png)

#### [ AKUN PENDAFTARAN PUSKESMAS ]
- [ AKUN PENDAFTARAN ] -> Terdapat penambahan tombol skip dan batal di akun loket pendaftaran.
  
![tombol-skip-batal](media/changelog-1-1-1-4-tombol-skip-batal.png)

#### [ AKUN ANJUNGAN PUSKESMAS ]
- [ AKUN ANJUNGAN ] -> Terdapat keterangan usia di popup verifikasi bagian kanan bawah.
  
![keterangan-usia](media/changelog-1-1-1-5-keterangan-usia.png)



### CHANGED
---
#### [ AKUN ANJUNGAN ]
- [ AKUN ANJUNGAN ] -> Cara bayar pasien sesuai dengan kondisi saat cetak antrian, jika pasien umum maka data cara bayar nya akan tunai, jika pasien jkn maka cara bayar nya akan jkn.
  
![cara-bayar-pasien-anjungan](media/changelog-1-1-1-2-cara-bayar-pasien-sesuai-kondisi-saat-cetak-antrian.png)

#### [ AKUN PENDAFTARAN ]
- [ AKUN PENDAFTARAN ] -> Dibagian pasien Ketika klik Selesai akan muncul verifikasi pasien yang tadinya BPJS/Gratis menjadi di pisah Gratis dan BPSJ, kemudian ada keterangan usia pasien tersebut. 
  
![cara-bayar-pasien-anjungan](media/changelog-1-1-1-6-pemisahan-usia-keterangan-usia.png)

---

## 1.1.0 - 15-09-25

Version: 1.1.0 |
Tanggal: 15 September 2025

### ADDED
---
#### [ AKUN ADMIN PUSKESMAS ]
- [ AKUN ADMIN PUSKESMAS ] -> Tampilan jadwal praktek BPJS ditampilkan di bagian tambah jadwal, sehingga menjadi panduan untuk menambahkan jadwal di aplikasi antrian dinkes.
  
![panduanpraktek](media/changelog-1-1-tampilan-jadwal-praktek-bpjs.png)

#### [ AKUN PENDAFTARAN ]
- Penambahan tombol Gratis/BPJS ketika menekan tombol selesai pendaftaran ![](media/selesaikan-pasien.png).
  
![tombolgratis](media/changelog-1-3-1-tombol-gratis-bpjs.png)

#### [ AKUN KASIR ]
- Penambahan tombol Gratis/BPJS ketika menekan tombol selesai Pembayaran ![](media/selesaikan-pasien.png).
  
![tombolgratis](media/changelog-1-3-2-tombol-gratis-bpjs-di-kasir.png)

#### [ AKUN POLI ]
- [ AKUN POLI ] -> terdapat filtering data pasien yang mengantri di tenaga kesehatan tertentu, sehingga memudahkan untuk filtering pemanggilan ke poli.
  
![Filter Poli](media/changelog-1-4-filter-berdasar-nakes-poli.png)


### CHANGED
---
#### [ AKUN PENDAFTARAN ]
- [ AKUN PENDAFTARAN ] -> Editing NIK di bagian Pendaftaran ( bagi yang sudah cetak antrian pasien baru di anjungan ), memungkinkan dilakukan peng-editan di pendaftaran.
  
![editnikpendaftaran](media/changelog-1-2-edit-nik-pendaftaran.png)
![editnikpendaftaran](media/changelog-1-2-1-modal-edit-nik-pendaftaran.png)

---