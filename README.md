## patika_veri_yapilar-_ve_Algoritmalar_proje2
#proje2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Bölme Aşaması:

[16, 21, 11] | [8, 12, 22]
Bölme Aşaması:

[16] | [21, 11]   -   [8] | [12, 22]
Bölme Aşaması:

[16] | [21] | [11]   -   [8] | [12] | [22]
Birleştirme Aşaması:

[16] | [21, 11]   -  [8] | [12, 22]
Birleştirme Aşaması:

[11, 16, 21] - [8, 12, 22]
Birleştirme Aşaması:

[8, 11, 12, 16, 21, 22]


Big-O gösterimini yazınız.
2^x = n   x = log(n)  cevap:O(nlogn)
