# Fundamentación del Proyecto

## 1. Desarrollo del Sitio

El sitio fue desarrollado utilizando **HTML5** como lenguaje de marcado y **Tailwind CSS** como framework de estilos.  
Tailwind CSS fue elegido por su enfoque que permite crear diseños personalizados y responsivos rápidamente a través de clases predefinidas.
Esto facilitó mantener una apariencia consistente a lo largo del sitio sin necesidad de escribir CSS personalizado, acelerando el desarrollo y mejorando la mantenibilidad del código.

## 2. Criterios de Diseño

Se implementó un diseño minimalista con una paleta de colores sobria basada en tonos oscuros (`#1a1a1a`) para áreas prominentes como la navegación, y fondos claros para el contenido principal.  
Esta estructura respeta principios de la **Teoría de Gestalt** como:

- **Proximidad**: elementos relacionados están agrupados visualmente.
- **Continuidad**: el flujo visual guía naturalmente de un elemento a otro.
- **Cierre**: las tarjetas y secciones crean unidades completas y cerradas.
- **Figura-fondo**: contraste entre los elementos de primer plano y el fondo.

## 3. Buenas Prácticas

El sitio incorpora numerosas buenas prácticas, incluyendo:

- Uso semántico de etiquetas HTML5 (`<nav>`, `<main>`, `<footer>`, `<section>`).
- Separación clara entre estructura (HTML) y presentación (Tailwind CSS).
- Atributos `target="_blank"` para enlaces externos, mejorando la experiencia de usuario.
- Nomenclatura descriptiva y consistente en clases y elementos.
- Estructura jerárquica adecuada de encabezados (`h1-h5`) para mejorar accesibilidad y SEO.

## 4. Estrategias de Responsividad

La responsividad se logró principalmente a través de:

- Sistema grid responsive de Tailwind CSS con clases como `grid-cols-1` y `md:grid-cols-2`.
- Diseño **mobile-first**, donde los estilos base son para dispositivos móviles.
- Uso de breakpoints (`sm:`, `md:`) para adaptar el diseño a diferentes tamaños de pantalla.
- Elementos fluidos que se ajustan a su contenedor con clases como `container` y `max-w-4xl`.
- Navegación adaptativa que cambia de vertical a horizontal según el dispositivo.
