---
title: "Mahallenin Küçük Sunucusu"
date: "2026-07-02"
series: "Dört Kısa Makale"
number: 45
category: "afet-sistemleri"
reading_time: "yaklaşık 20-25 dk"
tags:
  - homelab
  - afet
  - yerel-ag
  - dayanıklılık
summary: "Afet anında internet yokken mahalle, okul, hastane veya apartman ölçeğinde çalışan küçük yerel sunucuların nasıl bilgi omurgası, duyuru panosu ve kriz hafızası olabileceğini tartışan uzun-form deneme."
volume: "Volume 2026"
series_name: "Kırılgan Uygarlık"
series_part: 3
durability_score: 10
related_topics:
  - yerel sunucu
  - offline sistem
  - afet bilgi mimarisi
  - mesh ag
related_articles_note: "Bu yazı internet kesintisi, gökyüzü altyapısı, SARP, QR triyaj, LoRa, dijital ikizler ve mahalle dayanıklılığı üzerine kurulan GPTMakes metinleriyle birlikte okunabilir."
---

# Mahallenin Küçük Sunucusu

İnternet kesildiğinde bilgi yok olmaz.

Yalnızca uzak sunuculara giden yol kapanır.

Bir mahallede suyun nerede olduğu hâlâ biliniyordur. Hangi sokakta enkaz olmadığı, hangi binada yaşlı kaldığı, kimin ilaca ihtiyacı olduğu, hangi okul bahçesinin açık olduğu, hangi apartmanın boşaltıldığı, hangi gönüllünün telsizi olduğu, hangi jeneratörün çalıştığı bilgisi hâlâ üretilir.

Sorun, bu bilginin dolaşamamasıdır.

Modern dijital hayat bilgiyi uzaktaki bulutlara taşımaya alıştı. Normal zamanda bu verimli, rahat ve güçlüdür. Ama afet anında en zayıf halka bazen tam da bu uzaklıktır. Yerel bilgi yerelde üretilir, ama yerel ağ yoksa insanlar birbirine ulaşamaz.

Mahallenin küçük sunucusu fikri buradan doğar: Afet anında internet olmasa bile birkaç yüz metre içinde bilgi akışını sürdürecek, sade, dayanıklı, düşük güç tüketimli bir yerel bilgi omurgası.

Büyük teknoloji değil.

Küçük bir kutu, yerel Wi-Fi, basit bir web arayüzü, batarya, önceden hazırlanmış veri formları ve biraz toplumsal güven.

## Kısa Giriş: Bulutun Altındaki Katman

Bulut bilişim gündelik hayatı kolaylaştırdı. Dosyalar uzakta, uygulamalar çevrimiçi, veriler senkronize, haritalar güncel, mesajlar anlık. Ama bulutun görünmez bir varsayımı vardır: bağlantı.

Afette bu varsayım kırılabilir. Fiber kopar, baz istasyonu susar, elektrik gider, DNS çalışmaz, uygulamalar açılmaz, kimlik doğrulama yapılamaz, harita yüklenmez, mesaj kuyruğa düşer. İnsanlar hâlâ aynı mahallededir; ama dijital olarak birbirinden kopar.

Bu yüzden afet mimarisinde bulutun altında bir yerel katman gerekir. İnternet varsa dış dünyayla konuşan, yoksa içeride çalışmaya devam eden sistemler. Buna offline-first yaklaşım denebilir: önce yerelde çalış, bağlantı gelirse senkronize ol.

Mahalle sunucusu, bu fikrin en küçük ve en pratik biçimlerinden biridir.

Bir okulda, apartman sitesinde, muhtarlıkta, hastanede, belediye hizmet noktasında veya afet toplanma alanında küçük bir cihaz çalışır. İnsanlar telefonlarıyla ona bağlanır. Uygulama indirmeden, hesap açmadan, internet gerektirmeden temel bilgilere ulaşır ve güncelleme yapar.

Afette bazen en güçlü sistem, en az şeye ihtiyaç duyan sistemdir.

## Yerel Bilgi Neden Değerlidir?

Afet bilgisinin büyük kısmı yereldir. Bir ulusal kriz merkezi çok şey bilebilir; ama her apartmanın kapısını, her sokağın gerçek durumunu, her bodrumun su alıp almadığını, her yaşlının evde olup olmadığını ilk anda bilemez.

Mahalle bilir.

Ama mahalle bilgisi dağınıktır. Bir kişi su noktasını bilir, biri ilaca ihtiyaç duyanı, biri açık yolu, biri yıkılmamış binayı, biri çalışan jeneratörü. Bu bilgi konuşmalar, notlar, sosyal medya mesajları, bağırışlar, kağıt listeler ve kişisel hafızalar arasında parçalanır.

Küçük sunucu bu parçalı bilgiyi tek bir yerel panoya dönüştürebilir.

Temel modüller çok basit olabilir:

Durum panosu: Hangi alan güvenli, hangi yol kapalı, hangi bina boşaltıldı?

İhtiyaç kaydı: Su, ilaç, battaniye, jeneratör, bebek maması, tıbbi destek.

Kapasite kaydı: Kimde araç var, kim sağlık personeli, kim telsiz kullanabiliyor, hangi yerde şarj var?

Kırılgan kişi kontrolü: Yalnız yaşayanlar, hareket kısıtlılığı olanlar, tıbbi cihaz bağımlıları için mahremiyetli takip.

Duyuru panosu: Resmi veya yerel doğrulanmış kısa bilgiler.

Harita: Offline çalışan basit mahalle haritası, toplanma noktaları, su ve sağlık noktaları.

Bu modüllerin amacı her şeyi dijitalleştirmek değildir. Kaosu biraz düzenlemektir.

## Teknik Sadelik, Sosyal Zorluk

Mahalle sunucusunun teknik hali görece basit olabilir. Küçük bir bilgisayar, batarya, yerel Wi-Fi yönlendirici, offline web uygulaması, QR kodla giriş, basit formlar. Zor olan sosyal kısımdır.

Kim yönetecek? Kim bilgi girecek? Hangi bilgi doğru sayılacak? Yanlış kayıt nasıl düzeltilecek? Mahrem veriye kim erişecek? İnsanlar sistemi krizden önce tanıyacak mı? Elektrik kesilince kim açacak? Bataryayı kim şarjlı tutacak? Cihaz nerede duracak?

Afet sistemlerinde teknik çözüm, sosyal protokol olmadan çalışmaz.

Bu yüzden mahalle sunucusu yalnızca donanım kutusu değildir. Bir bakım ve güven sistemi gerektirir. Muhtar, apartman sorumluları, okul yönetimi, yerel gönüllüler, sağlık çalışanları ve belediye ekipleri önceden rol paylaşmalıdır.

Kriz anında yeni sistem öğrenilmez. Kriz anında yalnızca önceden prova edilmiş basit şeyler çalışır.

Bu nedenle arayüz aşırı sade olmalıdır. Büyük düğmeler, kısa formlar, renk kodları, düşük okuryazarlık eşiği, çok dilli destek, erişilebilir tasarım, internet gerektirmeyen çalışma. Kullanıcı panik halindeyken bile ne yapacağını anlamalıdır.

Mahalle sunucusu teknoloji değil, prova edilmiş alışkanlıktır.

## Mahremiyet ve Güvenlik

Yerel afet bilgisi hassas olabilir. Kimin evde olmadığı, hangi binanın boşaltıldığı, kimde jeneratör olduğu, hangi kişinin ilaca ihtiyaç duyduğu, hangi ailede çocuk olduğu bilgisi kötüye kullanılabilir.

Bu yüzden mahalle sunucusu "her şeyi herkes görsün" mantığıyla kurulamaz. Bilgi katmanları gerekir.

Kamusal bilgi: Su noktası, toplanma alanı, yol durumu, genel duyurular.

Sınırlı bilgi: Gönüllü ekiplerin görebileceği ihtiyaç kayıtları, görev listeleri, kaynak kapasitesi.

Hassas bilgi: Sağlık, yaşlı, çocuk, tıbbi cihaz, evde yalnız kalma gibi yalnız yetkili kişilerin erişeceği kayıtlar.

Veri mümkün olduğunca az toplanmalıdır. Afet için gerekli olmayan kişisel ayrıntılar istenmemelidir. Kayıtların ne zaman silineceği belli olmalıdır. Sistem internet geldiğinde dışarıya ne gönderdiğini açıkça göstermelidir.

Güvenlik yalnızca şifreleme değildir. Sosyal güvenlik de vardır: Kim cihazı yönetiyor, kim yetki veriyor, kim kayıtları siliyor, kim yanlış bilgiyi düzeltiyor?

İnsanlar sisteme güvenmezse, en iyi sunucu boş kalır.

## Düşünce Deneyi: Apartmanın Afet Kutusu

Her apartman sitesinde veya okulda küçük bir afet kutusu olduğunu düşünelim.

İçinde powerbank, basit telsiz, QR kartlar, küçük yerel sunucu, güneş paneli, birkaç basılı form, mahalle haritası, acil kişi listesi protokolü ve kısa kullanım talimatı var.

Elektrik kesildiğinde kutu açılıyor. Sunucu çalışıyor. Telefonlar "Mahalle-Afet" adlı yerel ağa bağlanıyor. Tarayıcı açılınca otomatik olarak basit bir sayfa geliyor:

"Güvendeyim."

"Yardıma ihtiyacım var."

"Birini kontrol et."

"Su/ilaç/gıda ihtiyacı bildir."

"Duyuruları oku."

"Gönüllü olarak kayıt ol."

İnternet yok. Ama mahalle içinde bilgi akıyor. Bir görevli her saat kağıt panoya özet yazıyor. Uydu ya da telsiz bağlantısı varsa dış koordinasyona sıkıştırılmış özet gidiyor.

Bu sistem mükemmel değildir. Ama kaosu azaltır. İnsanlara yalnız olmadığını gösterir. Bilgiyi aynı yere toplar. Tekrarlı panik mesajları yerine sınıflandırılmış ihtiyaç üretir.

Krizde bazen en büyük fark, bilginin nerede toplanacağını bilmektir.

## Karşıt Görüşler ve Eleştiriler

Birinci eleştiri bakım yüküdür. Cihaz alınır ama unutulur, batarya ölür, yazılım eskir, şifre kaybolur, kimse kullanmayı bilmez. Bu gerçek bir risktir. Çözüm, cihazı "satın alınan ürün" değil, düzenli tatbikat ve bakım gerektiren altyapı olarak görmektir.

İkinci eleştiri kullanım alışkanlığıdır. İnsanlar kriz anında bilmedikleri sisteme güvenmez. Bu yüzden mahalle sunucusu yılda bir kez değil, küçük etkinliklerde de kullanılabilir: mahalle duyurusu, tatbikat, okul afet günü, gönüllü kaydı. Sistem normal zamanda tanıdık hale gelmelidir.

Üçüncü eleştiri veri doğruluğudur. Yanlış bilgi girilebilir, söylenti yayılabilir, kötü niyetli kayıt yapılabilir. Bu nedenle doğrulama düzeyleri gerekir: bildirildi, gönüllü gördü, resmi ekip doğruladı, çözüldü. Her kayıt kesin bilgi gibi görünmemelidir.

Dördüncü eleştiri erişimdir. Herkes akıllı telefon kullanmayabilir. Bu yüzden yerel sunucu kağıt formlar, duyuru panosu, gönüllüler ve sözlü bilgilendirmeyle birlikte çalışmalıdır. Dijital sistem fiziksel sistemi tamamlamalı, onun yerine geçmemelidir.

## Geleceğe Yönelik Çıkarımlar

Birinci çıkarım, afet bilgi mimarisinin yerelden başlamasıdır. Bulut ve ulusal sistemler güçlüdür; ama ilk veri mahallede oluşur. Yerel toplayıcı olmadan merkez kör kalır.

İkinci çıkarım, offline-first tasarımın kamu hizmeti haline gelmesidir. Kritik afet uygulamaları internet yokken de temel işlevlerini sürdürebilmelidir.

Üçüncü çıkarım, küçük sunucuların standartlaşmasıdır. Her belediye, okul veya apartman kendi başına farklı sistem kurarsa karmaşa olur. Açık standartlar, veri formatları, güvenlik ilkeleri ve eğitim materyalleri gerekir.

Dördüncü çıkarım, yerel enerji yedeğidir. Sunucu, yönlendirici ve telefon şarjı için düşük güç, batarya ve güneş desteği planlanmalıdır. Bilgi altyapısı enerji altyapısından ayrı düşünülemez.

Beşinci çıkarım, teknoloji ile insan ağının birlikte kurulmasıdır. Mahalle sunucusu muhtarın, gönüllünün, öğretmenin, sağlık çalışanının, apartman görevlisinin ve komşunun yerini almaz. Onların hafızasını ve koordinasyonunu güçlendirir.

Altıncı çıkarım, belediyelerin bu sistemleri lüks hobi olarak değil, mikro-altyapı olarak görmesidir. Nasıl yangın tüpü, acil çıkış levhası ve toplanma alanı planlanıyorsa, kritik mahalle noktalarında offline bilgi noktaları da planlanabilir.

Yedinci çıkarım, açık kaynak ve yerel sahiplenmedir. Afet anında çalışacak sistemler kapalı, bakımsız ve tek tedarikçiye bağımlı olursa kırılganlaşır. Basit, denetlenebilir, yerel ekiplerin anlayabileceği ve gerektiğinde elle de sürdürülebilecek sistemler daha dayanıklıdır.

## Belediye İçin Uygulama Taslağı

Bir belediye bu fikri hayata geçirmek isterse önce büyük platform kurmak zorunda değildir. Küçük pilotlarla başlayabilir.

İlk adım riskli mahalleleri seçmektir: sel riski, sıcak dalgası kırılganlığı, yaşlı nüfus, iletişim kesintisi geçmişi veya ulaşım zorluğu olan bölgeler. İkinci adım yerel düğüm noktalarını belirlemektir: okul, muhtarlık, aile sağlığı merkezi, spor salonu, kütüphane, ibadet yeri veya apartman sitesi yönetimi.

Üçüncü adım teknik kutuyu değil, protokolü tasarlamaktır. Kim açacak, kim bilgi girecek, kim doğrulayacak, kim kağıt panoya özet yazacak, kim hassas veriye erişecek? Dördüncü adım tatbikattır. Sistem yılda bir kez değil, küçük mahalle egzersizleriyle tanıdık hale gelmelidir.

Beşinci adım, sistemin analog yedeğini kurmaktır. QR kart çalışmazsa kağıt form, Wi-Fi çalışmazsa pano, telefon yoksa gönüllü listesi, elektrik yoksa basılı harita devreye girmelidir.

Mahalle sunucusu fikri en iyi şu ilkeyle çalışır: Dijital olan analog olanı yok etmez; onun hızını ve düzenini artırır.

## Güçlü Kapanış: Dijital Çağın Muhtarı

Büyük afetlerde büyük sistemler gerekir. Ulusal koordinasyon, uydu bağlantısı, profesyonel ekipler, hastane ağları, lojistik merkezleri. Ama ilk düzen bazen küçük bir kutudan başlar.

Mahallenin küçük sunucusu, dijital çağın muhtarı gibi çalışabilir.

Her şeyi bilmez. Herkesi kurtarmaz. Ama bilgiyi toplar, duyuruyu taşır, ihtiyacı görünür kılar, dış dünya susarken içeride bir düzen kurar.

İnternet yokken bile toplum tamamen çevrimdışı kalmak zorunda değildir.

Yeter ki bilgi, önce yakınındaki insana ulaşabilsin.

## Kaynak Notları

Bu yazı offline-first yazılım, mesh ağlar, yerel sunucular, afet iletişimi, düşük bant genişlikli veri protokolleri, homelab kültürü ve mahalle dayanıklılığı tartışmalarından ilham alır. Metin belirli bir ürün önerisi değildir; afet anında yerel bilgi omurgasının neden gerekli olduğunu tartışan kuramsal bir denemedir.

Mahalle sunucusu fikri, bulut sistemlerinin yerine geçmeyi değil, bağlantı kesildiğinde temel bilgiyi yerel ölçekte sürdürebilmeyi hedefler. Değeri teknik kapasitesinden çok, önceden hazırlanmış sosyal protokol ve sade kullanım alışkanlığıyla ortaya çıkar.

## İlişkili Okuma Ağı

- "İnternet Kesilince Toplumun Gerçek Ağları Ortaya Çıkar" yazısıyla offline afet protokolleri üzerinden doğrudan bağlanır.
- "Uydu Telefonu Değil, Gökyüzü Altyapısı" yazısıyla yerel özet verinin dış koordinasyona taşınması fikrini paylaşır.
- "Şehirlerin Gölge Nüfusu" yazısıyla kırılgan kişilerin mahremiyetli yerel takibi temasına bağlanır.
- "Su Basınca Şehir Yalan Söylemez" yazısıyla bakım verisi ve yerel afet panoları üzerinden ilişki kurar.
- SARP sistem tasarımı için yerel veri omurgası fikrini destekler.

## Kalıcılık Notu

Merkezi sistemler güçlendikçe bile yerel dayanıklılık ihtiyacı ortadan kalkmayacak. İnternet, bulut ve uydu bağlantıları gelişse de kriz anında yakın çevrede bilgi toplama, doğrulama ve paylaşma gereği sürecek. Bu yazı belirli bir cihazdan çok yerel bilgi mimarisine odaklandığı için uzun ömürlüdür.
