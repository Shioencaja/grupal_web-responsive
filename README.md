# Proyecto Grupal Muñoz Ballón

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.2.

## Como iniciar el proyecto

Este proyecto usa Angular para realizar la actividad. Se usa Angular Material en conjunto con Bootstrap para la realización de la interfaz.

Para iniciar el proyecto, es necesario iniciar el proyecto con `npm install` para instalar las dependencias y `npm install -g @angular/cli` para instalar
Angular CLI en la computadora.

Optamos por usar Angular por su facilidad de correción al usar Typescript, y la facilidad de estructura para crecimiento de la aplicación, además de contar con su propia librería de materiales que acelararían la creación del proeycto. Además, algunos componentes usan bootstrap para el layour general de la aplicación.

En la carpeta `app/auth` y `app/guard` se encuentran unas reglas para validar los accesos a la aplicación con correos que se jalan de el API [https://reqres.in/api], además de usar el API [https://63bdfb7ae348cb0762070d1a.mockapi.io/] para jalar los datos necesarios en la lista de alumnos.

Se han creado formularios para poder crear nuevos alumnos y agregarlos a la lista que son almacenados en el session storage. Se usar un servicio en la carpeta `src/app/core/services` que almacena la sesión.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
