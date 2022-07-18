# Patika.dev Data Structures Course Projects

## Insertion Sort Projesi
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje
### Talep
[22,27,16,2,18,6] -> Insertion Sort

1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2)Big-O gösterimini yazınız.

3)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### Çözüm

Sort Aşamaları
```
  [22,27,16,2,18,6]
  
1 [16,22,27,2,18,6]
2 [2,16,22,27,18,6]
3 [2,16,18,22,27,6]
4 [2,6,16,18,22,27]
```

Big-O Gösterimi
```
Worst Case   = O(n^2)
Avarage Case = O(n^2)
Best Case    = O(n)
```

Time Complexity
 ```
 Best Case  = [2,6,16,18,22,27]
 Worst Case = [27,22,18,16,6,2]
 ```
 
Sıralama Sonrasında 18 Sayısı Hangi Case Kapsamında?
 ```
 En ortada olduğu için ne worst ne de best. Average Case kapsamına girer.
 ```
### Talep
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

### Çözüm
 ```
   [7,3,5,8,2,9,4,15,6]
  
1 [3,7,5,8,2,9,4,15,6]
2 [3,5,7,8,2,9,4,15,6]
3 [3,5,7,2,8,9,4,15,6]
4 [3,5,2,7,8,9,4,15,6]
```

## Merge Sort Projesi
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje

### Talep
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

### Çözüm

Aşamaları
 ```
                [16,21,11,8,12,22]
 
          |16,21,11|           |8,12,22|
 
|16|         |21,11|           |8,12|         |22|
 
|16|     |21|   |11|           |8|   |12|     |22|
 
|16|         |11,21|           |8,12|         |22|
 
          |11,16,21|           |8,12,22|
 
                |8,11,12,16,21,22|
 
 
 ```

Big-O Gösterimi
 ```
Worst Case   =  θ(nLogn) 
Average Case =  θ(nLogn)
Best Case    =  θ(nLogn) 
 ```
 
 ## Binary Search Tree Projesi
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje

### Talep
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Çözüm
```
                      7
                  
                      7
                    /
                  5
                  
                      7
                    /
                   5
                  /
                1
              
                      7
                     /  \
                    5    8
                  /
                1
              
                      7
                     /  \
                    5    8
                  /
                1 
                  \
                    3
                
                      7
                     /  \
                    5    8
                   /  \
                  1    6
                    \
                     3
                
                       7
                     /  \
                   5      8
                  /  \
                 1    6
               /  \
              0    3


                       7
                     /  \
                   5      8
                  /  \      \
                 1    6       9
               /  \
              0    3
              
                      7
                     /  \
                   5      8
                  /  \      \
                 1    6       9
               /  \
              0    3
                    \
                     4
                     
                      7
                     /  \
                   5      8
                  /  \      \
                 1    6       9
               /  \
              0    3
                  / \
                 2   4
```
