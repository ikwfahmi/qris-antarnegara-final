# QRIS Antarnegara — Arsip Final

Animasi Blender tentang Amir, wisatawan Malaysia, dan Ardi, penjual suvenir di Yogyakarta.
Blender **5.2.3 LTS**, 1080 × 1920, 24 fps, 2.880 frame / 120 detik.

## Unduh proyek lengkap

Buka [Release final-v1](https://github.com/ikwfahmi/qris-antarnegara-final/releases/tag/final-v1) lalu unduh **QRIS-FINAL-LENGKAP.tar.zst** dan berkas SHA256.
File Blender dan media besar berada di lampiran Release, tidak dalam riwayat Git.
Repo ini privat: masuk menggunakan akun yang diberi akses.

Di Linux, ekstrak dengan:

```bash
tar --zstd -xf QRIS-FINAL-LENGKAP.tar.zst
```

## Isi paket

| Folder | Isi |
|---|---|
| `01-Blender` | Proyek utama `QRIS-120detik-Server-CPU.blend`, alternatif Eevee, sumber/cache cloth, dan skrip render sampai MP4 |
| `02-Edit-CapCut` | Video render, audio gabungan, SRT penonton, SRT dengan label tokoh |
| `03-Storyboard-dan-Dokumen` | Storyboard final PDF, kamera, naskah take terbaru, ketentuan UAS/lomba dan lisensi |
| `04-Audio-Sumber` | Audio asli, sumber CC0, SFX, serta musik/SFX/ambience terpisah |
| `05-Pratinjau` | Video acuan take dubbing dengan subtitle terbaru |
| `06-Skrip-Proses` | Kode produksi dan perbaikan sebagai catatan proses; sebagian path historis perlu disesuaikan jika dijalankan ulang |
| `07-Verifikasi` | Pemeriksaan video, subtitle, simulasi dan perbaikan karakter |

## Pemakaian

- Mulai dengan proyek CPU untuk server tanpa GPU render; gunakan Eevee pada GPU yang mendukung.
- Aset gambar/font proyek utama sudah dipaketkan dalam `.blend`.
- Video yang tersedia di folder kerja adalah **hasil render tanpa dubbing**, bukan ekspor CapCut final yang sudah dipublikasikan. Audio gabungan berisi musik/SFX/ambience, tidak termasuk rekaman dialog manusia.
- Subtitle terbaru berisi 47 cue; semua kata naskah dipertahankan. Impor salah satu SRT, dengan video mulai tepat 00:00.
- Naskah take terbaru dan subtitle terbaru menjadi acuan waktu. Beberapa dokumen storyboard/audit historis masih menyebut cue sebelum revisi subtitle.
- Izin musik/aset, penggunaan bantuan AI, dan syarat lomba tetap mengikuti dokumen sumber; repo privat ini tidak memberi lisensi publik atas aset pihak ketiga.

Gambar PNG render mentah, cache pemeriksaan, ZIP salinan, dan revisi lama tidak disertakan karena hasil utama beserta proyek editnya dipertahankan.
