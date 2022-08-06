**Table of Contents**

- [Support Me](#support-me)
- [Keterangan Config](#keterangan-config)
  - [Config Rule Online](#config-rule-online)
    - [Kekurangan Rule Online](#kekurangan-rule-online)
    - [Kelebihan Rule Online](#kelebihan-Rule-Online)
  - [Config Rule Offline](#config-rule-offline)
    - [Kekurangan Rule Offline](#kekurangan-rule-offline)
    - [Kelebihan Rule Offline](#kelebihan-rule-offline) 
- [Persiapan](#persiapan)  
  - [Download File Config](#download-file-config)
  - [Setting Clash For Android](#setting-clash-for-android)     
- [Langkah Pemasangan Config Rule Online](#langkah-pemasangan-config-rule-online)
- [Langkah Pemasangan Config Rule Offline](#langkah-pemasangan-config-rule-offline)
- [Cara Update Rule Online](#cara-update-rule-online)
- [Thanks To](#thanks-to)

# SUPPORT ME
Anda Bisa Menghubungi Kami Untuk Permasalahan Config

- [Instagram](https://instagram.com/afthon_pc)
- [Telegram](https://t.me/AfthonPc)
- [Whatsapp](https://wa.me/6285334821022)


# KETERANGAN CONFIG
**Config Yang Saya Sediakan Terdapat Dua Model yaitu:** `CONFIG RULE ONLINE` **dan** `CONFIG RULE OFFLINE`

## Config Rule Online

**Config rule online adalah config yang rule provider nya berbasis `URL` dan akan selalu sinkron dengan repository github ini ketika melakukan update**

### Kekurangan Rule Online

1. Diwajibkan untuk terhubung ke internet dalam pemasangan config. Baik melalui data reguler, wifi, inject atau yang lain. Karena pemasangan config akan melalui proses download repository github
2. Rule provider tidak bisa di custom dengan rule milik anda sendiri, karena akan auto sinkron dengan rule di repo github ini

### Kelebihan Rule Online

1. Config yang rule providernya tinggal pakai tidak perlu repot-repot edit, memasukkan manual dan bingung mencari rule sana sini.
2. Rule akan memperoleh update terbaru jika menyinkronkannya

## Config Rule Offline

**Config rule offline adalah config yang rule providernya berbasi `FILE` dengan metode pemasangan secara manual**

### Kekurangan Rule Offline

1. Proses pemasangan config akan sedikit ribet karena perlu memasukkan rule provider satu persatu (manual)
2. Rule provider tidak bisa auto update dengan kata lain harus mengedit dan menambahkan sendiri

### Kelebihan Rule Offline

1. Tidak perlu terhubung ke internet pada saat pemasangan config karena tidak ada proses download
2. Rule provider bisa anda custom dengan kemauan sendiri

MODE | Kelebihan | Kekurangan
------------ | ------------- | -------------
Rule Online </span> | Config yang rule providernya tinggal pakai tidak perlu repot-repot edit, memasukkan manual dan bingung mencari rule sana sini </span> | Diwajibkan untuk terhubung ke internet dalam pemasangan config. Baik melalui data reguler/wifi. Karena pemasangan config akan melalui proses download repository github  
</span> | 2. kekurangan


# PERSIAPAN

## Download File Config

**Unduh File Keseluruhan Config dan ekstrak zip menggunakan `Zarchiver` atau pengekstrak yang lain. Download zip config** [DISINI](https://github.com/GboyGud/clash_for_android/files/9267975/clash_for_android-main.zip)


## Setting Clash For Android

1. Pada halaman awal aplikasi, pilih tab `Settings`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/setting1.jpg" border="0">

2. Kemudian pilih tab `Override`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/setting2.jpg" border="0">

3. Pada menu Override tadi, scroll kebawah hingga berada pada tab `Mode`. Pastikan anda mengatur mode yang semula Do not modify menjadi `Rule Mode`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/setting3x.jpg" border="0">

4. Maka pada langkah ini selesai. Untuk settingan yang lain pada menu `Override` tidak perlu diubah karena sudah include dalam config


# LANGKAH PEMASANGAN CONFIG RULE ONLINE

1. Pastikan perangkat anda terhubung dengan internet

2. Pada halaman awal apikasi, pilih tab `Profile`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import1.jpg" border="0">

3. Pilih icon `tambah` pada pojok kanan atas

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/icontambah.jpg" border="0">

4. Klik tab `File`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import2.jpg" border="0">

5. Isi kolom `Name` sesuai keinginan anda, lalu klik `Browse Files`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import3.jpg" border="0">

6. Klik titik tiga kemudian pilih `Import`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import4.jpg" border="0">

7. Arahkan ke directory anda mengekstrak file config. Kemudian pilih file yang bernama `CONFIG_RULE_ONLINE.yaml`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/imprt5.jpg" border="0">

8. Setelah config utamanya diimport, selanjutnya adalah mengimport file proxy. Dengan cara klik `Provider Files`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import6.jpg" border="0">

9. Kemudian klik icon tambah pada pojok kanan atas

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/icontambah2.jpg" border="0">

10. Arahkan kembali ke directory anda mengekstrak file config, lalu masuk ke folder `proxy_provider`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/imprt7.jpg" border="0">

11. Tambahkan kedua file yang ada di dalam folder `proxy_provider` tersebut

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import8.jpg" border="0">

12. Maka akan muncul kedua file yang telah diimport tadi

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import9.jpg" border="0">

**Cukup dua file yang diimport, selebihnya tidak perlu, karena rule provider berbasis `URL` bukan lagi file**

13. Edit kedua file `AKUN_UMUM.yaml` dan `AKUN_GAME.yaml` untuk menambahkan akun vpn anda. Pastikan sesuai dengan [FORMAT AKUN CLASH](https://github.com/GboyGud/FORMAT_AKUN_CLASH). Pengeditan bisa menggunakan app editor apapun, namun saran saya menggunakan `QuickEdit`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import10.jpg" border="0">

14. Setelah pengeditan selesai, klik back dan jangan lupa disimpan dengan menekan tombol di pojok kanan atas

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import11.jpg" border="0">

15. Maka akan ada proses download repository github seperti pada gambar

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import11prt2.jpg" border="0">

16. Pastikan profile yang dibuat tadi telah di `select` dan berwarna biru seperti digambar

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import12.jpg" border="0">

17. Maka proses pemasangan config telah selesai. Selanjutnya tinggal mengkonekkannya dengan cara klik `Tap to start` hingga berubah menjadi `Running`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/run1.jpg" border="0">

18. Pastikan akun vpn yang anda masukkan tadi telah muncul ping untuk memastikan konek/tidaknya. Dengan mengeceknya pada tab `Proxy`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/run2.jpg" border="0">

19. Tekan icon `petir` untuk mengecek ping, dan pastikan semua akun keluar pingnya seperti digambar

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/run3x.jpg" border="0">

20. Selesai


# LANGKAH PEMASANGAN CONFIG RULE OFFLINE
- Coming Soon

# CARA UPDATE RULE ONLINE

1. Konekkaan clash android anda agar muncul menu `Providers` lalu diklik

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/update1.jpg" border="0">

2. Klik icon refresh pada pojok kanan atas

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/update2.jpg" border="0">

3. Pastikan status berubah menjadi `Recently`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/update3.jpg" border="0">

4. Lakukan update seperti ini setidaknya satu kali dalam sebulan agar rule tetap dalam keadaan update


# THANKS TO

- **ALLAH SWT**
- **KELUARGA**
- **SEMUA PIHAK YANG TELAH MENSUPORT AGAR PROJECT INI TERUS BERLANJUT**
- **SEMUA PIHAK YANG TELAH MEMBANTU DALAM BENTUK MATERI MAUPUN DOA**
