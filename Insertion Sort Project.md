<strong>[22,27,16,2,18,6] -> Insertion Sort</strong>

<strong>1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.</strong>

1.1. [2, 27, 16, 22, 18, 6] -> 2 ile 22 yer değiştirir <br>
1.2. [2, 6, 16, 22, 18, 27] -> 6 ile 27 yer değiştirir <br>
1.3. [2, 6, 16, 22, 18, 27] -> 16 sayının 3. en küçük elemanı olduğu için yer değiştirmez <br>
1.4. [2, 6, 16, 18, 22, 27] -> 18 ile 22 yer değiştirir ve dizi son halini alır.

<strong>2. Big-O gösterimini yazınız.</strong>

Insertion sort'un BigO'su O(n²)'dir. Elimizdeki dizi ise 6 elemanlı olduğu için bu dizinin BigO'su O(6²) yani O(36) olacaktır.

<strong>3. Time Complexity:</strong> <br> 
Average case: Aradığımız sayının ortada olması, <br>
Worst case: Aradığımız sayının sonda olması, <br>
Best case: Aradığımız sayının dizinin en başında olması.

<strong>4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.</strong>

Average case.


<strong>[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.</strong>

1. [2, 3, 5, 8, 7, 9, 4, 15, 6]
2. [2, 3, 5, 8, 7, 9, 4, 15, 6]
3. [2, 3, 4, 8, 7, 9, 5, 15, 6]
4. [2, 3, 4, 5, 7, 9, 8, 15, 6]
