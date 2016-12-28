---
title: "Obje içinde özellik kontrolü: hasOwnProperty"
date: Apr 20, 2016 01:09
tags: es-3,es-5-1,es-2015
author:
  name: "V. Mahir Yılmaz"
  email: "mahir@vedatmahir.com"
  link: "http://www.vedatmahir.com"
  bio: "Yazılım Geliştirici"
---
Bir Javascript nesnesinin içinde belirttiğimiz isimde bir özelliğin olup 
olmadığını bulmak için kullanacağımız fonksiyon: `hasOwnProperty`.READ_MORE

```js
object.hasOwnProperty(propName)

skills = {
    "javascript": {},
    "go": {}
}

skills.hasOwnProperty('javascript'); // true
skills.hasOwnProperty('lisp'); // false
```