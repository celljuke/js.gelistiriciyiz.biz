---
title: "Obje içinde özellik kontrolü: hasOwnProperty"
date: Apr 20, 2016 01:09
tags: js
author:
  name: "V. Mahir Yılmaz"
  email: "mahir@vedatmahir.com"
  link: "www.vedatmahir.com"
  bio: "Yazılım Geliştirici"
---
Bir Javascript nesnesinin içinde belirttiğimiz isimde bir özelliğin olup olmadığını bulmak için kullanacağımız fonksiyon: `hasOwnProperty`.

```js
object.hasOwnProperty(propName)
```
READ_MORE

```js
skills = {
    "javascript": {},
    "go": {}
}

skills.hasOwnProperty('javascript'); // true
skills.hasOwnProperty('lisp'); // false
```