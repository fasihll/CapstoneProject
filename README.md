# Culinaryndo App
> This application aims to identify various types of food. Apart from helping users identify food, this application also provides detailed information about the origin, main ingredients and Indonesian food, thereby helping them choose food more intelligently..

## Developed by
M015BSY1175 - Muhammad Alansyah - Universitas Negeri Yogyakarta -  Machine Learning

M015BSY1428 - Firman Satria Sasmita - Universitas Negeri Yogyakarta -  Machine Learning

M487BSX0078 - Diajeng Mahai Sukma - Universitas Alma Ata -  Machine Learning

C015BSY3780 - Ilham Maulana - Universitas Negeri Yogyakarta - Cloud Computing

C008BSX4077 - Elyra Dina Oktaviani - Universitas Gadjah Mada - Cloud Computing

A179BSY2366 - Muhamad Andhika Satya Azizi - Universitas Ahmad Dahlan - Mobile Development

A129BSY2594 - Ach Fasihul Lisan - Politeknik Negeri Jember - Mobile Development


![](header.png)

## Setup Server side

Install Node JS:

https://nodejs.org/en/download/

Clone Project:

```sh
git clone https://github.com/Mahantaa/CapstoneProject
```

Setup .env:

```sh
PORT = YOUR_PORT

DB_USERNAME = USERNAME
DB_PASSWORD = YOUR_PASSWORD
DB_NAME = DATABASE_NAME
DB_HOST = DATABASE_HOST
DB_DIALECT = mysql
DB_PORT = DATABASE_PORT

JWT_SECRET = YOUR_JSW_SCRET
```
Migrate Databse:

```sh
db:migrate
```
Run Server-side:

```sh
npm run start
```

## Setup Andoid Studio Project

Set Google Credential or API_KEY in local.properties:

```sh
MAPS_API_KEY= YOUR_GOOGLE_API_KEY
```

## Api Documentation

https://documenter.getpostman.com/view/30105572/2s9YkjA3QE

## Contributing

1. Fork it (https://github.com/Mahantaa/CapstoneProjec)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
