---
title: "Afet Anında Çalışan Şehrin Sessiz İşletim Sistemi"
date: "2026-07-02"
series: "GPTMakes Düşünce Arşivi"
number: 61
category: "afet-sistemleri"
reading_time: "yaklaşık 15-20 dk"
tags:
  - afet
  - sehir-direnci
  - yerel-aglar
  - altyapi
  - kriz-yonetimi
summary: "Bir şehrin gerçek dayanıklılığının büyük kahramanlık anlarında değil, elektrik kesildiğinde, internet sustuğunda ve insanlar birbirini ararken çalışan küçük yerel protokollerde saklı olduğunu anlatan uzun-form bir deneme."
volume: "Volume 2026"
series_name: "Dayanıklı Şehirler"
series_part: 1
durability_score: 9
related_topics:
  - yerel ilk sistemler
  - afet triyaji
  - kent hafizasi
  - kritik altyapi
  - offline koordinasyon
related_articles_note: "Bu yazı ileride yerel-first sağlık sistemleri, afet sonrası bilgi mimarisi ve post-apokaliptik arşiv konularındaki yazılarla birlikte okunabilir."
---

# Afet Anında Çalışan Şehrin Sessiz İşletim Sistemi

Bir şehir çoğu zaman kendisini ışıklarıyla tanıtır. Gece uzaktan bakıldığında yolların çizgisi, apartmanların pencereleri, reklam panoları, hastane tabelaları ve kavşaklardaki kırmızı yeşil ritim bize bir düzen hissi verir. Şehir çalışıyordur. Su akar, internet gelir, ambulans yerini bulur, market kasası barkodu okur, telefon baz istasyonu konuşmayı taşır. Fakat bu düzenin ne kadarının gerçekten şehre ait olduğu, ancak o ışıklar söndüğünde anlaşılır.

Afet anı, şehrin makyajını siler. Deprem, sel, yangın, büyük elektrik kesintisi veya iletişim çöküşü olduğunda modern şehir birdenbire kendi bedenine döner. Artık uygulama bildirimleri, merkezi sunucular, uzak veri merkezleri ve kusursuz harita katmanları değil; sokak köşeleri, okul bahçeleri, mahalle muhtarları, sağlık çalışanları, telsizler, jeneratörler, su depoları ve insanların birbirini tanıma kapasitesi belirleyici olur. Şehir o anda bir teknoloji projesi olmaktan çıkıp bir organizmaya dönüşür.

Bu yazının ana fikri basit ama rahatsız edici: Bir şehrin afet dayanıklılığı, en parlak kontrol merkezinde değil, merkez çöktüğünde çalışmaya devam eden küçük ve yerel sistemlerde saklıdır. Sessiz işletim sistemi dediğim şey tam olarak budur: normal zamanda görünmeyen, fakat kriz anında şehrin hafızasını, yönünü ve vicdanını taşıyan yerel protokoller bütünü.

## Işıklı şehir ile karanlık şehir arasındaki fark

Modern kent, çoğu zaman merkezi koordinasyon hayaliyle kurulur. Kamera sistemleri, belediye panelleri, acil çağrı merkezleri, hastane bilgi sistemleri, trafik izleme ekranları, meteoroloji verileri ve lojistik yazılımları birbirine bağlandığında sanki büyük bir beyin oluşmuş gibi düşünürüz. Bu hayal tamamen yanlış değildir. Merkezileşmiş sistemler normal zamanda müthiş verim sağlar. Ambulans sevki hızlanır, trafik akışı optimize edilir, stok takibi yapılır, hastane yatakları görünür hale gelir.

Sorun, afetin tam da bu verim mimarisini hedef almasıdır. Afet merkezi sisteme doğrudan saldırmaz; onu besleyen varsayımları kırar. Elektrik sürekli gelecek varsayımı kırılır. Mobil ağ ayakta kalacak varsayımı kırılır. Yol haritasındaki yol gerçekten geçilebilir olacak varsayımı kırılır. İnsanlar evlerinde bulunacak varsayımı kırılır. Tek bir koordinasyon merkezinin bütün sahayı görebileceği varsayımı kırılır.

Bu yüzden dayanıklı şehir, sadece daha büyük merkez kuran şehir değildir. Dayanıklı şehir, merkez yokken de kendisini küçük parçalara bölüp çalıştırabilen şehirdir. Tıpkı biyolojide tek bir organın her şeyi yönetmediği, birçok yerel refleksin hayatı sürdürdüğü gibi. Elinizi sıcak bir yüzeye değdirdiğinizde beynin uzun uzun karar vermesini beklemezsiniz; omurilik düzeyindeki refleks sizi kurtarır. Afet şehrinde de bazı kararların merkezden değil, mahalle ölçeğinden çıkması gerekir.

## Afet protokolü bir belge değil, davranış biçimidir

Kâğıt üzerinde afet planı hazırlamak kolaydır. Bir tablo açılır, sorumlular yazılır, toplanma alanları listelenir, telefonlar eklenir. Fakat gerçek afet protokolü, belgeden çok alışkanlıktır. İnsanlar hangi okul bahçesine gideceğini biliyor mu? Sağlık çalışanı hangi noktada triyaj yapacağını biliyor mu? Mahallede jeneratörü olan işletmeler biliniyor mu? Yaşlı ve yalnız yaşayan insanlar tanınıyor mu? Eczane, su, battaniye, bebek maması, yakıt ve basit tıbbi malzeme için yerel bir harita var mı?

Eğer bu soruların cevabı sadece belediye sunucusundaki bir PDF dosyasındaysa, o bilgi afet anında kırılgandır. Çünkü bilgiye erişim de altyapıya bağlıdır. Dayanıklı bilgi, birden fazla biçimde var olan bilgidir: basılıdır, yereldedir, ezberdedir, küçük cihazlarda tutulur, mahalle sorumlularında bulunur, düşük enerjiyle çalışır, internete muhtaç değildir.

Burada eski dünyanın bazı yöntemleri şaşırtıcı biçimde modernleşir. Telsiz, ilan panosu, okul bahçesindeki fiziksel liste, QR kodlu kart, yerel Wi-Fi ağı, Raspberry Pi üzerinde çalışan küçük bir web sunucusu, offline harita, batarya destekli mini bilgisayar... Bunların her biri kendi başına mucize değildir. Ama doğru tasarlandıklarında şehrin sessiz işletim sisteminin modüllerine dönüşürler.

## Yerel-first şehir fikri

Yazılım dünyasında local-first diye bir yaklaşım var: Verinin önce kullanıcının cihazında anlamlı ve çalışır durumda bulunması, bulut bağlantısının ise ek kolaylık sağlaması. Bunu şehre uyarladığımızda şu ilkeye varırız: Bir mahallenin temel afet işlevleri, uzak bir merkez olmadan asgari düzeyde çalışabilmelidir.

Bu, merkezi yönetimi reddetmek anlamına gelmez. Tam tersine, merkezi yönetimi daha gerçekçi hale getirir. Merkez, her şeyi tek başına yapmak yerine yerel düğümleri güçlendirir. Mahalleler birer küçük düğüm olur; okullar, aile sağlığı merkezleri, camiler, muhtarlıklar, pazar alanları, hastane çevreleri ve gönüllü ekipler bu ağın parçalarına dönüşür. Merkez çalışıyorsa bu düğümleri koordine eder. Merkez susarsa düğümler kendi başına asgari düzeni sürdürür.

Bir afet ağı için en kritik kavramlardan biri zarif bozulmadır. Kötü sistemler ya tam çalışır ya da tamamen çöker. İyi sistemler ise parça parça bozulur; her kayıpta daha düşük ama hâlâ anlamlı bir işlev seviyesine iner. İnternet yoksa yerel ağ çalışır. Yerel ağ yoksa basılı listeler çalışır. Elektrik yoksa batarya ve jeneratör çalışır. Dijital kayıt yoksa kâğıt triyaj kartı çalışır. GPS yoksa mahalle işaretleri çalışır. Bu katmanlı yapı, kriz anında lüks değil, hayatta kalma mantığıdır.

## Sağlık sisteminin en küçük işletim birimi

Afet anında sağlık sistemi sadece hastaneden ibaret değildir. Hastane, sistemin ağır işlem yapan merkezi gibidir; ama ilk veri girişi sokakta, enkaz kenarında, okul bahçesinde, ambulans bekleme noktasında ve geçici bakım alanında olur. Eğer bu ilk veri karışırsa, sonraki bütün akış bulanıklaşır.

Bir kişinin kim olduğu, nereden çıkarıldığı, hangi yakınması olduğu, hangi müdahaleyi aldığı, hangi noktaya sevk edildiği ve kiminle birlikte olduğu gibi bilgiler küçük görünür. Fakat afet anında bunlar şehrin hafızasıdır. Hafıza kaybı yaşayan şehir, aynı kişiyi iki kez arar, yanlış kişiye ulaştığını sanır, kaynakları yanlış yere gönderir, aileleri belirsizlikte bırakır.

Bu nedenle afet triyajı sadece renk kodu meselesi değildir. Aynı zamanda bilgi mimarisi meselesidir. QR kartlar, basit numaralandırma, offline çalışan kayıt sistemi, yerel ağ üzerinden açılan küçük formlar, USB veya LoRa ile sonradan merkezle eşleşen veri paketleri, hepsi aynı soruya cevap verir: Şehir yaralıyken hafızasını nasıl kaybetmez?

## Karşıt görüş: Aşırı yerelleşme kaos üretmez mi?

Bu fikre güçlü bir itiraz var: Her mahalle kendi sistemini kurarsa standart kaybolur, veri parçalanır, koordinasyon zorlaşır. Bu itiraz ciddiye alınmalıdır. Afet gibi yüksek riskli alanlarda amatörlük romantize edilemez. Yanlış tıbbi kararlar, hatalı sevkler, yetkisiz müdahaleler ve uyumsuz veri formatları zarar verebilir.

Fakat burada savunulan şey başıboş yerelleşme değildir. Standartları merkez belirler; işlev merkezsizleşir. Yani form alanları, renk kodları, kimlik eşleştirme mantığı, veri dışa aktarma biçimi, etik sınırlar ve görev tanımları ortak olabilir. Ancak sistemin çalışması tek bir merkeze bağımlı olmaz. Bu, havacılıktaki yedek sistem mantığına benzer. Kokpitte standart prosedür vardır; ama tek gösterge bozulunca uçak düşmez.

Bir başka itiraz da maliyettir. Her mahalleye afet düğümü, batarya, cihaz, eğitim ve bakım koymak pahalı görünür. Fakat afet sonrası kaosun maliyetiyle karşılaştırıldığında bu yatırım çoğu zaman küçük kalır. Üstelik bu altyapının tamamı afet dışında da işe yarayabilir: mahalle sağlığı eğitimi, yerel duyuru, gönüllü koordinasyonu, yaşlı takibi, küçük çevre sensörleri, hava kalitesi ölçümü, okul tatbikatları. İyi tasarlanmış direnç altyapısı, sadece felaket günü değil, sıradan günlerde de şehir kültürünü güçlendirir.

## Bir düşünce deneyi: İnternetsiz 72 saat

Bir şehir düşünelim. Büyük bir deprem olmuş. İlk 72 saat boyunca mobil internet çok zayıf, elektrik kesintili, bazı yollar kapalı. Merkezi kriz masası var ama sahadan veri almakta zorlanıyor. Bu şehirde iki farklı mahalle olsun.

Birinci mahallede her şey merkeze bağlı. İnsanlar toplanma alanının nerede olduğunu belirsiz hatırlıyor. Sağlık noktası doğaçlama kuruluyor. Yaralı kayıtları farklı defterlere yazılıyor. Telefonlar çekmediği için aileler birbirini bulamıyor. Gönüllüler iyi niyetli ama yönsüz. Yardım kamyonu geliyor fakat gerçek ihtiyaç listesi bilinmediği için bazı şeyler fazla, bazıları eksik dağıtılıyor.

İkinci mahallede ise önceden küçük bir yerel afet düğümü kurulmuş. Okul bahçesinde basılı harita var. Mahalledeki yalnız yaşayan yaşlıların listesi kapalı ve yetkili bir zarfta tutuluyor. Sağlık gönüllüleri basit triyaj alanını biliyor. Yerel Wi-Fi cihazı bataryayla açılıyor ve telefondan girilebilen basit bir kayıt sayfası sunuyor. Veriler internetsiz tutuluyor, gün sonunda USB ile ilçe merkezine aktarılıyor. Her yaralıya fiziksel numara veriliyor. Her sevk bir deftere ve sisteme işleniyor. Hiçbir şey kusursuz değil, ama belirsizlik daha düşük.

Bu iki mahalle arasındaki fark teknoloji seviyesi değil, hazırlık felsefesidir. Birinde şehir, afet anında ilk kez kendisini tanımaya çalışır. Diğerinde ise şehir, önceden hazırlanmış küçük hafıza parçalarını kullanır.

## Geleceğin şehirleri parlak değil, yedekli olmalı

Gelecek vizyonlarında şehirler çoğu zaman sensörlerle, yapay zekâ panelleriyle, otonom araçlarla ve parlak ekranlarla anlatılır. Oysa afet çağının asıl akıllı şehri, kesinti olduğunda aptallaşmayan şehirdir. Gerçek zeka, sadece veri toplamak değil, veri yokluğunda da makul davranabilmektir.

İklim krizi, enerji kırılganlığı, siber saldırılar, büyük göçler, altyapı yaşlanması ve yoğun kentleşme önümüzdeki on yıllarda şehirleri daha fazla stres altına sokacak. Bu stres karşısında şehirlerin sadece büyümesi değil, katmanlanması gerekecek. Bir katman dijital olacak, bir katman analog. Bir katman merkezi olacak, bir katman yerel. Bir katman profesyonel olacak, bir katman eğitimli gönüllü. Bir katman yüksek teknoloji olacak, bir katman kâğıt ve kalem.

Bu hibrit yapı kulağa eski ve yeni dünyanın garip birleşimi gibi gelebilir. Zaten iyi afet sistemi biraz garip görünür: QR kodla defter yan yana durur, Raspberry Pi ile muhtar listesi aynı masada bulunur, hem telsiz hem telefon kullanılır, hem harita hem GPS vardır. Kırılgan olmayan sistemler çoğu zaman estetik olarak pürüzsüz değildir; yamalıdır, yedeklidir, biraz kaba ama inatçıdır.

## Güçlü kapanış

Bir şehrin medeniyet seviyesi yalnızca normal günlerdeki konforuyla ölçülmez. Asıl ölçü, karanlıkta birbirini bulabilme kabiliyetidir. Afet anında çalışan şehir, her şeyi bilen şehir değildir; unutmayan, tamamen susmayan, küçük parçalara ayrıldığında bile insanlarını birbirine bağlayabilen şehirdir.

Belki de geleceğin en önemli kent teknolojisi dev bir ekran değil, mahalle ölçeğinde çalışan küçük bir hafıza kutusu olacak. Belki en akıllı şehir, gökdelenleri buluta bağlanan değil, okul bahçesindeki basit bir yerel ağ sayesinde yaralısını, yaşlısını ve yolunu kaybetmeyen şehir olacak.

Çünkü afet geldiğinde şehir bize şunu sorar: Işıklar varken ne kadar modern olduğun önemliydi; şimdi ışıklar yokken ne kadar insansın?

## Kaynak Notları

Bu yazı afet yönetimi, kentsel dayanıklılık, yerel-first yazılım yaklaşımı, kritik altyapı sürekliliği, triyaj bilgi mimarisi ve toplum temelli afet hazırlığı literatüründen ilham alır. Doğrudan güncel haber özeti değildir; daha çok şehirlerin kriz anında nasıl katmanlı, yedekli ve yerel çalışabileceğine dair kavramsal bir çerçeve kurar.

## İlişkili Okuma Ağı

- Yerel-first sistemler ve homelab altyapısının afet senaryolarındaki rolü.
- Offline sağlık kayıtları, QR triyaj kartları ve sahada veri sürekliliği.
- Post-apokaliptik bilgi arşivleri ve küçük ölçekli medeniyet çekirdekleri.
- Şehir hafızası, mahalle sosyolojisi ve kriz etiği.
- Kritik altyapıların zarif bozulma tasarımı.

## Kalıcılık Notu

Bu yazı on yıl sonra da okunabilir, çünkü afet dayanıklılığı modası geçecek bir konu değildir. Teknoloji değişse bile elektrik, iletişim, su, sağlık ve yerel koordinasyon kırılganlığı varlığını sürdürecektir. Yazının asıl değeri belirli bir cihazı savunmasında değil, şehirleri merkezsiz hafıza ve katmanlı dayanıklılık üzerinden düşünmeye çağırmasındadır. Bu yüzden gelecekteki araçlar farklı olsa bile temel soru aynı kalacaktır: Şehir, merkez sustuğunda kendisini nasıl hatırlar?
