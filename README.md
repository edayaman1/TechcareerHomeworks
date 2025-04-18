# TechcareerHomeworks

# API Test Projesi

Bu repo, Swagger PetStore API'si ve Trendyol Manuel Test senaryolarını içeren bir test projesidir.

## İçerik

- [Postman Koleksiyonu](#postman-koleksiyonu)
- [Manuel Test Senaryoları](#manuel-test-senaryoları)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)

## Postman Koleksiyonu

`postman_collection.json` dosyası, Swagger PetStore API'sinin kullanıcı işlemleri için hazırlanmış bir Postman koleksiyonudur. Bu koleksiyon aşağıdaki API endpoint'lerini içerir:

- **Kullanıcı Oluşturma** (`POST /user`)
- **Kullanıcı Bilgisi Alma** (`GET /user/{username}`)
- **Kullanıcı Güncelleme** (`PUT /user/{username}`)
- **Kullanıcı Silme** (`DELETE /user/{username}`)
- **Kullanıcı Girişi** (`GET /user/login`)
- **Kullanıcı Çıkışı** (`GET /user/logout`)

## Manuel Test Senaryoları

`Trendyol_Manuel Test.xlsx` dosyası, Trendyol web sitesi/uygulaması için hazırlanmış manuel test senaryolarını içerir. 

## Kurulum

### Postman Koleksiyonunu İçe Aktarma

1. [Postman](https://www.postman.com/downloads/) uygulamasını indirin ve kurun
2. Postman'i açın
3. "Import" butonuna tıklayın
4. `postman_collection.json` dosyasını seçin ve import edin

## Kullanım

### Postman API Testlerini Çalıştırma

1. Postman'de import ettiğiniz koleksiyonu seçin
2. İstediğiniz API endpoint'ini seçin (örn. "create user")
3. "Send" butonuna tıklayarak isteği gönderin
4. Yanıtı inceleyerek API'nin beklenen şekilde çalışıp çalışmadığını kontrol edin

### Manuel Test Senaryolarını Çalıştırma

1. `Trendyol_Manuel Test.xlsx` dosyasını açın
2. Test senaryolarını takip ederek manuel testleri gerçekleştirin
3. Excel dosyasında belirtilen adımları izleyin ve sonuçları kaydedin
