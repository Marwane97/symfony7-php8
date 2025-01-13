# Symfony 7 Project Template

Bu proje Symfony 7 ve PHP 8.2 kullanılarak oluşturulmuş bir başlangıç projesidir.

## Gereksinimler

- PHP 8.2 veya üzeri
- Composer
- Symfony CLI
- MySQL8

## Kurulum

1. Projeyi klonlayın
   git clone [proje-url]
   cd [proje-klasörü]

2. Bağımlılıkları yükleyin
   composer install

3. .env dosyasını kopyalayın ve düzenleyin
   cp .env .env.local

4. Veritabanını oluşturun
   php bin/console doctrine:database:create
   php bin/console doctrine:migrations:migrate

5. Symfony development sunucusunu başlatın
   symfony server:start

## Proje Yapısı

```
.
├── bin/
├── config/
├── migrations/
├── public/
├── src/
│   ├── Controller/
│   ├── Entity/
│   ├── Repository/
│   └── Service/
├── templates/
└── tests/
```

## Özellikler

- Symfony 7.x
- PHP 8.2
- Doctrine ORM
- Twig Template Engine
- Symfony Security
- Symfony Forms

## Geliştirme

- Controller'lar src/Controller/ dizininde bulunur
- Entity'ler src/Entity/ dizininde bulunur
- Twig şablonları templates/ dizininde bulunur

## Test

php bin/phpunit

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## İletişim

[İsminiz] - [email@example.com]

Proje Linki: https://github.com/username/repo