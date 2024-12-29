---
title: Tutorial Dasar Pemrograman Python (Bagian 4, Apa itu Variabel dan Tipe Data dalam Python)
tags: [Tutorial, Python]
style: fill
color: info
description: Mengenal tentang Variabel dan Tipe Data dalam bahasa pemrograman Python
---

Hai, teman-teman, Sekarang kita akan lanjut materi kita yaitu mengenal Apa itu Variabel dan Tipe Data dalam Python.

## Penulisan Statement Pada Python

Statement? makanan apakah ini? hehe, jadi statement merupakan sebuah kalimat perintah atau instruksi yang nantinya akan diproses oleh komputer yang kita gunakan.

**Contoh:**

>```python
print('Hello, World!')
print("Felix begitu tamvan")
```

Penulisan statement pada bahasa Python tidak memerlukan tanda titik koma `;` pada akhir statementnya. Namun kita bisa menambahkan tanda titik koma `;` jika kita ingin membuat beberapa statement dalam satu baris.

**Contoh:**

>```python
print('Hello, World!'); print("Felix beneran tamvan pake banget")
```

Eitsss, namun penulisan seperti di atas tidak direkomendasikan karena akan jadi sulit dibaca.

## Penulisan String Pada Python

String? hmm, apakah ada hubungannya dengan celana dalam? bukannn yahh, itu beda lagi hehe.
Singkatnya, String adalah salah satu tipe data yang ada dalam bahasa pemrograman, string biasanya berisi sebuah kalimat yang dibungkus menggunakan tanda petik, bisa menggunakan petik tunggal `'` ataupun ~~janda~~ ganda `"`.

**Contoh:**

>```python
print('ini merupakan string')
print("ini juga merupakan string")
```

## Penulisan Case Pada Python 

Perlu kita ketahui bahwa sintaks yang ada pada python itu bersifat *Case Sensitive*, artinya `felix` dan `Felix` merupakan sesuatu yang berbeda,

**Contoh:**

>```python
felix = "felix yang ini"
Felix = "Berbeda dengan yang ini"
```

Berdasarkan rekomendasi dari para Ahli, berikut merupakan contoh penulisan case yang disarankan.

**Contoh:**

>```python
# Snake Case digunakan pada:
module_name, package_name, method_name, function_name, , global_var_name, instance_var_name, function_parameter_name, local_var_name.
# CamelCase digunakan Pada:
ClassName, ExceptionName
# ALL CAPS digunakan Pada:
GLOBAL_CONSTANT_NAME
```

## Penulisan Blok Program Pada Python

Blok program merupakan kumpulan dari beberapa statement yang digabungkan dalam satu blok. penulisan blok program harus ditambahkan indentasi (tab atau spasi 2x/4x).

**Contoh yang benar:**

>```python
# blok percabangan if
if username == 'felixtamvan':
    print("Selamat Datang Manusia paling Tamvan")
# blok percabangan for
for i in range(10):
    print i
```

**Contoh yang salah:**

>```python
# blok percabangan if
if username == 'felixtamvan':
print("Selamat Datang Manusia paling Tamvan")
# blok percabangan for
for i in range(10):
print i
```

## Penulisan Komentar Pada Python

Komentar merupakan baris kode yang tidak akan dieksekusi. digunakan untuk memberikan informasi tambahan dan untuk menonaktifkan kode. Cara menulis komentar pada pemrograman Python yaitu dengan menggunakan tanda pagar `#`.

**Contoh:**

>```python
# ini adalah komentar
# Ini juga komentar
```

## Penutup

Dan demikianlah kisah percintaan kita pada kali ini, untuk selanjutnya kita akan mencoba mengenal apa itu yang dinamakan Variabel dan Tipe Data pada bahasa pemrograman Python, sampai jumpa lagi yahh 😀