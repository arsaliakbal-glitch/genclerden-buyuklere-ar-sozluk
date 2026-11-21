# Gençlerden Büyüklere · AR Sözlük

Canlı site: https://arsaliakbal-glitch.github.io/genclerden-buyuklere-ar-sozluk/

Gençlerin günlük dilindeki 40 kelimeyi tanım, açıklama, kullanım örneği ve "Yani" bölümüyle anlatan interaktif sözlük.

## Kullanım

- **Kitap görünümü:** Sağ/sol ok düğmeleri, klavyedeki ← → tuşları veya parmakla kaydırarak kelimeler arasında gez. Soldaki listeden kelime arayıp doğrudan seçebilirsin.
- **3B Görünüm:** Kitabı fareyle ya da parmakla döndür, tekerlek veya iki parmakla yaklaştır. Sola kaydırarak (veya **İleri** düğmesiyle) kapağı aç ve sayfaları çevir; son kelimeden sonra kitap arka kapağa döner.
- **AR’de aç:** Arka kamera tam ekran açılır ve sözlük kamera görüntüsünün ortasına sabitlenir. Ekranda sola kaydırınca ileri, sağa kaydırınca geri gider (ilk kaydırma kapağı açar); iki parmakla kıstırarak büyütüp küçültebilirsin. **Kapat ✕** ile çıkınca kitap görünümü son baktığın kelimede açılır. iPhone ve Android’de aynı şekilde çalışır; kamera izni verilmezse sözlük kamerasız gösterilir.

## Teknik not

- Tek sayfalı uygulamadır; her şey `index.html` içindedir. Kelimeler dosyanın başındaki `words` listesinde tutulur. Sayaçlar ve kapak yazıları bu listenin uzunluğundan hesaplanır, kelime eklemek ya da çıkarmak için yalnızca listeyi düzenlemek yeterlidir.
- 3B görünüm için Three.js (0.159) CDN’den yüklenir; bu görünümü açarken internet bağlantısı gerekir. Kamera görünümü ek kütüphane kullanmaz.
- Kamera için HTTPS bağlantısı ve tarayıcının kamera izni gerekir.

## Yayınlama

Depoda `main` dalının kök dizinini GitHub Pages kaynağı olarak seç. Uygulama `index.html` üzerinden çalışır.
