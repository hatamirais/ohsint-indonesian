# OhSINT Writeup (IDN)

TryHackMe [Challange Room](https://tryhackme.com/room/ohsint)
Hatami Ra'is Bukhari (Althemier)


## What information can you possible get with just one photo?
OhSINT atau OSINT, adalah berbagai metode atau cara dalam mengumpulkan informasi, menganalisanya dan membuat keputusan dengan infromasi yang di dapat dari public resources (Bisa di akses semua orang seperti googling, dll)

Ruang ini akan mengenalkan tool - tool yang digunakan dalam OSINT untuk mengekstrak informasi dari sebuah foto.

Writeup ini ditulis dengan menggunakan Kali Linux sebagai test environtment. Hasil/proses bisa berbeda.

Klik download untuk memulai, anda akan mendapat file dengan nama `WindowsXP.jpg`.

> **Saran** : Sebelum memulai, ada baiknya untuk membuat folder baru. semua proses penulisan room ini akan di simpan di `readme.md` pada folder ohsint-indonesian

### What is this users avatar of?
Tool bernama exiftool digunakan untuk mengekstrak metadata (informasi) yang ada di dalam foto tersebut seperti dimana foto itu diambil, nama pemilik, ukuran, dll. Untuk menginstall exiftool bisa [klik disini](https://exiftool.org/install.html#Unix).

Setelah program terinstall, cukup menjalankan command `exiftool WindowsXP.jpg` di folder yang ada WindowsXP.jpg.

[Exiftool](https://exiftool.org/install.html#Unix) akan mengeluarkan hasil seperti `File Name`, `File Size`, dll, namun yang di perlukan pada challange ini adalah pada bagian ini
```bash
Copyright   : OWoodflint
```
Googling dengan keyword `OWoodflint` dan google akan mengeluarkan banyak hasil pencarian, salah satunya twitter. Di situlah jawabannya.

> Hint: klik hasil dari twitter, github, dan wordpress di tab baru untuk memudahkan pengerjaan ruangan ini

### What city this person in?

Github

###  Whats the SSID of the WAP he connected to?

"Jelajahi"
