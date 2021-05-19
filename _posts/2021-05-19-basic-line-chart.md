---
title: Çizgi Grafik (Line Plot)
categories: [visualization]
comments: true
---

Python'da Matplotlib kitaplığını kullanarak basit ve hızlı bir şekilde çizgi grafikleri oluşturabilirsiniz. Bunun için gerekli kütüphaneleri yükledikten sonra veri setini oluşturmanız gerekiyor. Verisetinde verilen veriler X ekseninde ( Yatay ekseninde ) sıralı bir şekilde listelenir. 

```python

# libraries | kütüphaneleri yüklüyoruz.

import matplotlib.pyplot as plt
import numpy as np

# --------------------------------------
 
# create data | veri oluşturuyoruz.
values=np.cumsum(np.random.randn(8,10))

# --------------------------------------
 
# use the plot function | yazıcı fonksiyonunu kullanıyoruz.
plt.plot(values)

# --------------------------------------

# show the graph | grafiği ekrana yazdırıyoruz.
plt.show()

# --------------------------------------

```


![alt text][logo]

[logo]: https://raw.githubusercontent.com/imonur/imonur.github.io/main/_posts/2021-05-16-datavisualization.png "Logo Title Text 2"
    



```python

```
