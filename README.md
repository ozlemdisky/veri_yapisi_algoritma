# veri_yapisi_algoritma
<pre>
[22,27,16,2,18,6] -> Insertion Sort

[2,22,27,16,18,6] n
[2,6,22,27,16,18] n-1
[2,6,16,22,27,18] n-2
[2,6,16,18,22,27] n-3

n+(n-1)+(n-2)+(n-3)+(n-4)+1=(n(n+1))/2=n^2
Big-=O notasyonu: n^2'dir.

18 sayısı average case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı:

[2,7,3,5,8,9,4,15,6]
[2,3,7,5,8,9,4,15,6]
[2,3,4,7,5,8,9,15,6]
[2,3,4,5,7,8,9,15,6]

<hr>

[16,21,11,8,12,22] -> Merge Sort
<br></br>
[16,21,11] [8,12,22] </br>
16 [21,11] [8,12] 22

16 [11,21] [8,12] 22

[11,16,21] [8,12,22]

8,11,12,16,21,22


Big-O: 2^x=n = O(nlogn)

<hr>


[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Rootu belirliyoruz.Daha sonra sayı dizisindeki tüm sayıları sırayla kontrol edip büyük olan sayıları rootun soluna, küçükleri sağına ekliyoruz.


root:3

         3
      /     \
    1          7
    /  \       /  \
    0    2     5    8
        /  \     \
       4    6      9   
                   
</pre>


