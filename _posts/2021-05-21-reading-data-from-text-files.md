---
title: Metin Dosyalarından Veri Okuma ( Reading Data from Text Files )
categories: [DataAnalysis]
comments: true
---

Metin dosyalarından veri okumak için ilk önce bağlantı kurmamız gerekiyor ve bunun için open() fonksiyonunu kullanmaktayız. İlk önce;

```python

    veriBaglantisi = open('C:/Users/kullaniciadi/Desktop/veriDosyasi.txt', mode='r')

```

fonksiyonu ile verilerin olduğu metin dosyası ile bağlantı kurulur. Burada open() bağlantı kurarken 'r' sadece veri okumak için kullanılır. Burada okuma modu ile bağlantı kurulduğu için herhangi bir değişiklik yapılamaz. Eğer mode olarak 'w' (Write) seçilmiş olsaydı o zaman bu dosya üzerinde değişiklik yapılabilirdi. Burada ki bağlantı dosyasının bulunduğu dizin yolu doğru verilmez ise bağlantı hatası oluşacaktır. Bunun için dosyanın bulunduğu dizin yolu tam olarak verilmelidir. Metin dosyasından veri okumak için örnek bir kod bloğu;

```python

    veriBaglantisi = open('C:/Users/kullaniciadi/Desktop/veriDosyasi.txt', mode='r') # Metin dosyası ile bağlantı kuruldu.
    veri = veriBaglantisi.read() # Bağlantı kurduktan sonra verilerimizi okuyoruz. 
    veriBaglantisi.close() # Bağlantıyı kapatıyoruz.
    print(veri)  # Okunan verileri ekrana yazdırıyoruz.

```



![alt text][logo]

[logo]: https://raw.githubusercontent.com/imonur/imonur.github.io/main/_posts/2021-05-20-seaborn-basic-line-chart.png "Basic Line Chart"