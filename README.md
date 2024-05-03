# 2.1. Original code of broadcast chat

<h3>Server Terminal</h3>

![Server](img/tutorial2-Server.png)

<h3>Three Client Terminal</h3>

![Client](img/tutorial2-Client.png)

cara menjalankannya adalah membuat 4 terminal berbeda, lalu jalankan "cargo run --bin server" pada salah satu terminal dan jalankan "cargo run --bin client" pada tiga terminal lainnya. Jika dijalankan keempatnya, kita bisa mengirim pesan dari salah satu client, lalu pesan tersebut dapat terlihat dari server dan dua client lainnya. Namun pesan yang diterima pada client masih bertulisan from server, jadi tidak diketahui siapa yang menuliskan pesan tersebut.