<strong>[16,21,11,8,12,22] -> Merge Sort</strong>

<strong>1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.</strong>
 
 1. [16, 21, 11]  - [8, 12, 22]
 2. [16] | [21, 11] - [8] [12, 22]
 3. [16] | [21] | [11] - [8] |[12] | [22]
 4. [16] | [11, 21] - [8] |[12, 22]
 5. [11, 16, 21] - [8 12, 22]
 6. [8, 11, 12, 16, 21, 22]
 
 <strong>2. Big-O gösterimini yazınız.</strong>

Merge Sort'un BigO'su nlogn'dir. Elimizdeki dizi 6 elemanlı olduğuna göre 6.log6 olacaktır. Yani log6⁶
