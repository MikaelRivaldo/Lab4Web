# Lab4Web

# Langkah pertama buat dokumen HTML dengan nama file lab4_box.html

`Untuk sourcodenya bisa menggunakan dibawah ini:`

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Box Element</title>
</head>
<body>
<header>
<h1>Box Element</h1>
</header>
</body>
</html>
```
# Selanjutnya Membuat Box Element

`Kemudian tambahkan kode untuk membuat box element dengan tag div seperti berikut`

`Untuk sourcodenya bisa menggunakan dibawah ini:`

```html
<section>
<div class="div1">Div 1</div>
<div class="div2">Div 2</div>
<div class="div3">Div 3</div>
</section>
```
# Selanjutnya Membuat CSS Float Property

`Selanjutnya tambahkan deklarasi CSS pada head untuk membuat float element, seperti berikut`

`Untuk sourcodenya bisa menggunakan dibawah ini:`

```html
<style>
div {
float:left;
padding: 10px;
}
.div1 {
background: red;
}
.div2 {
background: yellow;
}
.div3 {
background: green;
}
</style>
```
`Untuk hasilnya akan seperti ini:`

![tampilan css float](https://github.com/MikaelRivaldo/Lab4Web/assets/115770247/6ec69bcf-a2b0-4194-9028-22cfc3576771)

`Selanjutnya Mengatur Clearfix Element`

`Clearfix digunakan untuk mengatur element setelah float element. Property clear digunakan untuk
mengaturnya`

Tambahkan element div lainnya seteleah div3 seperti berikut

```html
<section>
<div class="div1">Div 1</div>
<div class="div2">Div 2</div>
<div class="div3">Div 3</div>
<div class="div4">Div 4</div>
</section>
```
Kemudian atur property clear pada CSS, seperti berikut

```html
.div4 {
background-color: blue;
clear: left;
float: none;
}
```

`Untuk hasilnya akan seperti ini:`

![tampilan clearfix](https://github.com/MikaelRivaldo/Lab4Web/assets/115770247/69e5c8b7-a9b0-4370-8817-7c30b622d55d)

---

# Selanjutnya Buat folder baru dengan nama lab4_layout, kemudian buatlah file baru didalamnya dengan nama
home.html, dan file css dengan nama style.css.

`Untuk sourcodenya bisa menggunakan dibawah ini:`

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Layout Sederhana</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div id="container">
</div>
</body>
</html>
```
`Kemudian tambahkan kode ini:`

```html
<header>
<h1>Layout Sederhana</h1>
</header>
<nav>
<a href="home.html" class="active">Home</a>
<a href="artikel.html">Artikel</a>
<a href="about.html">About</a>
<a href="kontak.html">Kontak</a>
</nav>
<section id="hero"></section>
<section id="wrapper">
<section id="main"></section>
<aside id="sidebar"></aside>
</section>
<footer>
<p>&copy; 2021 - Universitas Pelita Bangsa</p>
</footer>
```
`Untuk hasilnya akan seperti ini:`

![tampilan layout sederhana](https://github.com/MikaelRivaldo/Lab4Web/assets/115770247/1e29194a-2788-429b-aa4b-229b0659c3b3)






