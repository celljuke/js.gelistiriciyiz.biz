---
title: "typeof operatörü"
date: Apr 20, 2016 09:36
tags: core
author:
  name: "V. Mahir Yılmaz"
  email: "mahir@vedatmahir.com"
  link: "www.vedatmahir.com"
  bio: "Yazılım Geliştirici"
---
Belirttiğimiz ifadenin veri tipini bulabilmek için `typeof` operatörünü 
kullanıyoruz.

```js
var sayi = 1,
    yazi = "Geliştiriciyiz.biz",
    nesne = {};
typeof sayi;   // "number"
typeof yazi;   // "string"
typeof nesne;  // "object"
typeof Foo;    // "undefined"
```