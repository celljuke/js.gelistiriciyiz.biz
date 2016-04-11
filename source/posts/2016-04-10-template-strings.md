---
title: "Template Strings"
date: Apr 10, 2016 21:05
tags: ecmascript6,es6,backtick
author:
  name: "V. Mahir Yılmaz"
  email: "mahir@vedatmahir.com"
  link: "www.vedatmahir.com"
  bio: "Yazılım Geliştirici"
---
ES6 ile beraber Javascript dünyasına **template string**’ler de girmiş oldu. Peki 
Template String’lerin Klasik ve Double String’lerden ne farkı var?READ_MORE

## Çoklu satırlarla çalışırken newline (`\n`) ifadesine ve/veya string'leri birleştirmek 
için  `+` operatörüne ihtiyaç duymazsınız.

**Eski Yöntem**:

```js
var sheldonQuotes = "Bazinga Punk!\n" +
                    "Now we are even.";

console.log(sheldonQuotes);
// Bazinga Punk!
// Now we're even
```

**Yeni Yöntem**:

```js
var sheldonQuotes = `Bazinga Punk!
Now we are even.`;

console.log(sheldonQuotes);
// Bazinga Punk!
// Now we're even
```



## `${}` ifadesini kullanarak basit Javascript ifadeleri yazabilirsiniz.

**Eski Yöntem**:

```js
var isim    = "Vedat Mahir",
    soyisim = "Yılmaz";

console.log("Merhaba Dünya! Ben " + isim + " " + soyisim + "!");
// Merhaba Dünya! Ben Vedat Mahir Yılmaz!

var a = 1,
    b = 2;

console.log("Toplam = " + (a + b))
// Toplam = 3
```

**Yeni Yöntem**:

```js
let isim    = "Vedat Mahir",
    soyisim = "Yılmaz";

console.log(`Merhaba Dünya! Ben ${isim} ${soyisim}!`)
// Merhaba Dünya! Ben Vedat Mahir Yılmaz!

let a = 1,
    b = 2;

console.log(`Toplam = ${a + b}`)
// Toplam = 3
```