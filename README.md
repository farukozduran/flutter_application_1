# Mini Katalog Uygulaması

## Proje Adı

Mini Katalog Uygulaması

## Proje Açıklaması

Bu proje, Flutter kullanılarak geliştirilen basit bir mobil katalog uygulamasıdır.
Uygulama, temel Flutter kavramlarını öğrenmek amacıyla geliştirilmiştir.

Proje kapsamında aşağıdaki konular uygulanmıştır:

* Flutter widget yapısı
* Sayfalar arası geçiş (Navigation)
* Temel kullanıcı arayüzü (UI) tasarımı
* Veri modeli oluşturma
* Proje klasörleme yapısı

Uygulamada ürünlerin listelendiği bir ana sayfa bulunmaktadır. Kullanıcılar bir ürüne tıkladığında ürünün detay bilgilerini görüntüleyebilmektedir.

## Kullanılan Teknolojiler

* Flutter
* Dart
* Material Design Widgets (`material.dart`)

## Flutter Sürümü

Bu proje aşağıdaki Flutter sürümü kullanılarak geliştirilmiştir:

```
Flutter 3.41.4
```
## Proje Yapısı

```
lib/
│
├── main.dart
├── model/
│   └── product.dart
├── services/
│   ├── api_service.dart
├── components/
│   ├── product_card.dart
└── views/
    └── home_screen.dart
    └── cart_screen.dart
    └── product_detail_screen.dart
```

## Uygulamayı Çalıştırma Adımları

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz.

1. Depoyu klonlayın

```
git clone https://github.com/kullaniciadi/projeadi.git
```

2. Proje klasörüne girin

```
cd projeadi
```

3. Gerekli paketleri yükleyin

```
flutter pub get
```

4. Uygulamayı çalıştırın

```
flutter run
```

## Not

Bu proje eğitim amacıyla geliştirilmiş bir uygulamadır ve Flutter'ın temel kullanımını göstermek için hazırlanmıştır.
