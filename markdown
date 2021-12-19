  1. [16,21,11,8,12,22] -> Merge Sort 
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
                   [16,21,11,8,12,22]
            [16,21,11]            [8,12,22]  ->n
           [16]    [21,11]       [8]    [12,22] ->n
           [16]    [21] [11]     [8]    [12] [22] ->n
           [16]    [11,21]       [8]    [12,22]
              [11,16,21]           [8,12,22]  
                       [8,11,12,16,21,22]
  2.Big-O gösterimini yapınız.
2^x=n   -->  x=logn
  O(nlogn)
