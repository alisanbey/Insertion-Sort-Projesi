# Insertion Sort Projesi
1. [22,27,16,2,18,6] -> Insertion Sort
```
[22,27,16,2,18,6] n
[16,22,27,2,18,6] n-1
[2,16,22,27,18,6] n-2 
[2,16,22,27,18,6] n-3
[2,16,18,22,27,6] n-4
[2,6,16,18,22,27] n-5
```
2. Big-O
````
n+(n-1)+(n-2)+(n-3)+....+1=n!
n!= n*(n+1)/2 = (n²+n)/2
O(n²) 
````
3. Time Complexity
```
* Average Case "aradigimiz sayinin dizinin ortasinda olmasi"
* Worst Case "dizinin buyukten kucuge sirali gelmesi"
    [27,22,18,16,6,2] O(n²)
* Best Case "dizinin kucukten buyuge sirali gelmesi"
    [2,6,16,18,22,27] O(n)
```
4. Dizi siralandiktan sonra **[2,6,16,18,22,27]** 18 sayisi ortada bulundugundan "Avaraage Case" 

5. [7,3,5,8,2,9,4,15,6] -> insertion Sort

```
1. [3,7,5,8,2,9,4,15,6]
2. [3,5,7,8,2,9,4,15,6]
3. [2,3,5,7,8,9,4,15,6]
4. [2,3,4,5,7,8,9,15,6]
````