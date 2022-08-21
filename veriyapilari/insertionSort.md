### [22,27,16,2,18,6] -> Insertion Sort

##### 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

|1->|22|27|16|2|18|6|
|------|- |- |- |-|- |-|
|2->|22|16|27|2|18|6|
|------|- |- |- |-|- |-|
|3->|16|22|27|2|18|6|
|------|- |- |- |-|- |-|
|4->|16|22|2|27|18|6|
|------|- |- |- |-|- |-|
|5->|16|2|22|27|18|6|
|------|- |- |- |-|- |-|
|6->|2|16|22|27|18|6|
|------|- |- |- |-|- |-|
|7->|2|16|22|18|27|6|
|------|- |- |- |-|- |-|
|8->|2|16|18|22|27|6|
|------|- |- |- |-|- |-|
|9->|2|16|18|22|6|27|
|------|- |- |- |-|- |-|
|10->|2|16|18|6|22|27|
|------|- |- |- |-|- |-|
|11->|2|16|6|18|22|27|
|------|- |- |- |-|- |-|
|12->|2|6|16|18|22|27|
|------|- |- |- |-|- |-|

|SONUC -> |2|16|6|18|22|27|


##### 2. Big-O gösterimini yazınız.

O(n^2)

##### 3. Time Complexity: 
###### - Worst case: Aradığımız sayının sonda olması,
Tam ters verilmiş dizi, bu durumda dizinin her bir elemanı bir gerisindekinden küçük olacaktır. Dolayısıyla 1inci eleman için iç döngü 0 2 eleman için geriye doğru 1, 3. eleman için iki daha sonra 3 4 5 6… n kadar geriye hareket yapacaktır. Yani 0+1+2+3+4…..+n-1 = [n*(n-1)]/2   :  n^2

###### - Average case: Aradığımız sayının ortada olması,
Worst case ile best casein ortalamasını aldığımızda   n^2 olarak buluruz.

###### - Best case: Aradığımız sayının dizinin en başında olması.
Tam sıralı dizi, n tane sayinin üzerinden birer defa geçer ve hiç birini geriye doğru ilerletme gereği olmadığı için bu tek geçişle kalır. Yani n

##### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
veri setinin ortasında olduğu için average case kapsamına girer.
    
#### 2. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
|1.Adım|7|3|5|8|2|9|4|15|6| 
|------|- |- |- |-|- |-|
|2.Adım|3|7|5|8|2|9|4|15|6| 
|------|- |- |- |-|- |-|
|3.Adım|3|5|7|8|2|9|4|15|6| 
|------|- |- |- |-|- |-|
|4.Adım|3|5|7|8|2|9|4|15|6|  
|------|- |- |- |-|- |-|