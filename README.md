## Joe Mathew Rusli
## 2306152310 / Adpro A

### Experiment 2.1
![Experiment 2.1](./image.png)

Cara Menjalankan:

1.  **Menjalankan Server:**
    ```bash
    cargo run --bin server
    ```
    Server akan dimulai dan menunggu koneksi dari klien.

2.  **Menjalankan Klien:**
    Buka tiga terminal atau command prompt baru. Untuk setiap terminal, run perintah berikut:
    ```bash
    cargo run --bin client
    ```
    Setiap perintah akan menjalankan satu instance klien yang akan mencoba terhubung ke server.

**Apa yang Terjadi:**

Setelah server berjalan dan ketiga klien terhubung, jika kita mengetikkan sebuah pesan di salah satu jendela klien dan menekan Enter, pesan tersebut akan dikirim ke server. Server kemudian akan meneruskan pesan ini ke semua klien lain yang sedang terhubung. Hasilnya, pesan yang kita ketik di satu klien akan muncul di jendela terminal semua klien lainnya, termasuk klien pengirim. Ini mendemonstrasikan fungsionalitas broadcast dari server.