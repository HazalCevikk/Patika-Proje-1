# Veri Yapıları ve Algoritmalar - İnsertion Sort Projesi :v:
## 1. Problem
**Insertion Sort;**
[22,27,16,2,18,6] dizinin sort türüne göre aşamalarını yazınız.

```
1. [2,27,16,22,18,6]
2. [2,6,16,22,18,27]
3. [2,6,16,22,18,27]  ---> 16 doğru sırada olduğundan yeri değişmeyecektir.
4. [2,6,16,18,22,27]  ---> 18'den sonra sıralanmayan iki değer de sorgulandığında doğru olduklarından yerleri değişmeyecektir.
```
**Big-O Gösterimi;**
```
n+(n-1)+(n-2)+...+1 den O(n^2) olur.
```
**Time Complexity;**
- **Average case:** Aradığımız sayının ortada olması
- **Worst case:** Aradığımız sayının sonda olması
- **Best case:** Aradığımız sayının dizinin en başında olması.
```
Average case: n/2 den 3-4 işlem,
Worst case: n kadar işlem 6,
Best case : 1 işlem,
```
**Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?**
```
18'in dizinin ortasında yer aldığından cevap average case olacaktır.
```
## 2. Problem
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6] ---> dizinin ikinci elemanı doğru olduğu için değişiklik olmayacaktır.
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]
5. [2,3,4,5,6,9,8,15,7]
6. [2,3,4,5,6,7,8,15,9] 
7. [2,3,4,5,6,7,8,15,9] ---> 7'den sonraki eleman 8 olduğundan dizi değişmeyecektir.
8. [2,3,4,5,6,7,8,9,15] 
```
