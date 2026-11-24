# Maaş İade ve Borç Hesaplama Programı — Güncelleme Kanalı

Bu depo yalnızca uygulamanın **herkese açık sürüm bildirimlerini (`version.json`)** ve derlenmiş Windows kurulum paketlerini (**GitHub Releases**) barındırır.

> Uygulamanın kaynak kodları gizli (Private) depoda tutulmaktadır.

## Güncel Sürüm: `v2.1.2` (2026-11-24)

- **İndirme:** [Son Sürümü İndir (v2.1.2)](https://github.com/burhannecare57-dev/maas-iade-programi-updates/releases/tag/v2.1.2)
- **Dosya Adı:** `Maas_Iade_Programi.exe`
- **Dosya Boyutu:** `59.48 MB`
- **SHA-256:** `3004911cc48f5fffc48573139170729e3531d2c33d07b186b2b0d91420514c2c`

## Değişiklik Notları

- MEB ve kurumsal ağlarda yaşanan SSL sertifika doğrulama hatası giderildi (Windows CryptoAPI / truststore ve ROOT+CA sertifika deposu desteği)
- Python 3.13 katı X.509 doğrulamasının kurumsal SSL sertifikalarını reddetmesi sorunu çözüldü
- Kurumsal özel CA dosyası (MAAS_IADE_CA_BUNDLE / SSL_CERT_FILE) ve ayrıntılı SSL hata bildirimi eklendi
