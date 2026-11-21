# Gençlerden Büyüklere · AR Sözlük

Canlı site: https://arsaliakbal-glitch.github.io/genclerden-buyuklere-ar-sozluk/

Gençlerin günlük dilindeki 40 kelimeyi tanım, açıklama, kullanım örneği ve "Yani" bölümüyle anlatan interaktif sözlük.

## Kullanım

Sözlük bir okul defteri gibi tasarlandı: kareli sayfalar, kırmızı kenar çizgisi, kırmızı kalemle altı çizilmiş kelimeler ve mesaj balonunda gerçek bir kullanım örneği.

- **Defter görünümü:** Sağ sayfada kelime, kısa tanım ve açıklama; sol sayfada gençlerin o kelimeyi nasıl kullandığı ve "Yani" ile anlamı yer alır. Alttaki düğmeler, klavyedeki ← → tuşları ya da parmakla kaydırarak sayfa çevrilir.
- **Kelimeler ve arama:** Soldaki listede (telefonda **Kelimeler** düğmesi) kelimeler konularına göre gruplanır. Arama kutusu kelimenin yanında anlamında da arar; örneğin "utan" yazınca "cringe" bulunur.
- **Kelimeye özel bağlantı:** Adres çubuğundaki bağlantı açık olan kelimeyi gösterir (ör. `#ghostlamak`); paylaşılınca doğrudan o sayfa açılır.
- **3B defter:** Spiralli defteri fareyle ya da parmakla döndür, kıstırarak yakınlaştır. **İleri** / **Geri** düğmeleriyle ya da kaydırarak kapağı aç ve sayfaları çevir; son kelimeden sonra arka kapaktaki kelime tablosu görünür.
- **Kamerada aç:** Arka kamera tam ekran açılır ve defter kamera görüntüsünün ortasına sabitlenir. Sola kaydırınca ileri, sağa kaydırınca geri gider (ilk kaydırma kapağı açar); iki parmakla kıstırarak büyütüp küçültebilirsin. **Kapat** ile çıkınca defter son baktığın kelimede açılır. iPhone ve Android’de aynı şekilde çalışır; kamera izni verilmezse defter kamerasız gösterilir.

## Teknik not

- Tek sayfalı uygulamadır; her şey `index.html` içindedir. Kelimeler dosyanın başındaki `words` listesinde tutulur. Sayaçlar ve kapak yazıları bu listenin uzunluğundan hesaplanır, kelime eklemek ya da çıkarmak için yalnızca listeyi düzenlemek yeterlidir.
- Yazı tipi: az gören okurlar düşünülerek tasarlanmış Atkinson Hyperlegible Next (Google Fonts).
- 3B görünüm için Three.js (0.159) CDN’den yüklenir; bu görünümü açarken internet bağlantısı gerekir. Kamera görünümü ek kütüphane kullanmaz.
- Kamera için HTTPS bağlantısı ve tarayıcının kamera izni gerekir.

## Yayınlama

Depoda `main` dalının kök dizinini GitHub Pages kaynağı olarak seç. Uygulama `index.html` üzerinden çalışır.
