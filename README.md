# Insertion Sort


[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması.
Worst case: Aradığımız sayının sonda olması.
Best case: Aradığımız sayının dizinin en başında olması.


### Cevap

1.[22,27,16,2,18,6]   8.[2,16,22,18,27,6]       
2.[22,16,27,2,18,6]   9.[2,16,18,22,27,6] 
3.[16,22,27,2,18,6]  10.[2,16,18,22,6,27] 
4.[16,22,2,27,18,6]  11.[2,16,18,22,6,27]           Big O Notation = O(n^2)
5.[16,2,22,27,18,6]  12.[2,16,18,6,22,27]
6.[2,16,22,27,18,6]  13.[2,16,6,18,22,27] 
7.[2,16,22,27,18,6]  14.[2,6,16,18,22,27]                     



# Selection Sort


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

### Cevap

1.[2,3,5,8,7,9,4,15,6]  3.[2,3,4,8,7,9,5,15,6]
2.[2,3,4,8,7,9,5,15,6]  4.[2,3,4,5,7,9,8,15,6]


# Merge Sort


[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

### Cevap

[16,21,11,8,12,22] Diziyi 16,21,11 ve 8,12,22 olarak 2 parçaya ayırıyoruz.
2.Ayırma işlemini devam ettiriyoruz; 16,21 - 11 8,12 -22

İkilileri kendi arasında sıralıyoruz (burada sıralanmış) ve tekrar diğer parçalarla sıralayarak birleştiriyoruz. 11,16,21 8,12,22

Kalan iki diziyi de sıralayarak birleşiriyoruz. [8,11,12,16,21,22]

Big O Notation = O(logn)


# Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Cevap

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Binary-Search-Tree aşamaları

İlk olarak dizimizin root kökünü belirlememiz lazım. Root kök olarak 3 belirliyorum

Dizimizdeki ilk rakamdan başlayarak root rakamımızdan büyük olanları soluna küçük olanları sağına ekliyoruz.

Her rakam için öncelikle root sayımızdan büyük mü ona bakıyoruz sola veya sağa ekliyoruz.

Root rakamından sonra gelen rakama bakıp büyükse sola küçükse sağa ekliyoruz

            3
     /        \
    1          7
   /  \       /  \
  0    2     5    8
           /  \     \
          4    6      9                     
