# Practica05 - Sass

## Instalación de Sass con Bootstrap 5

- requisitos Node.js
- extensiones de Visual Studio Code : Open Live Server y Live Sass Compiler

- en el area de trabajo abrimos el terminal :

  ##### - npm init -y

  ##### - npm install bootstrap@5.3.1

- Añadimos la carpeta js de /node_modules/boostrap/dist/js
  (solo nos interesan los archivo bootstrap.min.js y bootstrap.min.map)
- Creamos el archivo .gitignore para que no se incluyan ciertos archivos y carpetas : /node_modules , /sass y .gitignore
  -.,,

-SAAS . Creamos la carpeta saas. En el interior creamos el archivo custom.scss
ver : https://getbootstrap.com/docs/5.3/customize/sass/
añadimos: @import "../node_modules/bootstrap/scss/bootstrap";

- una vez guardado el archivo compilamos Watch Saas , es la extension Live Saas Compiler de Visual Studio per obtener el archivo custom.css
- para que se haya efectivo añadiremos en dentro del <head> del archivo index.html <link rel="stylesheet" href="css/custom.css"> para vincularlo
-

- TIPOGRAFIA - añadimos una fuente de Google Fonts (https://fonts.google.com/ ) - copiaremos el codigo con @import en el archivo custom.scss
- revisar el archivo \_variables.scsss localizado en /node_modules/bootstrap/scss/\_variables.scss
