# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız

>                                  7  **-> Root**
>                                 / \
>        **Küçük sayı sola  <-** 5   8 **-> Büyük sayı sağa**
>                               / \   \
>                              1   6   9
>                             / \
>                            0   3
>                               / \
>                              2   4

>> Root "7" alındıktan sonra, büyük sayılar sağ tarafa ve küçük sayılar sol tarafa alınır. "8" ve "9" değerleri sağa, "5" değeri sola yazılır. Bir sonraki değer olarak "5" alınır ve aynı işlem uygulanır. "5" için bakıldığında; "1" sola, "6" sağa yazılır. Devamı olarak "1" alınır. "1" için bakıldığında; sol tarafa "0" ve sağ tarafa "3" gelir. Son olarak "3" alınır ve "3" için bakıldığında; sol tarafa "2", sağ tarafa ise "4" gelir. 

