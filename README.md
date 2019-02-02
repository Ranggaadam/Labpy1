# Labpy1
 ## Program menentukan bilangan terbesar dari 3 buah input bilangan

Ketika baris program memeriksa kondisi nilai a, b, dan c. Nilai yang dimasukkan akan disimpan ke dalam variabel tersebut, kemudian dibandingkan dengan menggunakan pemilihan if (dalam hal ini nilai dari a, b, dan c dipastikan tidak boleh sama atau harus berbeda).

a = int(input ("masukan nilai a : "))
b = int(input ("masukan nilai b : "))
c = int(input ("masukan nilai c : "))

if a > b :
    if a > c :
        print ("nilai terbesarnya adalah", a)
    else :
        print ("nilai terbesarnya adalah", c)
elif b > c :
    print ("nilai terbesarnya adalah", b)
else :
    print ("nilai terbesarnya adalah", c)
   
Hasil nya :
![alt text](https://github.com/Ranggaadam/Labpy1/blob/master/Screenshot1.png)
