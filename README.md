# NesnelerinInterneti
Problemin Tanımı ve Önerilen Çözüm
Günümüzde sağlık takibi, özellikle pandemi koşullarında daha da önem 
kazanmaktadır. Ancak, birçok bireyin evde sağlık durumlarını takip etmeleri 
konusunda sınırlılıklar yaşanmaktadır. Bu bağlamda, oksijen seviyelerini 
ölçmek ve nabız verilerini anlık olarak izlemek, sağlık durumunu 
değerlendirmek adına hayati öneme sahiptir. Bu ihtiyaçtan yola çıkarak, Pulse 
Oximeter projesi, bireylerin evdeki konforlarında sağlık durumlarını güvenilir 
bir şekilde izleyebilmeleri amacını taşımaktadır.
Proje, evde kullanım için tasarlanmış bir pulse oximeter cihazını içermektedir. 
Pulse oximeter, parmak ucuna yerleştirilen sensörler aracılığıyla oksijen 
seviyesini ve nabzı ölçen bir cihazdır. Bu sensörlerden alınan veriler kullanıcı 
dostu bir arayüzle bireyin cep telefonuna veya bilgisayarına iletilir. Bu sayede, 
bireyler oksijen seviyelerini ve nabzı anlık olarak izleyebilir, verilerini 
kaydedebilir ve sağlık profesyonelleri ile paylaşabilirler. Projede kullanılan IoT 
(Nesnelerin İnterneti) teknolojisi, cihazın uzaktan izlenebilir ve yönetilebilir 
olmasını sağlar, böylece sağlık durumu takibi daha etkili bir şekilde 
gerçekleştirilebilir.
Bu proje, bireylere evlerinde kendi sağlık durumlarını takip etme ve potansiyel 
sorunları erken tespit etme imkanı sunarak, sağlık hizmetlerine daha bilinçli bir 
şekilde katılım sağlamayı amaçlamaktadır.
Gerekli Materyaller ve Kullanılan Teknolojiler
Gerekli Materyaller 
 Nodemcu ESP8266
 Pulse Oximeter Max30100
 OLED Ekran
 BreadBoard
 Jumperlar
 Mikro USB Kablo
Kullanılan Teknolojiler
 Blynk Iot Platformu
 NodeMCU ESP8266: Bir mikrodenetleyici kartıdır ve özellikle IoT 
uygulamaları için tasarlanmıştır. WiFi modülü ile entegre bir şekilde 
çalışır ve düşük maliyetli olmasının yanı sıra, geniş bir geliştirici kitlesi 
tarafından desteklenir. IoT projelerinde, sensörlerden alınan verilerin 
toplanması, işlenmesi ve internete iletilmesi gibi görevlerde kullanılır.
 Pulse Oximeter Max30100: Kızılötesi ve kırmızı LED'leri kullanarak 
parmak ucundaki cilt üzerinden oksijen seviyelerini (SpO2) ve nabzı 
ölçen bir sensördür. Bu sensör, sağlık izleme uygulamalarında sıklıkla 
kullanılır. IoT uygulamalarında, Max30100 sensörü kullanılarak elde 
edilen canlı sağlık verileri, NodeMCU ESP8266 gibi IoT cihazları 
aracılığıyla toplanabilir, işlenebilir ve çeşitli hedeflere iletilerek uzaktan 
izleme ve analiz imkanı sağlar.
 Blynk IoT Platformu: Projeleri oluşturmak için kullanılan bir 
platformdur. Blynk, mobil uygulama aracılığıyla cihazları uzaktan kontrol 
etme imkanı sağlar. Kullanıcılar, Blynk uygulamasını kullanarak 
projelerini izleyebilir ve kontrol edebilirler. Blynk platformu, Arduino, 
Raspberry Pi ve diğer mikrodenetleyicilerle entegre edilebilir. Projelerin 
veri alışverişi ve kontrolü için bir Blynk sunucusu kullanılır ve Blynk 
kütüphaneleri, mikrodenetleyicilere Blynk platformuyla iletişim kurma 
yeteneği ekler.
 OLED Ekran: OLED (Organik Işık Yayan Diyot) ekranlar, ince film 
organik bileşenler kullanılarak üretilen, hafif, esnek ve yüksek kontrastlı 
ekranlardır. IoT projelerinde, özellikle sağlık izleme uygulamalarında, 
sensörlerden elde edilen verilerin kullanıcıya anlık olarak görsel olarak 
iletilmesi için OLED ekranlar kullanılır. Bu ekranlar, düşük güç tüketimi 
ve yüksek parlaklık gibi avantajlara sahiptir. Örneğin, Pulse Oximeter 
Max30100 ile ölçülen oksijen seviyeleri ve nabız değerleri, NodeMCU 
ESP8266 tarafından işlenerek OLED ekran aracılığıyla kullanıcıya anlık 
olarak gösterilebilir. Bu sayede, bireyler sağlık durumlarıyla ilgili önemli 
bilgileri kolayca takip edebilirler.

