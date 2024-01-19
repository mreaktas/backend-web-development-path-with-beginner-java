# Merge Sort

#### Soru
```
  [16,21,11,8,12,22] dizinin Merge Sort algoritmasına göre aşamalarını yazınız.
```

#### Cevap
```
Step 1:               [16,21,11]                             [8,12,22]
                    /           \                         /           \
Step 2:          [16,21]    -    [11]                  [8,12]    -    [22]
                /        \             \               /      \            \
Step 3:      [16]    -    [21]    -    [11]        [8]     -    [12]    -    [22]   
                \       /              /             \         /            /
Step 4:          [16,21]    -    [11]                  [8,12]    -    [22]
                     \            /                        \           /
Step 5:                [11,16,21]                            [8,12,22]
                                  
Step 6:                               [8,11,12,16,21,22]
``` 

#### Big-O gösterimini yazınız.

#### Cevap
```
O(nlogn)
```