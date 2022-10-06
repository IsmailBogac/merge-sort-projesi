[16,21,11,8,12,22] -> Merge Sort
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

# merge-sort-projesi![Ekran görüntüsü 2022-10-06 234843](https://user-images.githubusercontent.com/92868619/194416757-7d57528d-7e13-43ed-8615-74db5844e49d.png)

2. Big-O gösterimini yazınız.
Recursive bir fonksiyon olduğu için sürekli kendini çağırarak diziyi hep ikiye bölmektedir. Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından O(n*(logn)) --> O(6*(log6)) olacaktır.
