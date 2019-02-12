# One Day Coding Series

## Personal Website

### HTML

1. [Apa itu HTML](#html_1)
2. [Anatomi sebuah elemen HTML](#html_2)
3. [Membuka file HTML di browser](#html_3)
4. [Struktur sebuah halaman HTML](#html_4)
5. [Memasukkan gambar ke HTML](#html_5)
6. [Membuka link ke halaman lain](#html_6)
7. Membuat website pribadi (Demo)

### CSS

1. [Apa itu CSS](#css_1)
2. [Membuat file style.css](#css_1)
3. [Menyambungkan css dengan HTML](#css_1)
4. [Mempelajari CSS Flexbox](#css_1)
5. Mempercantik website pribadi (Demo)

### Bootstrap

1. [Apa itu Bootstrap](#bootstrap_1)
2. [Menyambungkan Bootstrap ke HTML](#bootstrap_2)
3. [Menggunakan Bootstrap di HTML](#bootstrap_3)

<a name="html_1" />

## Apa itu HTML

HTML adalah singkatan dari Hyper Text Markup Language. HTML digunakan untuk memberikan sebuah struktur ke sebuah website dengan menggunakan teks, tautan, gambar, dll.

<a name="html_2" />

## Anatomi sebuah elemen HTML

```html
<h1>Hello World!</h1>
```

#### Penjelasan

- Semua elemen HTML memiliki tag pembuka, Dalam kasus di atas, tag pembukannya adalah `<h1>`

- Kebanyakan elemen HTML membutuhkan tag penutup, ditandai dengan sebuah `/`. Dalam kasus di atas tag penutupnya adalah `</h1>`

- Pengunjung _website_ hanya melihat isi diantara tag pembukan dan penutup.

<a name="html_3" />

## Membuka file HTML di browser

Kita bisa menggunakan ekstensi VS Code bernama [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) untuk mempermudah dalam proses pembuatan sebuah halaman website, karena ekstensi tersebut akan otomatis mengulang sebuah halaman ketika kita menyimpan file HTML.

<a name="html\_4" />

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
