# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Makine Öğrenmesi Nedir ?

![Makine-Öğrenmesi-Nedir-Ne-İşe-Yarar-Rehber](https://user-images.githubusercontent.com/54184905/85115651-b1379c80-b224-11ea-82d4-305cd13cb08f.jpg)

Makine öğrenimi, bilgisayarların algılayıcı verisi ya da veritabanları gibi veri türlerine dayalı öğrenimini olanaklı kılan algoritmaların tasarım ve geliştirme süreçlerini konu edinen bir bilim dalıdır. Makine öğrenimi araştırmalarının odaklandığı konu bilgisayarlara karmaşık örüntüleri algılama ve veriye dayalı akılcı kararlar verebilme becerisi kazandırmaktır. Bu, makine öğreniminin istatistik, olasılık kuramı, veri madenciliği, örüntü tanıma, yapay zekâ, uyarlamalı denetim ve kuramsal bilgisayar bilimi gibi alanlarla yakından ilintili olduğunu göstermektedir.

![20200619_121923](https://user-images.githubusercontent.com/54184905/85117772-0f19b380-b228-11ea-9bf6-f1825e217931.jpg)

* Uygulamaları : Makine öğreniminin başlıca uygulamaları makine algılaması, bilgisayarlı görme, doğal dil işleme, sözdizimsel örüntü tanıma, arama motorları, tıbbi tanı, biyoinformatik, beyin-makine arayüzleri ve kiminformatik, kredi kartı dolandırıcılığı denetimi, borsa çözümlemesi, DNA dizilerinin sınıflandırılması, konuşma ve elyazısı tanıma, bilgisayarlı görmede nesne tanıma, oyun oynama, yazılım mühendisliği, uyarlamalı web siteleri ve robot gezisidir. 
    
![0*NgXCHXv1L4xm7e_L](https://user-images.githubusercontent.com/54184905/85115787-e80db280-b224-11ea-8896-bcd4aea62e56.png)


# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Makine Öğrenmesinin Dört Kategorisi


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Denetimli Öğrenme :

En sık kullanılan kategoridir. Bir veri seti üzerindeki girdilerden bilinen çıktılara olan eşleştirmeyi öğrenmeyi kapsar.
Her ne kadar Denetimli öğrenme temelde sınıflandırma ve bağlanım barındırsa da daha ilginç biçimleride bulunmaktadır.
Bağımlı değişken ve bağımlı değişkeni meydana getiren bağımsız değişkenler bir aradaysa, bu duruma gözetimli öğrenme denir.(Etiket-Veri)

* Dizi oluşturma : Verilen bir resimden başlığını tanımlamak. Dizi oluşturma genellikle arka arkaya sınıflandırma problemi olarak formüle edilmektedir.

* Sözdizimi ağacı tahmini : Verilen bir cümleden sözdizimi ağacını çözümlemek.

* Nesne Tespiti : Verilen bir resimden resim içindeki nesneleri çerçeve içine almak. Bu da aslında sınıflandırma problemi olarak ya da çerçevelerin kordinatlarının vektör bağlanımı ile tahmin edildiği sınıflandırma ve bağlanım problemlerinin birleşimi olarak görülebilir.

![Object_detection_Blog_Image_Q3_19](https://user-images.githubusercontent.com/54184905/85119756-eb0ba180-b22a-11ea-88a3-40d8b1b0ce43.jpg)

* Resim Bölütleme : Verilen bir resimde nesneye özel görüntü noktası seviyesinde maske oluşturmak.


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Denetimsiz Öğrenme :

Makine öğrenmesinin bu kategorisinin amacı veriyi görselleştirmek, verileri sıkıştırmak, verilerdeki gürültüyü azaltmak ya da eldeki veriler arasındaki korelasyonu anlamak için girdilerden herhangi bir bilinen olmaksızın amaca uygun dönüşümleri bulmaktır.
Bağımlı değişkenin çalışmanının içinde olmadığı öğrenme türüdür.(Veri var, Etiket yok) Birbirlerine benzer özellikler ile bir araya getirilir.

![clustering1](https://user-images.githubusercontent.com/54184905/85119762-ee069200-b22a-11ea-936b-6406c483b46e.jpg)


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Yarı Denetimli Öğrenme :

Denetimli öğrenmenin özel bir örneğidir ama kendi özel kategorisini hak etmektedir. Yarı-Denetimli öğrenme, Denetimli öğrenmenin etkili verilerinin olmadığı halidir. Denetimli öğrenmenin insanın olmadığı döngüsü olarak düşünebilirsiniz. Hayla etiketleri vardır ama bunlar girdilerden keşifsel olarak oluşturulur. Örneğin : Otokodlayıcılar(autoencoder) yarı denetimli öğrenmenin çok bilinen bir örneğidir, hedef girdilerden öğrenilmektedir.

![0*uq2_ZipB9TqI9G_k](https://user-images.githubusercontent.com/54184905/85122369-198b7b80-b22f-11ea-847a-f36051d9d3eb.png)


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Pekiştirmeli Öğrenme :

Makine öğrenmesini bu kategorisi uzun süre dikkate alınmamış ancak Google DeepMind tarafından geliştirilen ve ateri oyunları(En son GO oyununda en üst seviye oyuncuları yenebilmiştir.) oynamayı öğrenmesi ile yeniden dikkatleri üzerine çekebilmiştir. Pekiştirmeli öğrenmede bir ajan çerçevesi ile ilgili bir bilgi alır ve ödülünü arttırmak için bir hareket seçer. Örneğin bir sinir ağı, bilgisayar oyununun ekranına bakarak ve skorunu artıracak hareketi seçebilmek için pekiştirmeli öğrenme ile eğitilebilir.

![440px-Pekistirmeli-ogrenme-diyagram svg](https://user-images.githubusercontent.com/54184905/85122373-1abca880-b22f-11ea-8aa2-6e3e1a02df39.png)


# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Temel Kavramlar

* Bu başlık altında ise Makine Öğrenmesi için gerekli olan temel kavramları göreceğiz.


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Bağımlı Değişken - Bağımsız Değişken

* Bağımlı Değişken : Makine öğrenmesi probleminde tahmin etmek için hedeflediğimiz ana değişkendir(Etiket).

* Bağımsız Değişken : Bağımlı değişkenlerin belirlenmesinde öncü olur. KM, Hasar durumu, Marka, Model gibi.


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Regresyon - Sınıflandırma

* Regresyon : Bağımlı değişken, sayısal/sürekli bir değişken ise bu bir regresyon problemidir.(Ev tahmin problemi(Ev fiyati 150000 TL))

* Sınıflandırma Problemi : Bağımlı değişken kategorik bir değiken ise bu bir sınıflandırma problemidir.(Hastanın yaşayıp yaşayamaması(0,1)) 


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Değişken Seçimi (Variable Selection)

![Screenshot_2020-06-19_12-05-00](https://user-images.githubusercontent.com/54184905/85115962-3a4ed380-b225-11ea-8d1c-8fc203d77c2a.png)

* Amaç : En az değişkenle en fazla açıklanabilirliği yakalamak


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Makine Öğrenme Modellerinin Değerlendirilmesi (Test-Train)

* Makine öğrenmesinde amaç, modellerin GENELLEŞTİRMESİDİR. Hiç görmediği verilerde başarılı olmalıdır. Önündeki en büyük engel de aşırı uydurmadır.

* Elimzideki veri setinin bir kısmını modeli eğitirken kullanırız diğer kısmını ise eğitilen modeli test ederken kullanırız.

![Screenshot_2020-06-19_12-00-26](https://user-images.githubusercontent.com/54184905/85115581-906f4700-b224-11ea-870d-79f0492e43e3.png)


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Model Seçimi

![1*ioZ200iYyX-QJfOLs17gow](https://user-images.githubusercontent.com/54184905/85116427-fd371100-b225-11ea-9a5f-ba867a9babf3.jpeg)

* Oluşabilecek değişken kombinasyonları ile oluşturulan modeller arasından en iyi modelin seçilmesi.

* ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Model neye göre seçilir ? : 

* Regresyon için açıklanabilirlik oran ve RMSE türevi bir değer.

* Sınıflandırma için doğru sınıflandırma oranı türevi bir değer


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Aşırı Öğrenme (Overfitting)

* Algoritmanın veri setini ezberlemesi, yeni veriler üzerinden tahmin yapılmak istendiğinde modelin başarısız olması.

![Overfitted_Data](https://user-images.githubusercontent.com/54184905/85117779-10e37700-b228-11ea-8fcd-a6f5c86261a6.png)


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Deterministik - Stokastik Modeller

* Deterministik modeller : Değişken arasında kesin bir ilişki olduğu varsayılan modeller.

![det](https://user-images.githubusercontent.com/54184905/85123705-6708e800-b231-11ea-9729-6bc5a360b5f2.png)

* Stokastik Modeller : Olasılıksal modeller bizim kullanacağımız modeller.

![Screenshot_2020-06-19_13-30-49](https://user-images.githubusercontent.com/54184905/85123703-66705180-b231-11ea-92f0-3f9402d1f0dc.png)


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Doğrusal Modeller - Doğrusal Olmayan Modeller

* Doğrusal modeller : Doğru ile ifade edilebilmeli.

![dog](https://user-images.githubusercontent.com/54184905/85124170-2067bd80-b232-11ea-8074-882867705060.png)

* Doğrusal olmayan modeller : Eğri aracılığıyla, ağaca dayalı yöntemler veya yöntemler ile değişkenler arasındaki ilişkilerin modellenmeye çalışmak. 

![Screenshot_2020-06-19_13-35-21](https://user-images.githubusercontent.com/54184905/85124167-1fcf2700-b232-11ea-9fa6-9c9739a716c9.png)


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Makine Öğrenmesi - Matematik - İstatistik - Olasılık

* Makine öğrenmesi, matematikten istatistiğe geçiş ve matematik istatistik optimizasyon arasında bir yerde konumlanmaktadır.

* Matematikte kesinlik vardır. İstatistik ve olasılıkta kesinlik yoktur.

![20200619_134240](https://user-images.githubusercontent.com/54184905/85124694-0084c980-b233-11ea-9be0-9f01abef45e0.jpg)


# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Model Doğrulama Yöntemleri (Model Validation)

* Modellerin ürettiği sonuçların doğru değerlendirilmesi çalışmaları.

* Model kurmak : Bağımlı değişken ile bağımsız değişkenler arasındaki ilişkiyi modellemek demektir.


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Yöntemler


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Holdout Yöntemi (Sınama Testi)

![Screenshot_2020-06-19_12-00-26](https://user-images.githubusercontent.com/54184905/85115581-906f4700-b224-11ea-870d-79f0492e43e3.png)

* Belli bir orana göre veri seti parçalanır. Bir kısmı eğitimde kullanılır bir kısmı testte kullanılır. 


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) K - Katlı Çapraz Doğrulama (K Fold Cross Validation)

![Screenshot_2020-06-19_14-13-03](https://user-images.githubusercontent.com/54184905/85126914-198f7980-b237-11ea-9dd4-1a39158eb91a.png)

* Veri seti K adet parçaya ayrılır, belirlenen alt kümelerden birisi dışarıda bıraklır. Diğer kümeler eğitim verisi olur ve seçilen küme test verisi olur. Aynı işlem diğer kümeler içinde tekrar eder, bu işlem sonucunda elde edilen hataların ortlaması alındığında bu doğrulama hatası olur.
En son ayrılan test verisiyle test ederiz.


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Leave One Out

![Screenshot_2020-06-19_14-18-30](https://user-images.githubusercontent.com/54184905/85127302-d71a6c80-b237-11ea-9961-82ad4494f4e9.png)

* Eğitim seti n kadar alt kümeye ayrılır ve bu kümelerden biri haricinde diğer tüm kümeler eğitim için kullanılır. Seçilen küme test için kullanılır, bu şekilde seçilen küme değiştirilerek devam eder.
En sonayrılan test veri setiyle model test edilir.

* Veri seti boyutu büyüdükçe bu doğrulamanın gerçekleşmesi imkansızlaşır.


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) Bootstrap

![Screenshot_2020-06-19_14-22-41](https://user-images.githubusercontent.com/54184905/85127602-6c1d6580-b238-11ea-895d-5a4928a66454.png)

* Yeniden örnek oluşturacak şekilde çalışır, orjinal veri seti içersinden seçilen örneklerle bootstrap örnekler oluşturulur.
x kadar bootstrap veri ile model kurulur ve test edilir. Yerine koymalı bir şekilde veri seti içerisinden veri türetmek şeklinde kullanılır. 


# ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) Model Başarı Değerlendirme Yöntemleri

* Modelin tahmin başarısının değerlendirilmesi. Ortalama hata hesaplamaya çalışılır.


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Regresyon Modelleri İçin Başarı Değerlendirme


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) MSE (Hata Kareleri Ortalaması)

![Screenshot_2020-06-19_14-29-42](https://user-images.githubusercontent.com/54184905/85128137-63795f00-b239-11ea-989f-d5f7a15b2104.png)

* n = Gözlem sayısı
* yi = Gerçek değerler (Etiket)
* y' = Tahmin edilen değerler

* Bir ev fiyatlandırma problemi düşünelim, model evi 150000 tl olarak tahmin etti ama evin gerçek değeri 151000 tl.

((151000 - 150000)² / örnek sayısı) olarak düşünebiliriz.


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) RMSE (Hata Kareleri Ortalaması Karekökü)

![Screenshot_2020-06-19_14-34-18](https://user-images.githubusercontent.com/54184905/85128566-3c6f5d00-b23a-11ea-941f-19f860fb1b22.png)

* n = Gözlem sayısı
* yi = Gerçek değerler (Etiket)
* y' = Tahmin edilen değerler

* MSE 'nin karekökü alınmış hali
* Bir ev fiyatlandırma problemi düşünelim, model evi 150000 tl olarak tahmin etti ama evin gerçek değeri 151000 tl.

√((151000 - 150000)² / örnek sayısı) olarak düşünebiliriz.


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) MAE (Ortalama Mutlak Hata)

![Screenshot_2020-06-19_14-39-51](https://user-images.githubusercontent.com/54184905/85128882-d2a38300-b23a-11ea-85a7-99c69693fd44.png)

* n = Gözlem sayısı
* yi = Gerçek değerler (Etiket)
* y' = Tahmin edilen değerler

* Bir ev fiyatlandırma problemi düşünelim, model evi 150000 tl olarak tahmin etti ama evin gerçek değeri 151000 tl.

(|151000 - 150000| / örnek sayısı) olarak düşünebiliriz.


## ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) Sınıflandırma Modelleri İçin Başarı Değerlendirme

![Screenshot_2020-06-19_14-45-49](https://user-images.githubusercontent.com/54184905/85129393-af2d0800-b23b-11ea-9d40-fd8f193e1baf.png)

* a : True Pozitif (TP)
* d : True Negatif (TN)
* c : False Pozitif (FP)
* b : False Negatif (FN)

* Modeldeki doğruluk için : (TP + TN) / Hepsi
* Modeldeki hata oranı için : (FN + FP) / Hepsi
* Modeldeki kesinlik için : TP / (TP + FP)
* Modeldeki anma için : TP / (TP + FN)


### ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) ROC Eğrisi




