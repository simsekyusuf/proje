Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

SORU  1)Big-O gösterimini yazınız.
CEVAP 1):
  -Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor.
  -İkinci en küçük elemanı buluyor ve 2. sıra ile değiştiriyor. 
  !!! BU İŞLEM SONUÇLANANA KADAR DEVAM EDİYOR.
[22,27,16,2,18,6] n
[2,22,27,16,18,6] n-1
[2,6,22,27,16,18] n-2
[2,6,16,22,27,18] n-3
[2,6,16,18,22,27] 1

Big-O = n + (n-1) + (n-2) + (n-3) +1
Big-O = (n * (n+1) )/ 2
Big-O = (n²)

SORU 2)Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1.Average case: Aradığımız sayının ortada olması
2.Worst case: Aradığımız sayının sonda olması
3.Best case: Aradığımız sayının dizinin en başında olması.

CEVAP 2):
[2,6,16,18,22,27]=1 
-Aradığım sayı ortada olduğu için :
                                    (AVERAGE CASE )



SORU 3)[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
CEVAP 3):
[7,3,5,8,2,9,4,15,6] n
[2,7,3,5,8,9,4,15,6] n-1
[2,3,7,5 ,8,9,4,15,6] n-2
[2,3,4,7,5,8,9,15,6] n-3
[2,3,4,5,7,8,9 ,15,6] n-4



