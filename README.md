# İnsertion Sort
[22,27,16,2,18,6] 

**soru:**
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

**cevap:** 

En küçük eleman bulunur ve ilk elemanla yeri değiştirilir. Her adım da bir diğer eleman geçerek aynı işlem sıralama doğru olana kadar uygulanır.

[2|27,16,22,18,6]

[2,6|16,22,18,27]

[2,6,16|22,18,27]

[2,6,16,18|22,27]

[2,6,16,18,22,27]

**soru:**
Big-O gösterimini yazınız.

**cevap:** 

[n(n+1)]/2 = (n^2+n)/2 

Big O Notation : O(n^2)

**soru:**
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

**cevap:**
1. **Average case: Aradığımız sayının ortada olması**(18 sayısı bu kısma girer)

2. Worst case: Aradığımız sayının sonda olması

3. Best case: Aradığımız sayının dizinin en başında olması.

**soru:**
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

**cevap:**

[2|3,5,8,7,9,4,15,6]

[2,3|5,8,7,9,4,15,6]

[2,3,4|7,9,5,15,6]

[2,3,4,5,7,9,8,15,6]