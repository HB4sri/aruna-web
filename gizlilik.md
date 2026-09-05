# Aruna Gizlilik Politikası / Privacy Policy

**Sürüm / Version:** 1.0 · **Yürürlük / Effective:** 5 Eylül 2026 / 5 September 2026
**İletişim / Contact:** destek@hb4.aleeas.com

[Türkçe](#türkçe) · [English](#english)

---

## Türkçe

### Özet

Aruna'nın sunucusu yok, hesap istemiyor ve internet izni bile yok. Yazdıklarınız,
fotoğraflarınız ve ses kayıtlarınız telefonunuzda kalır. Telefondan çıkmasının iki yolu vardır
ve ikisini de siz başlatırsınız: yedek dosyası ve paylaşım.

Bu politika, Aruna (paket adı `com.hb4sri.aruna`) Android uygulaması için geçerlidir.

### Sorumlu

Aruna'yı bağımsız bir geliştirici olarak tek başıma yapıyorum; arkasında bir şirket yok.
Sorularınız ve talepleriniz için bana yazabilirsiniz: **destek@hb4.aleeas.com**

### Telefonunuzda ne saklanıyor

Uygulamanın sakladığı her şey telefonunuzun kendi uygulama alanındadır. Veritabanı dosyası ve
medya klasörleri uygulamanın özel dizinindedir; başka uygulamalar oraya giremez.

**Günlük içeriğiniz:** her notun başlığı, gövdesi (biçimlendirmesiyle birlikte), oluşturma ve
son düzenleme zamanı, varsa ruh hâli işareti, favori ve kilit durumu, çöp kutusuna atıldıysa
silinme zamanı. Nota eklediğiniz fotoğraflar ve üzerlerine yaptığınız çizimler, ses kayıtları
ve süreleri, oluşturduğunuz etiketler ve renkleri.

**Profiliniz ve ayarlarınız:** uygulamaya verdiğiniz ad ve seçtiyseniz profil fotoğrafınız;
tema, renk, punto, dil, bildirim ve gizlilik tercihleri; çöp kutusu saklama süresi.

**Güvenlik:** PIN kurduysanız yalnızca tuzlu özeti saklanır, PIN'in kendisi değil. Kurtarma
cümleniz Android'in anahtar deposu (Keystore) ile şifrelenerek saklanır; o anahtar
telefonunuza bağlıdır ve telefonu terk etmez.

**Tanılama:** uygulama bir hatayla karşılaşırsa telefonda tutulan yerel bir günlüğe teknik bir
kayıt düşer. Bu kayıtlar notlarınızın içeriğini taşımaz; en çok 50 kayıt tutulur ve eskisi
silinir. Kayıtlar kendiliğinden hiçbir yere gönderilmez.

**Saklanmayanlar:** e-posta adresiniz, telefon numaranız, konumunuz, kişileriniz, cihaz
kimliğiniz ve reklam kimliğiniz. Bunların hiçbiri istenmez ve saklanmaz. Uygulamaya verdiğiniz
ad yalnızca sizin görmeniz içindir ve telefonda kalır.

### Cihazda koruma

**Canlı veritabanı uygulama tarafından ayrıca şifrelenmez.** Koruma şuradan gelir: Android'in
cihaz şifrelemesi, Android'in uygulama kum havuzu (başka uygulamalar Aruna'nın dosyalarına
erişemez) ve isterseniz kurduğunuz uygulama kilidi.

Uygulama kilidi PIN ya da telefonunuzun biyometrisiyle açılır ve seçtiğiniz süre sonunda
kendiliğinden kilitlenir. Notları tek tek de kilitleyebilirsiniz.

**Biyometrik veriniz uygulamaya hiç gelmez.** Parmak izinizi ya da yüzünüzü Android doğrular;
Aruna yalnızca "doğrulandı" veya "doğrulanmadı" sonucunu görür.

Kilitli bir notun içeriği ekrandayken uygulama ekran görüntüsünü, ekran kaydını ve "son
uygulamalar" önizlemesini engeller; bu koruma ayardan kapatılabilir. Uygulamanın tamamı için de
ayrı bir koruma anahtarı vardır ve varsayılanı kapalıdır.

**Android'in bulut yedeği uygulamada kapalıdır:** verileriniz Google Drive yedeğine dahil
edilmez. Yeni bir telefona geçerken işletim sisteminin cihazdan cihaza aktarımı ise bazı
üreticilerin cihazlarında Aruna'nın verisini taşıyabilir; bunu siz ve işletim sistemi
başlatır, Aruna değil. Böyle bir aktarımda notlarınız, medyanız, ayarlarınız ve PIN'in özeti
taşınır; kurtarma cümleniz taşınmaz, çünkü eski telefonun anahtar deposuna bağlıdır ve yeni
telefonda okunamaz. Yeni telefonda PIN'i kaldırıp yeniden kurduğunuzda yeni bir kurtarma
cümlesi alırsınız. Verinizi kendiniz taşımanın güvenilir yolu aşağıdaki yedek dosyasıdır.

### Reklam, analitik ve izleme

Yoktur. Aruna'da reklam ağı, analitik, çökme telemetrisi ve çapraz uygulama izleme bulunmaz.
Reklam kimliğiniz okunmaz. Uygulamada üçüncü taraf bir veri toplama kütüphanesi
paketlenmemiştir.

Yazı tipleri uygulamanın içine gömülüdür ve çalışırken ağdan yazı tipi indirme kapalıdır.
Uygulama telefonunuzdan kişisel veri okumaz. Görünüm ve zamanlama için sistem ayarlarınızdan
yararlanır: dil, açık ya da koyu tema ve hareketi azaltma gibi görünüm tercihleri, açtıysanız
sistemin renk paleti, ve hatırlatıcıları doğru saatte kurmak için saat diliminiz. Bunlar
telefondan çıkmaz.

### İzinler

Uygulama `INTERNET` izni **istemez.** Bu izin olmadan uygulama kendi başına ağ üzerinden hiçbir
veri gönderemez.

İstenen izinler ve nedenleri:

- `RECORD_AUDIO` - nota ses kaydı eklemek için; ilk kayıtta istenir.
- `POST_NOTIFICATIONS` - hatırlatıcı ve anı bildirimlerini gösterebilmek için.
- `USE_BIOMETRIC` - uygulama kilidini parmak izi ya da yüzle açmak için.
- `RECEIVE_BOOT_COMPLETED` - telefon yeniden başladığında bekleyen hatırlatıcıları yeniden
  kurmak için.
- `VIBRATE` - bildirim titreşimi ve dokunma geri bildirimi için.

Kullanılan kütüphanelerin eklediği izinler de görünür: `USE_FINGERPRINT` (biyometri
kütüphanesi, eski Android sürümleri için), `ACCESS_NETWORK_STATE` (ses kütüphanesi; yalnızca
bağlantı durumunu sorgulamaya izin verir, ağ erişimi vermez ve uygulama tarafından
kullanılmaz) ve uygulamanın kendi adıyla başlayan `DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION`
(Android destek kütüphanesi kendi bileşenini başka uygulamalardan korumak için ekler).

**İstenmeyen izinler:** internet, fotoğraf ve video okuma, depolama, kesin alarm, tüm
uygulamaları görme, medya konumu, konum ve reklam kimliği.

Fotoğraf seçmek için izin istenmez: sistemin fotoğraf seçicisi açılır ve yalnızca seçtiğiniz
kareler uygulamaya gelir. Yedek dosyası seçerken de sistemin dosya seçicisi kullanılır.
Fotoğraf çekmek istediğinizde telefonunuzun kendi Kamera uygulaması açılır ve çektiğiniz kare
uygulamaya döner; Aruna kameraya doğrudan erişmediği için kamera izni de istemez.

Her izin, o özelliği ilk kullandığınızda istenir. Vermezseniz yalnızca o özellik çalışmaz;
uygulamanın kalanı çalışmaya devam eder.

### Bildirimler

İki tür bildirim vardır: kurduğunuz hatırlatıcılar, ve geçmiş yıllarda aynı güne yazdıklarınızı
hatırlatan anı bildirimi. Anı bildiriminin notunuzdan bir parça göstermesi ayardan açılıp
kapatılabilir; açık olsa bile kilit ekranında metin gizlenir ve ancak telefonun kilidini açınca
görünür.

**Kilitli notlar anı bildirimine hiçbir koşulda girmez** ve bildirimdeki "ve N tane daha"
sayısına bile katılmazlar. İçerik ayarının açık olması bunu değiştirmez; ikisi ayrı kapıdır.

Bildirimler kesin alarm iznini kullanmaz; sistem onları uygun bir anda gönderir. Bildirimler
telefonun içinde üretilir, bir sunucudan gelmez.

### Verinin telefondan çıkabileceği durumlar

Günlük içeriğiniz telefondan yalnızca iki yolla çıkar ve ikisini de siz başlatırsınız.
Uygulama kendiliğinden hiçbir veri göndermez.

**1. Yedek dosyası.** Ayarlardan yedek alırsanız verileriniz tek bir dosyaya yazılır; dosya
telefonun İndirilenler klasörüne (o klasör yoksa uygulamanın kendi dış klasörüne) kaydedilir ve
uygulama tam yolunu size gösterir. **Parola verirseniz dosya şifrelenir:** parolanızdan 150.000
turluk bir anahtar türetilir ve dosya AES ile şifrelenir. Parolayı siz belirlersiniz, uygulama
onu saklamaz; kaybederseniz dosya açılamaz. Güvenlik anahtarlarınız (PIN'in özeti ve kurtarma
cümleniz) yedeğe girmez. Kilitli notlarınız yedeğe giriyorsa dosya yazılmadan önce kimliğiniz
doğrulanır. Dosya yazıldıktan sonra sizindir; nereye taşıyacağınıza siz karar verirsiniz.

**2. Paylaşım.** Bir notu, fotoğrafı, ses kaydını ya da oluşturduğunuz PDF'i paylaştığınızda
içerik seçtiğiniz uygulamaya gider. Paylaşımı siz başlatırsınız ve hedefi siz seçersiniz.

**Tanılama dosyası.** Notlarınız değildir ama telefondan çıkabilen bir dosyadır ve yalnızca
siz isterseniz gider: sorun bildirirken e-postaya eklemeyi seçtiğinizde ya da Ayarlar >
Tanılama sayfasından paylaştığınızda. İçinde uygulamanın sürüm numarası ve hata kayıtları
(zaman, hatanın türü ve mesajı, teknik iz) vardır; notlarınız, fotoğraflarınız, cihaz
kimliğiniz ve cihaz modeliniz yoktur.

**Veri çıkışı olmayan iki eylem.** Bana yazmayı seçtiğinizde telefonunuzun e-posta uygulaması
yalnızca adres, konu ve boş bir şablonla açılır (e-posta uygulaması yoksa paylaşım menüsü);
mesajı siz yazar ve siz gönderirsiniz, mesaj kullandığınız posta sağlayıcısının koşullarına
tabidir. Notunuza yazdığınız bir bağlantıya dokunduğunuzda önce hangi adresin açılacağı
gösterilir ve onayınız alınır; Hakkında sayfasındaki web sitesi ve gizlilik politikası
bağlantıları doğrudan açılır. Her iki durumda da uygulama tarayıcıya adres dışında hiçbir şey
vermez.

### Fotoğraf üst verisi

Nota eklediğiniz fotoğraflar uygulamaya alınırken yeniden kodlanır. Bunun sonucu şudur:
fotoğrafın içindeki üst veri (konum, çekim tarihi, kamera bilgisi) **Aruna'ya hiç girmez** ve
paylaştığınız dosyada da bulunmaz.

Galeriden seçtiğiniz fotoğraflarda konum bilgisini Android 10 ve üstü zaten siler; Aruna ayrıca
kalan üst verinin tamamını düşürür.

### Ruh hâli işareti

Bir nota isterseniz beş kademeli bir ruh hâli işareti bırakabilirsiniz. Bu kişisel bir nottur:
tıbbi bir amacı yoktur, teşhis veya tedavi için kullanılamaz ve size bir öneri ya da program
sunmaz. İşareti ayarlardan tümüyle kapatabilirsiniz. Telefonunuzdan çıkmaz.

### Saklama süresi ve silme

Verileriniz siz silene ya da uygulamayı kaldırana kadar saklanır; süre sınırı yoktur.

Sildiğiniz notlar önce çöp kutusuna gider ve varsayılan olarak 30 gün sonra kalıcı olarak
silinir; bu süre ayardan değiştirilebilir. Çöp kutusundan tek tek ya da toptan kalıcı
silebilirsiniz. Bir not kalıcı silindiğinde ona bağlı fotoğraf, çizim ve ses dosyaları da
telefondan silinir.

Uygulamayı kaldırmak telefondaki tüm Aruna verisini siler.

Daha önce aldığınız yedek dosyaları sizin dosyalarınızdır; onları bulundukları yerden siz
silersiniz.

### Çocuklar

Uygulama 18 yaş ve üzeri içindir ve çocuklara yönelik değildir.

### Bu politikadaki değişiklikler

Politika değişirse bu sayfadaki sürüm numarası ve yürürlük tarihi güncellenir. Uygulamanın veri
davranışını değiştiren bir güncelleme yayımlanırsa politika aynı sürümde güncellenir.

### İletişim

**destek@hb4.aleeas.com**

---

## English

### Summary

Aruna has no server, asks for no account, and does not even have the internet permission. What
you write, your photos and your voice recordings stay on your phone. There are two ways data
can leave, and you start both: a backup file and sharing.

This policy applies to the Aruna Android app (package `com.hb4sri.aruna`).

### Who is responsible

I make Aruna on my own, as an independent developer; there is no company behind it. For
questions and requests, you can write to me: **destek@hb4.aleeas.com**

### What is stored on your phone

Everything the app stores lives in your phone's own app storage. The database file and the
media folders are in the app's private directory; other apps cannot reach them.

**Your journal content:** each entry's title, body (with its formatting), creation and last
edit time, the mood mark if you left one, its favourite and locked state, and the deletion time
if it is in the trash. The photos you attach and the drawings you make on them, voice
recordings and their durations, and the tags you create with their colours.

**Your profile and settings:** the name you give the app and, if you choose one, your profile
picture; theme, colour, text size, language, notification and privacy preferences; the trash
retention period.

**Security:** if you set a PIN, only its salted hash is stored, never the PIN itself. Your
recovery phrase is stored encrypted with Android's keystore; that key is bound to your phone
and never leaves it.

**Diagnostics:** if the app hits an error, a technical record is written to a local log kept on
the phone. These records never carry the content of your entries; at most 50 are kept and older
ones are dropped. Nothing is sent anywhere on its own.

**Not stored:** your email address, phone number, location, contacts, device ID or advertising
ID. None of these are requested or kept. The name you give the app is only for you to see and
stays on the phone.

### Protection on the device

**The live database is not additionally encrypted by the app.** Protection comes from
Android's device encryption, Android's app sandbox (other apps cannot reach Aruna's files), and
the app lock if you set one up.

The app lock opens with a PIN or your phone's biometrics and locks itself again after the delay
you choose. You can also lock individual entries.

**Your biometric data never reaches the app.** Android verifies your fingerprint or face; Aruna
only sees the "verified" or "not verified" result.

While the content of a locked entry is on screen, the app blocks screenshots, screen recording
and the "recent apps" preview; this protection can be turned off in settings. There is also a
separate switch that protects the whole app, off by default.

**Android's cloud backup is disabled in the app:** your data is not included in a Google Drive
backup. When you move to a new phone, however, the operating system's device-to-device transfer
may carry Aruna's data on devices from some manufacturers; you and the operating system start
that, not Aruna. In such a transfer your entries, media, settings and the PIN hash are carried
over; your recovery phrase is not, because it is bound to the old phone's keystore and cannot
be read on the new one. Removing the PIN on the new phone and setting it up again gives you a
new recovery phrase. The reliable way to move your data yourself is the backup file below.

### Ads, analytics and tracking

There are none. Aruna contains no ad network, no analytics, no crash telemetry and no cross-app
tracking. Your advertising ID is not read. No third-party data collection library is bundled in
the app.

Fonts are embedded in the app and runtime font fetching is disabled. The app reads no personal
data from your phone. For appearance and scheduling it uses your system settings: display
preferences such as language, light or dark theme and reduced motion, the system colour palette
if you enable it, and your time zone so that reminders fire at the right hour. None of these
leave the phone.

### Permissions

The app does **not** request the `INTERNET` permission. Without it, the app cannot send any
data over the network on its own.

The permissions it does request, and why:

- `RECORD_AUDIO` - to add a voice recording to an entry; asked at the first recording.
- `POST_NOTIFICATIONS` - to show reminders and memory notices.
- `USE_BIOMETRIC` - to open the app lock with a fingerprint or face.
- `RECEIVE_BOOT_COMPLETED` - to re-schedule pending reminders after the phone restarts.
- `VIBRATE` - for notification vibration and haptic feedback.

Permissions added by the libraries in use are also visible: `USE_FINGERPRINT` (the biometric
library, for older Android versions), `ACCESS_NETWORK_STATE` (the audio library; it only allows
querying connectivity state, grants no network access, and is not used by the app), and
`DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION`, which starts with the app's own name and is added
by an Android support library to protect its own component from other apps.

**Permissions that are not requested:** internet, reading photos and video, storage, exact
alarms, seeing all installed apps, media location, location, and the advertising ID.

No permission is asked to pick a photo: the system photo picker opens and only the images you
select reach the app. The system file picker is likewise used to choose a backup file. When you
want to take a photo, your phone's own camera app opens and the picture you take is returned to
the app; because Aruna never accesses the camera directly, it does not ask for the camera
permission either.

Each permission is requested when you first use that feature. If you decline, only that feature
stops working; the rest of the app carries on.

### Notifications

There are two kinds: the reminders you set, and the memory notice that brings back what you
wrote on the same day in previous years. Whether the memory notice shows a fragment of your
entry can be turned on or off in settings; even when it is on, the text is hidden on the lock
screen and appears only after you unlock the phone.

**Locked entries never enter the memory notice under any condition,** and they are not even
counted in its "and N more" number. Turning the content setting on does not change this; these
are two separate gates.

Notifications do not use the exact alarm permission; the system delivers them at a suitable
moment. They are produced inside the phone and do not come from a server.

### When data can leave your phone

Your journal content leaves the phone in only two ways, and you start both. The app never
sends anything on its own.

**1. Backup file.** If you export a backup from settings, your data is written to a single
file; the file is saved to the phone's Downloads folder (or, if that folder does not exist, to
the app's own external folder) and the app shows you its full path. **If you provide a
password, the file is encrypted:** a key is derived from your password with 150,000 iterations
and the file is encrypted with AES. You choose the password and the app does not store it; if
you lose it, the file cannot be opened. Your security keys (the PIN hash and your recovery
phrase) are not included in the backup. If locked entries are going into the file, your
identity is verified before it is written. Once written, the file is yours; you decide where it
goes.

**2. Sharing.** When you share an entry, a photo, a voice recording or a PDF you generated, the
content goes to the app you pick. You start the share and you choose the destination.

**Diagnostic file.** It is not your journal, but it is a file that can leave the phone, and it
goes only if you want it to: when you choose to attach it while reporting a problem by email,
or when you share it from Settings > Diagnostics. It contains the app's version number and the
error records (time, the error's type and message, a technical trace); it contains none of your
entries or photos, no device ID and no device model.

**Two actions that are not data exits.** When you choose to write to me, your phone's email
app opens with only the address, the subject and an empty template (the share menu opens if
there is no email app); you write and send the message yourself, and it is subject to the terms
of the mail provider you use. When you tap a link you wrote in an entry, the app first shows
which address will open and asks for your confirmation; the website and privacy policy links on
the About page open directly. In both cases the app hands the browser nothing but the address.

### Photo metadata

Photos you attach to an entry are re-encoded as they are imported. The consequence is this: the
metadata inside the photo (location, capture date, camera information) **never enters Aruna**
and is not present in the file you share either.

For photos picked from the gallery, Android 10 and above already strips the location; Aruna
additionally drops all remaining metadata.

### The mood mark

If you wish, you can leave a five-level mood mark on an entry. It is a personal note: it has no
medical purpose, cannot be used for diagnosis or treatment, and offers you no advice or
programme. You can turn the mark off entirely in settings. It never leaves your phone.

### Retention and deletion

Your data is kept until you delete it or uninstall the app; there is no time limit.

Entries you delete go to the trash first and are permanently deleted after 30 days by default;
this period can be changed in settings. You can permanently delete items from the trash one by
one or all at once. When an entry is permanently deleted, the photo, drawing and audio files
attached to it are deleted from the phone as well.

Uninstalling the app deletes all Aruna data on the phone.

Backup files you exported earlier are your files; you delete them from wherever they are.

### Children

The app is for people aged 18 and over and is not directed at children.

### Changes to this policy

If the policy changes, the version number and effective date on this page are updated. If an
update changes the app's data behaviour, the policy is updated in the same release.

### Contact

**destek@hb4.aleeas.com**
