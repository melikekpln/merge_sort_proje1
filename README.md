# merge_sort_proje1

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

1. Listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölelim.

[16,21,11,8,12,22]

[16,21,11]              [8,12,22]

[16]  [21,11]           [8]   [12,22]
[16]  [21] [11]         [8]   [12] [22]

2. Ardından birleştirme işlemleri başlar. Birleştirirken ikili gruplar büyüklüğüne bakarak sıralanır. Küçük sayılar sola, büyük sayılar sağa yazılır.

[16]  [11,21]           [8]   [12,22]

[11,16,21]              [8,12,22]

[8,11,12,16,21,22]
