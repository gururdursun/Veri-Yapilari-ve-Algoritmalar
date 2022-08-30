# Binary Search Tree
### **[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** </p>
root: 7 </p>

1.adım: 5 elemanı 7'den küçük olduğu için solunda yer alır. 
```
    
                         7
                        /   
                       5
```
    


2.adım: 1 elemanı 7'den küçük olduğu için sağ tarafa yazılmaz. 5'ten de küçük olduğu için 5'in soluna yazılır.
```
                         7
                        / 
                       5
                      /
                     1
```


3.adım: 8 elemanı 7'den büyük olduğu için 7'nin sağında yer alır.
```
                        7
                       / \
                      5   8
                     /
                    1    
```
4.adım: 3 elemanı 7'den küçük olduğu için ağacın sol tarafından ilerlenir. 5'ten de küçük olduğu için 1 ile karşılaştırılır. 1'den büyük olduğu için 1'in sağına yazılır.
```  
                        7
                       / \
                      5   8
                     /
                    1
                     \
                      3    
```
5.adım: 6 elemanı 7'den küçük olduğu için ağacın sol tarafından ilerlenir. 5'ten büyük olduğu için 5'in sağına yazılır.
```
                        7
                       / \
                      5   8
                     / \
                    1   6
                     \
                      3   
```
6.adım: 0 elemanı 7'den küçük olduğu için ağacın solundaki değerlerle karşılaştırılır. En soldaki 1'den de küçük olduğu için 1'in solunda yer alır.
```
                        7
                       / \
                      5   8
                     / \
                    1   6
                   / \
                  0   3 
```
7.adım: 9 elemanı 7'den büyük olduğu için ağacın sağındaki değerlerle karşılaştırılır. 8'den de büyük olduğundan 8'in sağında yer alır.
```
                        7
                       / \
                      5   8
                     / \   \
                    1   6   9
                   / \
                  0   3
```
8.adım: 4 elemanı 7'den küçük olduğu için sırasıyla ağacın sol tarafındaki elemanlarla karşılaştırılır. 5'ten küçük olduğu için solundaki 1'le karşılaştırılır. 1'den büyük olduğu için sağındaki 3 değeriyle karşılaştırılır. 3'ten büyük olduğu için sağına yazılır.
```
                        7
                       / \
                      5   8
                     / \   \
                    1   6   9
                   / \
                  0   3
                       \
                        4
```
9.adım: 2 elemanı 7'den küçük olduğu için sırasıyla ağacın sol tarafındaki elemanlarla karşılaştırılır. 5'ten küçük olduğu için solundaki 1'le karşılaştırılır. 1'den büyük olduğu için sağındaki 3 değeriyle karşılaştırılır. 3'ten küçük olduğu için soluna yazılır.
```
                        7
                       / \
                      5   8
                     / \   \
                    1   6   9
                   / \
                  0   3
                     / \
                    2   4
```
