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
| `_layouts/default.html` | Sayfa düzeni ve tema. |
| `_config.yml` | Jekyll ayarları. |
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

## Tema

Düzenin tamamı `_layouts/default.html` içinde: tek bir stil bloğu, tek bir
küçük betik. Sayfa hiçbir dış kaynağa istek atmaz, yazı tipleri burada
barındırılır. Renk paleti hb4sri.com ile ortaktır.

## Yazı tipleri

`yazitipi/` altındaki iki aile de SIL Open Font License 1.1 ile dağıtılır ve
lisans metinleri yanlarındadır:

- **Bricolage Grotesque** - `bricolage-OFL.txt`
- **SEKUYA** - `sekuya-OFL.txt`
