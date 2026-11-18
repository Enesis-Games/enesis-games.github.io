# Çay Ocağı uzaktan ayar dosyası (config.json)

Oyun her açılışta bu dosyayı okur.

- `latestVersionCode`: Mağazadaki en yeni sürümün numarası (versionCode). Oyuncunun sürümü bundan eskiyse
  ana menüde bir kez "Yeni sürüm var: Güncelle / Sonra" penceresi çıkar. Oyuncu erteleyebilir.
- `minVersionCode`: İzin verilen en eski sürüm. Normalde **0**. Oyuncunun sürümü bundan eskiyse oyun açılmaz,
  "Güncellemen gerekiyor" ekranı çıkar. Sadece acil durumda yükselt (ciddi hata, hile açığı, mod APK salgını).
- `message`: Zorunlu güncelleme ekranında gösterilecek ek açıklama (boş bırakılabilir).

ÖNEMLİ: `minVersionCode` değerini mağazada henüz yayınlanmamış bir sürüme ayarlama.
Yoksa kimse oyunu açamaz. Önce güncellemenin Play'de herkese açıldığından emin ol.
