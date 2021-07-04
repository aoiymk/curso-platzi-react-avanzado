# Curso Avanzado React

El objetivo del curso es crear una aplicación muy parecida a Instagram, llamada petgram. Tendremos nuestras rutas, gestión de usuarios y likes.

## Tecnologías

1. Empaquetador y transpilador:
- Webpack
- Babel

2.Estilado con CSS en JS con:
- styled-components

3.Linter:
- Standard JS

4.Fetching (obtención) de datos:
- GraphQL
- React Apollo

5. Enrutado de la SPA:
- React Router

6. Para las buenas prácticas:
- Lighthouse
- Cypress

7. SEO, PWA y Deploy
- React Helmet
- Workbox
- Progressive Web App
- Deply con Now

## Configuración Inicial del proyecto

1. Clonar [este repositorio](https://github.com/midudev/curso-platzi-react-avanzado) que tiene todo el material inicial

2. Iniciar proyecto

       npm init -y

3. Instalar Webpack

        npm i webpack wepack-cli --save-dev.

4. Agregar archivo src/index.js con un log base

5. Agregar el webpack.config.js

6. Instalar html-webpack-pluging 

        npm i html-webpack-plugin --save-dev

6. Instalar webpack-dev-server

        npm i webpack-dev-server --save-dev

7. Añadir nuevo script para werpack serve en package.json

        "dev": "webpack serve"

8. Instalar React 

        npm i react react-dom

9. Instalar Babel
        npm i @babel/core @babel/preset-env babel-loader @babel/preset-react --save-dev

10. Instalar linter: standar

        npm i standard --save-dev