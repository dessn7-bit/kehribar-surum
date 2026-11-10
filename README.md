# Kehribar Vadisi — Android sürümleri

Bu depo yalnızca **Kehribar Vadisi** oyununun Android kurulum dosyalarını (APK) dağıtmak içindir. Kaynak kod burada değildir.

## Kurulum / güncelleme

1. Telefonda [Releases](../../releases/latest) sayfasını aç.
2. `KehribarVadisi_<sürüm>.apk` dosyasını indir ve aç.
3. Android ilk seferde "bu kaynaktan yüklemeye izin ver" diye sorar: izin ver, sonra **Kur / Güncelle**'ye dokun.

Oyun zaten kuruluysa üzerine güncellenir, kayıt (para, gün, dinozorlar) korunur.

6A-4 ve sonraki sürümlerde oyun güncellemeyi kendisi de denetler: açılışta ya da **Ayarlar → Güncellemeleri denetle** ile yeni sürüm varsa üstte "Güncelleme var: <sürüm> - İndir" çıkar; dokununca APK iner, SHA-256 özeti doğrulanır ve Android kurulum ekranı açılır.

## Dosyalar

Her Release'te iki dosya vardır:

- `KehribarVadisi_<sürüm>.apk` — oyun.
- `surum.json` — `versionCode`, `versionName`, APK indirme adresi, kısa değişiklik notu, APK'nın SHA-256 özeti ve boyutu. Oyun bu dosyayı okur.

Bütün APK'lar aynı anahtarla imzalanır. İmza sertifikasının SHA-256 özeti:

`9a07719872c2a170cbe29ce9ef05611869593aae8deddcbed5a22aad6cd48a9d`

## Lisans ve atıflar

Oyun ticari değildir, satılmaz. İçindeki üçüncü taraf varlıkların (modeller, dokular) yazarları ve lisansları oyunda **Ayarlar → Emeği geçenler** ekranında listelenir (CC BY / CC BY-NC / CC0 ve Megascans — Fab Standard License). APK'nın içindeki varlıklar ayrı ayrı çıkarılıp yeniden dağıtılamaz.
