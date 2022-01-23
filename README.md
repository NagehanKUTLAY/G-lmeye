# G-lmeye
Python-Döngüler

For Döngüsü: Aynı işi birden fazla kez yapman gerektiğinde kullanırsın.
Range Kullanımı: Başlangıç ve bitiş değeri belli olan durumlarda kullanılır.
Örnek:
for sayilar in range(10):
 print(sayilar)

  Ekran Çıktısı:
  0
  1
  2
  3
  4
  5
  6
  7
  8
  9

Örnek:
for sayilar in range(10):
  print(sayilar)
  
  Ekran Çıktısı:
  0
  1
  2
  3
  4
  5
  6
  7
  8
  9
  
  Örnek:
  for sayilar in range(5,20,3):
    print(sayilar)
    
    Ekran Çıktısı:
    5
    8
    11
    14
    17
    
Örnek:
for sayilar in range (20,5,-3):
  print(sayilar)

  Ekran Çıktısı:
  20
  17
  14
  11

Önemli Not: Toplama işleminde 0 etkisiz eleman olduğu için başlangıçta toplam değişkenine 0 atanır. Çarpma işleminde ise 1 etkisiz eleman olduğu için başlangıçta çarpım değişkenine 1 atanır.
Örnek:
for döngüsü ile 1'den 10'a kadar olan sayıların toplamını bulun.
  Çözüm:
  toplam=0
  for sayilar in range(11):
    toplam=toplam+sayilar
  print("Sayiların toplamı=",toplam)
  
   Çıktı
   Sayıların toplamı=55

in kullanımı: Bir elemanın listede olup olmadığını kontrol eder. For döngüsü ile kullanımı şu şekildedir;
meyveler=("çilek","muz","şeftali")
for meyve in meyveler:
  print(meyve)
  
  Çıktı:
  çilek
  muz
  şeftali

NOTE: "in" operatörü metinsel(string) ifadeleri de harf harf ekrana yazdırabilir.

Örnek:
for harfler in "Döngü":
  print(harfler)
  
   Çıktı:
   D
   ö
   n
   g
   ü

