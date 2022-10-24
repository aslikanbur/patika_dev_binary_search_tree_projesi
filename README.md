# patika_dev_binary_search_tree_projesi

Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Root ilk eleman olan 7 olarak seçilir. Root değerinden daha küçük olanlar sola, büyük olanlar sağa yazılır.
- (5), 7'den küçük olduğu için sola yazılır.
- (1), 7'den küçüktür. Aynı zamanda 5'ten de küçüktür. 5'in soluna yazılır.
- (8), 7'den büyüktür. Sağa yazılır.
- (3), 7'den ve 5'ten küçüktür ancak 1'den büyüktür. 1'in sağına yazılır.
- (6), 7'den küçük, 5'ten büyüktür. 5'in sağına yazılır.
- (0), 7'den, 5'ten ve 1'den küçüktür. 1'in soluna yazılır.
- (9), 7'den ve 8'den büyüktür. 8'in sağına yazılır.
- (4), 7'den ve 5'ten küçüktür ancak 1'den ve 3'ten büyüktür. 3'ün sağına yazılır.
- (2), 7'den, 5'ten küçüktür ancak 1'den büyük ve 3'ten küçüktür. 3'ün soluna yazılır.

                      7
                     / \
                    5   8
                   / \   \
                  1   6   9
                 / \
                0  3
                  / \
                 2   4
       
       
   www.patika.dev
