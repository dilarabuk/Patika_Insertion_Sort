# Patika_Insertion_Sort
Patika > Veri Yapıları ve Algoritmalar > Insertion Sort Projesi
[22,27,16,2,18,6]
1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
0.'dan baslayarak tum birimleri tarayip en kucuk birimi bulup en bastakiyle yer degistirir. Ve bu islemi her seferinde bir sonraki birimden baslayarak yapmaya devam eder.
Baslangic: [22,27,16,2,18,6]
1. adim:  [2,27,16,22,18,6]
2. adim:  [2,6,16,22,18,27]
3. adim:  [2,6,16,18,22,27]

2.Big-O gösterimini yazınız.
Insertion Sort ile siraladigimiz durumda her satirda kontrol edilmesi gereken sayi miktari birer birer azalacak. Bunlarin toplami da bize n*(n+1)/2 formulunu verdigi icin Big O Notation gosterimi "O(n^2)" olur.

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Best Case: O(n)
Average Case: O(n^2)
Worst Case: O(n^2)

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız
Geriye kalanlar arasinda ortada kaldigi icin "Average Case" kapsamina girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. adim: [2,3,5,8,7,9,4,15,6]
2. adim: [2,3,4,8,7,9,5,15,6]
3. adim: [2,3,4,5,7,9,8,15,6]
4. adim: [2,3,4,5,6,9,8,15,7]
