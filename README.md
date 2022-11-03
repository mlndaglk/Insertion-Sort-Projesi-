# Insertion-Sort-Projesi-
[22,27,16,2,18,6] -> Insertion Sort
Soru - 1
1-) [22,27,16,2,18,6]
2-) 22|,27,16,2,18,6
3-) 22,27|,16,2,18,6
4-) 22,16,27|,2,18,6
5-) 16,22,27|,2,18,6
6-) 16,22,2,27|,18,6
7-) 16,2,22,27|,18,6
8-) 2,16,22,27|,18,6
9-) 2,16,22,18,27|,6
10-) 2,16,18,22,27|,6
11-) 2,16,18,22,6,27|a
12-) 2,16,18,6,22,27|
13-) 2,16,6,18,22,27|
14-) 2,6,16,18,22,27| ->Dizi küçükten büyüğe başarıyla sıralandı.
Soru - 2
Big-O gösterimini yazınız
O(N^2)
Soru - 3
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olmasıdır.
Worst Case:
Küçükten büyüğe sıralanmak istenen bir dizinin tüm elemanlarının büyükten küçüğe sıralanmasıdır (reversed order).O(N x (N+1)) / 2 => O((N²+N)/2) => O(N²/2) => O(N²)
Best Case:
Küçükten büyüğe sıralamak istediğimiz bir dizinin elemanlarının zaten küçükten büyüğe sıralandığı durumdur.Dolayısıyla O(N)' dir.
Average Case: O(N²) + O(N) in ortalaması olacağı için yine N² cinsinden bir sonuç olur. Average case = O(N²)
Soru - 4
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[2,6,16,18,22,27]=> Siralanmis dizi
Cevap :Aradigimiz sayi beklenilen durum olarak Average Case'dir.
Soru-5
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1-)[2,3,5,8,7,9,4,15,6] -> 2 ile 7 sayısı yer değiştirdi
2-)[2,3,4,8,7,9,5,15,6] -> 5 ile 4 sayısı yer değiştirdi
3-)[2,3,4,5,7,9,8,15,6] -> 8 ile 5 sayısı yer değiştirdi
4-)[2,3,4,5,6,9,8,15,7] -> 6 ile 7 sayısı yer değiştirdi

