---
title: Seaborn Temalı Çizgi Grafiği (Seaborn Line Chart)
categories: [visualization]
comments: true
---

Seaborn kütüphanesi, Matplotlib destekli bir veri görselleştirme kütüphanesidir. İstatiksel verileri görselleştirmek için kullanmaktayız. Python'da Seaborn kütüphanesi kullanarak farklı temalarda grafikler  oluşturabiliriz.

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