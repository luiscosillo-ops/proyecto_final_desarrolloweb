# Proyecto Final: Réplica Visual de Apple

## 1. Descripción del Proyecto
Este proyecto es una réplica visual estática de la página de inicio de Apple (América Latina), construido desde cero utilizando exclusivamente HTML5 y CSS3, como parte del proyecto final del curso de Desarrollo Web.

## 2. Secciones Replicadas
- Barra de navegación superior oscura.
- Hero principal oscuro (Sección WWDC).
- Secciones destacadas (iPhone y MacBook Air).
- Cuadrícula de productos (Grid de 2 columnas).
- Banner promocional estático (Apple TV).
- Notas legales e información secundaria.
- Footer con columnas distribuidas.

## 3. Conceptos HTML Utilizados
Se implementó HTML semántico utilizando etiquetas como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, y `<footer>` para estructurar correctamente el contenido.

## 4. Conceptos CSS Utilizados
Se utilizó el Box Model (margin, padding, box-sizing), selectores de clase, pseudoclases como `:hover` en botones y enlaces, y posicionamiento relativo (`position: relative`).

## 5. Aplicación de Flexbox
Se utilizó Flexbox (`display: flex`) principalmente en la barra de navegación para alinear los enlaces horizontalmente, en los grupos de botones (`.button-group`) y en la distribución general de las columnas del footer.

## 6. Aplicación de CSS Grid
Se aplicó CSS Grid (`display: grid`) en la sección de la cuadrícula de productos (`.product-grid`), configurando 2 columnas simétricas (`grid-template-columns: repeat(2, 1fr)`) para pantallas de escritorio.

## 7. Diseño Responsivo
Se utilizaron Media Queries (`@media (max-width: 768px)`) para garantizar que la página sea adaptable. El cambio más importante ocurre en la cuadrícula de productos, que pasa de dos columnas a una sola columna en pantallas de dispositivos móviles.

## 8. Dificultades Encontradas
La parte mas complicada fue poderlo hacer en la situacion que estaba, se que no es nada con fin tecnico, pero me toco hacerlo en medio del fallecimiento de mi padre. Fue mas esfuerxo emocional que creativo.
