<h1 align="center">SM CardWars</h1>

<p align="center">
  Üç kartlık elle yapay zekâya karşı oynanan sıra tabanlı strateji kart oyunu.<br>
  İlk bireysel mobil oyun denemem · Demo v1.0
</p>

<p align="center">
  <a href="https://osmnnuri.github.io"><b>Güncel görseller için siteme göz at</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/osmnnuri/SM-CardWars-v2-AetherWorldCardWars-Showcase"><b>v2.0: Aether World Card Wars →</b></a>
</p>

---

## Oyun konsepti

Oyuncu ve yapay zekâ 30 canla başlar. Her tur oyuncuya rastgele üç kart gelir;
hangisini oynayacağını seçer, ardından yapay zekâ kendi hamlesini yapar. Canı
önce sıfırlanan kaybeder. Hangi kartı ne zaman oynayacağına karar vermek
oyunun strateji tarafını oluşturur.

Oyun çevrimdışı oynanır; rakip, uygulamanın içindeki oyun motorunda çalışan bir
yapay zekâdır.

## Kartlar

| Kart | Etkisi |
|---|---|
| **Saldırı** | Rakibe 6 hasar; önce kalkandan düşülür |
| **Savunma** | +5 kalkan |
| **Sersemletme (stun)** | Rakip bir tur oynayamaz |

## Yapay zekâ rakip

Rakip her tur olasılıklarla kart seçer: normalde ağırlık saldırıdadır
(%50 saldırı, %30 savunma, %20 sersemletme). Canı 10 ve altına düşünce
savunmaya geçer (%45 savunma, %35 saldırı, %20 sersemletme).

## Kullanılan teknolojiler

| Katman | Teknoloji |
|---|---|
| Dil | Kotlin |
| Arayüz | Fragment, ViewBinding |
| Gezinme | Navigation |
| Oyun motoru | Kart, oyuncu durumu ve tur sonucu sınıflarından oluşan ayrı bir motor |
| Ses | Kart oynama efektleri |
| Yaklaşım | Nesne tabanlı programlama |
| Geliştirme ortamı | Android Studio |

## Tasarım ve görseller

Oyun görselleri yapay zekâ ile üretildi; bunun dışındaki tasarım ve düzen bana
ait. Kodlama sürecinde yapay zekâ destekli araçlardan yararlandım.

## Durum ve yol haritası

Demo v1.0. Oyunun devamı, Flutter ile baştan yazılan
[Aether World Card Wars (v2.0)](https://github.com/osmnnuri/SM-CardWars-v2-AetherWorldCardWars-Showcase)
olarak geliştiriliyor.

## Kaynak kod

Kaynak kod özel bir depoda tutuluyor; inceleme için talep üzerine paylaşılabilir.

## İletişim

**osmnnuri** · [Web sitesi](https://osmnnuri.github.io) · [GitHub](https://github.com/osmnnuri) · osmannuriyasar57@gmail.com
