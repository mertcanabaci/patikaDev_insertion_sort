# patikaDev_insertion_sort

## [22,27,16,2,18,6] -> Insertion Sort
*Verilen dizinin sort türüne göre aşamaları*

[2,27,16,22,18,6] En küçük sayının 2 olduğunu belirler ve 22 ile yer değiştiririz.
[2,6,16,22,18,27] 2 dışında en küçük sayının 6 olduğunu belirler ve 27 ile yer değiştiririz.
[2,6,16,22,18,27] Üçüncü en küçük sayı zaten 16 olduğu için bu adımda bir şey yapmayız.
[2,6,16,18,22,27] Dördüncü en küçük sayı olan 18'in yeri değiştirildi.
[2,6,16,18,22,27] 22'nin yeri doğru olduğu için yer değiştirme yapmayız.
[2,6,16,18,22,27] 27 en büyük sayı olduğu için yer değiştirme yapmayız.

## Big-O gösterimini yapalım.
O(n^2)

## Time Complexity: 
Best Case: [2,6,16,18,22,27]
Worst Case: [27,22,18,16,6,2]'

##Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 
Başta veya sonda olmadığı Avarage Case kapsamında yer alır.

##[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı;

[2,3,5,8,7,9,4,15,6] En küçük sayının 2 olduğu belirlendi ve 7 ile yer değiştirdi.
[2,3,5,8,7,9,4,15,6] 2.adımda bir şey yapmıyoruz çünkü 3 doğru yerde.
[2,3,4,8,7,9,5,15,6] 4 ve 5 yer değiştiriyor.
[2,3,4,5,7,9,8,15,6] 4.adımda en büyük 4.sayı 5 olduğu için 5 ile 8 yer değiştiriyorlar.


