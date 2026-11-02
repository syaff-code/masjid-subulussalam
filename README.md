# Display Jadwal Sholat TV — Masjid Subulussalam

Aplikasi display jadwal sholat satu halaman (Single Page) berbasis web yang dirancang khusus untuk layar TV / Smart TV / STB Masjid Subulussalam, Kota Tangerang Selatan, Banten.

## Fitur Utama

- **Jadwal Akurat Sesuai Lokasi**: Menggunakan data resmi Bimas Islam Kementerian Agama RI (Kota Tangerang Selatan - ID: 1108) via MyQuran API, dengan fallback otomatis ke perhitungan Aladhan (Metode Kemenag RI).
- **Offline Resilient**: Menyimpan cache jadwal di browser lokal (`localStorage`). Tampilan tetap berjalan lancar meski koneksi internet terputus.
- **Kutipan Harian Islami & Gen Z (400+ Database)**:
  - Ayat-ayat Al-Qur'an pilihan lengkap dengan rujukan surat & ayat (`QS. ...`).
  - Hadits-hadits shahih & hasan lengkap dengan perawi (`HR. ...`).
  - Reminder Islami kekinian gaya Gen Z.
  - Berganti otomatis setiap hari sepanjang tahun tanpa pengulangan.
- **Transisi Sholat Otomatis**:
  - Countdown waktu sholat berikutnya (sorot emas interaktif).
  - Mode Layar Penuh Adzan saat masuk waktu.
  - Hitung mundur Iqamah otomatis (disesuaikan tiap waktu sholat).
  - Mode Layar Gelap (Quiet Screen) saat sholat berjamaah berlangsung.
- **Desain Modern & Bernuansa Islami**:
  - Warna hijau zamrud dengan aksen emas elegan (*non-AI look*).
  - Animasi lentera bergoyang, pola geometri kubah, dan siluet masjid.
  - Running text / ticker informasi masjid di bagian bawah.
  - Jam digital tabular dan penanggalan Hijriah Ummul Qura otomatis.
- **Optimasi Display TV 16:9**:
  - Auto fullscreen saat diklik / disentuh.
  - Screen Wake Lock API untuk menjaga layar tidak mati/tidur.
  - Auto-refresh berkala jam 01:00 dini hari untuk mencegah memory leak pada browser TV.

## Cara Penggunaan di TV Masjid

Cukup buka link GitHub Pages di browser Smart TV, Android TV, atau mini PC masjid:
`https://syaff-code.github.io/masjid-subulussalam/`

Klik sekali di layar atau tekan remote untuk mode fullscreen.
