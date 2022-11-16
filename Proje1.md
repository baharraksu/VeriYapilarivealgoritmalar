# Veri Yapilari Ve Algoritmalar
[www.patika.dev](https://www.patika.dev/tr)
## Insertion Sort Projesi<br>

`SORU: [22,27,16,2,18,6] -> Insertion Sort` 
1) 22,27,16,2,18,6  -> Başlangıçta, ilk iki öğe ekleme sıralamasında karşılaştırılır.<br>
2) 22|,27,16,2,18,6 ->Burada 27,22'den büyüktür. Bu, her iki öğenin de zaten artan sırada olduğu anlamına gelir.
3) 22,27|,16,2,18,6 ->Burada 16, 27'den küçüktür. Yani 27 doğru konumda değildir. Şimdi,27'i 16 ile değiştirin.
4) 22,16,27|,2,18,6 ->Burada 16 22 den küçüktür.Bu yüzden tekrar yer değişikliği yaptık.
5) 16,22,27|,2,18,6 ->Burada 2 ile 27'i karşılaştırıyoruz.2 daha küçük olduğu için sol tarafa alındı ve kıyaslamalara sol taraftan devam edildi.
6) 16,22,2,27|,18,6 ->2 burada 22 ile kıyaslandı.
7) 16,2,22,27|,18,6 ->2 burada 16 ile kıyaslandı.
8) 2,16,22,27|,18,6 ->Burada 18 ile 27 kıyaslandı.
9) 2,16,22,18,27|,6 ->Burada 18 ile 22 kıyaslandı.
10) 2,16,18,22,27|,6 ->Burada 27 ile 6 kıyaslandı.
11) 2,16,18,22,6,27| ->Burada 22 ile 6 kıyaslandı
12) 2,16,18,6,22,27| ->Burada 18 ile 6 kıyaslandı.
13) 2,16,6,18,22,27| ->Burada 6 ile 16 kıyaslandı.
14) 2,6,16,18,22,27| ->Artık dizi tamamen sıralanmıştır.

## Big-O gösterimini <br>
big(o) = o(n^2)

`SORU:Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. ` <br>
veri setinin ortasında olduğu için average case kapsamına girer.

`SORU: [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.` <br>
7|,3,5,8,2,9,4,15,6 <br>
3,7|,5,8,2,9,4,14,6 <br>
3,5,7|,8,2,9,4,14,6 <br>
3,5,7,8|,2,9,4,14,6 <br>
