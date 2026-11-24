# Sürüm Geçmişi (Changelog)

## v2.1.2 (2026-11-24)

- MEB ve kurumsal ağlarda yaşanan SSL sertifika doğrulama hatası giderildi (Windows CryptoAPI / truststore ve ROOT+CA sertifika deposu desteği)
- Python 3.13 katı X.509 doğrulamasının kurumsal SSL sertifikalarını reddetmesi sorunu çözüldü
- Kurumsal özel CA dosyası (MAAS_IADE_CA_BUNDLE / SSL_CERT_FILE) ve ayrıntılı SSL hata bildirimi eklendi

- **SHA-256:** `3004911cc48f5fffc48573139170729e3531d2c33d07b186b2b0d91420514c2c`

## v2.1.1 (2026-11-24)

- Kullanıcı Girişi (Şifre Kaydet, Yıl Seçimi/Yeni Yıl, Ağ Ayarları, Güncelleme) ve Kullanıcı Yetkilendirme ekranı eklendi
- Çalışma yılı izolasyonu eklendi: yalnızca seçili çalışma yılının kayıt ve raporları gösterilir
- Hesaplama ekranında III. Kesintiler (Satır 61-70) çoklu seçim listesi, canlı tutar kutucukları ve anlık otomatik hesaplama eklendi
- Veri sayfasına Onaylayanlar sekmesi ve her bilgisayara özel yerel varsayılan imza seçimi (EK-1 Excel/PDF uyumlu) eklendi
- Raporlama ekranında mükerrer hesaplama tespiti ve güvenli silme özelliği eklendi
- 300+ kayıtlı Bordro Kayıt tablosunda donmuş sütunlardaki satır kayması sorunu giderildi

- **SHA-256:** `aadc74899a62a48ff5f72f1f348838e2f2800e3fcc2266ed3f780cf2cf27a492`

## v2.1.0 (2026-11-23)

- 83 Sıra No.lu Genel Tebliğ EK-1 ve KBS bordro hesaplama motoru
- Yerleşik şifreli SQLite LAN sunucusu ve çok kullanıcılı senkronizasyon
- Üst başlık düzeni, yardım mevzuat belgeleri ve kurumsal ağ uyumlu otomatik güncelleme kontrolü

- **SHA-256:** `69261182d2e28d46df14aa867b450ec6c6d776f5dd475c736c913b68b34b178e`
