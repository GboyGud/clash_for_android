**Table of Contents**

- [Support Me](#support-me)
- [Keterangan Config](#keterangan-config)
  - [Config Rule Online](#config-rule-online)
    - [kekurangan Rule Online](#kekurangan-rule-online)
    - [Kelebihan Rule Online](#kelebihan-Rule-Online)
  - [Config Rule Offline](#config-rule-offline)
    - [kekurangan Rule Offline](#kekurangan-rule-offline)
    - [Kelebihan Rule Offline](#kelebihan-rule-offline)
- [Hal Pertama Yang Perlu Disetting](#hal-pertama-yang-perlu-disetting)    
- [Langkah Pemasangan Config Rule Online](#langkah-pemasangan-config-rule-online)
- [Langkah Pemasangan Config Rule Offline](#langkah-pemasangan-config-rule-offline)
- [Cara Update Rule Online](#cara-update-rule-online)

# SUPPORT ME
Anda Bisa Menghubungi Kami Untuk Permasalahan Config

- [Instagram](https://instagram.com/afthon_pc)
- [Telegram](https://t.me/AfthonPc)
- [Whatsapp](https://wa.me/6285334821022)

# KETERANGAN CONFIG
**Config Yang Saya Sediakan Terdapat Dua Model yaitu**: `CONFIG RULE ONLINE` **dan** `CONFIG RULE OFFLINE`

## Config RUle Online

Config rule online adalah config yang rule provider nya akan selalu sinkron dengan repository github ini ketika melakukan update. Dengan beberapa kekurangan dan kelebihan
### Kekurangan Rule Online

1. Diwajibkan untuk terhubung ke internet dalam pemasangan config. Baik melalui data reguler, wifi, inject atau yang lain. Karena pemasangan config akan melalui proses download repository github
2. Rule provider tidak bisa di custom dengan rule milik anda sendiri, karena akan auto sinkron dengan rule di repo github ini

### Kelebihan Rule Online

1. Config yang rule providernya tinggal pakai tidak perlu repot-repot edit, masukkan manual dan bingung mencari rule sana sini.
2. Rule akan memperoleh update terbaru jika menyinkronkannya

## Config Rule Offline

Config rule offline adalah config dengan metode penggunaan secara manual

### Kekurangan Rule Offline

1. Proses pemasangan config akan sedikit ribet karena perlu memasukkan rule provider satu-satu (manual)
2. Rule provider tidak bisa auto update dengan kata lain harus mengedit dan menambahkan sendiri

### Kelebihan Rule Offline

1. Tidak perlu terhubung ke internet pada saat pemasangan config karena tidak ada proses download
2. Rule provider bisa anda custom dengan kemauan sendiri

# HAL PERTAMA YANG PERLU DISETTING

1. Pada halaman awal aplikasi, pilih tab `Settings`

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/setting1.jpg" border="0">

2. Kemudian pilih tab `Override`

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/setting2.jpg" border="0">

3. Pada menu `Override` tadi, scroll kebawah hingga berada pada tab `Mode`. Pastikan anda mengatur mode yang semula Do not modify menjadi `Global Mode`

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/setting3.jpg" border="0">

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

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import52.jpg" border="0">

8. Setelah config utamanya diimport, selanjutnya adalah mengimport file proxy. Dengan cara klik `Provider Files`

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import6.jpg" border="0">

7. Kemudian klik icon tambah pada pojok kanan atas

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/icontambah2.jpg" border="0">

8. Arahkan kembali ke directory anda mengekstrak file config, lalu masuk ke folder `proxy_provider`

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import7.jpg" border="0">

9. Tambahkan kedua file yang ada di dalam folder `proxy_provider` tersebut

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import8.jpg" border="0">

10. Maka akan muncul kedua file yang telah diimport tadi

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/active9.jpg" border="0">

11. Edit kedua file tadi untuk menambahkan akun vpn anda. Bisa menggunakan app editor apapun, namun saran saya menggunakan `QuickEdit`

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import10.jpg" border="0">

12. Setelah pengeditan selesai, klik back dan jangan lupa disimpan dengan menekan tombol di pojok kanan atas

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import11.jpg" border="0">

13. Pastikan profile yang dibuat tadi telah di `select` dan berwarna biru seperti digambar

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/import12.jpg" border="0">

14. Maka proses pemasangan config telah selesai. Selanjutnya tinggal mengkonekkannya dengan cara klik `Tap to start` hingga berubah menjadi `Running`

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/run1.jpg" border="0">

15. Pastikan proxy global tidak terpilih `DIRECT` dengan mengeceknya pada tab `Proxy`

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/run2.jpg" border="0">

16. Jika semula yang terpilih adalah proxy `DIRECT` maka cukup pindahkan ke salah satu didalam garis perssegi yang saya tandai ini

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/run32.jpg" border="0">

17. Selesai


# LANGKAH PEMASANGAN CONFIG RULE OFFLINE
- Coming Soon

# CARA UPDATE RULE ONLINE

1. Konekkaan clash android anda agar muncul menu `Providers` lalu diklik

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/update1.jpg" border="0">

2. Klik icon refresh pada pojok kanan atas

<img src="https://raw.githubusercontent.com/GboyGud/clash_for_android/main/assets/update2.jpg" border="0">

3. Pastikan status berubah menjadi `Recently`
