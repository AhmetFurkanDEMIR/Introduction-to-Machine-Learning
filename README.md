# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Makine Öğrenmesi Nedir ?

![Makine-Öğrenmesi-Nedir-Ne-İşe-Yarar-Rehber](https://user-images.githubusercontent.com/54184905/85115651-b1379c80-b224-11ea-82d4-305cd13cb08f.jpg)

Makine öğrenimi, bilgisayarların algılayıcı verisi ya da veritabanları gibi veri türlerine dayalı öğrenimini olanaklı kılan algoritmaların tasarım ve geliştirme süreçlerini konu edinen bir bilim dalıdır. Makine öğrenimi araştırmalarının odaklandığı konu bilgisayarlara karmaşık örüntüleri algılama ve veriye dayalı akılcı kararlar verebilme becerisi kazandırmaktır. Bu, makine öğreniminin istatistik, olasılık kuramı, veri madenciliği, örüntü tanıma, yapay zekâ, uyarlamalı denetim ve kuramsal bilgisayar bilimi gibi alanlarla yakından ilintili olduğunu göstermektedir.

![20200619_121923](https://user-images.githubusercontent.com/54184905/85117772-0f19b380-b228-11ea-9bf6-f1825e217931.jpg)

* Uygulamaları : Makine öğreniminin başlıca uygulamaları makine algılaması, bilgisayarlı görme, doğal dil işleme, sözdizimsel örüntü tanıma, arama motorları, tıbbi tanı, biyoinformatik, beyin-makine arayüzleri ve kiminformatik, kredi kartı dolandırıcılığı denetimi, borsa çözümlemesi, DNA dizilerinin sınıflandırılması, konuşma ve elyazısı tanıma, bilgisayarlı görmede nesne tanıma, oyun oynama, yazılım mühendisliği, uyarlamalı web siteleri ve robot gezisidir. 
    
![0*NgXCHXv1L4xm7e_L](https://user-images.githubusercontent.com/54184905/85115787-e80db280-b224-11ea-8896-bcd4aea62e56.png)



# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Makine Öğrenmesinin Dört Kategorisi

* ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Denetimli Öğrenme :

En sık kullanılan kategoridir. Bir veri seti üzerindeki girdilerden bilinen çıktılara olan eşleştirmeyi öğrenmeyi kapsar.
Her ne kadar Denetimli öğrenme temelde sınıflandırma ve bağlanım barındırsa da daha ilginç biçimleride bulunmaktadır.
Bağımlı değişken ve bağımlı değişkeni meydana getiren bağımsız değişkenler bir aradaysa, bu duruma gözetimli öğrenme denir.(Etiket-Veri)

1-) Dizi oluşturma : Verilen bir resimden başlığını tanımlamak. Dizi oluşturma genellikle arka arkaya sınıflandırma problemi olarak formüle edilmektedir.

2-) Sözdizimi ağacı tahmini : Verilen bir cümleden sözdizimi ağacını çözümlemek.

3-) Nesne Tespiti : Verilen bir resimden resim içindeki nesneleri çerçeve içine almak. Bu da aslında sınıflandırma problemi olarak ya da çerçevelerin kordinatlarının vektör bağlanımı ile tahmin edildiği sınıflandırma ve bağlanım problemlerinin birleşimi olarak görülebilir.

![Object_detection_Blog_Image_Q3_19](https://user-images.githubusercontent.com/54184905/85119756-eb0ba180-b22a-11ea-88a3-40d8b1b0ce43.jpg)

4-) Resim Bölütleme : Verilen bir resimde nesneye özel görüntü noktası seviyesinde maske oluşturmak.

* ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Denetimsiz Öğrenme :

Makine öğrenmesinin bu kategorisinin amacı veriyi görselleştirmek, verileri sıkıştırmak, verilerdeki gürültüyü azaltmak ya da eldeki veriler arasındaki korelasyonu anlamak için girdilerden herhangi bir bilinen olmaksızın amaca uygun dönüşümleri bulmaktır.
Bağımlı değişkenin çalışmanının içinde olmadığı öğrenme türüdür.(Veri var, Etiket yok) Birbirlerine benzer özellikler ile bir araya getirilir.

![clustering1](https://user-images.githubusercontent.com/54184905/85119762-ee069200-b22a-11ea-936b-6406c483b46e.jpg)



# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Temel Kavramlar


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Bağımlı Değişken - Bağımsız Değişken

* Bağımlı Değişken : Makine öğrenmesi probleminde tahmin etmek için hedeflediğimiz ana değişkendir(Etiket).

* Bağımsız Değişken : Bağımlı değişkenlerin belirlenmesinde öncü olur. KM, Hasar durumu, Marka, Model gibi.


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

* ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Model neye göre seçilir ? : 

* Regresyon için açıklanabilirlik oran ve RMSE türevi bir değer.

* Sınıflandırma için doğru sınıflandırma oranı türevi bir değer


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Aşırı Öğrenme (Overfitting)

* Algoritmanın veri setini ezberlemesi, yeni veriler üzerinden tahmin yapılmak istendiğinde modelin başarısız olması.

![Overfitted_Data](https://user-images.githubusercontent.com/54184905/85117779-10e37700-b228-11ea-8fcd-a6f5c86261a6.png)
