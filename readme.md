# MÜ-Patika / Veri Bilimi ve Algoritma Projeleri
##  [Patika.dev](https://app.patika.dev) ve Marmara Üniversitesi ortak patikası
---
> Yazılıma başlangıç patikasındaki Veri yapıları ve Algoritmalar dersinin sonundaki 3 proje için readme dosyası

# Proje 1

``` 
[22,27,16,2,18,6] -> Insertion sort
    > Dizisinin sort türüne göre aşamalarını yazınız.
    > Big-O gösterimini yazınız 
    > 18 sayısının hangi case'e dahil olduğunu belirtiniz

    1) [22,27,16,2,18,6] n = 6 
    2) [2,27,16,22,18,6] n-1  
    3) [2,6,16,22,18,27] n-2
    4) [2,6,16,18,22,27] n-3
    5) [2,6,16,18,22,27] n-4
    6) [2,6,16,18,22,27] n-5
```
``` 
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

    1) [7,3,5,8,2,9,4,15,6]
    2) [2,3,5,8,7,9,4,15,6]
    3) [2,3,5,8,7,9,4,15,6]
    4) [2,3,4,8,7,9,5,15,6]
```
> En basit sıralama algoritmasıdır. Sıra sıra her elemana bakılır ve küçük olan başa getirilir.
> Data sayısının çok olduğu durumlarda kullanışlı değildir.
# Proje 2

``` 
[16,21,11,8,12,22] -> Merge Sort
    > Dizisinin sort türüne göre aşamalarını yazınız.
    > Big-O gösterimini yazınız 
``` 
                    [16,21,11,8,12,22]
        [16,21,11]                      [8,12,22]
       [16]  [21,11]                   [8,12] [22]
      [16] [21] [11]                  [8] [12] [22] 
        [11,16,21]                       [8,12,22]
                    [8,11,12,16,21,22]

> Diziyi ikiye bölerek daha hızlı sıralama imkanı buluyoruz 

>Big-O Notation -> O(nlogn)
# Proje 3

``` 
[7,5,1,8,3,6,0,9,4,2] 
    > Dizisinin Binary-Search-Tree aşamalarını yazınız. 
``` 
                            7
             5                                8
        1        6                                9
    0       3
        2       4          

> ilk eleman başa yerleştirip sıradan gelen her eleman büyüklük küçüklük durumuna göre sağa yada sola yerleşecek ve böylelikle ağacımız ortaya çıkacak