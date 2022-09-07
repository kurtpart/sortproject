# sortproject
Insertion Sort Projesi - Merge Sort Projesi - Binary Search Tree Projesi
--------------
## Insertion Sort Projesi 
[22,27,16,2,18,6] -> Insertion Sort
### 1)
[22,27,16,2,18,6] -> n

[2,27,16,22,18,6] -> n-1

[2,6,16,22,18,27] -> n-2

[2,6,16,18,22,27] -> 1

### 2)
O(n^2)
### 3)
Time Complexity: Average case

-------------------------
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,9,8,15,6]

[2,3,4,5,6,9,8,15,7]



## Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

*             [16,21,11]                   [88,12,22]
*          [16]     [21,11]              [88]     [12,22]
*         [16]     [21]  [11]           [88]    [12]   [22]
*        [16]       [11,21]             [88]      [12,22]
*          [11,16,21]                     [12,22,88]
*                      [11,12,16,21,22,88]
---------------------------
O(logn)

## Binary Search Tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


* root'u 7 alırsak sağında 8 ve 9 bulunur. solunda 0, 1, 2, 3, 4, 5 ve 6 bulunur.
