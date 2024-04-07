Angular 17 CRUD example with REST API

BezKoder 2/4/2024

https://www.bezkoder.com/angular-17-crud-example/

This is the Front End for tutorial_api (Ruby on Rails)

Angular 17.2

CSS

SSR - no

npm i bootstrap@5.3.3

ng g class models/tutorial

ng g c components/add-tutorial
ng g c components/tutorial-details
ng g c components/tutorials-list

ng g s services/tutorial

angular.json

"node_modules/bootstrap/dist/css/bootstrap.min.css",

"node_modules/jquery/dist/jquery.slim.min.js",
"node_modules/popper.js/dist/umd/popper.min.js",
"node_modules/bootstrap/dist/js/bootstrap.min.js"

app.config.ts

provideHttpClient()

app.routes.ts

lazy-load components

ng s -o to test if the app is running in browser

app.component.html



