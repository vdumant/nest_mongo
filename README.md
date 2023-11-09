## Nest Modular
- Generar modulo: nest g mo <module_name>
- Administrar Variables de Ambiente: npm i @nestjs/config  |   npm i 3.@nestjs/axios
- Validar esquemas Env: npm i --save joi
- Documentar Api: npm i --save @nestjs/swagger
- Habilitar CORS: main.ts--> app.enableCors();
## MongoDb
- Driver: npm i mongodb
- Tipado: npm i @types/mongodb -D
- Mongoose: npm i --save @nestjs/mongoose mongoose
- Pipe: nest g pi common/mongoId --flat
  - Main.ts: ```transformOptions: { enableImplicitConversion: true }```

## Installation

```bash
$ npm install
```

## Running the app

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

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).
