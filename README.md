# DataLife Engine Güncel Türkçe Yaması
<img src="https://img.shields.io/badge/dle-14.0-007dad.svg"> <img src="https://img.shields.io/badge/lang-tr-ce600f.svg"> <img src="https://img.shields.io/badge/license-GNU-60ce0f.svg">

DLE Türkçe dil dosyasını ve sistem üzerinde yapılması gereken değişiklikleri plugin olarak sisteminize yükleyebilirsiniz.

## Çeviri Sahipleri

* **MaRZoCHi** DLE 9.7 ve sonrası
* **Supremacy** DLE 9.6 ve öncesi ( *Çevirileri için teşekkürler..* )

### Değişiklikler
---------
* Türkçe çeviri üzerinde düzenlemeler yapıldı. ( Kendi [çevirimizin](https://github.com/dlenettr/dle-turkce) tamamlanan kısımları mevcut dil dosyasına dahil edildi. )
* Kullanılan Rusça servisler Türkçe muadilleri ile değiştirildi.
* URL Rewrite için Türkçe karakter desteği eklendi.

## Güncelleme
1. Yönetici panelinizde **Tüm panel bölümleri > Eklentileri Yönet** (`admin.php?mod=plugins`) sayfasını açınız.
2. Eklenti listesinin en altında bulunan veya `DLE Türkçe Yama` eklentisine ait menüde bulunan **Güncellemeleri kontrol et** butonuna tıklayınız.
3. Çeviriler otomatik olarak Github'dan çekilerek güncellenecektir.

## Kurulum
1. Yönetici panelinizde **Tüm panel bölümleri > Eklentileri Yönet** (`admin.php?mod=plugins`) sayfasını açınız.
2. **Eklenti yükle** butonuna tıklayınız.
3. Açılan penceredeki **Dosya seç** butonuna tıklayınız.
4. Buradan indirdiğiniz arşivdeki plugins klasöründe bulunan `plugins/dle<sürüm>.zip` dosyasını seçiniz.
5. Ardından **Eklenti yükle** butonuna tıklayınız.
6. Son olarak **Site Ayarları > Genel Ayarlar** sayfasından (`admin.php?mod=options&action=syscon`) Site dilini Türkçe olarak seçip kaydedebilirsiniz.
7. Yeni DLE sürümleri yüklediğinizde tek yapmanız gereken **Güncellemeleri kontrol et** butonuna tıklamak olacaktır. Eğer güncelleme varsa otomatik olarak indirilerek yüklenecektir.



> **Not:** Açıklamalar Türkçe olarak yazılmıştır. İngilizce veya Rusça olarak kullandığınızda, çeviri yaparak aynı işlemleri gerçekleştirebilirsiniz.
>
> Plugin yüklendiğinde hata alırsanız önemsemeyiniz.



![Ekran 1](/docs/screen1.png?raw=true)

![Ekran 2](/docs/screen2.png?raw=true)

![Ekran 3](/docs/screen3.png?raw=true)

## Kurulum Sonrası

* Kurulumdan sonra `/templates/opensearch.tpl` dosyasını sitenize göre düzenleyiniz.
* Yönetici panelinize girerek tüm sistem ve kullanıcı ayarlarını inceleyiniz.

