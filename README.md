# Gençlerden Büyüklere · AR Sözlük

Canlı site: https://arsaliakbal-glitch.github.io/genclerden-buyuklere-ar-sozluk/

## Kullanım

- Kitap görünümünde sağ/sol oklarla veya klavyeyle 40 kelime arasında gez.
- **AR Görünümü** düğmesi, desteklenen Android cihazlarda WebXR yüzey AR’sini başlatır.
- iPhone/iPad Safari’de uygulama, görüntü işaretçisi takibiyle kamera AR’sine geçer. HTTPS bağlantısı ve kamera izni gerekir.
- iPhone’u işaretçiye doğrult. İşaretçiyi başka ekranda aç veya yazdır; aynı telefonun ekranındaki işaretçiyi kendi kamerasıyla tarayamaz.
- İşaretçi görünürken sözlük kartı hedefin üzerinde sabitlenir; alttaki oklarla kelimeler arasında geçiş yap.

## iPhone işaretçisi

[İşaretçi görselini aç](https://hiukim.github.io/mind-ar-js-doc/assets/images/card-06cb9111a8e32627db6bfafc7aa22a4d.png)

## Teknik not

Görüntü takibi MindAR ve A-Frame ile çalışır. Bu kütüphaneler CDN’den yüklenir; AR’yi açarken internet bağlantısı gerekir. Kitap görünümü ve 40 kelimenin içeriği uygulamanın içine gömülüdür. iOS Safari, WebXR `immersive-ar` oturumunu sunmadığından işaretçi tabanlı yol kullanılır. Kamera erişimi tarayıcının izin penceresiyle istenir.

## Yayınlama

Depoda `main` dalının kök dizinini GitHub Pages kaynağı olarak seç. Tek sayfalı uygulama `index.html` üzerinden çalışır.
