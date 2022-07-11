# CarRentalSystem



    Sisteme araç kiralayan firmalar eklenecek.
    Firmalar bulundukları şehri sisteme girmelidir.
    Firmalar kendilerine ait araçları sisteme girecekler
    Araçların günlük fiyatlarını ve fiyatların geçerli olduğu tarih aralıklarını
    Aracın tipini (binek, arazi , ticari araçlar vs.)
    Hangi tarihlerde müsait olduklarını
    Varsa ek hizmetlerini ve fiyatlarını tanımlamalılar.
    Kullanıcılar sisteme kaydolmalılar.
    Kullanıcılar sistemde şehirler üzerinden araç tipine ve tarihe göre uygun araçları listeleyebilmeli ve rezervasyon yapabilmeli.
    Rezervasyon yapılan tarihte ilgili aracın müsait olması ve başka kiralama ile çakışmaması gerekmektedir.
    Firmalar ve kullanıcılar yaptıkları rezervasyonları listeleyebilmeliler.
    Rezervasyonlar en erken 1 gün öncesinden iptal edilebilir.

### Kullanılması gereken teknikler:

    Veritabanı (DATABASE)
    Kullanıcı Arayüzü (GUI)



# Uygulama Resimleri 

## Açılış Ekranı
![Photo](https://user-images.githubusercontent.com/58556840/178132015-70cca23e-0b31-457a-9fe0-8533fda4a55a.png)

## Giriş Tipi Seçimi
````
Öncelikle firma girişi mi kullanıcı girişi mi yapılacağı seçiliyor ve giriş ekranlarına yönlendiriliyor.
````
![Photo](https://user-images.githubusercontent.com/58556840/178132016-fa5eb481-8801-46b6-942c-a1ee2f971386.png)

## Firma İşlemleri
````
Giriş yaparken veritabanı sorgulamaları yapılıyor ve kayıt mevcutsa giriş başarılı mesajı alınıyor.Örnek olarak giriş yaptığımız "Firma A" kendi araçlarını
kiralayan kullanıcıların bilgi dökümünü rezervasyonlar kısmından inceleyebiliyor. Araç Listesi sekmesinden ise firmaya ait eklenmiş araçların bilgilerini
inceleyebiliyor ve yeni araç ekleyip silebiliyor. Hesap kısmında ise firmaya ait üyelik bilgileri görünüyor ve güncellenebiliyor.İsteğe göre hesaplarını 
kapatabiliyorlar.
````
![Photo](https://user-images.githubusercontent.com/58556840/178132013-3dc85461-153f-4388-beb3-16315140f452.png)
![Photo](https://user-images.githubusercontent.com/58556840/178132017-57278a74-00ae-4e7c-8896-584ec34869cd.png)

![Photo](https://user-images.githubusercontent.com/58556840/178132019-5897f3fc-dc0d-45a2-8a28-3c45c771a703.png)
![Photo](https://user-images.githubusercontent.com/58556840/178132012-9773d7ee-57b8-4b20-98f9-14dba9aeb1c3.png)

## Kullanıcı İşlemleri
````
Kullanıcılar araçlar sekmesinde uygulamaya kayıtlı tüm araçların listesini müsaitlik durumlarını ve hangi şirkete ait olduklarını görebiliyorlar.İsteklerine göre
arama yapabilmeleri için bir filtreleme butonu da mevcut.Kiralama yapmak istedikleri tarihi girip kiralama butonuna bastıklarında eğer araç müsait ise kullanıcı adına
rezervasyon işlemi yapılıyor. Profil sekmesinde ise kullanıcı üyelik bilgilerini inceleyip güncelleyebiliyor ve yaptığı kiralama geçmişine ait bilgileri görebiliyor.
````
![Photo](https://user-images.githubusercontent.com/58556840/178132014-5b476249-2d35-40f7-a048-c3f42499a41c.png)


![Photo](https://user-images.githubusercontent.com/58556840/178132020-448f2876-4337-4707-86a6-00d1606c3dbc.png)


![Photo](https://user-images.githubusercontent.com/58556840/178132018-fbd3ca27-698c-4493-a35c-1d1994b85e8c.png)
