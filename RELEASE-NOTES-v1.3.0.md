# MirrorSync v1.3.0

## Perubahan utama

- Dashboard sekarang dibuka melalui aplikasi Windows native berbasis WebView2,
  tanpa address bar atau icon Chrome.
- Layar HP tetap menjadi jendela terpisah untuk setiap perangkat, tetapi judul
  dan icon taskbar diganti menjadi branding MirrorSync serta inisial HP.
- Connection manager menyimpan perangkat WiFi yang pernah dikenal, menemukan
  connection port terbaru melalui ADB mDNS, dan mencoba reconnect dengan backoff.
- Perangkat yang sengaja diputus atau terkena kebijakan idle tidak langsung
  disambungkan kembali oleh auto-reconnect.
- Updater mencatat status download, verifikasi SHA-256, instalasi, dan kegagalan.
- Dashboard memeriksa update saat dibuka dan menampilkan banner, badge pending,
  serta pemberitahuan pada judul jendela. Update tetap menunggu klik user.
- Installer menutup backend, ADB server, dan host native sebelum mengganti file
  untuk mencegah error file sedang digunakan.

## Cara menguji update

Dari MirrorSync v1.2.1, klik **Check Update**, lalu **Download & Install**.
Aplikasi lama akan ditutup, update diverifikasi, lalu shortcut MirrorSync membuka
dashboard native v1.3.0. Tidak perlu mengunduh installer secara manual.
