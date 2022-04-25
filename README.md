# Insertion Sort Project

> [22, 27, 16, 2, 18, 6]

1. Dizinin elemanları tek tek incelenir ve en küçüğü başa yazılır.
2. Önceden ilk sırada olan eleman en küçük sayının yerine geçer.
3. İlk eleman belirlendi, 2. en küçük olanı bulmak için sayılar tek tek incelenir.
4. En küçük olan 2.sıraya yazılır ve ikinci sıradaki ise yerine geçen sayının yerine geçer.
5. Bu aşamalar sıralama gerçekleşene kadar devam eder.

# Big O notation
N sayı var ve her defasında 1 eksilerek
>n + (n-1) + (n-2) + (n-3) ... +1

>Birden n'ye kadar olan sayıların toplamı: n.(n+1)/2

### Domine edeni alıyoruz n^2. Dolayısıyla **O(n^2)**

## Time Complexity
[2, 6, 16, 18, 22, 27] aranılan sayı 18 dizinin ortasında bulunuyor. Dolayısıyla Average case.

> [7, 3, 5, 8, 2, 9, 4, 15, 6]
1. [2, 3, 5, 8, 7, 9, 4, 15, 6]
2. [2, 3, 5, 8, 7, 9, 4, 15, 6]
3. [2, 3, 4, 8, 7, 9, 5, 15, 6]
4. [2, 3, 4, 5, 7, 9, 8, 15, 6]