# Python Keywords And Identifier

Pada sesi kali ini saya akan membahas mengenai *keywords* atau kata kunci (yang disediakan oleh Python) dan identifier (nama yang diberikan pada variabel, fungsi, dll)

## Python Keywords

*Keyword* atau kata-kunci adalah kata yang disediakan di python.

Kita tidak bisa menggunakan kata-kunci ini sebagai nama variabel, nama fungsi, atau identifier lainnya.
Mereka digunakan untuk mendefinisikan sintaks atau struktur dari bahasa pemrograman python.

Di python, *keywords* bersifat *case sensitive* (huruf besar atau kecil diperhatikan)

Ada 33 *keywords* di Python 3.7. Jumlah ini mungkin bisa berubah mengikuti perkembangan dari python sendiri.

Semua *keywords* kecuali `True`, `False` dan `None` menggunakan huruf kecil (*lowercase*) dan harus ditulis secara semestinya. List dari *keywords* adalah sebagai berikut:

| | | | | |
|-|-|-|-|-|
| `False`  | `await`    | `else`    | `import`   | `pass`   |
| `None`   | `break`    | `except`  | `in`       | `raise`  |
| `True`   | `class`    | `finally` | `is`       | `return` |
| `and`    | `continue` | `for`     | `lambda`   | `try`    |
| `as`     | `def`      | `from`    | `nonlocal` | `while`  |
| `assert` | `del`      | `global`  | `not`      | `with`   |
| `async`  | `elif`     | `if`      | `or`       | `yield`  |

Melihat semua *keywords* sekaligus dan mencaritahu apa artinya mungkin berlebihan.
Jika ingin mengetahui arti dan penggunaannya, akan dibahas pada bab lain secara terperinci.

## Pyhton Identifier

Identifier adalah nama yang diberikan kepada entitas seperti kelas, fungsi, variabel, dll. Hal ini membantu untuk membedakan satu entitas dari entitas yang lain. 

### Aturan penulisan identifier
1. Identifier dapat berupa kombinasi antara huruf kecil (a sampai z) atau huruf besar (A sampai Z) atau digit (0 sampai 9) atau *underscore* `_`. Nama seperti `myClass`, `var_1` dan `print_this_to_screen` merupakan contoh yang valid.

2. Sebuah identifier tidak boleh diawali dengan digit atau angka. `1variable` contoh yang tidak valid, tapi `variable1` merupakan nama yang valid.

3. *Keywords* tidak dapat digunakan sebagai identifier.
```
global = 1
```
Output:
```
  File "<interactive input>", line 1
    global = 1
           ^
SyntaxError: invalid syntax
```

4. Kita tidak bisa menggunakan simbol spesial seperti **!,@,#,$,%** dll. pada indentifier.
```
a@ = 0
```
Output:
```
  File "<interactive input>", line 1
    a@ = 0
     ^
SyntaxError: invalid syntax
```
5. panjang dari identifier tidak dibatasi

-------
## Hal yang harus diperhatikan

Python adalah bahasa dengan *case-sensitive*. Ini berarti bahwa, `Variable` dan `variable` tidak sama.

Selalu berikan nama yang masuk akal untuk identifier. Dimana `c = 10` merupakan nama yang valid, menulisnya dengan `count = 10`akan membuatnya lebih baik, dan itu akan membuatnya lebih mudah untuk direpresentasikan ketika kita melihat code kita setelah gap yang lama.

kata yang banyak (*multiple words*) dapat dipisahkan menggunakan sebuah *underscore*, seperti `this_is_a_long_variable`. 

----------------------------------------------------------------------------------------------------------------
sumber : [programiz \| keyword and identifier](https://www.programiz.com/python-programming/keywords-identifier)

