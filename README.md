# Tomin <!-- omit in toc -->

Aplicacion Neobanking de inclusión financiera.

## Tabla de Contenido<!-- omit in toc -->
- [Acceso a la api](#acceso-a-la-api)
- [Ambiente del proyecto](#ambiente-del-proyecto)
  - [Ejecución de la api](#ejecuci%c3%b3n-de-la-api)

# Acceso a la api
La api se encuentra publicada en la siguiente ruta:

[Api tomin](http://tomin-env-2.eba-dymffph5.us-west-2.elasticbeanstalk.com/)

# Ambiente del proyecto

* AWS
  * API (Node Js - Adonis)
  * PostgreSQL
  * App móvil (Dart - Flutter)

## Ejecución de la api

Descargar el repo, configurar acceso a la bd y ejecutar lo siguiente

Instalar el CLI de adonis para usar comandos de consola
```shell
cd api
npm i
npm i -g @adonisjs/cli
```

Preparar ambiente
```shell
adonis migration:run
adonis serve --dev
```
