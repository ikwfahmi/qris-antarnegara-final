# Status produksi dan bukti

Paket ini adalah serah terima animasi dan bahan penyuntingan 120 detik. Render penuh,
rekaman manusia dan ekspor final CapCut belum dibuat di paket ini. Bukti teknis bukan
jaminan nilai dosen atau kelulusan lomba.

| Poin UAS yang diminta peserta | Bukti yang tersedia |
|---|---|
| 2. Cerita dan karakter | Tujuan Amir membeli hadiah, uang rupiah kurang, solusi QRIS, transaksi dan oleh-oleh selesai. Naskah/cue Ardi dan Amir disertakan. |
| 3. Storyboard dan perspektif | Storyboard-Final-120detik.pdf berisi 14 scene dengan objek, action, moment, kamera, timing dan audio. Panduan v9 dipertahankan sebagai arsip proses sebelum revisi akhir. |
| 4. Walk cycle dan osilasi | Amir berjalan pada adegan masuk/pulang. Ayunan lengan dan gerak kain hasil bake terlihat pada film. |
| 5. Transformasi | Kios, rak, suvenir, pot, bangku, pohon dan paving ditata dengan translasi/rotasi/skala. Proporsi tangan/lengan direvisi pada mesh dan rig. |
| 6. Proyeksi dan viewing | Kamera perspektif 35-78 mm, 27 marker kamera. Daftar-Kamera-Final.csv menyimpan lensa, FOV dan frame. |
| 7. Cahaya dan shading | Lampu KEY 650 W, FILL 420 W, RIM 850 W serta SUN kawasan. Material menggunakan diffuse/specular melalui Principled BSDF; objek matte dan mengkilap dapat dilihat pada contoh Cycles. |
| 8. Simulasi | Kain pada film berasal dari bake cloth + wind. File solver dan cache disertakan dalam 01-Blender/Bukti-Simulasi. Gerak film memakai hasil bake; tidak perlu menghitung simulasi ulang untuk render. |
| 9. Compositing | DOF aktif pada kamera dan node Color Balance aktif pada compositing. Contoh gambar Cycles memperlihatkan jalur render tersebut. |

# Tugas peserta sebelum pengumpulan

- Render dan ekspor final MP4/MOV 1080x1920, maksimal 120 detik. Preview kecil bukan hasil pengumpulan.
- Rekam suara manusia dan periksa sinkronisasi mulut; saat ini viseme mengikuti teks/cue.
- Ketentuan yang Anda salin pada percakapan melarang generative AI menghasilkan teks,
  audio atau visual utuh secara instan. Naskah sumber di folder Dubbing masih diberi
  penanda bantuan AI. Peserta perlu mengolah dan menetapkan naskah dengan bahasanya sendiri,
  serta jujur mencatat alat AI yang dipakai; paket ini tidak menyatakan naskah tersebut
  otomatis memenuhi orisinalitas lomba. Perubahan kata dapat mengharuskan cue/lip-sync disesuaikan.
- Pastikan asal dan izin aset karakter/lingkungan yang diberikan peserta; lisensi audio CC0
  di paket ini tidak otomatis membuktikan hak atas model 3D pihak lain.
- Publikasikan pada akun TikTok/Instagram publik, mention @bank_indonesia, gunakan caption
  wajib dan #BIDCC2026, lalu sediakan tautan Drive publik sesuai ketentuan peserta.
  Follow akun resmi, identitas/kelayakan, dan pengiriman tetap ditangani peserta.
- Daftar alat yang benar-benar dipakai untuk bantuan pada revisi ini: ChatGPT/Codex untuk
  arahan dan skrip; Blender + MCP untuk penyuntingan rig/pose; FFmpeg/Python untuk
  transkode, pengaturan audio, subtitle dan preview. Tidak dibuat dubbing AI atau visual AI baru.

Nominal MYR dan layar aplikasi pada film merupakan simulasi edukasi; bukan tangkapan
aplikasi Malaysia yang dipakai melakukan transaksi nyata. Jangan menghapus keterangan
simulasi sehingga tampak sebagai bukti transaksi sungguhan.

Pedoman tema dan soal UAS asli disertakan di folder Aturan. Status akun, hak aset,
keikutsertaan, unggahan dan keputusan penilaian tidak bisa diverifikasi dari file Blender.
