---
title: Covid19 Verilerinin Zaman Serileri ( Time Series Covid19 Confirmed )
categories: [python]
comments: true
---
Metin dosyalarından veri okumak için ilk önce bağlantı kurmamız gerekiyor ve bunun için open() fonksiyonunu kullanmaktayız. İlk önce;

```python

    veriBaglantisi = open('veriDosyasi.txt', mode='r')

```

fonksiyonu ile verilerin olduğu metin dosyası ile bağlantı kurulur. Burada open() bağlantı kurarken 'r' sadece veri okumak için kullanılır. Burada okuma modu ile bağlantı kurulduğu için herhangi bir değişiklik yapılamaz. Eğer mode olarak 'w' (Write) seçilmiş olsaydı o zaman bu dosya üzerinde değişiklik yapılabilirdi. Burada ki bağlantı dosyasının bulunduğu dizin yolu doğru verilmez ise bağlantı hatası oluşacaktır. Bunun için dosyanın bulunduğu dizin yolu tam olarak verilmelidir. Metin dosyasından veri okumak için örnek bir kod bloğu;

```python

    veriBaglantisi = open('C:/Users/kullaniciadi/Desktop/veriDosyasi.txt', mode='r') # Metin dosyası ile bağlantı kuruldu.
    veri = veriBaglantisi.read() # Bağlantı kurduktan sonra verilerimizi okuyoruz. 
    veriBaglantisi.close() # Bağlantıyı kapatıyoruz.
    print(veri)  # Okunan verileri ekrana yazdırıyoruz.

```

Python yazılımında veri okumak için read() metodunu kullanmaktayız. Bağlantı kurduktan sonra verileri okurken **with** fonksiyonunu kullanırsak eğer **close()** fonksiyonunu kullanmamıza gerek kalmaz. Bunun için şu şekilde bir yapı kullanırız.

```python

with open('D:\\Masaüstü\\veriDosyasi.txt', mode='r') as veriBaglantisi:
    print(veriBaglantisi.read())  # Okunan verileri ekrana yazdırıyoruz.


```
Eğer dosya boyutu büyük ise o zaman **read()** metodu yerine **readline()** metodunu kullanıyoruz. Bu metot, verileri satır satır okumamızı sağlıyor. Eğer **readline()** metodunu kullanırsak ilk satırı alacak ve ekrana yazacktır. Ancak **readlines()** metodunu kullanırsak ekrana yazıları her satırı tırnak '' içerisinde yazacktır. Burada alt satıra geçilirken verilen boşluk **\n** ile ifade edilerek veriler tek satırda yazılacaktır.

```python

with open('D:\\Masaüstü\\veriDosyasi.txt', mode='r') as veriBaglantisi:
    print(veriBaglantisi.readlines())  # Okunan verileri ekrana yazdırıyoruz.


```
