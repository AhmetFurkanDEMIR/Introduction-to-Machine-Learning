# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Makine Öğrenmesi Nedir ?

![Makine-Öğrenmesi-Nedir-Ne-İşe-Yarar-Rehber](https://user-images.githubusercontent.com/54184905/85115651-b1379c80-b224-11ea-82d4-305cd13cb08f.jpg)

Makine öğrenimi, bilgisayarların algılayıcı verisi ya da veritabanları gibi veri türlerine dayalı öğrenimini olanaklı kılan algoritmaların tasarım ve geliştirme süreçlerini konu edinen bir bilim dalıdır. Makine öğrenimi araştırmalarının odaklandığı konu bilgisayarlara karmaşık örüntüleri algılama ve veriye dayalı akılcı kararlar verebilme becerisi kazandırmaktır. Bu, makine öğreniminin istatistik, olasılık kuramı, veri madenciliği, örüntü tanıma, yapay zekâ, uyarlamalı denetim ve kuramsal bilgisayar bilimi gibi alanlarla yakından ilintili olduğunu göstermektedir.

![20200619_121923](https://user-images.githubusercontent.com/54184905/85117772-0f19b380-b228-11ea-9bf6-f1825e217931.jpg)

* Uygulamaları : Makine öğreniminin başlıca uygulamaları makine algılaması, bilgisayarlı görme, doğal dil işleme, sözdizimsel örüntü tanıma, arama motorları, tıbbi tanı, biyoinformatik, beyin-makine arayüzleri ve kiminformatik, kredi kartı dolandırıcılığı denetimi, borsa çözümlemesi, DNA dizilerinin sınıflandırılması, konuşma ve elyazısı tanıma, bilgisayarlı görmede nesne tanıma, oyun oynama, yazılım mühendisliği, uyarlamalı web siteleri ve robot gezisidir. 
    
![0*NgXCHXv1L4xm7e_L](https://user-images.githubusercontent.com/54184905/85115787-e80db280-b224-11ea-8896-bcd4aea62e56.png)



# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Makine Öğrenmesinin Dört Kategorisi


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Denetimli Öğrenme :

En sık kullanılan kategoridir. Bir veri seti üzerindeki girdilerden bilinen çıktılara olan eşleştirmeyi öğrenmeyi kapsar.
Her ne kadar Denetimli öğrenme temelde sınıflandırma ve bağlanım barındırsa da daha ilginç biçimleride bulunmaktadır.
Bağımlı değişken ve bağımlı değişkeni meydana getiren bağımsız değişkenler bir aradaysa, bu duruma gözetimli öğrenme denir.(Etiket-Veri)

* Dizi oluşturma : Verilen bir resimden başlığını tanımlamak. Dizi oluşturma genellikle arka arkaya sınıflandırma problemi olarak formüle edilmektedir.

* Sözdizimi ağacı tahmini : Verilen bir cümleden sözdizimi ağacını çözümlemek.

* Nesne Tespiti : Verilen bir resimden resim içindeki nesneleri çerçeve içine almak. Bu da aslında sınıflandırma problemi olarak ya da çerçevelerin kordinatlarının vektör bağlanımı ile tahmin edildiği sınıflandırma ve bağlanım problemlerinin birleşimi olarak görülebilir.

![Object_detection_Blog_Image_Q3_19](https://user-images.githubusercontent.com/54184905/85119756-eb0ba180-b22a-11ea-88a3-40d8b1b0ce43.jpg)

* Resim Bölütleme : Verilen bir resimde nesneye özel görüntü noktası seviyesinde maske oluşturmak.


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Denetimsiz Öğrenme :

Makine öğrenmesinin bu kategorisinin amacı veriyi görselleştirmek, verileri sıkıştırmak, verilerdeki gürültüyü azaltmak ya da eldeki veriler arasındaki korelasyonu anlamak için girdilerden herhangi bir bilinen olmaksızın amaca uygun dönüşümleri bulmaktır.
Bağımlı değişkenin çalışmanının içinde olmadığı öğrenme türüdür.(Veri var, Etiket yok) Birbirlerine benzer özellikler ile bir araya getirilir.

![clustering1](https://user-images.githubusercontent.com/54184905/85119762-ee069200-b22a-11ea-936b-6406c483b46e.jpg)


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Yarı Denetimli Öğrenme :

Denetimli öğrenmenin özel bir örneğidir ama kendi özel kategorisini hak etmektedir. Yarı-Denetimli öğrenme, Denetimli öğrenmenin etkili verilerinin olmadığı halidir. Denetimli öğrenmenin insanın olmadığı döngüsü olarak düşünebilirsiniz. Hayla etiketleri vardır ama bunlar girdilerden keşifsel olarak oluşturulur. Örneğin : Otokodlayıcılar(autoencoder) yarı denetimli öğrenmenin çok bilinen bir örneğidir, hedef girdilerden öğrenilmektedir.

![0*uq2_ZipB9TqI9G_k](https://user-images.githubusercontent.com/54184905/85122369-198b7b80-b22f-11ea-847a-f36051d9d3eb.png)


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Pekiştirmeli Öğrenme :

Makine öğrenmesini bu kategorisi uzun süre dikkate alınmamış ancak Google DeepMind tarafından geliştirilen ve ateri oyunları(En son GO oyununda en üst seviye oyuncuları yenebilmiştir.) oynamayı öğrenmesi ile yeniden dikkatleri üzerine çekebilmiştir. Pekiştirmeli öğrenmede bir ajan çerçevesi ile ilgili bir bilgi alır ve ödülünü arttırmak için bir hareket seçer. Örneğin bir sinir ağı, bilgisayar oyununun ekranına bakarak ve skorunu artıracak hareketi seçebilmek için pekiştirmeli öğrenme ile eğitilebilir.

![440px-Pekistirmeli-ogrenme-diyagram svg](https://user-images.githubusercontent.com/54184905/85122373-1abca880-b22f-11ea-8aa2-6e3e1a02df39.png)


# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Temel Kavramlar

* Bu başlık altında ise Makine Öğrenmesi için gerekli olan temel kavramları göreceğiz.


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Bağımlı Değişken - Bağımsız Değişken

* Bağımlı Değişken : Makine öğrenmesi probleminde tahmin etmek için hedeflediğimiz ana değişkendir(Etiket).

* Bağımsız Değişken : Bağımlı değişkenlerin belirlenmesinde öncü olur. KM, Hasar durumu, Marka, Model gibi.


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Regresyon - Sınıflandırma

* Regresyon : Bağımlı değişken, sayısal/sürekli bir değişken ise bu bir regresyon problemidir.(Ev tahmin problemi(Ev fiyati 150000 TL))

* Sınıflandırma Problemi : Bağımlı değişken kategorik bir değiken ise bu bir sınıflandırma problemidir.(Hastanın yaşayıp yaşayamaması(0,1)) 


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Değişken Seçimi (Variable Selection)

![Screenshot_2020-06-19_12-05-00](https://user-images.githubusercontent.com/54184905/85115962-3a4ed380-b225-11ea-8d1c-8fc203d77c2a.png)

* Amaç : En az değişkenle en fazla açıklanabilirliği yakalamak


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Makine Öğrenme Modellerinin Değerlendirilmesi (Test-Train)

* Makine öğrenmesinde amaç, modellerin GENELLEŞTİRMESİDİR. Hiç görmediği verilerde başarılı olmalıdır. Önündeki en büyük engel de aşırı uydurmadır.

* Elimzideki veri setinin bir kısmını modeli eğitirken kullanırız diğer kısmını ise eğitilen modeli test ederken kullanırız.

![Screenshot_2020-06-19_12-00-26](https://user-images.githubusercontent.com/54184905/85115581-906f4700-b224-11ea-870d-79f0492e43e3.png)


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Model Seçimi

![1*ioZ200iYyX-QJfOLs17gow](https://user-images.githubusercontent.com/54184905/85116427-fd371100-b225-11ea-9a5f-ba867a9babf3.jpeg)

* Oluşabilecek değişken kombinasyonları ile oluşturulan modeller arasından en iyi modelin seçilmesi.

* ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Model neye göre seçilir ? : 

* Regresyon için açıklanabilirlik oran ve RMSE türevi bir değer.

* Sınıflandırma için doğru sınıflandırma oranı türevi bir değer


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Aşırı Öğrenme (Overfitting)

* Algoritmanın veri setini ezberlemesi, yeni veriler üzerinden tahmin yapılmak istendiğinde modelin başarısız olması.

![Overfitted_Data](https://user-images.githubusercontent.com/54184905/85117779-10e37700-b228-11ea-8fcd-a6f5c86261a6.png)


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Deterministik - Stokastik Modeller

* Deterministik modeller : Değişken arasında kesin bir ilişki olduğu varsayılan modeller.

![det](https://user-images.githubusercontent.com/54184905/85123705-6708e800-b231-11ea-9729-6bc5a360b5f2.png)

* Stokastik Modeller : Olasılıksal modeller bizim kullanacağımız modeller.

![Screenshot_2020-06-19_13-30-49](https://user-images.githubusercontent.com/54184905/85123703-66705180-b231-11ea-92f0-3f9402d1f0dc.png)


# ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Doğrusal Modeller - Doğrusal Olmayan Modeller

* Doğrusal modeller : Doğru ile ifade edilebilmeli.

![dog](https://user-images.githubusercontent.com/54184905/85124170-2067bd80-b232-11ea-8074-882867705060.png)

* Doğrusal olmayan modeller : Eğri aracılığıyla, ağaca dayalı yöntemler veya yöntemler ile değişkenler arasındaki ilişkilerin modellenmeye çalışmak. 

![Screenshot_2020-06-19_13-35-21](https://user-images.githubusercontent.com/54184905/85124167-1fcf2700-b232-11ea-9fa6-9c9739a716c9.png)





