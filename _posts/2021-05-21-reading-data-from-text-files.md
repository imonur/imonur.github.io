---
title: Metin Dosyalarından Veri Okuma ( Reading Data from Text Files )
categories: [dataanalysis]
comments: true
---

Metin dosyalarından veri okumak için ilk önce bağlantı kurmamız gerekiyor ve bunun için open() fonksiyonunu kullanmaktayız. İlk önce;

```python

    veriBaglantisi = open('veriDosyasi.txt', mode='r')

```

fonksiyonu ile verilerin olduğu metin dosyası ile bağlantı kurulur. Burada open() bağlantı kurarken 'r' sadece veri okumak için kullanılır. Burada okuma modu ile bağlantı kurulduğu için herhangi bir değişiklik yapılamaz. 




![alt text][logo]

[logo]: https://raw.githubusercontent.com/imonur/imonur.github.io/main/_posts/2021-05-20-seaborn-basic-line-chart.png "Basic Line Chart"