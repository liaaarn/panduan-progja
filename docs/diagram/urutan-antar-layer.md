---
sidebar_position: 3
title: Urutan Antar-Layer
---


## Urutan Antar-Layer

Diagram ini menjelaskan alur berurutan dari atas ke bawah (Yayasan → Divisi → Bidang/Unit) dalam menyusun, menyetujui, hingga memfinalisasi Sasaran Mutu (SM).

![Urutan Antar-Layer](../images/dig3.png)

## Urutan Langkah

1. Susun SM Yayasan: Yayasan membuat SM dengan total ($\Sigma$) bobot tepat 100%.
2. Pengesahan Yayasan: Yayasan mengajukan SM tersebut dan statusnya langsung disahkan otomatis.
3. Susun SM Divisi: Divisi mulai menyusun SM dengan memilih SM Yayasan yang sudah sah sebagai induk.
4. Ajukan ke Yayasan: Divisi mengirimkan pengajuan SM ke Yayasan.
5. Persetujuan Yayasan: Yayasan memeriksa lalu menyetujui atau mengembalikan SM Divisi.
6. Susun SM Unit: Unit/Bidang mulai menyusun SM dengan memilih SM Divisi yang sudah disetujui sebagai induk.
7. Ajukan ke Divisi: Unit mengirimkan pengajuan SM ke Divisi.
8. Persetujuan Divisi: Divisi memeriksa lalu menyetujui atau mengembalikan SM Unit.
9. Finalisasi: Yayasan melakukan finalisasi akhir setelah semua syarat beres dan tidak ada lagi penghalang.

## Aturan & Ketergantungan
* Cabang berjalan mandiri: Antar-cabang atau divisi yang berbeda (misalnya Divisi Pendidikan dan Divisi Humpro) berjalan sendiri-sendiri tanpa saling menunggu.
* Divisi tanpa unit di bawahnya: Divisi seperti Humpro langsung memasang Lag KPI pada langkah 3 dan alurnya selesai setelah disetujui Yayasan pada langkah 5 (tidak melewati langkah 6–8).
* Unit wajib menunggu induk disetujui: Unit tidak bisa mulai menyusun SM sebelum SM Divisi di atasnya disetujui (pilihan SM induk akan kosong atau ditolak dengan pesan "Sasaran induk belum disetujui").

## Syarat Finalisasi
1. Penghalang Finalisasi (Memblokir sistem sampai diperbaiki):
* Yayasan belum memiliki SM.
* Total bobot SM di suatu unit tidak sama dengan ($\neq$) 100%.
* Masih ada SM yang belum disetujui.
* Ada SM yang menggantung (tidak diturunkan dan tidak punya Lag KPI).
* Total bobot Lag KPI di dalam suatu SM tidak sama dengan ($\neq$) 100%.
2. Peringatan Saja (Tidak menghambat finalisasi):
* Ada unit yang belum menyusun SM.
* Ada Lag KPI yang belum dilengkapi aktivitas.