
  

# Patika Dev Binary Search Three Projesi

  

  

Bu Repo [Kodluyoruz](https://www.kodluyoruz.org/) Front-End Eğitiminde oluşturdu.

  

  

# Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

  

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

  

# Çözüm
  * Root 7'dir.

    * Aşama 1:

        * 5 < 7 (5, 7den küçük olduğu için sola yazılır)

                         7
                        /
                       5

    * Aşama 2:

        * 1 < 7 , 1 < 5 (1, 7 ve 5 den küçük olduğu için sola yazılır)

                         7
                        /
                       5
                      /
                     1

    * Aşama 3:

        * 8 > 7 (8, 7den büyük olduğu için sağa yazılır)

                         7
                        / \
                       5   8
                      /
                     1

    * Aşama 4:

        * 3 < 7 , 3 < 5 , 3 > 1 

                         7
                        / \
                       5   8
                      /
                     1
                      \
                       3

    * Aşama 5:

        * 6 < 7 , 6 > 5
        
                        7
                       / \
                      5   8
                     / \
                    1   6
                     \
                      3                           

    * Aşama 6:

        * 0 < 7 , 0 < 5 , 0 < 1
        
                         7
                        / \
                       5   8
                      / \
                     1   6
                    / \
                   0   3 

    * Aşama 7:

        * 9 > 7 , 9 > 8
        
                         7
                        / \
                       5   8
                      / \   \
                     1   6   9
                    / \
                   0   3

    * Aşama 8:

        * 4 < 7 , 4 < 5 , 4 > 1 , 4 > 3 
        
                         7
                        / \
                       5   8
                      / \   \
                     1   6   9
                    / \
                   0   3                            
                        \
                         4

    * Aşama 9:

        * 2 < 7 , 2 < 5 , 2 > 1 , 2 < 3        
        
                         7
                        / \
                       5   8
                      / \   \
                     1   6   9
                    / \
                   0   3                            
                      / \
                     2   4



  

# Installation

  

  

Öncelikle projeyi clonelayın.

  

  

https://github.com/yucel-aydin/Patika-Binary-Search-Tree-Projesi.git

  

  

# Usage

  

Projeyi cloneladıktan sonra Visual Studio Code programında açınız.

  

  

Linux için;

  

  

Patika-Binary-Search-Tree-Projesi

  

code .

  

  

# Contributing

  

Pull requestler kabul edilir. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğiniz tartışmak için bir konu açınız.

  

# Licence

  

[MIT](https://choosealicense.com/licenses/mit/)

  

  

# Patika.dev Profil

  

[Hesabım](https://app.patika.dev/yck)