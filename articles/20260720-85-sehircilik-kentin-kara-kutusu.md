---
title: "Kentin Kara Kutusu: Bir Şehir Çöktüğünde Geride Ne Kalmalı?"
date: "2026-07-20"
series: "GPTMakes Haftalık Dergi"
number: 85
category: "sehircilik-ve-afet-sistemleri"
reading_time: "yaklaşık 18 dk"
tags:
  - şehir dayanıklılığı
  - afet sistemleri
  - kara kutu
  - yerel veri
  - kentsel hafıza
summary: "Şehirlerin yalnızca çalışırken değil, çökerken de anlaşılabilir olması gerektiğini; uçaklardaki kara kutu fikrinin kent ölçeğine nasıl taşınabileceğini inceleyen uzun-form deneme."
volume: "Volume 2026"
series_name: "Dayanıklı Şehrin Görünmeyen Sistemleri"
series_part: 1
durability_score: 10
related_topics:
  - afet sonrası inceleme
  - sensör ağları
  - yerel arşiv
  - altyapı adaleti
  - operasyonel hafıza
related_articles_note: "Afet sonrası zamanın mimarisi, hasta şehirlerin triaj masası ve kırık altyapıların ahlakı yazılarıyla birlikte okunabilir."
---

# Kentin Kara Kutusu: Bir Şehir Çöktüğünde Geride Ne Kalmalı?

Bir uçak düştüğünde herkes enkaza bakar; uzmanlar ise enkazın içindeki hafızayı arar.

Motorun son titreşimi, irtifadaki küçük sapma, kokpitte söylenen yarım bir cümle, bir sensörün beklenmedik değeri… Felaketin ardından anlamı kuran şey çoğu zaman büyük parçalar değil, düzenli kaydedilmiş küçük izlerdir. Uçak kazalarını yalnızca trajedi olarak bırakmayıp öğrenilebilir olaylara dönüştüren temel araç, halk arasında “kara kutu” dediğimiz kayıt sistemidir.

Şehirlerde ise durum tuhaf biçimde tersidir. Milyonlarca insanı barındıran, suyu, elektriği, ulaşımı, hastaneleri, haberleşmeyi ve gündelik hayatı birbirine bağlayan dev sistemler çöktüğünde çoğu zaman elimizde bütünlüklü bir kayıt bulunmaz. Hangi trafo önce sustu? Hangi kavşakta ambulans akışı kilitlendi? Hangi mahallede mobil şebeke kesildi? Hangi hastanenin jeneratörü yakıtı olduğu hâlde soğutma sorunu yüzünden devre dışı kaldı? Hangi tahliye kararı hangi veriye dayanıyordu? Bunlar aylar sonra parçalı raporlardan, tanıklıklardan, kamera görüntülerinden ve kurumların birbirini tutmayan kayıtlarından yeniden kurulmaya çalışılır.

Bu yazının ana fikri şudur: **Her modern şehir, yalnızca çalışan bir işletim sistemine değil, çöküşünü kaydeden bağımsız bir kara kutuya da ihtiyaç duyar.**

## Şehirler Neden Kendi Çöküşlerini Hatırlamaz?

Kentler tarih boyunca hafıza üretmiştir. Taş kitabeler, vergi kayıtları, su yolları, sur onarımları, mezarlıklar, yangın fermanları ve mahkeme defterleri geçmiş şehirlerin nasıl işlediğini anlamamızı sağlar. Fakat bunlar genellikle olayların ardından tutulmuş insan anlatılarıdır. Modern kent ise çok daha hızlı ve karmaşık çalışır. Bir elektrik kesintisi saniyeler içinde haberleşmeyi, ulaşımı, su pompalarını, hastane cihazlarını ve ödeme sistemlerini etkileyebilir.

Bu karmaşıklığa rağmen kentsel kayıt çoğu zaman kurumsal silolar içinde dağılır. Elektrik dağıtım şirketi kendi sistemini, belediye trafik merkezini, hastane bilgi işlem altyapısını, telekom operatörü baz istasyonlarını izler. Her kurum kendi ekranında bir parçayı görür; fakat kentin bütününün aynı anda nasıl davrandığını kaydeden bağımsız bir katman yoktur.

Dahası, olağan zamanda çalışan birçok kayıt sistemi afet anında ilk kaybolan şeylerden biridir. Bulut bağlantısı kesilir, merkezi veri merkezi erişilemez hâle gelir, saat senkronizasyonları bozulur, cihazlar farklı zaman damgaları üretir, loglar üzerine yazılır veya depolama alanı dolar. Felaketin kendisi, felaketin kaydını da bozar.

Bir kara kutu fikrinin gücü burada ortaya çıkar: Sistem, olaydan bağımsız değil; olay sırasında hayatta kalmak üzere tasarlanır.

## Uçaktan Şehre Taşınabilecek Üç İlke

Havacılıktaki kayıt sistemlerinin kentlere doğrudan kopyalanması mümkün değildir. Bir şehir, tek gövdeli bir makine değildir. Yine de üç temel ilke uyarlanabilir.

### 1. Kayıt, işletmeciden bağımsız olmalıdır

Bir kurum kendi performansını kaydettiğinde kaçınılmaz olarak seçici olur. Bu her zaman kötü niyet anlamına gelmez. Kurumlar kendi sorumluluk alanlarını ölçer, kendi teknik dilini kullanır ve kendi risklerini önceler. Kent kara kutusu ise belediye, enerji şirketi, telekom operatörü veya hastane zincirinden herhangi birinin mülkü olmamalıdır. Bağımsız, denetlenebilir ve çok paydaşlı bir yapıda çalışmalıdır.

### 2. Kayıt sistemi arıza anında da çalışmalıdır

Kara kutunun enerji kaynağı, iletişim yöntemi ve depolama mimarisi ana sistemlerden bağımsız olmalıdır. Güneş paneli, uzun ömürlü batarya, düşük güç tüketimli işlemci, LoRa benzeri dar bant haberleşme ve fiziksel olarak dağıtılmış düğümler bu yüzden önemlidir. Amaç yüksek çözünürlüklü her şeyi kaydetmek değil; kritik göstergelerin zaman çizelgesini korumaktır.

### 3. Kayıt sonradan yorumlanabilir olmalıdır

Ham veri tek başına hafıza değildir. On yıl sonra bir dosyanın açılması, içindeki değerlerin anlaşılacağı anlamına gelmez. Format, sensör kimliği, konum, kalibrasyon, zaman standardı ve bağlam korunmazsa kayıt anlamsızlaşır. Bu nedenle kent kara kutusu yalnızca veri değil, verinin sözlüğünü de saklamalıdır.

## Ne Kaydedilmeli?

Burada ilk refleks her şeyi kaydetmektir. Bu refleks yanlıştır. Her şeyi kaydetmeye çalışan sistem, maliyet, mahremiyet ve veri gürültüsü altında çöker. Kent kara kutusu gözetim makinesi değil, olay rekonstrüksiyon aracı olmalıdır.

Temel kayıt katmanları şöyle düşünülebilir:

- Elektrik şebekesinde kritik düğümlerin durum değişiklikleri
- Su basıncı ve ana hat kesintileri
- Hastanelerin enerji, oksijen, yatak ve acil servis kapasitesi
- Ana ulaşım koridorlarının geçiş süresi
- İtfaiye ve ambulans hareketlerinin anonimleştirilmiş yoğunluk haritası
- Mobil şebeke ve yerel haberleşme erişilebilirliği
- Hava kalitesi, sıcaklık, su seviyesi, sismik hareket gibi çevresel göstergeler
- Resmî uyarıların yayın zamanı ve ulaştığı tahmini nüfus
- Kritik kararların kim tarafından, hangi veriyle ve ne zaman alındığını gösteren idari kayıtlar

Buradaki amaç tek tek insanların hareketlerini takip etmek değildir. Tam tersine, bireysel veriyi en aza indirip sistem davranışını görünür kılmaktır. Bir mahallede kaç kişinin bulunduğunu değil, o mahallede iletişimin ne zaman kesildiğini bilmek çoğu afet incelemesi için yeterlidir.

## Kara Kutunun Fiziksel Mimarisi

Tek bir merkezî kutu, şehir ölçeğinde kötü fikirdir. Çünkü tek merkez, tek arıza noktasıdır. Daha gerçekçi model, birbirini doğrulayan dağıtık kayıt düğümleridir.

Her ilçede veya kritik altyapı bölgesinde küçük bir kayıt istasyonu bulunabilir. Bu istasyonlar düşük güçle çalışır, veriyi sıkıştırır, yalnızca durum değişikliklerini kaydeder ve komşu düğümlerle periyodik olarak özet paylaşır. İnternet bağlantısı varsa merkezle eşzamanlanır; yoksa yerelde çalışmayı sürdürür. Düğümlerden biri yok olduğunda diğerleri olayın bir bölümünü korur.

Sistem, “yüksek teknoloji” görüntüsü vermek zorunda değildir. Dayanıklı bir metal kutu, düşük güçlü tek kart bilgisayar, şifreli katı hâl depolama, bağımsız saat modülü, birkaç radyo arayüzü ve basit sensör girişleri çoğu işlevi karşılayabilir. Asıl zorluk donanım değil, yönetişimdir: Kimin erişeceği, neyin kaydedileceği, verinin ne zaman açılacağı ve hangi koşulda silineceği.

## Mahremiyet İtirazı

Kentin kara kutusu fikrine yöneltilecek en güçlü eleştiri açıktır: Böyle bir sistem kolayca kitlesel gözetim altyapısına dönüşebilir.

Bu itiraz ciddiye alınmalıdır. Afet güvenliği, tarih boyunca olağanüstü yetkilerin gerekçesi olmuştur. “Sadece kriz anında kullanılacak” denilen teknolojiler zamanla gündelik denetimin parçasına dönüşebilir. Bu nedenle sistemin tasarımında mahremiyet sonradan eklenen bir özellik değil, mimarinin temeli olmalıdır.

Birincisi, kişisel veri mümkün olduğunca hiç toplanmamalıdır. İkincisi, kayıtlar sürekli merkezî akış yerine yerelde tutulmalı ve yalnızca belirli eşikler aşıldığında paylaşılmalıdır. Üçüncüsü, şifre çözme anahtarları tek kurumda bulunmamalı; bağımsız kurumlara dağıtılmış çoklu onay mekanizması kullanılmalıdır. Dördüncüsü, kayıt erişimi kamuya açık tutanaklarla izlenmelidir.

En kritik ilke ise şudur: Kara kutu, insanları değil sistemleri izlemelidir.

## Siyasi İtiraz: Kimse Gerçek Bir Kara Kutu İstemez

Teknik olarak yapılabilir bir sistemin siyasi olarak istenmeyebileceğini kabul etmek gerekir. Çünkü gerçek bir kara kutu yalnızca arızayı değil, ihmali de görünür kılar. Uyarının geç yayımlandığını, bakımın ertelendiğini, jeneratör testinin kâğıt üzerinde yapıldığını veya bir mahallenin sistematik olarak düşük öncelik aldığını gösterebilir.

Kurumlar belirsizliği sever demek haksızlık olur; fakat belirsizlik sorumluluğu dağıtır. Verinin eksik olduğu yerde herkes kendi anlatısını kurabilir. Bağımsız zaman çizelgesi ise kararların sonuçlarını sert biçimde ortaya çıkarır.

Bu nedenle kent kara kutusu teknik projeden önce demokratik bir projedir. Toplum, felaket sonrasında yalnızca “ne oldu?” sorusunu değil, “neden böyle oldu ve kim hangi kararı verdi?” sorusunu sormayı kabul etmelidir.

## Özgün Düşünce Deneyi: Şehir 72 Saat Boyunca Konuşamasaydı

Bir milyon nüfuslu bir şehrin şiddetli depremden sonra 72 saat boyunca dış dünyayla iletişimini kaybettiğini düşünelim. İnternet yok, mobil şebeke parçalı, ana veri merkezi erişilemiyor. Kentin farklı bölgelerinde su, elektrik ve ulaşım durumu birbirinden tamamen farklı.

Üç gün sonra bağlantı geri geliyor. Şehir, dışarıya ne anlatabilir?

Geleneksel modelde her kurum kendi raporunu hazırlar. Belediye yolları, elektrik şirketi şebekeyi, hastaneler hasta yükünü, güvenlik birimleri olayları aktarır. Raporlar haftalar sonra birleşir; zaman damgaları tutmaz, boşluklar vardır.

Kara kutu modelinde ise şehir tek bir “durum günlüğü” üretir. Saat 04.18’de ana elektrik hattının koptuğu, 04.26’da iki hastanenin jeneratöre geçtiği, 05.10’da kuzey su deposunun basınç kaybettiği, 06.40’ta doğu koridorunun tamamen tıkandığı, 08.15’te ilk yerel radyo ağının kurulduğu görülebilir. İnsan hikâyeleri sonradan bu omurgaya bağlanır.

Bu kayıt, yalnızca hesap sormak için değil, bir sonraki afetin senaryosunu gerçek verilere göre yazmak için kullanılır.

## Geleceğin Şehir Planlaması: Performans Değil Öğrenme Kapasitesi

Bugün akıllı şehir söylemi çoğunlukla verimlilik etrafında döner: Trafik daha hızlı aksın, enerji daha az tüketilsin, sensörler arızayı önceden bildirsin. Oysa dayanıklı şehir için daha temel bir ölçüt vardır: **Şehir kendi hatasından ne kadar hızlı öğrenebiliyor?**

Bir sistem hiç hata yapmayacak şekilde tasarlanamaz. Depremler tahmin edilenden büyük, yangınlar beklenenden hızlı, insan davranışları modellerden farklı olabilir. Dayanıklılık kusursuzluk değil, hatayı tanıma ve yeniden örgütlenme kapasitesidir.

Kara kutu bu nedenle pasif kayıt cihazı değildir. Tatbikatların gerçekçi olup olmadığını, kaynakların hangi mahallelere geç ulaştığını, hangi yedek sistemlerin yalnızca kâğıt üzerinde var olduğunu gösteren bir öğrenme altyapısıdır.

## Kapanış: Enkazdan Önce Hafızayı İnşa Etmek

Felaketlerden sonra en sık duyulan cümlelerden biri “Bunu öngörmek mümkün değildi” olur. Bazen gerçekten mümkün değildir. Fakat çoğu zaman sorun öngörü değil, geçmiş olaylardan yeterince öğrenmemektir.

Bir şehir yalnızca binalardan, yollardan ve borulardan oluşmaz. Aynı zamanda kararların, gecikmelerin, arızaların ve başarılı müdahalelerin birikimidir. Bu birikim kaydedilmezse her afet, ilk kez yaşanıyormuş gibi karşılanır.

Kentin kara kutusu, gelecekteki araştırmacılar için teknik bir arşivden daha fazlasıdır. O, şehrin kendine karşı dürüst olma cihazıdır.

Çünkü enkaz kaldırılabilir, yollar yeniden yapılabilir, kablolar yenilenebilir. Fakat bir toplum felaketin gerçek sırasını kaybederse, aynı hatayı yeni betonun altında tekrar inşa eder.

## Kaynak Notları

Bu yazı; havacılıktaki uçuş veri kaydedicileri, kritik altyapı dayanıklılığı, olay günlükleme sistemleri, dağıtık sensör ağları, afet sonrası adli mühendislik ve mahremiyet odaklı tasarım ilkelerinden hareketle hazırlanmıştır. Kavram, mevcut tek bir standarttan ziyade farklı disiplinlerin kent ölçeğinde birleştirilmesine dayanan önerisel bir modeldir.

## İlişkili Okuma Ağı

- Afet Sonrası Zamanın Mimarisi
- Hasta Şehirlerin Triaj Masası
- Kırık Altyapıların Ahlakı
- Afet İletişimi: Sessizliğin Protokolü
- Kentlerin Yedek Hafızası

## Kalıcılık Notu

Bu metnin kalıcılık değeri, belirli bir teknoloji veya güncel olaydan çok, kentlerin kendi başarısızlıklarını kaydetme ve öğrenme zorunluluğuna dayanır. Sensörler, ağ protokolleri ve depolama araçları değişse de bağımsız operasyonel hafıza ihtiyacı varlığını koruyacaktır.