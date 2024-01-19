# Selection/Insertion Sort Örneği

### Insertion Sort

#### Örnek

```` 
    [22,27,16,2,18,6] dizinin Insertion Sort algoritmasına göre aşamalarını yazınız.
````

#### Cevap
````
   Step 1: [22,27,16,2,18,6] //22, 27'den küçük olduğu için hiç bir sıralama yapılmadı
   Step 2: [16,22,27,2,18,6] //16, 22’nin önüne taşınır
   Step 3: [2,16,22,27,18,6] //2, dizinin başına taşınır
   Step 4: [2,16,18,22,27,6] //18, 22’nin önüne taşınır
   Step 5: [2,6,16,18,22,27] //6, 16’nın önüne taşınır
````

##### Big-O gösterimini yazınız.

#### Cevap
```   
    O(n^2)
```
    

##### Time Comlexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
    1. Average Case: Aranan sayının ortada olması
    2. Worst Case: Aranan sayının sonda olması
    3. Best Case: Aranan sayının dizinin en başında olması

#### Cevap
```
    Average Case (Aranan sayı ortalarda bulunduğundan dolayı)
```

### Selection Sort

#### Örnek

````
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort algoritmasına göre ilk 4 adımını yazınız.
````

#### Cevap
````
    Step 1: [2,3,5,8,7,9,4,15,6] //İlk adımda en küçük eleman 2'dir. Bu eleman, dizinin ilk elemanıyla yer değiştirecek.
    Step 2: [2,3,5,8,7,9,4,15,6] //İkinci adımda en küçük eleman 3'tür. Bu eleman, dizinin ikinci elemanıyla yer değiştirecek.
    Step 3: [2,3,4,8,7,9,5,15,6] //Üçüncü adımda en küçük eleman 4'tür. Bu eleman, dizinin üçüncü elemanıyla yer değiştirecek.
    Step 4: [2,3,4,5,7,9,8,15,6] //Dördüncü adımda en küçük eleman 5'tir. Bu eleman, dizinin dördüncü elemanıyla yer değiştirecek.
````