- Overview :
  Repositori ini berisi proyek portofolio pemula dalam bidang Digital Forensik. Fokus utama adalah melakukan investigasi terhadap sebuah file PDF untuk memahami integritas data dan riwayat modifikasinya.

- Isi Repositori :
  memverifikasi pdf menggunakan hash, exiftool dan hxd.pdf:
  Laporan lengkap hasil analisis yang mencakup verifikasi Hash, melihat Metadata, dan inspeksi struktur Biner menggunakan Hex Editor.

- Ringkasan Analisis :
  Verifikasi Integritas: Menggunakan SHA-256 untuk memverifikasi integritas file.

- Rekonstruksi Riwayat: 
  Menemukan jejak penggunaan Microsoft Word 2016 dan Adobe InDesign CS6 yang tersimpan di dalam struktur biner, yang menunjukkan riwayat modifikasi file sebelum menjadi PDF final.

- Validasi Biner: 
  Mengonfirmasi kesamaan data antara metadata dengan data mentah pada struktur biner tertentu.

- Tools :
  ExifTool
  HxD 
  SHA-256 Hash Generator 
