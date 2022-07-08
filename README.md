# Insertion Sort Projesi
**Patika.dev Profilim: https://app.patika.dev/senaeser**
# Soru 1
[22,27,16,2,18,6] -> Insertion Sort

Verilen dizinin sort türüne göre aşamaları:
1. [22,27,16,2,18,6]
2. [**2**,27,16,**22**,18,6]
3. [2,**6**,16,22,18,**27**]
4. [2,6,**16**,22,18,27] ==> **Bu aşamada 16 sayısından daha küçük bir sayı yer almadığı için yer değişimi olmaz**
5. [2,6,16,**18**,**22**,27]
6. [2,6,16,18,22,27] ==> **Bu aşamada dizi sıralanmış olup bitmiştir.
# Soru 2
[22,27,16,2,18,6] -> Insertion Sort

Big-O gösterimi: 

(n.(n+1))/2 'den ==> O(n²) 
# Soru 3
Time Complexity: 
- Average Case : O(n^2)
- Worst Case: O(n^2)
- Best Case : O(n)
# Soru 4
18 sayısı sıralama işlemlerinden sonra;
**dizinin orta kısımlarına denk geleceği için *Average Case* kapsamına girer.**
#
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[**2**,3,5,8,**7**,9,4,15,6]
[2,**3**,5,8,7,9,4,15,6]
[2,3,**4**,8,7,9,**5**,15,6]
[2,3,**4**,**5**,7,9,**8**,15,6]
