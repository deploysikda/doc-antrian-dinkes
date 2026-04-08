# [HOME](README.md)

# INFORMASI UPDATE: FITUR BRIDGING ANTRIAN DENGAN BPJS

Halaman ini memuat informasi mengenai pembaruan terbaru pada Aplikasi Antrian Dinkes terkait pengaktifan fitur **Bridging dengan Sistem BPJS Kesehatan**.

---

## Ringkasan Pembaruan

Pada versi pembaruan ini, aplikasi telah mendukung integrasi data antrian secara _real-time_ ke sistem BPJS Kesehatan (Mobile JKN). Pembaruan ini secara otomatis akan mengirimkan _Task ID_ kepada server BPJS sesuai dengan pergerakan pasien di fasilitas kesehatan (Puskesmas).

### FITUR BARU & PENINGKATAN (ADDED & CHANGED)

---

### [ UPDATED: 08 April 2026 ]

---

#### 1. [ Pengecekan Status Antrian ]

Role: Admin

Pengecekan Status Antrian bisa di pantau di akun admin antrian dinkes pada menu "Antrian".

![Pengecekan Status Antrian](media/pengecekan-status-antrian.png)

#### 2. [ Kuota ANjungan dan Kuota JKN (Mobile JKN) ]

Kuota pasien di pisah menjadi Kuota Anjungan dan Kuota JKN (Mobile JKN)

![Kuota ANjungan dan Kuota JKN (Mobile JKN)](media/kuota-anjungan-dan-kuota-jkn.png)

#### 3. [ Edit Jadwal ]

Role: Admin

Penambahan fitur edit jadwal praktek dokter di akun admin puskesmas

![Edit Jadwal](media/penambahan-fitur-edit-jadwal.png)

#### 4. [ Validasi Skrining ]

Role: Anjungan

Adanya Validasi pasien yang belum skrining untuk pasien yang mengambil antrian poli ketika di puskesmas, ada keterangan pasien belum skrining di tiket antrian jika pasien belum melakukan skrining, kemudian ada tombol pindai skrining untuk melakukan skrining.

![Tiket Belum Skrining](media/tiket-belum-skrining.jpeg)
![Pindai Skrining](media/pindai-skrining.jpeg)

---

## Apa yang Harus Dilakukan Tindak Lanjut oleh Puskesmas?

1. **Update Jadwal Praktek**: Pastikan Admin Puskesmas mengisi jadwal praktek dokter di akun admin antrian dinkes di setiap tanggal pelayanan.

2. **Update Jadwal HFIS**: Pastikan Admin Puskesmas mengisi jadwal HFIS sesuai dengan jadwal praktek dokter di akun admin antrian dinkes.

3. **Selesaikan Status Antrian**: Pastikan Admin Puskesmas menyelesaikan status antrian pasien di akun admin atau poli di sistem antrian dinkes.

4. **Cakupan Antrian BPJS**: Pastikan untuk status di pcare dari setiap pasien adalah _**Bridging Antrian**_ / Bridging MJKN, karena perhitungan cakupan bpjs akan dihitung berdasarkan status tersebut.

---

<!-- > **Referensi Resmi**: Anda dapat merujuk ke portal **Web Service BPJS Kesehatan (Trustmark)** untuk informasi spesifikasi teknis API selengkapnya. -->
