*** Soru 3) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. ***

             7      
            / \
           5   8     
          / \   \
         1   6   9   
        / \
       0   3
          / \
         2   4


 - *İlk olarak root 7 seçilir.*
 - *İkinci adımda; 5 sayısı 7'den küçük olduğu için 7'nin soluna yazılır.*
 - *Üçüncü adımda; 1 sayısı hem 7'den hem de 5'ten küçük olduğu için 5'in soluna yazılır.*
 - *Dördüncü adımda; 8 sayısı 7'den büyük olduğu için 7'nin sağına yazılır.*
 - *Beşinci adımda; 3 sayısı 7'den küçük, 5'ten küçük ancak 1'den büyük olduğu için 1'in sağına yazılır.*
 - *Altıncı adımda; 6 sayısı 7'den küçük 5'ten büyük olduğu için 5'in sağına yazılır.*
 - *Yedinci adımda 0 sayısı 7'den, 5'ten, 1'den küçük olduğu için 1'in soluna yazılır.*
 - *Sekizinci adımda 9 sayısı 7'den ve 8'den büyük olduğu için 8'in sağına yazılır.*
 - *Dokuzuncu adımda 4 sayısı 7'den küçük, 5'ten küçük, 1'den büyük, 3'ten büyük olduğu için 3'ün sağına yazılır.*
 - *Onuncu adımda 2 sayısı 7'den küçük, 5'ten küçük, 1'den büyük, 3'ten küçük olduğu için 3'ün soluna yazılır.*