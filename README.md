# PRAKTIKUM 9

**Nama : Reka Hani Latifah Nurhasanah** <br>

**Nim : 312010343** <br>

**Kelas : TI.20.A2** <br>

**Matkul : Pemrograman Web** <br>

### Menjalankan MySQL Server

Jalankan XAMPP dan aktifkan `apache` dsn `MySQL` lalu akses http://localhost/phpmyadmin/ untuk membuat database. Kemudian membuat folder baru dengan nama `lab9_php_modular` pada directory `C:\XAMPP\htdocs` Langkah berikutnya masukkan kode pada VSCODE lalu simpan dengan nama `header.php`

`syntax`

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
        <a href="home.php">Home</a>
        <a href="about.php">Tentang</a>
        <a href="kontak.php">Kontak</a>
        </nav>
```
Kemudian masukkan kode pada VSCODE lalu simpan dengan nama `footer.php`

`syntax`

```
<footer>
            <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

Masukkan kode pada VSCODE lalu simpan dengan nama `home.php 

`syntax`

```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

Selanjutnya masukkan kode pada VSCODE lalu simpan dengan nama `about.php`

`syntax`

```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

### Berikut hasil dari kode-kode yang telah di input pada VSCODE 

Tampilan HOME

![1.png](img/1.png)

Tampilan ABOUT

![2.png](img/2.png)