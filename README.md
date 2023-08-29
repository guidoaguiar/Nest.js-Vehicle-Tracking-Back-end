# Nest.js Vehicle Tracking Back-end [WIP]

- [Nest.js Vehicle Tracking Back-end \[WIP\]](#nestjs-vehicle-tracking-back-end-wip)
  - [Description](#description)
    - [Tech used (or to be used)](#tech-used-or-to-be-used)
  - [Installation](#installation)
  - [Running the app](#running-the-app)
  - [Test](#test)
  - [Support](#support)
  - [Stay in touch](#stay-in-touch)
  - [License](#license)


## Description

Project to track vehicles in real time.
For this project I'll not use a live car, but will generate the lat and lng to be sent to the server simulating a live car riding on the street.

### Tech used (or to be used)
- [Node.js](https://nodejs.org/)
- [Nest.js](https://nestjs.com/)
- [Next.js](https://nextjs.org/)
- [Kafka](https://kafka.apache.org/)
- [Golang](https://golang.org/)
- [Docker](https://www.docker.com/)
- [Google Maps APIs](https://developers.google.com/maps)
- [MongoDB](https://www.mongodb.com/)
- [Prisma](https://www.prisma.io/)

## Installation

```bash
$ npm install
```

## Running the app

```bash
# start docker services
$ docker compose up
# Once it has started, get inside the container.
```

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Test API endpoints

Use Rest Client extension for VSCode to test the API endpoints.

```bash
# start the server
npm run start:dev


# open the file
.api.http
# and click on "Send Request" button to test the endpoints
``` 



## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- [Guido](https://www.linkedin.com/in/guidoaguiar/)
- [Buy me a :pizza:](https://www.buymeacoffee.com/guidoaguiar)
## License

Nest is [MIT licensed](LICENSE).
