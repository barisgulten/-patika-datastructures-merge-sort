# Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

---

# Solution
## A. Steps
[16,21,11,8,12,22] -> Merge Sort

  1. [16,21,11]  --- [8,12,22]        *** Divide element left and right ***
  2. [16],[21,11] --- [8],[12,22]     *** divide 2
  3. [16], [21], [11]---[8], [12],[22]*** divide 3
  4. [16], [11,21] --- [8], [12,22]   *** Merge started. 
  5. [11,16,21] ---- [8,12,22]        *** merge 2
  6. [8,11,12,16,21,22]               *** Merge completed and sorted. 

## B. Complexity 
O (nlogn)
