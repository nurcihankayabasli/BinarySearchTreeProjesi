# Binary-Search-Tree-Projesi
## Proje 3
- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
- Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1. Root 7'dir.
2. 5 rakamı 7'den küçük olduğu için root'un sol tarafında bulunur .              

             7
            /
           5
    
3. 1 rakamı 7'den ve 5'ten küçük olduğu için 5'in sol tarafında bulunur. 

             7
            /
           5
          /
         1
         
4. 8 rakamı 7'den büyük olduğu için 7'nin sağ tarafında bulunur.

               7
              / \
             5 8
            /
          1
          
5. 3 rakamı 7'den ve 5'ten küçük; 1'den büyük olduğu için 1'in sağ tarafında bulunur.

              7
             / \
            5 8
           /
          1
           \
             3
            
6. 6 rakamı 7'den küçük 5'den büyük olduğu için 5'in sağ tarafında bulunur.

               7
              / \
             5 8
            / \
           1 6
           \
             3
            
7. 0 tüm rakamlardan küçük olduğu için kendinden önceki en küçük rakam olan 1'in sol tarafında bulunur.

               7
              / \
             5 8
            / \
           1 6
          / \
         0 3
        
8. 9 tüm rakamlardan büyük olduğu için kendinden önceki en büyük rakam olan 8'in sağ tarafında bulunur.

                7
               / \
              5 8
             / \    \
            1 6 9
           / \
          0 3
         
9. 4 rakamı 7 ve 5'ten küçük; 1 ve 3'ten büyük olduğu için 3'ün sağ tarafında bulunur.
         
                 7
                / \
               5 8
              / \     \
             1 6 9
            / \
           0 3
                \
                 4
                
10. 2 rakamı 7 ve 5'ten küçük; 1'den büyük ve 3'ten küçük olduğu için 3'ün sol tarafında bulunur.

                   7
                  / \
                 5 8
                / \    \
               1 6 9
              / \
             0 3
                 / \
                2 4
                
       (https://app.patika.dev/)
                
