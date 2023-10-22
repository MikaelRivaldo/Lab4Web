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

Kemudian tambahkan kode CSS untuk membuat layoutnya

```html
/* import google font */
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400
;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0
,300;0,700;1,300&display=swap');
/* Reset CSS */
* {
margin: 0;
padding: 0;
}
body {
line-height:1;
font-size:100%;
font-family:'Open Sans', sans-serif;
color:#5a5a5a;
}
#container {
width: 980px;
margin: 0 auto;
box-shadow: 0 0 1em #cccccc;
}
/* header */
header {
padding: 20px;
}
header h1 {
margin: 20px 10px;
color: #b5b5b5;
}
```

`Untuk hasilnya akan seperti ini:`

![tampilan css1](https://github.com/MikaelRivaldo/Lab4Web/assets/115770247/895cb0f3-3e54-4811-8f71-5f144c28d569)

# Selanjutnya Membuat Navigasi

` Untuk sourcodenya bisa menggunakan di bawah ini:`

```html
/* navigasi */
nav {
display: block;
background-color: #1f5faa;
}
nav a {
padding: 15px 30px;
display: inline-block;
color: #ffffff;
font-size: 14px;
text-decoration: none;
font-weight: bold;
}
nav a.active,
nav a:hover {
background-color: #2b83ea;
}
```
`Untuk hasilnya akan seperti ini:`

![tampilan navigasi](https://github.com/MikaelRivaldo/Lab4Web/assets/115770247/45106588-dc81-4819-9a78-ecf3e440c433)

# Selanjutnya Membuat Hero Panel

`Selanjutnya membuat hero panel. Tambahkan kode HTML dan CSS seperti berikut.`

```html
<section id="hero">
<h1>Hello World!</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
pretium ac.</p>
<a href="home.html" class="btn btn-large">Learn more &raquo;</a>
</section>
```
`Untuk CSS`

```html
/* Hero Panel */
#hero {
background-color: #e4e4e5;
padding: 50px 20px;
margin-bottom: 20px;
}
#hero h1 {
margin-bottom: 20px;
font-size: 35px;
}
#hero p {
margin-bottom: 20px;
font-size: 18px;
line-height: 25px;
}
```

`Untuk hasilnya akan seperti ini:`

![tampilan hero panel](https://github.com/MikaelRivaldo/Lab4Web/assets/115770247/7fdf31a9-d41e-4095-a915-632c8b42a806)

# Selanjutnya Mengatur Layout Main dan Sidebar

Untuk mengatur main content dan sidebar, tambahkan CSS float.bisa menggunakan dibawah ini:

```html
/* main content */
#wrapper {
margin: 0;
}
#main {
float: left;
width: 640px;
padding: 20px;
}
/* sidebar area */
#sidebar {
float: left;
width: 260px;
padding: 20px;
}
```
# Selanjutnya Membuat Sidebar Widget

selanjutnya menambahkan element lain dalam sidebar.bisa menggunakan kode dibawah ini:

```html
<aside id="sidebar">
<div class="widget-box">
<h3 class="title">Widget Header</h3>
<ul>
<li><a href="#">Widget Link</a></li>
<li><a href="#">Widget Link</a></li>
<li><a href="#">Widget Link</a></li>
<li><a href="#">Widget Link</a></li>
<li><a href="#">Widget Link</a></li>
</ul>
</div>
<div class="widget-box">
<h3 class="title">Widget Text</h3>
<p>Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt
arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer
pharetra est nunc, nec pretium nunc pretium ac.</p>
</div>
</aside>
```
`Note`

Tambahkan kode diatas dan salin ke home.html

`Kemudian tambahkan CSS.bisa menggunakan kode dibawah ini:`

```html
/* widget */
.widget-box {
border:1px solid #eee;
margin-bottom:20px;
}
.widget-box .title {
padding:10px 16px;
background-color:#428bca;
color:#fff;
}
.widget-box ul {
list-style-type:none;
}
.widget-box li {
border-bottom:1px solid #eee;

}
.widget-box li a {
padding:10px 16px;
color:#333;
display:block;
text-decoration:none;
}
.widget-box li:hover a {
background-color:#eee;
}
.widget-box p {
padding:15px;
line-height:25px;
}
```
`Untuk hasilnya akan seperti ini:`

![tampilan sidebar ](https://github.com/MikaelRivaldo/Lab4Web/assets/115770247/1aa8f386-b039-419b-aeaf-305ebb582a33)

# Selanjutnya Mengatur Footer

Tambahkan CSS untuk footer

```html
/* footer */
footer {
clear:both;
background-color:#1d1d1d;
padding:20px;
color:#eee;
}
```
` Untuk hasilnya akan seperti ini:`

![tampilan footer](https://github.com/MikaelRivaldo/Lab4Web/assets/115770247/42a8ac1a-6353-455d-a4a2-2cc078321932)

# Selanjutnya Menambahkan Elemen lainnya pada Main Content

```html
<section id="main">
<div class="row">
<div class="box">
<img src="https://dummyimage.com/120/db7d25/fff.png" alt=""
class="image-circle">
<h3>Heading</h3>
<p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
<a href="#" class="btn btn-default">View detail</a>
</div>
<div class="box">
<img src="https://dummyimage.com/120/3e73e6/fff.png" alt=""
class="image-circle">
<h3>Heading</h3>
<p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
<a href="#" class="btn btn-default">View detail</a>
</div>
<div class="box">
<img src="https://dummyimage.com/120/71e6d4/fff.png" alt=""
class="image-circle">
<h3>Heading</h3>
<p>Donec sed odio dui. Etiam porta sem malesuada magna mollis
euismod.</p>
<a href="#" class="btn btn-default">View detail</a>
</div>
</div>
</section>
```

`Kemudian tambahkan CSS`

```html
/* box */
.box {
display:block;
float:left;
width:33.333333%;
box-sizing:border-box;
-moz-box-sizing:border-box;
-webkit-box-sizing:border-box;
padding:0 10px;
text-align:center;
}
.box h3 {
margin: 15px 0;
}
.box p {
line-height: 20px;
font-size: 14px;
margin-bottom: 15px;
}
box img {
border: 0;
vertical-align: middle;
}
.image-circle {
border-radius: 50%;
}
.row {
margin: 0 -10px;
box-sizing: border-box;
-moz-box-sizing: border-box;
-webkit-box-sizing: border-box;
}
.row:after, .row:before,
.entry:after, .entry:before {
content:'';
display:table;
}
.row:after,
.entry:after {
clear:both;
}
```
`Untuk hasilnya akan seperti ini:`

![tampilan main content](https://github.com/MikaelRivaldo/Lab4Web/assets/115770247/c9477e97-4868-4fa6-95af-18cbbb0f4d2b)

# Selanjutnya Menambahkan Content Artikel

Tambahkan HTML berikut pada main content

`Untuk sourcodenya bisa menggunnakan dibawah ini:`

```html
<hr class="divider" />
<article class="entry">
<h2>First featurette heading.</h2>
<img src="https://dummyimage.com/150/7b8a70/fff.png" alt="">
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
pretium ac.</p>
</article>
<hr class="divider" />
<article class="entry">
<h2>First featurette heading.</h2>
<img src="https://dummyimage.com/150/7b8a70/fff.png" alt=""
class="right-img">
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem
elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc
pretium ac.</p>
</article>
```

`Kemudian tambahkan CSS`

```html
.divider {
border:0;
border-top:1px solid #eeeeee;
margin:40px 0;
}
/* entry */
.entry {
margin: 15px 0;
}
.entry h2 {
margin-bottom: 20px;
}
.entry p {
line-height: 25px;
}
.entry img {
float: left;
border-radius: 5px;
margin-right: 15px;
}
.entry .right-img {
float: right;
}
```

`Untuk hasilnya akan seperti ini`

![tampilan akhir](https://github.com/MikaelRivaldo/Lab4Web/assets/115770247/82fb9a02-8783-4fc2-bc8b-4ba9956bd2d0)



