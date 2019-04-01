# Custom Macbook Login
Hilangkan pilihan "Other..." dan ganti wallpaper saat login di Mojave.

Pernah melihat pilihan user "Other..." seperti gambar di bawah ini?
<img src="https://github.com/omrobbie/Custom-Macbook-Login/blob/master/screenshot/preview1.png" />

Sebagian orang tidak suka dengan opsi ini, termasuk aku. Jadi aku memutuskan untuk menghilangkan opsi ini dengan perintah:
```bash
sudo defaults write /Library/Preferences/com.apple.loginwindow SHOWOTHERUSERS_MANAGED -bool FALSE
```

Kita bisa lihat contohnya seperti gambar di bawah ini:
<img src="https://github.com/omrobbie/Custom-Macbook-Login/blob/master/screenshot/preview2.png" />

Kemudian, sebelum logout untuk melihat hasilnya, sekalian saja ganti wallpapernya. Caranya, cari folder `/Library/Desktop\ Pictures/` dan ganti file `Mojave.heic` dengan gambar yang kalian suka. File lama bisa kita backup file aslinya seperti contoh gambar di bawah ini:
<img src="https://github.com/omrobbie/Custom-Macbook-Login/blob/master/screenshot/preview3.png" />

Ini hasilnya.
<img src="https://github.com/omrobbie/Custom-Macbook-Login/blob/master/screenshot/preview4.png" />

### Have fun!
