---
title: Seaborn Temalı Çizgi Grafiği (Seaborn Line Chart)
categories: [dataanalysis]
comments: true
---

Metin dosyalarından veri okumak için ilk önce bağlantı kurmamız gerekiyor ve bunun için open() fonksiyonunu kullanmaktayız. İlk önce;

    veriBaglantisi = open('veriDosyasi.txt', mode='r')

fonksiyonu ile verilerin olduğu metin dosyası ile bağlantı kurulur. Burada open() bağlantı kurarken 'r' sadece veri okumak için kullanılır. 

```python

# libraries | kütüphaneleri yüklüyoruz.

import matplotlib.pyplot as plt
import numpy as np
import seaborn as sns

# --------------------------------------

# use seaborn style | seaborn temasını kullanıyoruz. 
sns.set_theme()

# --------------------------------------
 
# create data | veri oluşturuyoruz.
values=np.cumsum(np.random.randn(1000,1))

# --------------------------------------
 
# use the plot function | yazıcı fonksiyonunu kullanıyoruz.
plt.plot(values)

# --------------------------------------

# show the graph | grafiği ekrana yazdırıyoruz.
plt.show()

# --------------------------------------

```


![alt text][logo]

[logo]: https://raw.githubusercontent.com/imonur/imonur.github.io/main/_posts/2021-05-20-seaborn-basic-line-chart.png "Basic Line Chart"