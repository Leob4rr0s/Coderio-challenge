![Coderio](./src/assets/logo.svg "Coderio")

# Coderio fullstack challenge: World clock
Tenemos que crear una aplicación que muestre diferentes timezones elegidos por el usuario. Esos timezones se obtienen desde [la siguiente API](http://worldtimeapi.org/) y se agregan a la app desde un search box.

## API
Se debe desarrollar una api con:

* GET /timezones -> Obtiene todos los timezones.
* GET /timezones/:name -> Obtiene un timezone específico.
* PUT /timezones/:name -> Agrega un timezone específico al usuario.
* DELETE /timezones/:name -> Elimina un timezone específico del usuario.

## Frontend
Debe tener un search box con auto complete. Debajo todos los timezones seleccionados, cada uno con su respectivo botón de borrar.

![Ejemplo](./src/assets/spec.png "Ejemplo")

## Modalidad de entrega
* Repositorio público subido a GitHub, Gitlab, Bitbucket.
* Link a la aplicación funcionando.

## Corriendo el proyecto
```bash
# Instalar dependencias del proyecto
npm i

# Correr el servidor de desarrollo
npm run dev
```
* MongoDB URL Local: 
    mongodb://localhost:27017/challenges

## Config the enverioment variables
    Rename the file __.env.template__ to __.env__

## Fill the DB with test info
    Call to:
    ```
        http://localhost:3000/api/seed
    ```
