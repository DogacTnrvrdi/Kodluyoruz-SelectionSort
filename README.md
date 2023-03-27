# Kodluyoruz - Selection Sort

###[22,27,16,2,18,6] -> Dizisinin Insertion Sort'a göre aşamaları:

1- [2,27,16,22,18,6] -> 2 ile 22 yer değiştirdi.
2- [2,6,16,22,18,27] -> 6 ile 27 yer değiştirdi.
3- [2,6,16,18,22,27] -> 18 ile 22 yer değiştirdi.

###Bu algoritmanın Big-O gösterimi şu şekildedir:

n + (n - 1) + (n - 2) ... + 1
= n * (n + 1) / 2
= (n^2 + n) / 2
= O(n^2)

Dizi sıralandıktan sonra 18 sayısının Time Complexity'si Average Case'dir

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 aşaması:

1- [2,3,5,8,7,9,4,15,6] -> 2 ile 7 yer değiştridi.
2- [2,3,4,8,7,9,5,15,6] -> 4 ile 5 yer değiştirdi.
3- [2,3,4,5,7,9,8,15,6] -> 5 ile 8 yer değiştirdi.
4- [2,3,4,5,6,9,8,15,7] -> 6 ile 7 yer değiştirdi.
