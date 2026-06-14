# MirrorSync v1.2.1

## Perubahan

- Keyboard scrcpy diubah dari input Android SDK menjadi keyboard fisik UHID.
- Tombol angka dan input keyboard PC menjadi lebih kompatibel dengan kolom teks
  Android, termasuk ketika terhubung melalui Wireless Debugging.
- MirrorSync tidak membaca atau menyimpan tombol, PIN, maupun password.
- Panduan koneksi WiFi dan batas paste/autotext pada kolom password diperjelas.

## Catatan keamanan

Aplikasi bank dapat sengaja memblokir clipboard, autotext, atau keyboard eksternal
pada kolom PIN/password. MirrorSync tidak mencoba melewati proteksi tersebut.
Ketik langsung dengan keyboard UHID atau gunakan layar HP jika aplikasi tetap
menolak input eksternal.
