# Merge-sort-analizi

Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1. bölme
-[16,21,11] ve [8, 12, 22]
-[16]  [21, 11] ve [8]  [12, 22]
-[16]  [21] [11] ve  [8] [12] [22]

2. birleştirme
-[21] + [11] → [11, 21]
-[16] + [11, 21] → [11, 16, 21]
-[12] + [22] → [12, 22]
-[8] + [12, 22] → [8, 12, 22]

3. Son Birleştirme
-[11, 16, 21] + [8, 12, 22] -> [8, 11, 12, 16, 21, 22]

Big-O gösterimini yazınız.

- O(nlogn)
