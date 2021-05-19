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

[logo]: https://raw.githubusercontent.com/imonur/imonur.github.io/main/_posts/2021-05-19-basic-line-chart.png "Basic Line Chart"
    



```python

<head>
 <meta charset="utf-8">
</head>
 
<table border="0" cellpadding="0" cellspacing="0" width="400">
  <tbody>
    <tr>
      <td border="0" cellpadding="0" cellspacing="0" height="43" width="231">
             <a href="https://www.kukumav.net"><img src="https://www.kukumav.net/images/logo.png" alt="Kukumav.Net Logo"></a><br>
      </td>
    </tr>
    <tr>
      <td height="80" style="font-family:Helvetica, Arial, sans-serif; font-size:18px; font-style:bold;">
        <strong>Enis ÖZTÜRK</strong>
        <br>
        <span style="font-size:17px; font-weight:400;">Dijital Pazarlama Uzmanı</span>
      </td>
    </tr>
	
	 <tr>
      <td height="30" style="font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#4d4d4e;"><strong style="color:#000">Telefon:</strong> 0 (555) 111 22 33
      </td>
    </tr>
	
	 <tr>
      <td class="hover" height="30" style="font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#e0070c;"><strong style="color:#000">Email:</strong>
        <a href="mailto:enisozturk@kukumav.net" onMouseOver="this.style.color='#ff9800'" onMouseOut="this.style.color='#e0070c'" style="color:#e0070c; ">enisozturk[@]kukumav.net</a>
      </td>
    </tr>
	
    <tr>
      <td height="60" style="font-family:Helvetica, Arial, sans-serif; font-size:16px; color:#4d4d4e;"><strong style="color:#000">Adres:</strong>
		Örnek Mah. Deneme Sok. No:1 Kukumav Plaza 34295
        <br> Beşiktaş/İstanbul<br><br>
      </td>
    </tr>
 
    <tr>
      <td height="40">
        <a href="https://www.facebook.com/kukumavnet/" target="_blank"><img src="https://www.kukumav.net/images/icons/sosyal-meyda-iconlari/facebook.png" alt="Facebook Icon"></a>
       <a href="https://twitter.com/KukumavNet" target="_blank"><img src="https://www.kukumav.net/images/icons/sosyal-meyda-iconlari/twitter.png" alt="Twitter İcon"></a>
       <a href="https://www.instagram.com/kukumavnet//" target="_blank"><img src="https://www.kukumav.net/images/icons/sosyal-meyda-iconlari/instagram.png" alt="Instagram Icon"></a>
	   <a href="https://www.linkedin.com/company/kukumavnet/" target="_blank"><img src="https://www.kukumav.net/images/icons/sosyal-meyda-iconlari/linkedin.png" alt="Linkedin Icon"></a>
	   <a href="https://www.youtube.com/channel/UCkscrRaIP5huAIsdXAfgF4Q" target="_blank"><img src="https://www.kukumav.net/images/icons/sosyal-meyda-iconlari/youtube.png" alt="Youtube Icon"></a>
      </td>
    </tr>
    <tr>
      <td height="40">
        <small style="font-family:Helvetica, Arial, sans-serif; font-size:10px; color:#4d4d4e;">Bilgilendirme: Bu mesajı yazdırmadan önce çevreye verebileceğiniz zararları bir kez daha düşününüz.</small>
      </td>
    </tr>
  </tbody>
</table>
```
