# Gençlerden Büyüklere · AR Sözlük

Canlı site: https://arsaliakbal-glitch.github.io/genclerden-buyuklere-ar-sozluk/

Gençlerin günlük dilindeki 40 kelimeyi tanım, açıklama, kullanım örneği ve "Yani" bölümüyle anlatan interaktif sözlük.

## Kullanım

- **Kitap görünümü:** Sağ/sol ok düğmeleri, klavyedeki ← → tuşları veya parmakla kaydırarak kelimeler arasında gez. Soldaki listeden kelime arayıp doğrudan seçebilirsin.
- **3B Görünüm:** Kitabı fareyle ya da parmakla döndür, tekerlek veya iki parmakla yaklaştır. Sola kaydırarak (veya **İleri** düğmesiyle) kapağı aç ve sayfaları çevir; son kelimeden sonra kitap arka kapağa döner.
- **AR’de aç (Android):** Desteklenen Android cihazlarda WebXR yüzey AR’si başlar. Telefonu yavaşça hareket ettir, yüzey algılanınca ekrana dokunarak sözlüğü yerleştir.
- **AR’de aç (iPhone/iPad):** Safari’de kamera açılır ve 3B kitap kamera görüntüsünün ortasında belirir. İki parmakla döndürerek kilidi aç, sola kaydırıp kapağı aç, sağa/sola kaydırarak sayfaları çevir, iki parmakla kıstırarak boyutunu ayarla. Kitap ortama sabitlenmez; ekranın ortasında durur.

## Teknik not

- Tek sayfalı uygulamadır; her şey `index.html` içindedir. Kelimeler dosyanın başındaki `words` listesinde tutulur. Sayaçlar ve kapak yazıları bu listenin uzunluğundan hesaplanır, kelime eklemek ya da çıkarmak için yalnızca listeyi düzenlemek yeterlidir.
- 3B görünüm için Three.js (0.159), iPhone AR için A-Frame (1.5) CDN’den yüklenir; bu görünümleri açarken internet bağlantısı gerekir. Kitap görünümü internetsiz de çalışır (yazı tipleri hariç).
- iOS Safari WebXR `immersive-ar` oturumunu sunmadığı için iPhone’da kamera görüntüsü üzerinde A-Frame sahnesi kullanılır; işaretçi (marker) gerekmez.
- Kamera için HTTPS bağlantısı ve tarayıcının kamera izni gerekir.

## Yayınlama

Depoda `main` dalının kök dizinini GitHub Pages kaynağı olarak seç. Uygulama `index.html` üzerinden çalışır.
