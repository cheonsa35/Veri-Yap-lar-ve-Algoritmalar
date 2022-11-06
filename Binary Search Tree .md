# Veri-Yap-lar-ve-Algoritmalar
Binary Search Tree Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizininin Binary-Search-Tree aşamalarını yazınız.

Örnek: kök x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

İkili Arama Ağacı sağ ve sol olarak adayk sağ tarafta x'ten elemanlar, sol tarafta x'ten küçük elemanlar olacak şekilde hazırlık ve bu şekilde ilerler. Burada x adında root denir ve root'u bu dizi için 7 seçiyoruz.

5 ve 8 rakamlarını yerleştiriyoruz. 5, 7'den küçük olduğu için sol tarafta 8 ise 7'den büyük olduğu için sağ tarafta yer alır. Daha sonra 5 için, 1 ve 6'yı aynı şekilde yerleştiriyoruz. Dizideki 8'den tek büyük sayı 9 olduğu için onu da 8'in uygun şekilde yerleştirildikten sonra 7'nin sağ parçası ile bir eski moda.

1 küçük küçük olduğu için 0, 1'in altında ve solda; 3 ise 1'den büyük olduğu için sağ tarafa eklenir. 2 sayı 1'den büyük, 3'ten azaldı. Bu yol 3'ün solu alan yer aldı. 4 ise 3'ten büyük olduğu için sağ tarafa yerleştirip binary search tree'yi tamamladık. Son hali;

                                                7
                                              /   \ 
                                            5      8
                                          /   \     \
                                         1     6     9
                                        /  \
                                       0    3
                                           /  \
                                          2    4
