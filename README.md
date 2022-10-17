## Binary Search Tree Projesi

Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Burada root=6 olarak belirledim.

>                            6
>                          /   
>                         5     
a-) burada 5 sayısı 6 sayısından küçük olduğu için 6 sayısının soluna eklendi.

>                            6
>                          /   
>                         5     
>                        /
>                       1
b-) burada 1 sayısı 6 ve 5 den küçük olduğu için 5 sayısının sol tarafına doğru eklenir.


>                            6
>                          /   \
>                         5     8
>                        /
>                       1
c-) burada 8 sayısı 6 sayısından büyük olduğu için sağ tarafına eklendi.

>                            6
>                          /   \
>                         5     8
>                        /
>                       1
>                         \
>                           3
d-) burada 3 sayısı 6 dan küçük olduğu için sol tarafa , sol tarafta da 5 ten küçük olduğu için 1 e bakılır , 1 den büyük olduğu için de 1 in sağına yazılır.

>                            6
>                          /   \
>                         5     8
>                        /
>                       1
>                     /   \
>                    0      3
e-) burada 0 sayısı 6 dan küçük sola , sol tarafta da 1 den küçük olduğu için 1 in de soluna yazılır.

>                            6
>                          /   \
>                         5     8
>                        /        \
>                       1          9
>                     /   \
>                    0      3
f-) burada 9 sayısı 6 dan büyük olduğu için 6 nın sağına 8 den de büyük olduğu için 8 sayısının da sağına yazılır.

>                            6
>                          /   \
>                         5     8
>                        /        \
>                       1           9
>                     /   \
>                    0      3
>                             \
>                               4

g-) burada 4 sayısı 6 dan küçük olduğu için 6 nın soluna burada da 5 ten küçük 3 ten büyük olduğu için 3 ün sağına yazılır.

>                            6
>                          /   \
>                         5     8
>                        /        \
>                       1           9
>                     /   \
>                    0      3
>                         /   \
>                       2       4
h-) burada 2 sayısı 6 dan küçük olduğu için 6 nın soluna burada da 1 den büyük 3 ten küçük olduğu için 3 ün soluna yazılır. Ve son halini alır.