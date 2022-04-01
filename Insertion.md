# INSERTON SORT





```
Verilen Dizi

[22,27,16,2,18,6] -> Insertion Sort
```

```
Sort türüne göre aşamaları;
* [22,27,16,2,18,6]
* [2,27,16,22,18,6]
* [2,6,16,22,18,27]
* [2,6,16,18,22,27]

```

```
Big-O gösterimi;

İlk eleman için n tane eleman kontrol edilir. İkinci eleman için (birinci eleman bulunduğu için) n-1 tane eleman kontrol edilir. Bu şekilde dizi tamamlanana kadar devam eder. 

Total yapılan işlem:
(n)+(n+1)+(n+2).....+1

Total yapılan işlem formülü: (n*(n+1))/2 yani (n^2+n)/2

Domine eden fonksiyon (en büyük katsayılı n) n^2 olduğu için Big-O notasyonu (n^2) olur.
```
```
Time Complexity;

* Average case: Aradığımız sayının ortada olması durumudur. Bu durumda sonuç O(n^2)'dir.

* Worst case: Aradığımız sayının sonda olması durumudur ki bu durumda da sonuç O(n^2)'dir.

* Best case: Aradığımız sayının dizinin en başında olması durumudur ve bu durumda sonuç O(n)'dir. Best casede dizi sıralıdır ve her bir eleman sadece bir defa kontrol edilir. 
```

```
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Dizinin sıralanmış hali şöyledir;
[2,6,16,18,22,27]

18 sayısı sıranın ortasında olduğu için "average case" kapsamına girer.
```

```
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

* [2,3,5,8,7,9,4,15,6]
* [2,3,4,8,7,9,5,15,6]
* [2,3,4,5,7,9,8,15,6]
* [2,3,4,5,6,9,8,15,7]