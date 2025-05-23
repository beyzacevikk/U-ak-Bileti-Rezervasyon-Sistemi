#✈️ Uçak Bileti Rezervasyon Sistemi (Java - Nesneye Yönelik Programlama Dersi)
Bu projede Java programlama dili kullanılarak bir uçak bileti rezervasyon sistemi geliştirdim. Kullanıcı, uçuşları listeleyebilir, tek yön veya gidiş-dönüş bilet rezervasyonu yapabilir, koltuk seçebilir ve yapılan tüm rezervasyonları görüntüleyebilir. Ayrıca tüm veriler CSV dosyalarına kaydedilmektedir.

# 📌 Proje Özellikleri
## 1. 🛫 Uçuş Listeleme
Sistemde tanımlı tüm uçuşları kullanıcı listeleyebilir.

Her uçuş için kalkış ve varış lokasyonu, saat, uçak modeli ve temel fiyat bilgileri gösterilir.

## 2. 🎟️ Rezervasyon Yapma
Kullanıcı, tek yön veya gidiş-dönüş rezervasyon seçebilir.

Rezervasyon sırasında:

Yolcunun adı ve yaşı girilir.

Ekonomi, Business veya First Class uçuş sınıfı seçilir.

Uygun koltuklar gösterilir ve kullanıcı boş koltuklardan birini seçer.

Yaşa göre indirim uygulanır (örneğin çocuk veya yaşlı indirimi).

Seçilen koltuk, o uçuşta rezerve edilmiş sayılır.

## 3. 💺 Koltuk Seçimi ve Kontrol
Her uçakta koltukların dolu/boş durumu takip edilir.

Kullanıcı sadece boş koltuklar arasından seçim yapabilir.

## 4. 🧾 CSV Dosyaya Yazma
Uçak, lokasyon, uçuş ve rezervasyon bilgileri CSV dosyalarına yazılır.

Bu sayede veriler daha sonra tekrar görüntülenebilir veya yedeklenebilir.

# 🧱 Kullanılan Sınıflar
Ucak: Uçak bilgilerini ve koltuk durumlarını tutar.

Lokasyon: Ülke, şehir ve havalimanı bilgilerini içerir.

Ucus: Kalkış-varış lokasyonları, uçuş saati, uçak ve fiyat bilgilerini barındırır.

Rezervasyon: Yolcu bilgisi, koltuk numarası, sınıf, uçuş türü (tek yön/gidiş-dönüş) ve ücret bilgilerini tutar.

CsvYonetici: Tüm verileri .csv formatında diske yazar.

# 🧭 Kullanım Talimatları
Program başlatıldığında kullanıcıya bir menü sunulur.

Menüden:

Uçuşları listeleyebilirsiniz.

Yeni rezervasyon yapabilirsiniz (tek yön veya gidiş-dönüş).

Tüm rezervasyonları görebilirsiniz.

Verileri CSV dosyalarına kaydedebilirsiniz.

Her aşamada, sistem doğru giriş yapılana kadar kullanıcıyı yönlendirir ve hatalı girişleri engeller.

