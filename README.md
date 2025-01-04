## ETS2 Telemetri Web Sunucusu 3.2.5 + Mobil Kontrol Paneli

Bu, WebSockets tabanlı C# ile yazılmış [Euro Truck Simulator 2](http://www.eurotrucksimulator2.com/) ve [American Truck Simulator](http://www.americantrucksimulator.com/) için ücretsiz bir Telemetri Web Sunucusudur. ve REST API'si. İstemci tarafı, herhangi bir modern masaüstü veya mobil tarayıcıda çalışan, kaplanabilir bir HTML5 mobil kontrol paneli uygulamasından oluşur. Android kullanıcıları ayrıca sağlanan yerel Android uygulamasını da kullanabilir.   

## Ana Özellikler

- Ücretsiz ve açık kaynak ile kendi kontrol panelinizi oluşturup kullanabilirsiniz
- Otomatik kurulum menüsü bulunmaktadır
- Telemetri verileri için REST API kullanılır
- WebSockets'e dayalı canlı telemetri veri akışı için HTML5 kontrol paneli uygulaması bulunur
- Özel kontrol paneli görünümleri için güçlü destek (görünüm eğitimi dahil) bulunur
- HTTP protokolü aracılığıyla belirli bir URL'ye yayınlanan telemetri verileri desteklenir

## KURULUM NOTLARI

### Desteklenen İşletim Sistemi

- **Windows Vista, Windows 7, 8 veya 10 (32 bit veya 64 bit)**. Windows XP'yi desteklemiyor.
- **.NET Framework 4.5** (Windows 8+'de önceden yüklenmiştir). Yüklü değilse, sunucuyu çalıştırdığınızda yüklemeniz istenecektir. 

### Desteklenen oyunlar

- Euro Truck Simulator 2 (32 bit veya 64 bit) sürüm 1.15+ (Steam veya Bağımsız).  
- American Truck Simulator (Steam veya Bağımsız)
- Çok oyunculu versiyonlar da desteklenmektedir. (TruckersMP veya Oyun İçi Konvoylar)

### Test edilen tarayıcılar

- Mobile Safari çalıştıran iOS 8+ (şiddetle tavsiye edilir, en iyi kullanıcı deneyimi)
- En son Firefox, Chrome, Microsoft edge veya IE11 (Firefox veya Chrome önerilir)
- Android 4+ (4.4+ şiddetle tavsiye edilir) Varsayılan veya Chrome tarayıcılar (performans sorunlarınız varsa tarayıcınızın SSS bölümüne bakınız)

### Kurulum

1. Bu sayfanın sağ tarafındaki **Releases** düğmesini tıklayarak **Ets2-Ats-Telemetri-Yoneticisi-Kurulum.exe** dosyasını indirin. 
2. **Ets2-Ats-Telemetri-Yoneticisi-Kurulum.exe** dosyasını çalıştırın 
3. Kurulumu gerçekleştirmek için bütün adımları sırasıyla takip ediniz 
4. Kurulum tamamlandığında masaüstünüze gelen kısayolu çift tıklayıp çalıştırınız
5. Kur butonuna basıp kurulumun bitmesini bekleyiniz
6. Wifi ile bağlanmak için **Wi-Fi** seçeneğini, (uzaktan bir telefon ile bağlanacaksanız bunu kullanın) kişisel bilgisayarınızda bir tarayıcıda çalıştıracaksanız **Loopback Pseudo-Interface 1** seçeneğini seçiniz.
7. HTML5 Uygulamada bulunan linke tıklayıp tarayıcınızda bağlantıyı açınız.
8. Oyununuzu çalıştırınız (Ets 2 veya Ats) 

### Kaldırma

Sunucu beklentilerinizi karşılamadıysa ve onu kaldırmaya karar verirseniz:

1. Euro Truck Simulator / American Truck Simulator'dan çıkış yapınız
2. Sunucunun menüsünden seçim yapın: Sunucu -> Kaldır
3. Açılan pencerede "**Kaldır**" düğmesini tıklayın
4. NOT: Eğer hatalarla birlikte kaldırıldıysa lütfen kurulum dizinini ve oyununuzda bulunan telemetry-server.dll dosyasını silip Steam'den oyun dosyalarını doğrulamayı unutmayınız.

##### NOT #####

Ben sadece bu uygulamayı Türkçe'ye çevirip oyunların sürüm desteğini genişlettim.(Ets 2 ve Ats'nin son sürümlerinde sıkıntı çıkarıyordu.)
Bu programın yapımcına https://github.com/Funbit/ets2-telemetry-server burdan ulaşabilirsiniz.
