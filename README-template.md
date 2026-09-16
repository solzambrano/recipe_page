Proyecto Web

Página web desarrollada utilizando HTML5 y CSS3 puro, sin frameworks ni librerías externas.

El diseño está realizado siguiendo el enfoque Mobile First, comenzando por los estilos para dispositivos móviles y utilizando Media Queries para adaptar la interfaz a resoluciones de escritorio.

Tecnologías utilizadas

HTML5

CSS3

Media Queries

@font-face

Visual Studio Code

Live Server

Características

Diseño Responsive.

Metodología Mobile First.

Adaptación para dispositivos de escritorio mediante @media.

Tipografía personalizada utilizando @font-face.

HTML y CSS sin frameworks.

Estructura sencilla y fácil de mantener.

Estructura del proyecto
/
├── index.html
├── css/
│ └── styles.css
├── fonts/
│ └── ...
└── README.md

La estructura de carpetas puede variar según la organización del proyecto.

Diseño Responsive

El proyecto utiliza el enfoque Mobile First. Los estilos base están pensados para dispositivos móviles y, a medida que aumenta el ancho de pantalla, se aplican cambios mediante Media Queries.

Ejemplo:

/_ Estilos base - Mobile _/
.elemento {
width: 100%;
}

/_ Estilos para escritorio _/
@media (min-width: 768px) {
.elemento {
width: 50%;
}
}

Tipografía

La fuente utilizada pertenece al propio proyecto y se carga mediante @font-face.

@font-face {
font-family: "NombreFuente";
src: url("../fonts/fuente.woff2") format("woff2");
}

Esto permite utilizar la tipografía sin depender de servicios externos.

Cómo ejecutar el proyecto

El proyecto puede ejecutarse utilizando la extensión Live Server de Visual Studio Code.

Abrir el proyecto en Visual Studio Code.

Instalar la extensión Live Server si todavía no está instalada.

Abrir el archivo index.html.

Hacer clic derecho sobre el archivo.

Seleccionar "Open with Live Server".

El proyecto se abrirá automáticamente en el navegador.

También es posible utilizar el botón Go Live que proporciona Live Server en Visual Studio Code.

Objetivo

El objetivo del proyecto es implementar una página web sencilla utilizando únicamente HTML y CSS, aplicando buenas prácticas de estructura, estilos responsive y una metodología Mobile First.

# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.
