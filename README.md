# Gençlerden Büyüklere AR Sözlük

Gençlerin günlük konuşmalarında ve dijital dünyada karşılaştığımız 40 kelimeyi anlaşılır tanımlar, ek açıklamalar ve günlük örneklerle sunan etkileşimli bir sözlük.

## Özellikler

- Kitap görünümünde sayfaları ileri ve geri çevirme
- Klavyedeki sağ ve sol ok tuşlarıyla gezinme
- Dokunmatik ekranda yana kaydırarak sayfa değiştirme
- Kelime ve konu başlığına göre arama
- WebXR destekli cihazlarda kameradan görünen ortama yerleştirilen AR kitap görünümü
- Telefon ve bilgisayar ekranlarına uyumlu tasarım

## Kullanım

`index.html` dosyasını bir tarayıcıda açarak sözlüğün kitap görünümünü kullanabilirsin. AR görünümü için sayfanın HTTPS üzerinden sunulması, tarayıcı ve cihazın WebXR `immersive-ar` özelliğini desteklemesi ve kamera izninin verilmesi gerekir. AR desteği cihaz ve tarayıcıya göre değişir.

## GitHub Pages ile yayımlama

1. Bu dosyaları yeni bir GitHub deposunun ana dizinine ekle.
2. Depoda **Settings → Pages** bölümünü aç.
3. **Deploy from a branch** seçeneğini seç; `main` dalı ve `/ (root)` klasörünü ayarla.
4. GitHub Pages adresi hazır olduğunda siteyi HTTPS bağlantısından aç. AR’yi WebXR destekli Android cihazda, uyumlu bir tarayıcıyla dene.

## İçerik

40 kelimenin tanımları, örnek cümleleri ve sözlük açıklamaları uygulamanın içine gömülüdür. Kelime listesi uygulama açıldığında internetten indirilmez. Google Fonts bağlantısı çevrim içi olduğunda özel yazı tiplerini yükler; bağlantı yoksa sistem yazı tipleri kullanılır.

## Gizlilik

Uygulama sözlük aramalarını herhangi bir sunucuya göndermez. AR düğmesine basıldığında kamera erişimi, tarayıcı ve cihazın AR özelliğine bağlı olarak istenir. Kamera görüntüsü uygulama kodu tarafından kaydedilmez veya bir sunucuya gönderilmez.

## Uygulama dosyası

- `index.html` — sözlüğün tamamı ve çalışma kodu tek dosyada.
