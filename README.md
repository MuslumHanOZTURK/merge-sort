Merge Sort Projesi
[16,21,11,8,12,22]

Yukarıdaki dizinin merge sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Merge Sort Projesi Cevap
[16,21,11,8,12,22]

Yukarıdaki dizinin merge sort türüne göre aşamalarını yazınız.

![merge](https://user-images.githubusercontent.com/93899998/189490666-0898788d-03dc-40ad-880f-e88db434bf3b.PNG)




Big-O gösterimini yazınız.

Cevap: Recursive(özyinelemeli) bir fonks. olduğu için tekrarlı bir şekilde kendini çağırarak diziyi hep ikiye bölmektedir. Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından O(n*(logn)) --> O(6*(log6)) olacaktır.
