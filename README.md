# VeriYapıları ve Algoritmalar Ödev
Patika.dev Profile:
## Ödev1
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[->22,->27,16,2,18,6]

[22,->27,->16,2,18,6] [->22,->16,27,2,18,6] [16,22,27,2,18,6]

[22,27,->16,2,18,6] 

[16,22,->27,2,18,6]

[16,22,27,->2,18,6] 

[2,16,22,->27,18,6]

[2,16,22,27,->18,6]

[2,16,18,22,->27,6]

[2,16,18,22,27,->6]

[2,6,16,18,22,27]


Big-O gösterimini yazınız.

Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Ödev 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## Ödev 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1.Root 7'dir
<pre>
7
</pre>
2.5 < 7, 
  5, 7'nin soluna gelir
<pre>
  7
 /
5
</pre>
3.1<7
  1 7'nin soluna
  1<5
  1,5'in soluna
<pre>
    7
   /
  5
 /
1
</pre>


<pre>
    7
   / \
  5   8
 /
1
</pre>

<pre>
    7
   / \
  5   8
 /
1
 \
  3
</pre>

<pre>
    7
   / \
  5   8
 / \
1   6
 \
  3
</pre>

<pre>
      7
     / \
    5   8
   / \
  1   6
 / \
0   3
</pre>

<pre>
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3      
</pre>

<pre>
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
     \
      4
</pre>

<pre>
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
</pre>
