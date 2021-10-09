# -MergeSort
[16,21,11,8,12,22] dizisinin Merge Sort türüne göre aşamaları:
1. aşama:
Dizi 2 parçaya ayrılır.
[16,21,11] ve [8,12,22]
2. aşama:
Bölünen parçalar kendi içinde tekrar 2 parçaya ayrılır.
[16] / [21,11] ve [8,12] / [22] 
3. aşama:
Her bir eleman tek parça haline gelir.
[16] / [21] / [11] ve [8] / [12] / [22]
4. aşama:
Soldaki elemanlar kendi arasında sağdakiler de kendi arasında sıralanarak birleştirilir.
[11,16,21] ve [8,12,22]
5. aşama:
Son olarak tüm elemanlar küçükten büyüğe sıralanarak tek dizi halinde sıralanmış olur.
[8,11,12,16,21,22]

Big-O gösterimini: O(nlog(n))
