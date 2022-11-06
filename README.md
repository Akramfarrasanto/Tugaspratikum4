## Latihan 1

## Buat program sederhana dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statment if.
### Penjelasan program
- 1.user1=int(input("Masukan bilangan pertama=")) Untuk mementukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat
- 2.user2=int(input("Masukan bilangan kedua=")) Untuk menentukan jumlah input yang di inginkan sesuai tipe data yaitu interger tipe data bilangan bulat
- 3.if untuk membandingkan kedua bilangan user1 dan user2 jika true maka akan mencetak print(f"{user1}lebih besar dari{user2}")
- 4.Jika false maka program akan mencetak print(f"{user1}lebih kecil dari{user2}")

pertama-tama kita buat input terlebih dahulu contohnya seperti dibawah ini:
```
k = int(input('Masukan bilangan pertama : '))

y = int(input('Masukan bilangan kedua : '))
```
lalu kita enter, masukan if untuk menjalani program yang sebelumnya dan tambahkan k > y : lalu print('Bilangan terbesar = ', k)

lalu tambahkan else untuk menambah aksi untuk menentukan bahwa k lebih besar dari y 

 else :
 
      print('Bilangan terbesar = ', y)
      
dan saat running kita diminta untuk memasukan bilangan pertama lalu bilangan kedua,      
lalu hasil runing nya seperti gambar berikut:
![gambar1](https://user-images.githubusercontent.com/115552876/200197621-23ebd131-a6af-4cb2-97da-6734a2287e03.png)
<img width="658" alt="gambar1(b)" src="https://user-images.githubusercontent.com/115552876/200197670-abaf26bc-8610-4ad0-871c-66286f21aca6.png">

## latihan 2

pertama-tama kita buat input terlebih dahulu contohnya seperti dibawah ini:
```
a = int(input('Bilangan ke-1 = '))

b = int(input('Bilangan ke-2 = '))

c = int(input('Bilangan ke-3 = '))
```
lalu tambahkan 
```
if a < b:

    if b < c:
    
        print('Urutan bilangan : ', a,b,c)
        
    else:
    
        print('Urutan bilangan : ', c,a,b)
        
else:

    if a < c:
    
        print('Urutan bilangan : ',b,a,c)
        
    else:
    
        if b < c:
        
            print('Urutan bilangan : ', b,c,a)
            
         else:
         
            print('Urutan bilangan : ', c)
```            
dan saat running kita sebut bilangan yang ingin kita urutkan 
lalu hasil running nya seperti gambar berikut:
![gambar2](https://user-images.githubusercontent.com/115552876/200197730-a24e777a-5468-430b-b2ce-21f5b1f11ccf.png)
<img width="702" alt="gambar2(b)" src="https://user-images.githubusercontent.com/115552876/200197744-aa0325c3-5520-433e-b728-1efe930b3391.png">

## latihan 3

pertama-tama kita buat codingannya dulu seperti berikut:
```
for i in range(0, 10):

    for j in range(0, 10):
    
        product = i+j
        
        print(f"{product:>3}", end='')
    print()
print("Rian Fauza")

maka runingannya akan seperti gambar berikut:
```
![gambar3](https://user-images.githubusercontent.com/115552876/200197912-7b7fa399-3724-4b2e-a27d-2cde48424e88.png)
<img width="468" alt="gambar3(b)" src="https://user-images.githubusercontent.com/115552876/200197957-a84693cd-04f2-4d9a-b714-32645d059936.png">

## latihan 4

pertama-tama kita buat codingannya dulu seperti berikut:
```
import random

n = int(input("masukan nilai N : "))

for i in range(n):

    a = random.uniform(0.0, 0.5)
    
    print("data ke :", i+1, "=> ", a)
    
    print("Rian Fauza")
```    
setelah runing akan diminta masukan nilai N, disini saya memasukan nilai n-nya 7
dan hasil runningannya akan seperti gambar berikut:
![gambar4](https://user-images.githubusercontent.com/115552876/200198023-9da7b303-c196-4e03-9f19-3f637ff64ec0.png)
<img width="460" alt="gambar4(a)" src="https://user-images.githubusercontent.com/115552876/200198031-f317cf61-1d62-480c-9ab9-f8265bc48748.png">

## latihan 5

![gambar5](https://user-images.githubusercontent.com/115552876/200198065-428cc67a-6e78-4f28-86c9-6ddfaf9f5098.png)

jadi masukan a, b, c sebagai inputan untuk memasukan bilangan
lalu tambahkan if menandakan bahwa a lebih besar dari b lalu tambahkan titik dua 
jadi seperti ini
If  a > b:
lakukan juga pada a dan b lalu print dan ketik masukan bilangan terbesar,
lalu selanjutnya tambahkan elif dan else yaitu untuk menambah aksi untuk menentukan bahwa a lebih besar dari b dan c lebih besar dari d,
setelah menjalani codingan seperti penjelasan dan gambar di atas lalu runing

<img width="697" alt="gambar5(b)" src="https://user-images.githubusercontent.com/115552876/200198106-a289d17d-f9f6-4356-8c7b-6ecaf3b7133d.png">

setelah running masukan bilangan dari yang terbesar hingga terkecil, hasil akhirnya menunjukan bilangan terbesar dari tiga bilangan yang di masukan

## latihan 6

![gambar6](https://user-images.githubusercontent.com/115552876/200198208-42a5f37b-e9f4-4299-877b-62360be19f71.png)

pertama-tama kita print dan masukan nama kita 
lalu masukan n, =, dan 1, lalu enter dan masukan a, =, dan 0. jadi keliahatnnya seprti ini:
```
n=1
a=0
```
fungsi nya adalah untuk menentukan nilai terbesar, lalu enter dan tambahkan while n, !, =, 0, dan :. setelah itu enter, nah pas saat enter pastikan tidak sejajar dengan while, setelah itu tambahkan if n, >, a, dan : enter lalu tambahkan a = n, kemudian enter tambahkan n dan = lalu input ketik masukan bilangan gunakan (, :, dan " sebagai syntax nya, lalu lanjut enter dan tambahkan if, r, ==, 0, dan : enter dan masukan break tidak sejajar dengan if, enter masukan printnan seperti sebelumnya bedanya tambahkan a. jadi keliatannya seperti ini:
```
while n !=0:

    if n > a:
        a = n
    n = int(input("masukan Bilangan: "))
    
    if n == 0:
        break
    print("Nilai terbesarnya adalah:", a)
```
fungsinya adalah memasukan nilai terbesar.

<img width="691" alt="gambar6(b)" src="https://user-images.githubusercontent.com/115552876/200198295-1db31378-2977-46d1-a157-09a33165d900.png">

## latihan 7

![gambar7](https://user-images.githubusercontent.com/115552876/200198326-7508e830-3e44-4237-8a5a-5b744ec2f598.png)

Masukkan codingan sperti diatas adalah untuk menghitung laba dari bulan kesatu hingga ke 8

<img width="711" alt="gambar7(b)" src="https://user-images.githubusercontent.com/115552876/200198329-73966aa3-c681-48b7-a0e7-ed5564dc57cb.png">
