Anda bisa mendapatkan api key disini: [https://dmbf.dz-tools.my.id/user/get-api-key](https://dmbf.dz-tools.my.id/user/get-api-key)

jika anda belum punya akun anda bisa daftar dulu disini: [https://dmbf.dz-tools.my.id/user/create](https://dmbf.dz-tools.my.id/user/create)

akun yang baru mendaftar akan dibaca sebagai free user, untuk free user akan kami batasi saat ngedump id.

jika ingin tidak dibatasi anda bisa meng-upgrade ke premium user dengan harga 40k/bulan (dana/pulsa) ke nomor *6282211142579*

#### CARA UPGRADE KE PREMIUM:
 - kirim email anda ke whatsApp [Admin](https://wa.me/6282211142579) yang tadi buat daftar di web [ini](https://dmbf.dz-tools.my.id)
 - kirim bukti tf ke whatsApp [Admin](https://wa.me/6282211142579)

maaf jika saya jarang on, saya sendiri punya kesibukan di real life hhee.

#### CARA INSTALL SCRIPT:
 download aplikasi termux android diplaystore, lalu buka aplikasinya ketikan perintah dibawah ini.
 ```
  pkg update && pkg upgrade
  pkg install python git
  pip install requests bs4 futures
  rm -rf dmbf
  git clone https://github.com/dz-id/dmbf
 ```
 oke sekarang script sudah terinstall
#### CARA MENJALANKAN SCRIPT:
 sekarang karena script sudah diinstall tinggal kita jalankan, ketikan perintah dibawah ini:
 ```
 cd $HOME/dmbf
 python run.py
 ```
 oke script sudah berhasil dijalankan tinggal pastekan api key anda yang baru saja dibuat disini: [https://dmbf.dz-tools.my.id/user/get-api-key](https://dmbf.dz-tools.my.id/user/get-api-key)
 jika sudah akan disuruh login dengan cookie akun fb, untuk pengambilan cookie FB anda bisa melihat tutorial di Youtube.

##### info:
 untuk versi sekarang hanya support di perangkat yang *aarch64* untuk mengecek
 ketik perintah ini : ```uname -m``` jika muncul *aarch64* selamat anda bisa menggunakan script ini,
 oh iya script ini juga cuma bisa dijalanin dipython veri 3.9 untuk mengecek versi python
 ketik perintah ini : ```python --version```

##### catatan:
 gunakanlah dengan bijak, atas apapun yang terjadi admin tidak bertanggung jawab.
