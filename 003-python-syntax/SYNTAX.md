# PYTHON SYNTAX

## Mengeksekusi Sintaks Python

Seperti pada materi sebelumnya. Kita dapat mengeksekusi kode Python langsung melalui terminal atau pada IDE.

## Indentasi Python

Indentasi mengacu pada ruang atau jarak pada baris baru sebuah kode program.

Indentasi pada Python menjadi sangat krusial penggunaannya, berbeda dengan bahasa pemrograman lain yang relatif untuk keperluan _readibility_.

Indentasi pada Python menandakan blok kode berada.

**Contoh Benar**:

```
if 5 > 2:
  print("Five is bigger than Two")
```

**Contoh Salah**:

```
if 5 > 2:
print("Five is bigger than Two")
```

Spasi pada indentasi secara umum yang digunakan adalah 4. Namun, hal tersebut tidaklah mutlak.

Minimal menggunakan 1 spasi pada indentasi

```
if 5 > 2:
  print("Five is greater than Two")
if 5 > 3:
        print("Five is greater than Three")
```

Jika dalam suatu kondisi blok kode menampung lebih dari satu statement. Maka spasi pada indentasi haruslah sama.

**Contoh Benar**:

```
if 5 > 2:
  print("Five is bigger than Two")
  print("Five is exactly bigger!")
```

**Contoh Salah**:

```
if 5 > 2:
  print("Five is bigger than Two")
    print("Five is exactly bigger!")
```

## Variabel Python

Dalam Python, variabel dibuat ketika nilai sudah pasti ditetapkan.

```
x = 5
y = "Hello World"
```

Python tidak memiliki keyword khusus untuk mendeklarasikan Variabel.

## Comments

Komentar pada Python digunakan untuk memberikan dokumentasi pada kode program.

Membuat komentar pada Python dapat menggunakan tanda #.

Ketika baris sebuah kode diawali tanda #, maka baris tersebut merupakan sebuah komentar.

```
#This is a comment.
print("Hello World!")
```
