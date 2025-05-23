# Uçak Bileti Rezervasyon Sistemi
Bu projede Java dilini kullanarak bir uçak bileti rezervasyon sistemi geliştirdim. Kullanıcılar uçuşları listeleyebiliyor, tek yön veya gidiş-dönüş rezervasyon yapabiliyor ve tüm rezervasyonları görüntüleyebiliyor. Ayrıca veriler CSV dosyalarına kaydedilebiliyor.

## emel Özellikler
1)Uçuş listeleme

Tek yön ve gidiş-dönüş rezervasyon

3)Ekonomi, Business ve First Class sınıf seçimi

4) Yaşa göre indirimli fiyatlandırma

5)Koltuk numarası seçimi (boş koltuk kontrolüyle birlikte)

6)Uçak, lokasyon ve rezervasyon bilgilerini CSV dosyalarına yazma

## Kullanılan Sınıflar
Ucak: Uçak bilgileri ve koltuk durumu tutuluyor.

Lokasyon: Ülke, şehir ve havalimanı bilgisi içeriyor.

Ucus: Kalkış-varış lokasyonları, saat, uçak ve baz fiyat bilgisi bulunuyor.

Rezervasyon: Yolcu bilgisi, koltuk numarası, sınıf, ücret ve uçuş türü tutuluyor.

CsvYonetici: Nesne listelerini .csv formatında dosyaya kaydediyor.

## Çalışma Mantığı
Program açıldığında kullanıcıya bir menü sunuluyor. Buradan uçuşlar listelenebiliyor, rezervasyon yapılabiliyor ya da kayıtlı veriler CSV olarak dışa aktarılabiliyor. Rezervasyon yapılırken koltuklar boş/dolu durumuna göre seçilebiliyor.
