# One Day Coding Series

## Personal Website

### HTML

1. [Apa itu HTML?](#html_1)
2. [Anatomi sebuah elemen HTML](#html_2)
3. [Membuka file HTML di browser](#html_3)
4. [Struktur sebuah halaman HTML](#html_4)
5. [Memasukkan gambar ke HTML](#html_5)
6. [Membuka link ke halaman lain](#html_6)
7. [Membuat form](#html_7)
8. Membuat website pribadi (Demo)

### CSS

1. [Apa itu CSS?](#css_1)
2. [Anatomi CSS](#css_2)
3. [Menyambungkan CSS ke HTML](#css_3)
4. Mempercantik website pribadi (Demo)

### Bootstrap

1. [Apa itu Bootstrap?](#bootstrap_1)
2. [Menyambungkan Bootstrap ke HTML](#bootstrap_2)
3. [Menggunakan Bootstrap di HTML](#bootstrap_3)

# HTML

<a name="html_1" />

## Apa itu HTML?

HTML adalah singkatan dari Hyper Text Markup Language. HTML digunakan untuk memberikan sebuah struktur ke sebuah website dengan menggunakan teks, tautan, gambar, dll.

<a name="html_2" />

## Anatomi sebuah elemen HTML

```html
<a href="https://www.google.com/">Google</a>
```

#### Penjelasan

- Semua elemen HTML memiliki tag pembuka, Dalam kasus di atas, tag pembukannya adalah `<a>`

- Kebanyakan elemen HTML membutuhkan tag penutup, ditandai dengan sebuah `/`. Dalam kasus di atas, tag penutupnya adalah `</a>`
- Kebanyakan elemen HTML juga memiliki atribut. atribut digunakan untuk menambahkan informasi tambahan kepada sebuah elemen HTML. Dalam kasus di atas, atributnya adalah `href`

- Pengunjung website hanya melihat isi diantara tag pembukan dan penutup.

<a name="html_3" />

## Membuka file HTML di browser

Kita bisa menggunakan ekstensi VS Code bernama [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) untuk mempermudah dalam proses pembuatan sebuah halaman website, karena ekstensi tersebut akan otomatis mengulang sebuah halaman ketika kita menyimpan file HTML.

<a name="html_4" />

## Struktur sebuah halaman HTML

```html
<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

#### Penjelasan

1.  `<html></html>` digunakan untuk menyatakan bahwa halaman website kita menggunakan bahasa HTML.
2.  `<head></head>` adalah kepala dari halaman website. digunakan untuk meletakkan meta, css, font, nama website, dll.
3.  `<meta />` digunakan untuk menambahkan keterangan tambahan tentang halaman itu sendiri.
4.  `<title></title>` digunakan untuk menyatakan nama/judul halaman website anda.
5.  `<body></body>` digunakan untuk menampilkan halaman website anda.

<a name="html_5" />

## Memasukkan gambar ke HTML

```html
<img src="image.png" alt="Profile" />
```

#### Penjelasan

- `src` wajib ditulis, karena digunakan untuk meletakkan alamat (lokasi) gambar.
- `alt` digunakan untuk menampilkan teks pengganti yang akan muncul ketika gambar tidak dapat ditampilkan.

<a name="html_6" />

## Membuka link ke halaman lain

```html
<a href="https://www.google.com/">Google</a>
```

#### Penjelasan

- `href` wajib ditulis, karena digunakan untuk meletakkan alamat yang dituju.


<a name="html_7" />

## Membuat form
```html
<form>
  <input type="text" placeholder="Full Name" />
  <input type="email" placeholder="Email" />
  <button type="submit">Submit</button>
</form>
```

#### Penjelasan
- `type` digunakan untuk menentukan tipe data yang dimasukkan.
- `placeholder` digunakan untuk memberikan petunjuk kepada pengguna.

# CSS

<a name="css_1" />

## Apa itu CSS?

CSS adalah singkatan dari Cascading Style Sheets. CSS digunakan untuk mengubah/mempercantik tampilan sebuah website.

<a name="css_2" />

## Anatomi CSS

```css
selector {
  property: value;
}
```

#### Penjelasan

- `selector` adalah elemen yang akan diubah. contohnya: `h1`, `.title` atau `#main`
- `property` adalah karakteristik yang akan diubah. contohnya: `color`, `font-weight`, dll.
- `value` adalah nilai dari properti. contohnya: `pink`, `10px`, dll.

<a name="css_3" />

## Menyambungkan CSS ke HTML

```html
<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body></body>
</html>
```

#### Penjelasan

1. Tambahkan `<link />` ke `<head></head>`.
2. berikan atribut `rel="stylesheet"`.
3. Isi atribut `href` sesuai dengan nama css yang anda buat.

# Bootstrap

## Apa itu Bootstrap?

Bootstrap adalah sebuah CSS framework yang berisi CSS yang siap digunakan untuk mempercepat pembuatan sebuah halaman website. Kita

## Menyambungkan Bootstrap ke HTML

```html
<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Document</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.0/css/bootstrap.min.css" integrity="sha384-PDle/QlgIONtM1aqA2Qemk5gPOE7wFq8+Em+G/hmo5Iq0CCmYZLv3fVRDJ4MMwEA" crossorigin="anonymous"/>
  </head>
  <body>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.0/js/bootstrap.min.js" integrity="sha384-7aThvCh9TypR7fIc2HV4O/nFMVCBwyIUKL8XCtKE+8xgCgl/PQGuFsvShjr74PBp" crossorigin="anonymous"></script>
  </body>
</html>
```

## Menggunakan Bootstrap di HTML

Karena Bootstrap sudah menyediakan CSS yang siap digunakan, kita hanya perlu memanggil nama class yang sudah disediakan oleh Bootstrap, tidak perlu lagi menulis CSS dari awal.

```html
<div class="alert alert-primary" role="alert">
  A simple primary alert—check it out!
</div>
```
