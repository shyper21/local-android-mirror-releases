# MirrorSync v1.3.1

## Perbaikan

- Backend lama pada port 3030 sekarang dihentikan berdasarkan listener port,
  sehingga versi dashboard dan backend tidak lagi berbeda setelah update.
- Download update berjalan di background dan dashboard menampilkan tahap serta
  progress. Installer baru dijalankan setelah SHA-256 selesai diverifikasi.
- Dashboard dan jendela scrcpy memakai AppUserModelID yang sama agar Windows
  mengelompokkannya di bawah satu ikon taskbar MirrorSync.
- Activity & Error Log dipindahkan ke tab tersendiri dan ukuran dashboard native
  diperkecil agar halaman kontrol lebih ringkas.
- Mode keyboard baru dapat dipilih antara UHID dan SDK. Tombol Fix Keyboard
  me-restart sesi mirror dengan mode alternatif tanpa pair ulang.
- Tombol Keyboard Settings membuka pengaturan Physical Keyboard Android untuk
  memilih layout perangkat HID.

## Catatan keyboard aman

Gunakan UHID lebih dulu karena diperlakukan Android sebagai keyboard fisik.
Aplikasi perbankan atau kolom password tertentu tetap dapat menolak keyboard
eksternal berdasarkan kebijakan keamanan aplikasi tersebut.
