# Gençlerden Büyüklere · AR Sözlük

Canlı site: https://arsaliakbal-glitch.github.io/genclerden-buyuklere-ar-sozluk/

## Kullanım

- Kitap görünümünde sağ/sol oklarla veya klavyeyle 40 kelime arasında gez.
- **AR Görünümü** düğmesi, desteklenen Android cihazlarda WebXR yüzey AR’sini başlatır.
- iPhone/iPad Safari’de uygulama, görüntü işaretçisi takibiyle kamera AR’sine geçer. HTTPS bağlantısı ve kamera izni gerekir.
- iPhone’u işaretçiye doğrult. İşaretçiyi başka ekranda aç veya yazdır; aynı telefonun ekranındaki işaretçiyi kendi kamerasıyla tarayamaz.
- İşaretçi görünürken kapak hedefin üzerinde belirir. Ekranı sola kaydırarak kapağı aç, sağa/sola kaydırarak sayfaları çevir; AR görünümünde sayfa düğmeleri kullanılmaz.

## iPhone işaretçisi

[Kullanılacak işaretçi görselini aç](https://cdn.jsdelivr.net/gh/hiukim/mind-ar-js@1.2.5/examples/image-tracking/assets/card-example/card.png)

## Teknik not

Görüntü takibi MindAR ve A-Frame ile çalışır. Bu kütüphaneler CDN’den yüklenir; AR’yi açarken internet bağlantısı gerekir. Kitap görünümü ve 40 kelimenin içeriği uygulamanın içine gömülüdür. iOS Safari, WebXR `immersive-ar` oturumunu sunmadığından işaretçi tabanlı yol kullanılır. Kamera erişimi tarayıcının izin penceresiyle istenir. İşaretçi olarak MindAR’ın `1.2.5` sürümündeki `card.png` dosyasını kullan.

## Yayınlama

Depoda `main` dalının kök dizinini GitHub Pages kaynağı olarak seç. Tek sayfalı uygulama `index.html` üzerinden çalışır.
