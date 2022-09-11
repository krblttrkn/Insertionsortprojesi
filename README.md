# Insertion Sort Projesi

# Proje 1
- **[22,27,16,2,18,6]**->Insertion Sort
1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case:Aradığımız sayının ortada olması, Worst case:Aradığımız sayının sonda olması, Best case:Aradığımız sayının dizinin en başında olması. 
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.<br><br>
- **[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk dört adımını yazınız.

# Cevaplar
- **[22,27,16,2,18,6]**->Insertion Sort
1.
    * [2,27,16,22,18,6]
    * [2,6,16,22,18,27]
    * [2,6,16,22,18,27]
    * [2,6,16,18,22,27]
2. Big-O(n²)-->Big-O(6²)-->Big-O(36)  
3. **Time Complexity** 
    *Average Case: 16
    *Worst Case: 27
    *Best Case: 2
4. [2,6,16,18,22,27]
    Dizi sıralandıktan sonra 18 sayısı **Average Case** kapsamına girer.

- **[7,3,5,8,2,9,4,15,6]**
* **[2,3,5,8,7,9,4,15,6]**
* **[2,3,4,8,7,9,5,15,6]**
* **[2,3,4,5,7,9,8,15,6]**
* **[2,3,4,5,6,9,8,15,7]**