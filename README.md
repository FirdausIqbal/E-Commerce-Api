# Learning Create E-Commerce API

** Deskripsi ** <br>
Belajar membuat sistem API untuk E-Commerce yang dapat Post, Put, Update, dan Delete pada database. Dibuat menggunakan NodeJs, Express, dan PostgreQL.
<br><br>
** Route **<br>
- auth<br>
pada route ini akan melakukan registrasi akun atau login
- cart<br>
route cart akan membuat response pada sistem keranjang belanja, seperti menyimpan barang sebelum di checkout
- order<br>
route order akan membuat response pada pembuatan pemesanan
- product<br>
route product akan menghandle response untuk mendapatkan data produk
- user<br>
route user melakukan update data user, mendapatkan semua data user, dan menghapus data user (ini hanya bisa dilakukan untuk admin "isAdmin = true")



** Instlasi **<br>
1. Clone repository "git clone https://github.com/FirdausIqbal/E-Commerce-Api.git"
2. Masuk ke directori proyek "cd E-Commerce-API"
3. Install dependencies "npm install"
4. Jalankan proyek "npm start" | disarankan untuk install 'nodemon' "npm i -g nodemon"
5. Coba semua route menggunakan Postman pada 'localhost:3001'

