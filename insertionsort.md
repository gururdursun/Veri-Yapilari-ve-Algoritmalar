# Insertion Sort Projesi
### **1.[22,27,16,2,18,6]** 
Önce en küçük eleman bulunur ve ilk elemanla yeri değiştirilir. Geri kalan elemanlar için aynı sıralama işlemleri yapılır. </p>
```
1. [2,27,16,22,18,6]
2. [2,6,16,22,18,27]
3. [2,6,16,18,22,27]
```
### **2.Big O-Notation** 
```
Her sıralama işleminde veri sayısı 1 eksilir. </p>
n veri varsa;</p>
n + (n-1) + (n-2) +.....+ 1 = [(n^2) + n]/2 </p>
Big O-Notation: O(n^2)
```
### **3.Time Complexity**
```
1.  Average Case: O(n) 
2.  Worst case: O(n^2) 
3.  Best case: O(n^2)
```
### **4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?**
```
[2,6,16,18,22,27] --> Average case
```
### **[7,3,5,8,2,9,4,15,6]** Insertion Sort'a göre Sıralama (ilk 4 adım)
```
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6] 
```
