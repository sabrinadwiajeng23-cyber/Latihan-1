# Latihan-1
print("Nama: Sabrina Dwi Ajeng")

#Buat program sederhana dengan input 4 buah bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.

a = int(input("Masukkan bilangan pertama:"))
b = int(input("Masukkan bilangan kedua:"))
c = int(input("Masukkan bilangan ketiga:"))
d = int(input("Masukkan bilangan keempat:"))
 
print("=================") 

max = a

if b > max: 
    max = b
if c > max: 
    max = c
if d > max: 
    max = d

print("bilangan terbesar:", max)
