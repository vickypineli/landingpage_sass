# Landing Page con Sass
![Descripción de la imagen](assets\img\Mockup.png)

Este repositorio contiene el código fuente de una landing page construida utilizando **HTML**, **CSS** y **Sass**. El proyecto está diseñado para ser limpio, responsive y fácil de mantener gracias al uso de Sass para gestionar estilos de manera eficiente.

## Tecnologías utilizadas

- **HTML5**: Estructura semántica del contenido.
- **CSS3**: Estilos y diseño responsive.
- **Sass**: Preprocesador CSS que facilita la modularización y la reutilización de estilos.

## Estructura del Proyecto

```plaintext
landingpage_sass/
├── index.html
├── css/
│   ├── main.css
    │──   main.css.map
├── scss/
│   ├── main.scss
└── assets/
    └── img/
        └── furniture
        └── products
    └── earth.png
    └── ecology.png
    └── facebook-logo.png
    └── gallery-1.png
    └── furniture-2.png
    └── furniture-3.png
    └── Mockup.png

Instrucciones para instalar y configurar Sass mediante Node.js
Abre una terminal y navega hasta la carpeta raíz de tu proyecto.
Asegúrate de tener Node.js instalado en tu sistema. Puedes verificarlo escribiendo node -v en la terminal. Si no lo tienes instalado, ve al sitio web oficial de Node.js para descargarlo e instalarlo.

Ejecuta el siguiente comando para instalar Sass a nivel global:
npm install -g sass
Ahora que tienes Sass instalado a nivel global, puedes compilar tus archivos Sass en CSS con el siguiente comando en la terminal:
sass input.scss output.css
Reemplaza “input.scss” con la ruta y el nombre de tu archivo Sass, y “output.css” con la ruta y el nombre de tu archivo CSS de salida. Por ejemplo:
sass styles/main.scss styles/main.css
Si quieres compilar automáticamente tus archivos Sass en CSS cada vez que hagas cambios, puedes usar la opción --watch:
sass --watch input.scss:output.css
Si estás utilizando Node.js en tu proyecto, también puedes usar un paquete de npm llamado sass para compilar tus archivos Sass en CSS. Para instalarlo, ejecuta el siguiente comando:
npm install sass
En tu archivo de configuración de Node.js (como package.json) agrega un script para compilar tus archivos Sass en CSS. Por ejemplo:
"scripts": {
  "build:css": "sass input.scss output.css"
}
Ahora puedes ejecutar el script con el siguiente comando:
npm run build:css
Eso es todo. Con estas instrucciones deberías poder instalar y configurar Sass en tu proyecto de Node.js.