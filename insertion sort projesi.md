
# [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


## CEVAP:
Dizi içerisindeki en küçük sayı bulunup, listenin en başına yerleştirilir. Daha sonra ikinci en küçük sayı bulunur. Bu şekilde işlem devam eder.
[2,22|27,16,18,6]
[2,6,|22,27,16,18]
[2,6,16|22,27,18]
[2,6,16,18|22,27]

Big-O : O(n^2)

Average case
