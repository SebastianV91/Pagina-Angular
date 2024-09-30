# AngDockerizedApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.1.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

DockerAngular

## Construir con Docker Angular

Correr `docker build --no-cache --progress=plain -t angular-dockerized ` para construir el proyecto.

## Correr Docker Angular

Correr `docker run -d -it -p 4000:80/tcp angular-dockerized`

## Correr con docker compose

Correr `docker-compose up --build`
