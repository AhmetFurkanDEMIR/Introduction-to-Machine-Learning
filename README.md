# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Makine Öğrenmesi Nedir ?

![Makine-Öğrenmesi-Nedir-Ne-İşe-Yarar-Rehber](https://user-images.githubusercontent.com/54184905/85115651-b1379c80-b224-11ea-82d4-305cd13cb08f.jpg)

Makine öğrenimi, bilgisayarların algılayıcı verisi ya da veritabanları gibi veri türlerine dayalı öğrenimini olanaklı kılan algoritmaların tasarım ve geliştirme süreçlerini konu edinen bir bilim dalıdır. Makine öğrenimi araştırmalarının odaklandığı konu bilgisayarlara karmaşık örüntüleri algılama ve veriye dayalı akılcı kararlar verebilme becerisi kazandırmaktır. Bu, makine öğreniminin istatistik, olasılık kuramı, veri madenciliği, örüntü tanıma, yapay zekâ, uyarlamalı denetim ve kuramsal bilgisayar bilimi gibi alanlarla yakından ilintili olduğunu göstermektedir.

* Uygulamaları : Makine öğreniminin başlıca uygulamaları makine algılaması, bilgisayarlı görme, doğal dil işleme, sözdizimsel örüntü tanıma, arama motorları, tıbbi tanı, biyoinformatik, beyin-makine arayüzleri ve kiminformatik, kredi kartı dolandırıcılığı denetimi, borsa çözümlemesi, DNA dizilerinin sınıflandırılması, konuşma ve elyazısı tanıma, bilgisayarlı görmede nesne tanıma, oyun oynama, yazılım mühendisliği, uyarlamalı web siteleri ve robot gezisidir. 

* Öğrenme Yaklaşımları : 
    
    Gözetimli öğrenme - Girdileri hedef çıktılara eşleyen bir işlev üretir.
    
    Gözetimsiz öğrenme - Bir girdi kümesi modeller.
    
    Pekiştirmeli öğrenme - Dünya algısına dayalı bir öğrenme biçimi. Her eylem ortamda bir etki oluşturmakta ve ortam, öğrenme
    algoritmasına yol gösteren ödüller biçiminde dönütler vermektedir.
    
    Yarı gözetimli öğrenme - Uygun işlev ya da sınıflandırıcılar oluşturmak için etiketli ve etiketsiz örnekleri birlikte ele
    alır.
    
![0*NgXCHXv1L4xm7e_L](https://user-images.githubusercontent.com/54184905/85115787-e80db280-b224-11ea-8896-bcd4aea62e56.png)


# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Temel Kavramlar


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Bağımlı Değişken - Bağımsız Değişken

* Bağımlı Değişken : Makine öğrenmesi probleminde tahmin etmek için hedeflediğimiz ana değişkendir(Etiket).

* Bağımsız Değişken : Bağımlı değişkenlerin belirlenmesinde öncü olur. KM, Hasar durumu, Marka, Model gibi.


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Gözetimli - Gözetimsiz Öğrenme

* Gözetimli Öğrenme : Bağımlı değişken ve bağımlı değişkeni meydana getiren bağımsız değişkenler bir aradaysa, bu duruma gözetimli öğrenme denir.(Etiket-Veri)

* Gözetimsiz Öğrenme : Bağımlı değişkenin çalışmanının içinde olmadığı öğrenme türüdür.(Veri var, Etiket yok) Birbirlerine benzer özellikler ile bir araya getirilir.


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Regresyon - Sınıflandırma

* Regresyon : Bağımlı değişken, sayısal/sürekli bir değişken ise bu bir regresyon problemidir.(Ev tahmin problemi(Ev fiyati 150000 TL))

* Sınıflandırma Problemi : Bağımlı değişken kategorik bir değiken ise bu bir sınıflandırma problemidir.(Hastanın yaşayıp yaşayamaması(0,1)) 


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Model Eğitmek: Test - Train

* Elimzideki veri setinin bir kısmını modeli eğitirken kullanırız diğer kısmını ise eğitilen modeli test ederken kullanırız.

![Screenshot_2020-06-19_12-00-26](https://user-images.githubusercontent.com/54184905/85115581-906f4700-b224-11ea-870d-79f0492e43e3.png)


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Değişken Seçimi (Variable Selection)

![Screenshot_2020-06-19_12-05-00](https://user-images.githubusercontent.com/54184905/85115962-3a4ed380-b225-11ea-8d1c-8fc203d77c2a.png)

* Amaç : En az değişkenle en fazla açıklanabilirliği yakalamak


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Model Seçimi

![1*ioZ200iYyX-QJfOLs17gow](https://user-images.githubusercontent.com/54184905/85116427-fd371100-b225-11ea-9a5f-ba867a9babf3.jpeg)

* Oluşabilecek değişken kombinasyonları ile oluşturulan modeller arasından en iyi modelin seçilmesi.

* ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Model neye göre seçilir ? : 

* Regresyon için açıklanabilirlik oran ve RMSE türevi bir değer.

* Sınıflandırma için doğru sınıflandırma oranı türevi bir değer



