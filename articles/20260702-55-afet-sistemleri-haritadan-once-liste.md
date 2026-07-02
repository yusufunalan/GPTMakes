---
title: "Haritadan Önce Liste"
date: "2026-07-02"
series: "Dört Kısa Makale"
number: 55
category: "afet-sistemleri"
reading_time: "yaklaşık 20 dk"
tags:
  - afet
  - liste
  - veri
  - operasyon
summary: "Afet anında renkli haritalardan önce sade, doğrulanmış, güncel ve düşük bant genişliğinde çalışabilen listelerin neden operasyonun omurgası olduğunu tartışan uzun-form deneme."
volume: "Volume 2026"
series_name: "Afet Zekâsı"
series_part: 3
durability_score: 10
related_topics:
  - afet veri modeli
  - operasyon listesi
  - saha koordinasyonu
  - yerel sistem
related_articles_note: "Bu yazı mahallenin küçük sunucusu, elektrik kesintisinin ilk gecesi, sel zekâsı ve gökyüzü altyapısı üzerine GPTMakes boyunca kurulan metinlerle birlikte okunabilir."
---

# Haritadan Önce Liste

Afet anında herkes harita ister.

Büyük ekranlar, renkli noktalar, canlı katmanlar, hareket eden ikonlar, yoğunluk haritaları. Bunlar etkileyicidir. Mekânı görmek insana kontrol hissi verir.

Ama sahadaki ekip çoğu zaman daha basit bir şeye ihtiyaç duyar:

Kim nerede?

Neye ihtiyaç duyuyor?

Durum ne zaman güncellendi?

Bilgi kim tarafından doğrulandı?

Hangi iş kapandı, hangisi açık?

Harita gözü ikna eder. Liste operasyonu ayakta tutar.

## Kısa Giriş: Haritanın Hamuru

Harita sonuç katmanıdır. Noktayı, çizgiyi, alanı ve yoğunluğu gösterir. Ama o noktanın anlamı listeden gelir. Bir hanenin durumu, bir okul bahçesindeki kişi sayısı, bir su ihtiyacı, bir yol kapanması, bir ilaç talebi, bir jeneratör kapasitesi önce kayıt olarak doğar.

Liste kötü ise harita güzel kaos üretir.

Afet bilgi sistemlerinde en büyük risklerden biri görselleştirmeye fazla erken koşmaktır. Renkli ekran, verinin doğru olduğu hissini verir. Oysa alttaki kayıtlar tekrarlı, eksik, güncellenmemiş, doğrulanmamış veya belirsizse harita yalnızca hatayı estetik hale getirir.

İyi afet sistemi önce listeyle düşünür, sonra haritaya çizer.

## İyi Liste Nasıl Olur?

İyi liste az ama doğru alan içerir. Kriz anında kimse uzun formlar dolduramaz. İnsanlar yorgun, korkmuş, uykusuz ve zaman baskısı altındadır. Bu yüzden kayıt sistemi sade olmalıdır.

Temel alanlar çoğu durumda yeterlidir:

Konum.

Durum.

İhtiyaç.

Öncelik.

Zaman.

Doğrulama.

Sorumlu kişi veya ekip.

Sonraki adım.

Bu alanlar netse, harita, rapor, görev listesi, stok planı ve önceliklendirme sonradan üretilebilir. Net değilse her şey tartışmaya dönüşür.

"Yardım gerekiyor" insani bir cümledir ama operasyonel olarak zayıftır. "Mahalle X, bina Y, 2 yaşlı, su yok, ilaç ihtiyacı var, saat 16.20, komşu tarafından doğrulandı" cümlesi daha değerlidir.

Afette iyi veri, edebî değil kullanılabilir olmalıdır.

## Liste ve Zaman

Afet verisinin en kritik özelliği zamanla bozulmasıdır. Bir ihtiyaç karşılanmış olabilir. Bir yol açılmış olabilir. Bir bina boşaltılmış olabilir. Bir kişi bulunmuş olabilir. Bir su noktası tükenmiş olabilir.

Bu yüzden her kaydın zamanı olmalıdır.

Zaman damgası yoksa bilgi yaşlanma hızını saklar. Eski bilgi yeniymiş gibi görünür. Ekipler kapanmış çağrılara gider, çözülen sorunlar tekrar gündeme gelir, gerçek ihtiyaçlar geride kalır.

Liste yalnızca ne olduğunu değil, bilginin ne kadar taze olduğunu da göstermelidir.

Afet yönetiminde "bilmiyoruz" kadar "bunu üç saat önce biliyorduk" cümlesi de önemlidir.

## Doğrulama ve Tekrar Kayıt Sorunu

Kriz anında aynı ihtiyaç farklı kişiler tarafından defalarca bildirilebilir. Bu kötü niyet değildir; endişenin doğal sonucudur. Ama sistem tekrarları ayıramazsa kaynak israfı olur.

Doğrulama alanı bu yüzden hayati önemdedir. Bilgi kimden geldi? Yerinde görüldü mü? İki kaynak doğruladı mı? Resmî ekip geçti mi? Tahmin mi, gözlem mi?

Doğrulama, insanlara güvenmemek için değil, kaynakları doğru yönlendirmek için gerekir.

Kötü liste, söylentiyi kayıt sanır. İyi liste, söylentiyi işlenmemiş bilgi olarak tutar ve doğrulama ister.

## Offline ve Düşük Bant Genişliği

Afet anında internet olmayabilir. Elektrik kesilebilir. Cihaz şarjı sınırlı olabilir. Bu nedenle liste sistemleri düşük bant genişliğinde ve mümkünse offline çalışmalıdır.

Kâğıt liste hâlâ değerlidir. Basit tablo, QR kodla sonradan sisteme bağlanabilir. Yerel sunucuda tutulan kayıtlar bağlantı gelince eşitlenebilir. SMS veya kısa mesaj formatlarıyla veri aktarılabilir.

En iyi sistem, teknoloji seviyesi düştüğünde tamamen çökmeyen sistemdir.

Bir afet listesi, lüks yazılım değil, temel saha aracı olarak tasarlanmalıdır.

## Mahremiyet

Listeler hassas bilgi taşır. Yaşlı hane, engelli kişi, ilaç kullanan birey, boş ev, yaralı sayısı, gıda stoğu, telefon numarası, konum. Bu bilgiler hayat kurtarabilir; yanlış elde zarar verebilir.

Bu nedenle afet listeleri açık veri romantizmiyle yönetilemez. Kim hangi bilgiye erişecek? Ne kadar süre saklanacak? Kriz bitince ne silinecek? Hangi bilgiler anonimleştirilecek?

İyi liste, insanı görünür kılar ama savunmasız bırakmaz.

## Karşıt Görüşler ve Eleştiriler

Birinci eleştiri, haritaların vazgeçilmez olduğudur. Doğrudur. Afette mekân bilgisi olmadan operasyon körleşir. Ancak harita iyi listenin üzerine kurulduğunda işe yarar.

İkinci eleştiri, kriz anında kimsenin form dolduramayacağıdır. Bu da doğrudur. Bu yüzden form değil, kısa kayıt protokolü gerekir. En iyi liste, yorgun bir insanın bile doldurabileceği kadar basittir.

Üçüncü eleştiri, listelerin bürokrasi yaratacağıdır. Kötü liste yaratır. İyi liste ise sahadaki belirsizliği azaltır ve gereksiz konuşmayı önler.

## Düşünce Deneyi: İki Merkez

İki afet koordinasyon merkezi düşünelim. Birinde büyük ekranlı mükemmel harita var; ama kayıtlar tutarsız. Noktaların bazıları eski, bazıları tekrarlı, bazıları doğrulanmamış.

Diğerinde sade bir tablo var. Her satırda konum, ihtiyaç, zaman, doğrulama ve sorumlu ekip net. Harita yok ya da çok basit.

İlk saatlerde hangisi daha işe yarar?

Çoğu zaman sade tablo kazanır. Çünkü operasyon netlik ister.

## Geleceğe Yönelik Çıkarımlar

Afet teknolojilerinde liste tasarımı temel beceri haline gelmelidir. Veri alanları önceden belirlenmeli, yerel ekipler eğitilmeli, kâğıt ve dijital sistemler birbirini tamamlamalı, güncelleme ve kapatma disiplini öğretilmelidir.

Haritalar, grafikler ve yapay zekâ sınıflandırmaları bu temiz listenin üstünde çalışmalıdır. Temel kayıt bozuksa en gelişmiş araç bile belirsizliği büyütür.

## Güçlü Kapanış: Önce Satır

Afet anında dünya karmaşıklaşır. İyi sistemin görevi bu karmaşayı tek hamlede çözmek değildir. Önce küçük bir satır üretmektir:

Kim, nerede, neye ihtiyaç duyuyor, bilgi ne kadar taze, kim doğruladı, sıradaki adım ne?

Bu satırlar doğruysa harita konuşur.

Değilse harita yalnızca renkli bir suskunluktur.

## Kaynak Notları

Bu yazı afet veri yönetimi, saha koordinasyonu, offline-first operasyon sistemleri, düşük bant genişlikli iletişim ve insani yardım kayıt modelleri üzerine pratik çerçevelerden ilham alır. Metin haritaları reddetmez; haritaların iyi kayıt düzenine bağımlı olduğunu vurgular.

Afet listeleri mahremiyet, doğrulama, zaman damgası ve kapanan işlerin temizlenmesi ilkeleriyle birlikte tasarlanmalıdır.

## İlişkili Okuma Ağı

- "Mahallenin Küçük Sunucusu" yazısıyla yerel ve offline veri altyapısını paylaşır.
- "Afetlerin Yeni Dili" yazısıyla olasılık ve operasyon diline bağlanır.
- "Elektriksiz Geçen İlk Gece" yazısıyla basılı liste ve komşuluk bilgisini sürdürür.
- "Su Basınca Şehir Yalan Söylemez" yazısıyla afet verisinin saha gözlemiyle beslenmesi temasına yaklaşır.
- Gelecekte afet veri modeli ve düşük bant genişliği mesaj şablonları üzerine yazılacak metinlere zemin olabilir.

## Kalıcılık Notu

Afet teknolojileri değişebilir; fakat doğru, sade ve güncel kayıt ihtiyacı kalıcıdır. Bu yazı belirli bir yazılıma değil, operasyonun temel veri mantığına odaklandığı için uzun ömürlüdür.
