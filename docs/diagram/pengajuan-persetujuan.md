---
sidebar_position: 2
title: Pengajuan & Persetujuan
---

## Alur Pengajuan dan Persetujuan Sasaran Mutu

Diagram ini menjelaskan alur pengajuan, persetujuan, hingga revisi Sasaran Mutu (SM) beserta aturan pembagian wewenang dan kondisi khusus di aplikasi.

![Pengajuan dan Persetujuan SM](../images/dig2.png)

1. Penyusunan & Pengajuan Draf: Penyusun (Yayasan/Super Admin, Kepala Divisi, atau Kabid/Kasi; Staf hanya bisa melihat) membuat SM berstatus Draf yang masih bebas diedit atau dihapus, lalu mengajukan seluruh draf unit sekaligus.
2. Validasi Bobot 100%: Sistem mengecek apakah total bobot seluruh SM di unit tersebut (termasuk yang sudah disetujui) tepat 100%; jika belum, pengajuan ditolak untuk diperbaiki terlebih dahulu.
3. Jalur Pengesahan:
   * Khusus Yayasan: Langsung disahkan otomatis saat diajukan tanpa memerlukan penyetuju.
   * Divisi & Unit: Status berubah menjadi Menunggu Persetujuan dan data dikunci sementara agar tidak diubah selama diperiksa.
4. Keputusan Penyetuju: Penyetuju dapat memproses per SM maupun sekaligus satu unit (dilarang menyetujui unitnya sendiri):
   * Dikembalikan: Wajib disertai catatan alasan agar SM bisa diedit dan diajukan ulang, sementara status SM lainnya di unit tersebut tetap aman.
   * Disetujui (Terkunci): Judul, bobot, SM induk, dan Lag KPI terkunci permanen; hanya bagian Aktivitas yang masih bisa diubah.
5. Urutan Turunan & Lag KPI: Unit bawahan baru dapat memilih SM induk setelah SM di atasnya disetujui (wajib berurutan dari Yayasan → Divisi → Bidang/Unit). Pastikan SM ujung sudah memiliki Lag KPI sebelum diajukan karena tidak dapat ditambahkan setelah disetujui tanpa membuka revisi.
6. Proses Revisi: Jika SM yang sudah disetujui perlu diubah, penyusun mengajukan revisi beserta alasannya; begitu dibuka penyetuju, seluruh SM unit tersebut kembali menjadi Draf Revisi (khusus revisi pasca-finalisasi, setiap SM wajib sudah diturunkan atau punya Lag KPI dengan total bobot 100% sebelum diajukan ulang).

## Penyusun dan Penyetuju

| Tingkatan Unit | Penyusun (Pengaju) | Penyetuju |
| :--- | :--- | :--- |
| **Yayasan (Layer 1)** | Pengguna Yayasan / Super Admin | Tidak ada (langsung sah otomatis) |
| **Divisi (Layer 2)** | Kepala Divisi | Pengelola Yayasan / Super Admin |
| **Unit / Bidang (Layer 3+)** | Kabid / Kasi unit tersebut | Kepala Divisi induk (Yayasan & Super Admin juga berwenang) |
| **Aturan Umum** | **Staf** hanya dapat melihat (tidak bisa menyusun, mengajukan, atau menyetujui) | Pengaju dilarang menyetujui SM unitnya sendiri (kecuali Yayasan) |
