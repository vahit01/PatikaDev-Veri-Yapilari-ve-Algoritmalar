# **Insertion Sort Projesi** 
## *Soru 1* 
[22,27,16,2,18,6] -> Insertion Sort
- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
## *Cevap 1*

- [22,27,16,2,18,6] -> Insertion Sort

* [22,27,**16**,2,18,6]
* [22,**16**,27,2,18,6]
* [**16**,22,27,2,18,6]
***
* [16,22,27,**2**,18,6]
* [16,22,**2**,27,18,6]
* [16,**2**,22,27,18,6]
* [**2**,16,22,27,18,6]
***
* [2,16,22,27,**18**,6]
* [2,16,22,**18**,27,6]
* [2,16,**18**,22,27,6]
***
* [2,16,18,22,27,**6**]
* [2,16,18,22,**6**,27]
* [2,16,18,**6**,22,27]
* [2,16,**6**,18,22,27]
* [2,**6**,16,18,22,27]
***
* **[2,6,16,18,22,27]**
***
- Big-O Notation
```
Big-O(n²)
```
***
- Time Compilexity
```
Avarage case: O(n²)
Worst case: O(n²)
Best case: O(n)
```
***
- [22,27,16,2,18,6] dizisi [2,6,16,18,22,27] olarak sıralanır. 18 sayısı *avarage case* kapsamına girer.
## *Soru 2*
- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
## *Cevap 2*
* [7,**3**,5,8,2,9,4,15,6]
* [**3**,7,5,8,2,9,4,15,6]
***
* [3,7,**5**,8,2,9,4,15,6]
* [3,**5**,7,8,2,9,4,15,6]
***
* [3,5,7,8,**2**,9,4,15,6]
* [3,5,7,**2**,8,9,4,15,6]
* [3,5,**2**,7,8,9,4,15,6]
* [3,**2**,5,7,8,9,4,15,6]
* [**2**,3,5,7,8,9,4,15,6]
***
* [2,3,5,7,8,9,**4**,15,6]
* [2,3,5,7,8,**4**,9,15,6]
* [2,3,5,7,**4**,8,9,15,6]
* [2,3,5,**4**,7,8,9,15,6]
* [2,3,**4**,5,7,8,9,15,6]
