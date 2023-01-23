**PROJE TASARIMI VE GERÇEKLEME**

Bu projede bir akıllı sera yapmayı planladım.

**Yapılacak olan işlemler:**

*Seraya sadece yetkili kişilerin giriş yapabileceği bir şekilde RFID kartla okuma yapıyor.

*Yetkili kişinin giriş yapmasından sonra ThingSpeak platformu içine yetkili kişinin hesabına sensörlerden gelen sıcaklık,nem mesafe bilgileri gönderiliyor.

*Gelen mesafe bilgisine göre kapı açılıp kapanması işlemi yapılıyor. Bu işlemi led yakma işlemi olarak gerçekleştirdim.

*Tasarım aşamasında ilk olarak gerekli olan malzemeleri temin ettim. Bunlar sıcaklık ve nem sensörü (DHT11), mesafe sensörü (HCSR-04), Rfid kart okuyucu (RC522).

*Gerekli olan malzemeleri temin ettikten sonra devreyi nasıl bağlayacağımı planlayıp , çizip devre kurulumunu tamamladım.

*Devre kurulumunu tamamladıktan sonra her malzemeyi tek tek çalışıp çalışmadığına dair kontrol etim. Her malzemenin kodunu ayrı ayrı NodeMCU’ya bağlayıp çalıştırdım. Böylece hata riskini azalttım.

*En son olarak da tüm kodu birleştirip projemi çalıştırdım.

**BUSINESS CANVAS İŞ MODELİ**

![image](https://user-images.githubusercontent.com/73073517/213988293-e5ea48f9-b58f-413c-984c-e74ed0056378.png)

**SİSTEMİN ÇALIŞMA MANTIĞI(ACTIVITY DIAGRAM)**

![image](https://user-images.githubusercontent.com/73073517/213988466-c54f2171-5008-47d3-b35b-366c696b19ad.png)

**KULLANILAN TEKNOLOJİLER**

->NODEMCU ESP8266

->DHT-11

->HC-SR04 ULTRASONİK MESAFE SENSÖRÜ

->RFID RC522

->THİNG-SPEAK











