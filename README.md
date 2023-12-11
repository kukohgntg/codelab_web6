Nama : Kukoh Fatchu Rahman

NIM : 202110370311001

Kelas : Pemrograman Web B

# Codelab Modul 6

## REST API

1.  Get All Product Category

    ![](media/c09c07c38b12144a0c71e679bc9130ad.png)

2.  Get All Product By ID

    ![](media/95460e7624d01f7a2d1b7adff5c5658b.png)

3.  Create Product Category

    ![](media/0ccf58481cddaa5485e46fc38e1ead31.png)

    ![](media/6ff43396e17348376717cd54ee19d529.png)

4.  Update Product Category

    ![](media/dfa775196e284fb75aae05160eef79d4.png)

    ![](media/b55f9806160bb3801499664c849cacee.png)

5.  Delete Product Category

    ![](media/eab723f89cd7952177c0b95459dc94ed.png)

    ![](media/99e0496d00fad0bf8f089d0709b1e3c7.png)

## PENJELASAN SINGKAT

1.  Environtment ini berfungsi untuk meletakkan variable yang terkait dengan koneksi ke database, nama app, base url, dan variable – variable lainnya

    ![](media/6f6d19ca8624f5a08a79546106dd437e.png)

2.  Laravel migration adalah fitur untuk membuat suatu skema tabel dengan berbentuk sebuah code.

    ![](media/d1be071148a867d164482562010535d4.png)

3.  Untuk membuat Model di Laravel cukup dengan mengetikan comand pada terminal “php artisan make:model ProductCategory”

    ![](media/cdf61835647e2048d7fa6ec752664d18.png)

4.  Laravel Request adalah fitur Laravel yang berfungsi untuk membuat validasi terhadap Request Body yang nantinya kita gunakan untuk melakukan CRUD pada API

    ![](media/5c80eb2a42fb2ec3a10e2e22564a2fcf.png)

5.  Laravel Resource merupakan fitur untuk melakukan formating terhadap response dari API yang akan kita buat dalam hal ini kita akan menggunakan format JSON sebagai response dari API kita nantinya

    ![](media/a01403ea37e6edb3a473e91b11cec520.png)

6.  Untuk membuat Controller di Laravel cukup dengan mengetikan comand pada terminal “php artisan make:controller ProductCategory --api” --api karena Controller khusus untuk pembuatan API

    ![](media/61d710925b4500c784fa0dd7979fdfdc.png)

7.  Route berguna untuk menentukan API dengan method tertentu seperti GET, POST, PUT, PATCH, DELETE. Untuk routing khusus API terdapat pada file routes/api.php,

    ![](media/8d1fc581b09be71cecb1b7c6219e2ca3.png)
