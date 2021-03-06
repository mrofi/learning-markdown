# learning-markdown
Tutorial Markdown Bahasa Indonesia

### Sedikit tanya jawab (tanya sendiri, jawab sendiri)
##### Apa itu Markdown?
Banyak definisi tapi mudahnya adalah untuk menghasilkan dokumen yang mudah dibaca dan mudah ditulis.

##### Baiklah, langsung saja kita mulai
Siip

### Basic Markdown

###### 1. Membuat Paragraf
Untuk membuat paragraf, cukup dengan mengetik beberapa kata kemudian diikuti dengan 1 atau beberapa enter (ganti baris)

###### Contoh :
```
Ini adalah paragraf, jadi Anda ketik apa saja otomatis akan dianggap sebagai paragraf

Ini adalah paragraf kedua. Lorem Ipsum adalah contoh teks atau dummy dalam industri percetakan dan penataan huruf atau typesetting. Lorem Ipsum telah menjadi standar contoh teks sejak tahun 1500an, saat seorang tukang cetak yang tidak dikenal mengambil sebuah kumpulan teks dan mengacaknya untuk menjadi sebuah buku contoh huruf. Ia tidak hanya bertahan selama 5 abad, tapi juga telah beralih ke penataan huruf elektronik, tanpa ada perubahan apapun. Ia mulai dipopulerkan pada tahun 1960 dengan diluncurkannya lembaran-lembaran Letraset yang menggunakan kalimat-kalimat dari Lorem Ipsum, dan seiring munculnya perangkat lunak Desktop Publishing seperti Aldus PageMaker juga memiliki versi Lorem Ipsum.
```
##### Hasilnya :
Ini adalah paragraf, jadi Anda ketik apa saja otomatis akan dianggap sebagai paragraf

Ini adalah paragraf kedua. Lorem Ipsum adalah contoh teks atau dummy dalam industri percetakan dan penataan huruf atau typesetting. Lorem Ipsum telah menjadi standar contoh teks sejak tahun 1500an, saat seorang tukang cetak yang tidak dikenal mengambil sebuah kumpulan teks dan mengacaknya untuk menjadi sebuah buku contoh huruf. Ia tidak hanya bertahan selama 5 abad, tapi juga telah beralih ke penataan huruf elektronik, tanpa ada perubahan apapun. Ia mulai dipopulerkan pada tahun 1960 dengan diluncurkannya lembaran-lembaran Letraset yang menggunakan kalimat-kalimat dari Lorem Ipsum, dan seiring munculnya perangkat lunak Desktop Publishing seperti Aldus PageMaker juga memiliki versi Lorem Ipsum.


##### 2. Heading. 
**Apa itu heading?** Heading adalah format penulisan berdasarkan ukuran biasanya untuk judul dan disingkat dengan inisial 'h', h1 itu paling gede (Judul paling atas), diikuti dengan h2, h3, h4, h5 dan terakhir paling kecil adalah h6. 
heading di markdown diwakili dengan tanda `#`. Jadi `#` artinya h1 kemudian diikuti text heading nya.. 

##### Contoh :
```
# Ini adalah h1
### Ini adalah h3
#### Ini adalah h4
###### Ini adalah h6
```

##### Hasilnya adalah sebagai berikut :
# Ini adalah h1
### Ini adalah h3
#### Ini adalah h4
###### Ini adalah h6


##### 3. **Bold** dan *Italic*
Tanda `**` akan mewakili **Bold** sedangakan `*` akan mewakili *Italic*.

##### Contoh :
```
**Ini akan terlihat Bold**
*Ini akan terlihat Italic*
Kalo ini akan tercetak ***Bold dan Italic***
```

##### Hasilnya :

**Ini akan terlihat Bold**

*Ini akan terlihat Italic*

Kalo ini akan tercetak ***Bold dan Italic***


##### 4. List
Untuk membuat list sangatlah mudah. Untuk list yg pake numbering **(Ordered List)** cukup dengan menggunakan `angka` diikuti dengan titik.

##### Contoh :
```
1. Item 1
2. Item 2
3. Item 3
```

##### Hasilnya :

1. Item 1
2. Item 2
3. Item 3

Untuk membuat List yang pake bullet cukup dengan `*` atau `-` diikuti dengan titik. 

##### Contoh :
```
* Item
* Item
* Item

- Item
- Item
- Item
```

##### Hasilnya :

* Item
* Item
* Item

- Item
- Item
- Item

Jika kita campur-adukkan maka jadinya seperti ini. 
##### Contoh :
```
1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3
```

##### Hasilnya :
1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3

##### 5. Image
Menampilkan image (photo). Formatnya adalah :  `Format: ![Alt Text](url)`.

##### Contoh :
```
![GitHub Logo](https://assets-cdn.github.com/images/modules/logos_page/GitHub-Mark.png)
```
##### Hasilnya :

![GitHub Logo](https://assets-cdn.github.com/images/modules/logos_page/GitHub-Mark.png)

##### 6. Link
Menampilkan link sangat mudah, langsung ketik aja urlnya atau dengan format : `[Text Link](url)`

##### Contoh :
```
http://github.com - automatic!
[GitHub](http://github.com)
```

##### Hasilnya :
http://github.com - automatic!
[GitHub](http://github.com)

##### 7. Blockquote
Untuk menampilkan blockquote cukup dengan menulis `>' di depan text quote nya.

##### Contoh :
```
As Kanye West said:

> We're living the future so
> the present is our past.
```
##### Hasilnya :
As Kanye West said:

> We're living the future so
> the present is our past.

##### 8. Inline Code
Inline code adalah menuliskan syntax ke dalam markdown. Caranya pake backtit (`). 

##### Contoh :
```
`var foo = 'bar';`
```

##### Hasilnya :
`var foo = 'bar';`

##### 9. Block Code
Untuk menulis syntax code dalam bentuk block (lebih dari 1 baris). Caranya dengan menggunakan 3 buah backtit (```)

##### Contoh :
    ```
    `var foo = 'bar';`
    ```

##### Hasilnya :
```
`var foo = 'bar';`
```

### GFM (Github Flavored Markdown)
**Apa itu?** Markdown rasa Github?? :smile:

##### 10. Syntax highlighting
Misal kita mau bikin code javascript tinggal ketik 'javascript' setelah 3 backtick pembuka

##### Contoh:
    ```javascript
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
    ```

##### Hasilnya :

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
Atau dengan memberi indentasi sebanyak 4 spasi akan memberikan hasil yang sama
```
        function fancyAlert(arg) {
          if(arg) {
            $.facebox({div:'#foo'})
          }
        }
```
##### 11. Task List
Ini menarik, kita bisa membuat checkbox seperti pada to do list app. Caranya cukup dengan `[x]` yang artinya **centang** dan `[ ]` yang artinya ga ke centang

##### Contoh :
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

##### Hasilnya :
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

##### 12. Tables
Kita bisa bikin table dengan membuat memberi `-` di bawah baris header (baris pertama) dan memisahkan antar column dengan tanda pipa `|`.

##### Contoh :
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```

##### Hasilnya :
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

##### 13. Mention @username untuk user di Github
Caranya seperti mention di twitter. Pake `@` diikuti dengan username user yang akan dimention

##### Contoh :
```
@mrofi akan saya mention
```

##### Hasilnya :
@mrofi akan saya mention

##### 14. Striketrough 
Untuk membuat ~~ Kayak gini ~~ caranya menggunakan 2 buah tilde `~~`

##### Contoh :
```
~~Ini adalah stikrtrough~~
```
##### Hasilnya :
~~Ini adalah stikrtrough~~

##### 15. Emoji
Keren kita bisa pasang emo di markdown nya github. Caranya cukup lihat di sini [Contekan Emoji](http://www.emoji-cheat-sheet.com/)

##### Contoh :
```
:smile: :kissing_heart: :heart_eyes: :camel: :poop:
```
##### Hasilnya :
:smile: :kissing_heart: :heart_eyes: :camel: :poop:


## What Next ?
Silakan kembangkan sendiri. Anda sudah siap untuk menulis di github. :smile: Maksudnya berkontribusi di dunia opensource
Oh iya, dokumen ini juga ditulis dengan format markdown, jadi silakan di Raw untuk melihat syntax aslinya. 

## Sumber Bacaan :
Diantaranya :

1. https://guides.github.com/features/mastering-markdown/
2. http://daringfireball.net/projects/markdown/

