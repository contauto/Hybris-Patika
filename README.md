
# Hybris-Patika

Bu proje SAP Hybris'te değiştirilen bazı dosyaları içermektedir.


## Adımlar

### Part 1

- core-items.xml dosyasına birer boolean ve Integer alanlar eklenir.

![quickShipment](https://iili.io/Hnctgyb.png)

![howMany](https://iili.io/HnctSae.png)

- ``ant all`` komutu kullanılır ardından Products sayfasına gidilir, yeni eklenen alanların sayfaya geldiği görülür.

![Products](https://iili.io/Hnct4uj.png)

- Facet kısmına girilir, indexlenen ürünlere quickShipment alanının eklemesi yapılır.

![Facet](https://iili.io/Hnct8F9.png)

- Indexlenmesi için boolean başka bir alanın value providerı verilir.

![Value Provider](https://iili.io/Hnct6wx.png)

- Eklediğimiz yeni boolean alanın indexlendiği Solr ekranından görüntülenir.

![Solr](https://iili.io/HnctQ6P.png)
--------------------------------------------------------------------------------------------------------

### Part 2

- ProductDao'ya metot imzası yazılır.

![ProductDao](https://iili.io/HnctsnV.png)


- Onun service dosyası olan DefaultProductDao'da metodun implementasyonu yapılır.

![DefaultProductDao](https://iili.io/HnctLMB.png)
