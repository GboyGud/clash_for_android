**Table of Contents**

- [Support Me](#support-me)
- [Keterangan Config](#keterangan-config)
  - [Kelebihan dan Kekurangan Tiap Config](#kelebihan-dan-kekurangan-tiap-config) 
- [Persiapan](#persiapan)  
  - [Download File Config](#download-file-config)
    - [Config Rule Online](#config-rule-online)
    - [Config Rule Offline](#config-rule-offline)
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
- Config rule online adalah config yang rule provider nya berbasis `URL` dan akan selalu sinkron dengan repository github ini ketika melakukan update
- Config rule offline adalah config yang rule providernya berbasis `FILE` dengan metode pemasangan secara manual

## Kelebihan dan Kekurangan Tiap Config

CONFIG | KEKURANGAN | KELEBIHAN
------------ | ------------- | -------------
Rule Online </span> | 1. Diwajibkan terhubung ke internet, baik melalui data reguler/wifi. Karena pemasangan config akan melalui proses download repository github </span> | 1. Rule provider tinggal pakai tidak perlu repot-repot edit, memasukkan manual dan bingung mencari rule sana sini  
</span> | 2. Rule provider tidak bisa di custom dengan rule milik anda sendiri, karena akan auto sinkron dengan rule di repo github ini </span> | 2. Rule akan memperoleh update terbaru jika menyinkronkannya
Rule Offline </span> | 1. Proses pemasangan config akan sedikit ribet karena perlu memasukkan rule provider satu persatu (manual) </span> | 1. Tidak perlu terhubung ke internet pada saat pemasangan config karena tidak ada proses download
</span> | 2. Rule provider tidak bisa auto update dengan kata lain harus mengedit dan menambahkan sendiri </span> | 2. Rule provider bisa anda custom dengan kemauan sendiri


# PERSIAPAN

## DOWNLOAD FILE CONFIG

### Config Rule Online

**Unduh File `CONFIG_RULE_ONLINE` dan ekstrak zip menggunakan `Zarchiver` atau pengekstrak yang lain. Download zip config** [DISINI](https://github.com/GboyGud/clash_for_android/files/9274534/clash_for_android-main.zip)

### Config Rule Offline

- Coming Soon


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

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import5v2.jpg" border="0">

8. Setelah config utamanya diimport, selanjutnya adalah mengimport file proxy. Dengan cara klik `Provider Files`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import6.jpg" border="0">

9. Kemudian klik icon tambah pada pojok kanan atas

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/icontambah2.jpg" border="0">

10. Arahkan kembali ke directory anda mengekstrak file config, lalu masuk ke folder `proxy_provider`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import7v2.jpg" border="0">

11. Tambahkan kedua file yang ada di dalam folder `proxy_provider` tersebut

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import8v2.jpg" border="0">

12. Maka akan muncul kedua file yang telah diimport tadi

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import9v2.jpg" border="0">

13. Edit kedua file `AKUN_UMUM.yaml` dan `AKUN_GAME.yaml` untuk menambahkan akun vpn anda. Pastikan sesuai dengan [FORMAT AKUN CLASH](https://github.com/GboyGud/FORMAT_AKUN_CLASH). Pengeditan bisa menggunakan app editor apapun, namun saran saya menggunakan `QuickEdit`

   <img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import10v2.jpg" border="0">

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
