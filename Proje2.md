# Veri Yapilari Ve Algoritmalar
# Merge Sort Projesi
[www.patika.dev](https://www.patika.dev/tr)


Merge sort sıralayacağımız diziyi her seferinde ikiye bölüp ayrı ayrı sıraladıktan sonra birleştirme mantığına dayanmaktadır.

            [16,21,11,8,12,22]                  Yapı ikiye bölünür.
    [16,21,11]               [8,12,22]          Tekrar bölüyoruz
    [16]    [21,11]         [8]    [12,22]      Tek eleman kalması için tekrar bölüyoruz.
    [16]   [21] [11]        [8]   [12] [22]     
    [16]    [11,21]         [8]    [12,22]      
    [11,16,21]              [8,12,22]           
            [8,11,12,16,21,22]



## Big-O gösterimini <br>
O(n.logn)
