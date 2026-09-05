# aruna-web

Aruna'nın halka açık belgelerini yayınlayan küçük site.

**Canlı adres:** <https://hb4sri.github.io/aruna-web/>
**Gizlilik politikası:** <https://hb4sri.github.io/aruna-web/gizlilik/>

Aruna, günlük ve not defteri için bir Android uygulamasıdır. Hesap istemez,
sunucusu yoktur ve internet izni bile yoktur.

---

The small site that publishes Aruna's public documents. Aruna is an Android
journal app: no account, no server, not even the internet permission.

## Deponun düzeni

| Dosya | Ne işe yarar |
| --- | --- |
| `gizlilik.md` | Gizlilik politikası (TR + EN). |
| `index.md` | Giriş sayfası. |
| `_layouts/default.html` | Sayfa düzeni, tema ve sunum betiği. |
| `_config.yml` | Jekyll ayarları ve **dil sözlüğü**. |
| `yazitipi/` | Yazı tipleri ve lisansları. |

`gizlilik.md`, Aruna uygulama deposundaki `docs/gizlilik_politikasi.md`
dosyasının **birebir kopyasıdır.** İkisi ayrışmasın diye dosya ön bilgi (front
matter) taşımaz; sayfaya özel ne gerekiyorsa `_config.yml` içindeki
varsayılanlardan verilir. Politika değişince kaynak dosya güncellenir ve buraya
olduğu gibi kopyalanır.

Kopyanın kaynakla aynı kaldığı şu komutla ölçülür:

```
diff docs/gizlilik_politikasi.md ../aruna-web/gizlilik.md
```

Politikadaki her iddianın koddaki kanıtı uygulama deposunda duruyor
(`docs/mimari/privacy_system.md`, iddia-kanıt tablosu); kanıtı olmayan cümle
politikaya girmez.

## Adres neden burada

Play, gizlilik politikasının herkese açık, düzenlenemez ve PDF olmayan bir
adreste durmasını istiyor. Uygulamanın kendi deposu kapalı olduğu için sayfa
oradan çıkamıyor; bu depo yalnız o adresi var etmek için duruyor.

Adres iki yere daha yazılı ve üçünün aynı kalması gerekiyor: Play Console'un
politika alanı ve uygulamanın içindeki `kArunaPrivacyUrl` sabiti (Ayarlar >
Hakkında > Gizlilik politikası). Uygulama tarafında bunu bir test mühürlüyor.

## Diller

Sayfa tek belgedir ve bütün dilleri içinde taşır; okuyucu üst çubuktaki
anahtarla birini seçer. Seçim yoksa tarayıcının dili denenir, o da listede
yoksa `_config.yml` içindeki `varsayilan_dil` açılır.

Kabuktaki her metin (üst çubuk, alt bilgi, dil ve tema düğmeleri, yan sütun
başlığı) `_config.yml` içindeki `diller` listesinden gelir. Şablonda ya da
betikte elle yazılmış bir dil metni ya da elle yazılmış bir dil kodu yoktur.

**Yeni dil eklemek:**

1. `_config.yml` içindeki `diller` listesine bir blok ekleyin (var olan bir
   bloğun bütün alanlarını doldurun).
2. `gizlilik.md` içine, listedekiyle **aynı sırada**, o dilin `## ` bölümünü
   yazın. Bölümün başına dilin kendi künyesini (sürüm, yürürlük, iletişim)
   koyun.
3. Şablona ve betiğe dokunmayın.

Sıra önemli, çünkü betik dil bölümlerini başlıklarından değil **kaynak
metindeki sıralarından** tanır: başlık her dilde farklı yazıldığı için
(Gizlilik Politikası / Privacy Policy / ...) sıradan başka ortak bir işaret
yok. Bölüm sayısı dil sayısına eşit değilse betik gövdeye hiç dokunmaz ve
sayfa bütün dilleri alt alta gösterir; yani yanlış eşleşme yerine düz metin.

## Tema

Düzenin tamamı `_layouts/default.html` içinde: tek bir stil bloğu, iki küçük
betik. Sayfa hiçbir dış kaynağa istek atmaz, yazı tipleri burada barındırılır.
Renk paleti hb4sri.com ile ortaktır.

Tema üç hâllidir: **Sistem**, **Açık**, **Koyu**. Seçim yoksa kök elemanda
hiçbir işaret olmaz ve yalnız `prefers-color-scheme` konuşur; seçim varsa
`data-tema` işareti onu yener. Seçim `<head>` içindeki ilk betikte, sayfa
çizilmeden önce uygulanır; sonradan uygulansaydı sayfa bir an yanlış renkle
görünürdü.

Marka rengi iki temada aynı hex değildir: bordo `#8E2F3C` açık zeminde 7.35
kontrast verir ama koyu zeminde 2.62'ye düşer, yani okunmaz. Koyu temada
açığa çekilmiş `#D98494` kullanılır (7.68).

## Yazı tipleri

`yazitipi/` altındaki iki aile de SIL Open Font License 1.1 ile dağıtılır ve
lisans metinleri yanlarındadır:

- **Bricolage Grotesque** - `bricolage-OFL.txt`
- **SEKUYA** - `sekuya-OFL.txt`
