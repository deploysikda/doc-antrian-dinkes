# [HOME](README.md)
# CHANGELOG | PEMBARUAN APLIKASI ANTRIAN DINKES

<!-- ![logo-antrian](media/logo-antrian-transparent.png) -->

## 1.1.3 - 08-01-26

Version: 1.1.3 |
Tanggal: 08 Januari 2025

### CHANGED
---
#### [ AKUN ADMIN PUSKESMAS ]
- [ PENGATURAN PASIEN BPJS ] -> Pasien BPJS hanya dapat mendaftar pada FKTP yang sesuai dengan data BPJSnya.
  
Pilih di pengaturan untuk memilih kondisi 

![pilih-kondisi](media/changelog-1-1-3-pilih-kondisi-pasien.png)

![kondisi-cara-bayar](media/changelog-1-1-3-kondisi-pasien-bpjs_19-12-25.png)

- [ PENGATURAN PASIEN IMUNISASI ] -> Pendaftaran KIA Imunisasi akan dijadikan gratis untuk semua pasien
  
Pilih di pengaturan untuk memilih kondisi 

![pilih-kondisi](media/changelog-1-1-3-3-kondisi_cara_bayar_pasien_imunisasi.png)
![pilih-kondisi](media/changelog-1-1-3-4-output_cara_bayar_pasien_imunisasi.png)


- [ SUARA PEMANGGILAN PASIEN DI POLI ] -> Pemanggilan pasien di poli bisa sesuaikan sesuai dengan preferensi di puskesmas.
  
Pilih di pengaturan untuk setting nama pemanggilan

![pilih-kondisi](media/changelog-1-1-3-5-pengaturan-pemanggilan-suara-poli.png)

Di bagian Poliklinik pilih Edit untuk mengatur custom suara per poli

![pilih-kondisi](media/changelog-1-1-3-6-edit-custom-suara-poli.png)

Akan muncul Popup dan klik Text to Sound untuk membuat custom sound

![pilih-kondisi](media/changelog-1-1-3-7-texttosound-custom-suara-poli.png)

Buat custom text sendiri di soundoftext.com

![pilih-kondisi](media/changelog-1-1-3-8-texttosound-custom-suara-poli-generate.png)

Download untuk disimpan di komputer yang nantinya akan di upload di pengaturan antrian dinkes

![pilih-kondisi](media/changelog-1-1-3-9-texttosound-custom-suara-poli-download.png)

Kembali ke Pengaturan Antrian Dinkes pilih custom

![pilih-kondisi](media/changelog-1-1-3-10-custom-suara-poli-set.png)

Di bagian Audio Pemanggilan pilih file yang sudah di download dari sounoftext.com dan pilih file audio nya untuk di upload.

![pilih-kondisi](media/changelog-1-1-3-11-custom-suara-poli-upload.png)

Kemudia klik tombol Simpan jika sudah selesai.

![pilih-kondisi](media/changelog-1-1-3-12-custom-suara-poli-simpan.png)

Jika sudah di set maka suara pemanggilan akan ada penambahan custom suara seperti yang sudah di set.


#### [ AKUN POLI PUSKESMAS ]

- [ FILTERING POLI DAN NAKES ] -> Di akun user poli bisa juga memanggil pasien di poli lain, sehingga satu user poli bisa digunakan untuk banyak poli.

![pilih-kondisi](media/changelog-1-1-3-13-filter-poli-nakes.png)

---



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