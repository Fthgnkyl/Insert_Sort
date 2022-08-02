# Proje 1

### [22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Cevaplar

### Soru 1

1. '[22,27,16,2,18,6]' **_ilk hali_**
2. '[2,27,16,22,18,6]' **_ilk aşama en küçük sayı belirlendi ve en başa alındı. Sayılar yer değiştirdi._**
3. '[2,6,16,22,18,27]' **_ikinci aşama ilk sabit ve 2. en küçük sayı bulunup yer değiştirildi._**
4. '[2,6,16,22,18,27]'
5. '[2,6,16,18,22,27]'

### Soru 2

**_n tane elaman için yapılan işlem n^2 olduğu için n=6 ve n^2=36 işlem yapılmıştır._**

### Soru 4

Dizi de **"18"** sayısı ortada yer aldığı için _avarge case_ yapısına uygundur

### Soru 5

_[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız._

1. '[2,3,5,8,7,9,4,15,6]'
2. '[2,3,5,8,7,9,4,15,6]'
3. '[2,3,4,8,7,9,5,15,6]'
4. '[2,3,4,5,7,9,8,15,6]'
5. '[2,3,4,5,6,9,8,15,7]'
6. '[2,3,4,5,6,7,8,15,9]'
7. '[2,3,4,5,6,7,8,9,15]'
