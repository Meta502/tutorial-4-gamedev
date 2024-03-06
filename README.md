# Proses Pembuatan Tugas Mandiri
Untuk membuat level baru, saya pertama mengubah target scene ketika mencapai roket di Level1 dari WinScreen menjadi scene yang bernama Level2. Selanjutnya saya membuat scene baru bernama Level2 yang merupakan duplikat dari Level1.

## Penambahan Tilemap
Untuk menambahkan variasi pada Level2, saya mengubah tilemap yang digunakan pada Level2 agar menggunakan `spritesheet_gr_planet.png `. Untuk melakukan hal tersebut, saya melakukan step-step yang telah dilakukan pada `Latihan: Membuat Tile Map`, yakni menambahkan *spritesheet* yang ingin saya jadikan referensi sebagai sebuah Texture Atlas, dan menambahkan collision pada setiap tile yang telah didefinisikan.

## Enemy Spawner
Pada Level2, saya mengganti jenis falling object yang di spawn dari `Fish` menjadi sebuah `Slime`. Untuk itu, saya melakukan re-use pada script yang digunakan oleh Fish, namun mengubah *hitbox* dan *sprite* yang digunakan pada scene baru agar sesuai dengan sprite Slime.

Untuk menambahkan variasi, saya mengubah `Gravity Scale` pada `Slime` dari `1` menjadi `5`. Hal ini membuat level 2 menjadi lebih susah, dikarenakan `Slime` yang berjatuhan akan jatuh ke tanah 5x lebih cepat.