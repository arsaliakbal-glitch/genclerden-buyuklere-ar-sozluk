# Gençlerden Büyüklere · AR Sözlük

Canlı site: https://arsaliakbal-glitch.github.io/genclerden-buyuklere-ar-sozluk/

## Kullanım

- Kitap görünümünde sağ/sol oklarla veya klavyeyle 40 kelime arasında gez.
- **AR Görünümü** düğmesi, desteklenen Android cihazlarda WebXR yüzey AR’sini başlatır.
- iPhone/iPad Safari’de uygulama, kamera görüntüsünün ortasında duran kamera göreli 3B kitap sahnesini açar. HTTPS bağlantısı ve kamera izni gerekir.
- iPhone’da AR görünümünü açınca kitap kamera görüntüsünün ortasında belirir; iki parmakla kilidi aç, sayfaları kaydır ve boyutunu kıstırarak ayarla.
- İşaretçi görünürken kilitli kapak hedefin üzerinde belirir. İki parmağınla kilidi döndür; açıldıktan sonra sola kaydırıp kapağı aç, sağa/sola kaydırarak sayfaları çevir. İki parmakla yaklaştırıp uzaklaştırarak boyutunu ayarla. AR görünümünde sayfa düğmeleri kullanılmaz.

## Teknik not

Görüntü takibi MindAR ve A-Frame ile çalışır. Bu kütüphaneler CDN’den yüklenir; AR’yi açarken internet bağlantısı gerekir. Kitap görünümü ve 40 kelimenin içeriği uygulamanın içine gömülüdür. iOS Safari, WebXR `immersive-ar` oturumunu sunmadığından işaretçi tabanlı yol kullanılır. Kamera erişimi tarayıcının izin penceresiyle istenir. İşaretçi olarak MindAR’ın `1.2.5` sürümündeki `card.png` dosyasını kullan.

## Yayınlama

Depoda `main` dalının kök dizinini GitHub Pages kaynağı olarak seç. Tek sayfalı uygulama `index.html` üzerinden çalışır.
