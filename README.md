# VETAPP

## BACKEND Canli Linki:
.......
## FRONTEND Github Linki:
.......
## Veteriner Yönetim Sistemi

Veteriner Yönetim Sistemi, veteriner kliniklerinin günlük işlerini düzenlemek ve yönetmek amacıyla oluşturulmuş bir REST API'dir. Bu API ile veteriner çalışanının veteriner doktorları, müşterileri, hayvanları ve aşılarını, randevuları yönetmesi sağlanır.

Backendi springboot app ile, database'i postgreSQL ile gelistirilmis olup docker isletim sistemi kullanilarak koyeb servisi ile canliya alinmistir.

## Kurulum
1. Projeyi klonlayın.
2. `src/main/resources/application.properties` dosyasında veri tabanı konfigürasyonunu yapın.
3. Projeyi ayağa kaldırmak için idenizden start edin.
4. Swagger üzerinden api kullanılabilir. Tarayıcınızdan http://localhost:8080/swagger-ui/index.html#/ url'ine gidin.
5. End pointlere istek atabilirsiniz.

## Docker
1. Projeyi klonlayın.
2. Kök dizinde
   - `docker-compose up`komutunu çalıştırın

## Ortam Değişkenleri (.ENV)

Bu projeyi çalıştırmak için aşağıdaki ortam değişkenlerini application.properties dosyasından değiştirmelisiniz.

VETAPP_DB_PASS
VETAPP_DB_USER
VETAPP_DB_URL
VETAPP_DB_NAME
