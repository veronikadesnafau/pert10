# TUGAS PERTEMUAN KE 10
**Nama	   	: Veronika Desna Ernayanti Fau** <br>
**Nim	  	: 312010333** <br>
**Kelas	  	: TI.20.A2** <br>
**Matkul    : Bahasa Pemrograman** <br>

## Latihan
# Untuk latihan kali ini merubah dari fungsi ke lambda Ada 4 fungsi yang harus dirubah ke lambda
Perhatikan Soal Berikut
<img width="291" alt="latihan" src="https://user-images.githubusercontent.com/73053784/100827099-85386c80-348e-11eb-8a14-057948b8d125.png">


## Hasil Source Code Diatas
```python
#veronikadesnafau
print("________________________________________")
#mengubah function menggunakan lambda
def a(x):
    return x ** 2

lambda x: x ** 2

print("1. Mengubah function menggunakan Lambda \n   def a(x): \n \t   return x ** 2")
print("   Hasil : lambda x: x ** 2")

def b(x, y):
    return math.sqrt(x ** 2 + y ** 2)

lambda x, y: math.sqrt(x ** 2 + y ** 2)

print("________________________________________")
print("2. Mengubah function menggunakan Lambda \n   def b(x, y): \n \t   return math.sqrt(x ** 2 + y ** 2)")
print("   Hasil : lambda x, y: math.sqrt(x ** 2 + y ** 2))")

def c(*args):
    return sum(args) / len(args)

lambda *args: sum(args) / len(args)

print("________________________________________")
print("3. Mengubah function menggunakan Lambda \n   def c(*args): \n \t   return sum(args) / len(args)")
print("   Hasil : lambda *args: sum(args) / len(args))")

def d(s):
    return "".join(set(s))

lambda s: "".join(set(s))

print("________________________________________")
print("4. Mengubah function menggunakan Lambda \n   def d(s): \n \t   return "".join(set(s))")
print("   Hasil : lambda s: "".join(set(s)))")

```

## Hasil output dari Source Code di atas
![1](https://user-images.githubusercontent.com/73016496/100845522-f2a8c500-34af-11eb-920e-5e7829b79884.png)

Dalam Hasil INPUTAN Diatas Ialah hasil dari proses lambda

## Tugas Praktikum
<img width="280" alt="praktikum" src="https://user-images.githubusercontent.com/73053784/100827730-02181600-3490-11eb-90df-be541b2fb339.png">

## Hasil Source Code Diatas





