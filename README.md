# Gençlerden Büyüklere Sözlüğü

Canlı site: https://arsaliakbal-glitch.github.io/genclerden-buyuklere-ar-sozluk/

Gençlerin günlük dilindeki 40 kelimenin okunuşunu, anlamını ve kullanım örneğini veren sözlük.

## Kullanım

Sayfa, basılı bir cep sözlüğü gibi dizildi: kelimeler alfabe sırasında, madde başı kalın, okunuş köşeli parantezde, örnek cümle italik. Sağ kenardaki kırmızı harf sekmeleri o harfe götürür.

- **Sözlük sayfası:** Her madde şu sırayla yazılır: kelime, [okunuş], kökeni, tanım; ardından italik örnek cümle ve "yani" ile anlamı; en altta kısa açıklama.
- **Arama:** Kelimenin yanında okunuşta, tanımda ve açıklamada da arar; örneğin "utan" yazınca "cringe" bulunur.
- **Kelimeye özel bağlantı:** Adres çubuğundaki `#cringe` gibi bir bağlantı doğrudan o maddeyi açar.
- **3B kitap:** Kırmızı bez kaplı cep sözlüğünü fareyle ya da parmakla döndür, kıstırarak yaklaş. **İleri** / **Geri** düğmeleriyle ya da kaydırarak kapağı aç ve sayfaları çevir. Sayfalarda iki madde, sayfa başında yol gösteren kelime ve harf sekmesi vardır; en sonda dizin bulunur.
- **Kamerada aç:** Arka kamera tam ekran açılır ve sözlük sayfası kamera görüntüsünün ortasına sabitlenir. Sola kaydırınca ileri, sağa kaydırınca geri gider (ilk kaydırma kapağı açar); iki parmakla kıstırarak büyütüp küçültebilirsin. **Kapat** ile çıkınca sayfa son baktığın maddeye gider. iPhone ve Android’de aynı şekilde çalışır; kamera izni verilmezse sözlük kamerasız gösterilir.

## Teknik not

- Tek sayfalı uygulamadır; her şey `index.html` içindedir. Kelimeler dosyanın başındaki `words` listesinde tutulur. Sayaçlar ve kapak yazıları bu listenin uzunluğundan hesaplanır, kelime eklemek ya da çıkarmak için yalnızca listeyi düzenlemek yeterlidir.
- Yazı tipi: Alegreya (Google Fonts). Okunuşlar `OKUNUS` listesinde tutulur ve yaklaşık değerlerdir.
- 3B görünüm için Three.js (0.159) CDN’den yüklenir; bu görünümü açarken internet bağlantısı gerekir. Kamera görünümü ek kütüphane kullanmaz.
- Kamera için HTTPS bağlantısı ve tarayıcının kamera izni gerekir.

## Yayınlama

Depoda `main` dalının kök dizinini GitHub Pages kaynağı olarak seç. Uygulama `index.html` üzerinden çalışır.
