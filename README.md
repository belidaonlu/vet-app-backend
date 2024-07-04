# VETAPP

## BACKEND Canli Linki:
https://favourite-sande-vet-api-943e089a.koyeb.app/
## FRONTEND Github Linki:
https://github.com/belidaonlu/vet-app-frontend
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



# VETAPP
## BACKEND Live Link:
https://favourite-sande-vet-api-943e089a.koyeb.app/

## FRONTEND GitHub Link:
https://github.com/belidaonlu/vet-app-frontend

## Veterinary Management System
The Veterinary Management System is a REST API created to organize and manage the daily operations of veterinary clinics. This API allows veterinary staff to manage veterinary doctors, clients, animals, vaccinations, and appointments.

The backend is developed with Spring Boot, the database with PostgreSQL, and it is deployed using the Koyeb service with Docker as the operating system.

## Setup
Clone the project.
Configure the database in the src/main/resources/application.properties file.
Start the project from your IDE.
The API can be used via Swagger. Go to http://localhost:8080/swagger-ui/index.html#/ in your browser.
You can make requests to the endpoints.
## Docker
Clone the project.
In the root directory, run
docker-compose up
Environment Variables (.ENV)
To run this project, you need to change the following environment variables in the application.properties file:

VETAPP_DB_PASS
VETAPP_DB_USER
VETAPP_DB_URL
VETAPP_DB_NAME
