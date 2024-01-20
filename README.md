# BELAJAR HTML DASAR

- progres saya belajar HTML
- sumber: [youtube programmer zaman now](https://www.youtube.com/watch?v=hMDJyb7VkYw&t=1856s)

## apa yang saya pelajari?

### hello-world

- memulai dengan menampilkan tulisan 'hello world' menggunakan tag `<html></html>`
- menampilkan program dengan menjalankanya di server lokal menggunakan extension [live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

### heading

- digunakan untuk menampilkan bagian penting pada konten web
- di HTML memuat heading hingga heading-6
- cara menggunakanya menggunakan tag `<h></h>`

### paragraph

- membuat paragraph pada HTML menggunakan tag `<p></p>`
- web browser akan menghapus enter dan spasi lebih dari satu kali jika digunakan dalam satu tag yang sama

### reserved-character

- ada banyak karakter yang sudah dipesan oleh HTML, contoh kecilnya yaitu: `<` `,` `/` dan `>`, jika memaksakan menulisnya maka akan dianggap error atau tidak akan ditampilkan
- contoh pelulisan: `<h2> Belajar <HTML> </h2>`, tulisan `HTML` tidak akan ditampilkan di web browser karena diaggap sebuah tag

### entities

- karakter yang sudah dipesan oleh HTML disebut entities
- kita tetap bisa menuliskan karakter entities secara langsung pada program, tetapi direkomendasikan menggunakan symbol entities agar lebih aman
- seluruh daftar entities HTML: [https://oinam.github.io/entities/](https://oinam.github.io/entities/)
- contoh penulisan menggunakan symbol entities: `<h2> Belajar &lt;HTML&gt; </h2>` tulisan `HTML` akan ditampilkan web browser karena sudah menggunakan symbol entities yaitu `&lt;`/`<` dan `&gt;`/`>`

### break-line

- digunakan untuk menambahkan enter pada satu tag paragraph
- cara menggunakanya dengan menambahkan tag `<br>`
- contoh:

```
<p>
    saya belajar website <br />
    dimulai dari HTML dasar
</p>
```

### horizontal-rule

- digunakan untuk menambahkan garis secara horizontal
- cara menggunakannya dengan manambahkan tag `<hr>`
- contoh:

```
<p>
    saya belajar website <hr>
    dimulai dari HTML dasar
</p>
```

### style

- menggunakan CSS sebagai styling pada HTML
- HTML memiliki atribut `style` yang digunakan untuk styling pada tulisan
- contoh sederhana menggunakan style pada HTML:

```
<p
    style="font-size: 24; color: coral">
    saya belajar website dimulai dari HTML dasar
</p>
```

### formating

- digunakan untuk menambahkan format pada teks seperti cetak tebal, garis miring, garis bawah dll
- contoh formating lengkap HTML ada di: [W3School](https://www.w3schools.com/html/html_formatting.asp)
- untuk menghasilkan teks `2^2` menggunakan tag `<sup></sup>`

### comment

- digunakan untuk komentar pada program
- comment tidak akan ditampilkan saat program dijalankan
- contoh comment pada HTML: `<!-- comment -->`

### colors

- HTML mendukung format RGB, HEX, HSL dll
- panduan lengkap tentang colors: [w3shool/colors](https://www.w3schools.com/colors/default.asp) atau [color piecker me](https://colorpicker.me)

### list

- secara garis besar ada 2 jenis list pada HTML yaitu: `ul` (unordered list) untuk list berupa simbol dan `ol` (ordered list) untuk list dengan nomor
- panduan lengkap tentang list pada HTML: [w3school](https://www.w3schools.com/html/html_lists.asp)
