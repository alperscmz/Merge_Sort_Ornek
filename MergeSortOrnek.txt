# Merge_Sort_Ornek
## patıka.dev Merge_Sort_Ornek calısma 

1))[16,21,11,8,12,22] -> Merge Sort
```
1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.
```
Merge sort bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde bize sunuyor.
```
-[16,21,11] ve [8,12,22] olarak ıkıye ayırırız.Daa sonrasında da tek eleman kalıncaya kadar ısleme devam ederız.
-[16][21,11]    [8][12,22] 
-[16]  [21][11]    [8]  [12][22]
-[16] [11] [21]     [8] [12] [22]
-[11][16][21]       [8][12][22]
- [8][11][12][16][21][22] 
```
```
Merge Sortun Bıg-O gosterımı O(nlogn) seklınde olacaktır.
```





