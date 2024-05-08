# Module 10 - Reflection
> Tegar Wahyu Khisbulloh (2206082032) - Pemrograman Lanjut A

## 2.1: Original code, and how it runs

**How to run:** <br>
Kita dapat menggunakan perintah `cargo run --bin server` untuk menjalankan server dan
`cargo run --bin client` untuk menjalankan client. 

![client_server.png](images/client_server.png)
**Example of use:** <br>
Seperti yang terlihat pada gambar di atas, kita dapat menjalankan server dan client secara 
bersamaan, yang mana semua client terhubung ke satu server yang sama. Ketika salah satu
client mengirimkan pesan, pesan tersebut akan diterima oleh server dan dikirimkan kembali
ke semua client yang terhubung.
