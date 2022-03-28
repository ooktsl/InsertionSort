# **InsertionSort** [www.patika.dev](url)

## Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

Input->  [22,27,16,2,18,6]
1. aşama  [2,27,16,22,18,6]
2. aşama  [2,6,16,22,18,27]
3. aşama  [2,6,16,22,18,27]
4. aşama  [2,6,16,18,22,27]
Output-> [2,6,16,18,22,27]


n-1 durum + (n-2) durum + (n-3) durum + ... + 1
(n-1)*n/2
n^2-n
O(n^2)

Average und Worstcase: O(n^2)
Best case: O(n)

Dizi sıralandıktan sonra 18 sayısı Average case kapsamında değerlendirilebilir.

Input-> [7,3,5,8,2,9,4,15,6]
1. aşama [2,3,5,8,7,9,4,15,6]
2. aşama [2,3,5,8,7,9,4,15,6]
3. aşama [2,3,4,8,7,9,5,15,6]
4. aşama [2,3,4,5,7,9,8,15,6]



