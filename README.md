# proje1-www.patika.dev
www.patika.dev


Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1.ADIM  22>2  -----------> [2,27,16,22,18,6]
2.ADIM  27>6  -----------> [2,6,16,22,18,27]
3.ADIM  16< 22,18,27 ----> [2,6,16,22,18,27]
4.ADIM  22>18 -----------> [2,6,16,18,22,27]
5.ADIM  22<27 -----------> [2,6,16,18,22,27]

Big-O gösterimini yazınız.

1.ADIM  n
2.ADIM  n-1
4.ADIM  n-2
O(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

[---18---] aradığımız sayı ortada olduğu için average case kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1.ADIM  7>2   ----------->  [2,3,5,8,7,9,4,15,6]
2.ADIM  3<[]  ----------->  [2,3,5,8,7,9,4,15,6]
3.ADIM  5>4   ----------->  [2,3,4,8,7,9,5,15,6]
4.ADIM  8>5   ----------->  [2,3,4,5,7,9,8,15,6]
5.ADIM  7>6   ----------->  [2,3,4,5,6,9,8,15,7]
6.ADIM  9>7   ----------->  [2,3,4,5,6,7,8,15,9]
7.ADIM  8<[]  ----------->  [2,3,4,5,6,7,8,15,9]
8.ADIM  15>9  ----------->  [2,3,4,5,6,7,8,9,15]
