# Praktikum 1 - HTML Dasar
**Nama:** [Rifqi Maulana]  
**NIM:** [312410529]  
**Mata Kuliah:** Pemrograman Web  

---

## 🎯 Tujuan
1. Memahami struktur dasar HTML.  
2. Mengenal tag-tag dasar HTML.  
3. Membuat dokumen HTML sederhana dengan menggunakan tag dasar.  

---

## 📝 Langkah Praktikum

### Struktur Dasar
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Tag HTML Dasar</title>
</head>
<body>
</body>
</html>
```
Hasil:

![Hasil Step 1](https://github.com/Shikilukeki/Lab1Web/blob/main/Lab1Web/ss/01_skeleton.png)

### Paragraf
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Tag HTML Dasar</title>
</head>
<body>
  <p>Ini adalah paragraf pertama.</p>
  <p>Ini adalah paragraf kedua.</p>
</body>
</html>
```
Hasil: 

![Hasil Step 2](https://github.com/Shikilukeki/Lab1Web/blob/main/Lab1Web/ss/02_paragraphs.png)

### Heading
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Tag HTML Dasar</title>
</head>
<body>
  <h1>Belajar Dasar HTML</h1>
  <h2>Paragraf pada HTML</h2>
</body>
</html>

```
Hasil: 

![Hasil Step 3](https://github.com/Shikilukeki/Lab1Web/blob/main/Lab1Web/ss/03_headings.png)

### Format Teks
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Tag HTML Dasar</title>
</head>
<body>
  <h1>Belajar Dasar HTML</h1>
  <p>Kami sedang belajar <mark>HTML dasar</mark>, pada mata kuliah 
     <b>Pemrograman</b> Web di Prodi <i>Teknik Informatika</i> 
     <u>Universitas Pelita Bangsa</u>.
  </p>
  <h2>Paragraf pada HTML</h2>
  <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat 
     yang saling mendukung sehingga menjadi satu kesatuan. 
  </p>
</body>
</html>

```
Hasil: 

![Hasil Step 4](https://github.com/Shikilukeki/Lab1Web/blob/main/Lab1Web/ss/04_format_text.png
)

### Menambahkan Gambar
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Tag HTML Dasar</title>
</head>
<body>
  <h1>Belajar Dasar HTML</h1>
  <p>Kami sedang belajar <mark>HTML dasar</mark>, pada mata kuliah 
     <b>Pemrograman</b> Web di Prodi <i>Teknik Informatika</i> 
     <u>Universitas Pelita Bangsa</u>.
  </p>
  <h2>Paragraf pada HTML</h2>
  <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat 
     yang saling mendukung sehingga menjadi satu kesatuan. 
  </p>

  <h3>Menambahkan Gambar</h3>
  <img src="images/logo.png" width="200" 
       title="Logo Universitas Pelita Bangsa" alt="Logo UPB">
</body>
</html>

```
Hasil: 

![Hasil Step 5](https://github.com/Shikilukeki/Lab1Web/blob/main/Lab1Web/ss/05_image.png)

### Hyperlink
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Tag HTML Dasar</title>
</head>
<body>
  <h1>Belajar Dasar HTML</h1>
  <p>Kami sedang belajar <mark>HTML dasar</mark>, pada mata kuliah 
     <b>Pemrograman</b> Web di Prodi <i>Teknik Informatika</i> 
     <u>Universitas Pelita Bangsa</u>.
  </p>
  <h2>Paragraf pada HTML</h2>
  <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat 
     yang saling mendukung sehingga menjadi satu kesatuan. 
  </p>

  <h3>Menambahkan Gambar</h3>
  <img src="images/logo.png" width="200" 
       title="Logo Universitas Pelita Bangsa" alt="Logo UPB">

  <h3>Hyperlink</h3>
  <nav>
    <a href="lab1_tag_dasar.html" target="_self">Dasar HTML</a> |
    <a href="lab1_halaman2.html" target="_blank">Halaman 2</a> |
    <a href="http://www.google.com" target="_top">Google</a>
  </nav>
</body>
</html>

```
Hasil: 

![Hasil Step 6](https://github.com/Shikilukeki/Lab1Web/blob/main/Lab1Web/ss/06_nav.png
)

### Halaman 2
```html
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Halaman 2</title>
</head>
<body>
  <h1>Ini Halaman 2</h1>
  <p>Ini adalah halaman kedua. Kontennya bebas, misalnya ringkasan materi atau teks contoh.</p>
  <a href="lab1_tag_dasar.html">Kembali ke Halaman Utama</a>
</body>
</html>

```
Hasil: 

![Hasil Halaman2](https://github.com/Shikilukeki/Lab1Web/blob/main/Lab1Web/ss/07_halaman2.png)

### Hasil cek Validator

![Hasil Validator](https://github.com/Shikilukeki/Lab1Web/blob/main/Lab1Web/ss/08_validator.png.png)
