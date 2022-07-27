[22,27,16,2,18,6] -> Insertion Sort

SORU: Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

CEVAP:

[2,27,16,22,18,6] 1.adım

[2,6,16,22,18,27] 2.adım

[2,6,16,22,18,27] Değişiklik olmaz.

[2,6,16,18,22,27] 3.adım

[2,6,16,18,22,27] Değişiklik olmaz.


SORU: Big-O gösterimini yazınız.

CEVAP: İlk adımda yapılacak işlem sayısı n, ikinci adımda yapılacak işlem sayısı n-1 diye giderken kalan son 1 işleme kadar olan işlemlerin sayısı toplamı (n.(n+1))/2 ile bulunur. (n^2+n)/2 ifadesinde dominant terim n^2 olduğu için Big-O gösterimi O(n^2) şeklindedir.


HATIRLATMA(?): Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.


SORU: Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

CEVAP: Her ne kadar 18 sayısı dizinin ortasında yer alsa da, en sonuncu işlemden sonra yerini bulduğu içi worst case kapsamındadır.


SORU: [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

CEVAP:

1.ADIM: [2,3,5,8,7,9,4,15,6]

[2,3,5,8,7,9,4,15,6] 3 yerindedir, değişiklik yapılmaz.

2.ADIM: [2,3,4,8,7,9,5,15,6]

3.ADIM: [2,3,4,5,7,9,8,15,6]

4.ADIM: [2,3,4,5,6,9,8,15,7]


PATİKA LİNKİ

https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje
