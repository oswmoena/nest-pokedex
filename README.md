<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456

[circleci-url]: https://circleci.com/gh/nestjs/nest

# Ejecutar en dsarrollo

1. Clonar el repo

2. Ejecutar

```
   npm i
```

3. Tener NestCLI instalado

```
   npm i -g @nestjs/cli
```

4. Levantar BDD

```
   docker-compose up -d
```

5. Clonar el archivo __.env.template__
6. Llenar las variables definidas en el __.env__
7. Ejecutar

```
   npm run start:dev
```

8. Recontruir la base de datos con la semilla

```
   http://localhost:3200/api/v2/seed
```

## Stack

* Mongo
* Nest
