<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar
```
yarn install
```

3. Tener Nest CLI instalado
```
npm i -g @nestjs/cli
```

4. Levantas la base de datos
```
docker-compose up -d
```

5. Clonar el archivo ```.env.template``` y renombar la copia a ```__.env```
```


```
6. Llenar las variables de entorno definidas en el ```.env```
```
http://localhost:3000/api/v2/seed

```
7. Ejecutar la aplicacion en dev:
```
yarn start:dev

```
8. Recontruir la base de datos con la semilla
```
http://localhost:3000/api/v2/seed

```

## Stack usado
* MongoDB
* Nest