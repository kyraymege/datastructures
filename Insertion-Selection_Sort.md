#[22,27,16,2,18,6] -> Insertion Sort

>1.Adım
>>[**22**,**27**,16,2,18,6] -> 22 ve 27 arasında büyüklük karşılaştırılması yapılır.
>
>2.Adım
>>[22,**27**,**16**,2,18,6] -> 27 büyük olduğu için yerinde kalır ve 16 ile karşılaştırılır.
>
>3.Adım
>>[22,**16**,27,2,18,6] -> 16, 27'den küçük olduğu için 27 ile yer değiştirir.
>>[**16**,22,27,2,18,6] -> 16, 22'den küçük olduğu için 22 ile yer değiştirir.
>
>4.Adım
>>[16,22,**27**,**2**,18,6] -> 27 ve 2 arasında büyüklük karşılaştırılması yapılır.
>
>5.Adım
>>[16,22,**2**,**27**,18,6] -> 2, 27'den küçük olduğu için 27 ile yer değiştirir.
>>[16,**2**,22,27,18,6] -> 2, 22'den küçük olduğu için 22 ile yer değiştirir.
>>[**2**,16,22,27,18,6] -> 2, 16'dan küçük olduğu için 16 ile yer değiştirir.
>
>6.Adım
>>[2,16,22,**27**,**18**,6] -> 27 ve 18 arasında büyüklük karşılaştırılması yapılır.
>
>7.Adım
>>[2,16,22,**18**,**27**,6] -> 18, 27'den küçük olduğu için 27 ile yer değiştirir.
>>[2,16,**18**,22,27,6] -> 18, 22'den küçük olduğu için 22 ile yer değiştirir.
>
>8.Adım
>>[2,16,18,22,**27**,**6**] -> 27 ve 6 arasında büyüklük karşılaştırılması yapılır.
>
>9.Adım
>>[2,16,18,22,**6**,**27**] -> 6, 27'den küçük olduğu için 27 ile yer değiştirir.
>>[2,16,18,**6**,22,27] -> 6, 22'den küçük olduğu için 22 ile yer değiştirir.
>>[2,16,**6**,18,22,27] -> 6, 18'den küçük olduğu için 18 ile yer değiştirir.
>>[2,**6**,16,18,22,27] -> 6, 16'dan küçük olduğu için 16 ile yer değiştirir.
>
>10.Adım
>>[2,6,16,18,22,27] -> Sonuç

>Big O Notation -> Best Case : O(n) , Avarage & Worst Case : O(n^2) 
>
>Dizi sıralandıktan sonra 18 sayısı sona daha yakın olduğu için worst case'e girer.

******
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

>1.Adım
>>[7,3,5,8,**2**,9,4,15,6] -> Min. değer 2 olarak bulunur.
>>[**2**,3,5,7,8,9,4,15,6] -> Min. değer 2 olduğu için en başa gelir.

>2.Adım
>>[2,3,5,7,8,9,**4**,15,6] -> ikinci min. değer 3 olduğu için üçüncü değere bakılır ve 4 bulunur.
>>[2,3,**4**,5,7,8,9,15,6] -> Min. değer 4 olduğu için 3. indexe gelir.

>3.Adım
>>[2,3,4,5,7,8,9,15,**6**] -> 5. değer için bakıldığında min. değer 6 olarak belirlenir.
>>[2,3,4,5,**6**,7,8,9,15] -> Min. değer 6 olduğu için 5. indexe gelir.

>4.Adım
>>[2,3,4,5,6,7,8,9,15] -> Sonuç