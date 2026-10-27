<div align="center">
  <img src="img/logo/logo.png" width="280">
  <h1>EcoMarket - Yurly Gonzalez</h1>
</div>


# 🌿 EcoMarket — Tienda de Productos Ecológicos

## 1. Descripción del proyecto

EcoMarket es una tienda virtual desarrollada con HTML5 y CSS3 para presentar productos ecológicos, reutilizables y sustentables.

El proyecto busca promover el consumo consciente mediante una interfaz clara, organizada y adaptable a diferentes dispositivos. Los usuarios pueden explorar el catálogo, conocer la historia de la tienda y consultar los medios de contacto.

## 2. Objetivos

- Promover el uso de productos reutilizables y ecológicos.
- Presentar un catálogo organizado de productos.
- Ofrecer una experiencia de navegación sencilla y agradable.
- Implementar un diseño responsive para computadores, tabletas y celulares.
- Aplicar los conocimientos de HTML5, CSS3 y control de versiones con Git y GitHub.

## 3. Identidad visual

La identidad visual de EcoMarket utiliza colores asociados con la naturaleza, la sostenibilidad y la limpieza visual.

| Elemento | Color |
|---|---|
| Verde principal | `#22c55e` |
| Verde oscuro | `#15803d` |
| Verde profundo | `#052e16` |
| Verde claro | `#bbf7d0` |
| Fondo principal | `#ffffff` |
| Fondo suave | `#f0fdf4` |

**Tipografías:** Arial para los textos generales y Georgia para los títulos, utilizando fuentes disponibles en el sistema, sin depender de servicios externos.

**Estilo:** diseño limpio, espacios organizados, tarjetas de productos, navegación sencilla y colores inspirados en la naturaleza.

## Tecnologías utilizadas

- **HTML5:** estructura semántica y organización del contenido de las páginas.
- **CSS3:** diseño visual, estilos, animaciones y efectos interactivos.
- **Flexbox y CSS Grid:** distribución y organización de los elementos.
- **Media Queries:** adaptación del diseño a dispositivos móviles, tabletas y computadores.
- **Selectores y pseudoclases CSS:** efectos `:hover`, validación de formularios y controles visuales.
- **Animaciones CSS:** transiciones, efectos visuales y movimiento de la marquesina.
- **Tipografías del sistema:** Arial para los textos generales y Georgia para los títulos, sin cargar fuentes externas.
- **Git y GitHub:** control de versiones, administración de ramas y alojamiento del repositorio.

**Restricciones técnicas:** el proyecto se desarrolla exclusivamente con HTML5 y CSS3, sin JavaScript, frameworks, `@import` ni dependencias externas para el diseño.

## 5. Estructura del proyecto

```text
EcoMarket_YurlyGonzalez/
│
├── index.html
├── README.md
│
├── css/
│   ├── main.css
│   ├── layout.css
│   ├── components.css
│   └── animations.css
│
├── views/
│   ├── productos.html
│   ├── sobre-nosotros.html
│   └── contacto.html
│
├── img/
│   ├── logo/
│   │   └── logo.png
│   │
│   ├── icons/
│   │   ├── logo-ecomarket.svg
│   │   ├── icono-busqueda.svg
│   │   ├── icono-carrito.svg
│   │   ├── icono-instagram.svg
│   │   └── icono-facebook.svg
│   │
│   ├── products/
│   ├── hero/
│   └── testimonials/
│
└── capturas/
```

## 6. Páginas del sitio web

### Inicio — `index.html`

Página principal que presenta la tienda, sus productos destacados y los accesos a las demás secciones.

**Captura de pantalla - Escritorio:**

![captura inicio](capturas/01-inicio-escritorio.png)

**Captura de pantalla - Movil:**

![captura inicio](capturas/05-inicio-movil.png)

### Productos — `views/productos.html`

Catálogo con 20 productos ecológicos, tarjetas de productos, precios, imágenes y controles visuales de filtrado.

**Captura de pantalla - Escritorio:**

![captura catalogo](capturas/02-catalogo-productos.png)

**Captura de pantalla - Movil:**

![captura catalogo](capturas/06-catalogo-productos-movil.png)

### Sobre nosotros — `views/sobre-nosotros.html`

Página informativa que presenta la historia, los valores y el propósito de EcoMarket.

**Captura de pantalla - Escritorio:**

<p align="center"><img src="capturas/03-sobre-nosotros.png" alt="nosotros" width="500"></p>

**Captura de pantalla - Movil:**

![captura nosotros](capturas/07-sobre-nosotros-movil.png)

### Contacto — `views/contacto.html`

Página con formulario de contacto, validaciones HTML/CSS, información de contacto y mapa integrado.

**Captura de pantalla - Escritorio:**

![captura contacto](capturas/04-contacto.png)

**Captura de pantalla - Movil:**

![captura contacto](capturas/08-contacto-movil.png)

## 7. Características principales

- Navegación entre las cuatro páginas del sitio.
- Encabezado fijo durante el desplazamiento.
- Catálogo de productos con tarjetas organizadas.
- Diseño adaptable a computadores, tabletas y celulares.
- Filtros visuales mediante controles CSS.
- Efectos visuales en las tarjetas y elementos interactivos.
- Validación visual de campos del formulario.
- Sección de testimonios con desplazamiento.
- Marquesina animada en la parte inferior.
- Preferencia de movimiento reducido mediante CSS.
- Integración de mapa en la página de contacto.
- Uso de imágenes e iconos organizados en carpetas.

## 8. Diseño responsive

El sitio utiliza CSS Grid, Flexbox y media queries para adaptar su distribución según el tamaño de la pantalla.

La cuadrícula del catálogo contempla:

- **Escritorio:** cuatro columnas.
- **Tableta:** dos columnas.
- **Celular:** una columna.

## 9. Interacciones y limitaciones

Las interacciones visuales se implementan exclusivamente con HTML y CSS.

- Los filtros utilizan controles de formulario y selectores CSS.
- Los corazones de favoritos utilizan estados visuales mediante pseudo-clases CSS.
- Los campos del formulario emplean validación HTML y estilos CSS.
- Los testimonios utilizan desplazamiento con `scroll-snap`.
- Las animaciones incluyen una alternativa para usuarios que prefieren movimiento reducido.

**Limitaciones:** al no utilizar JavaScript ni un backend, el proyecto no implementa procesamiento real de pedidos, almacenamiento permanente de favoritos, búsqueda dinámica, pagos ni envío de mensajes a un servidor. Los controles visuales no deben interpretarse como funciones de compra completas.

## 10. Organización del código CSS

Los estilos se distribuyen en cuatro archivos:

| Archivo | Función |
|---|---|
| `main.css` | Variables, colores, tipografías y estilos globales. |
| `layout.css` | Contenedores, encabezado, secciones y distribución responsive. |
| `components.css` | Navegación, tarjetas, formularios, filtros y otros componentes. |
| `animations.css` | Animaciones, transiciones y efectos visuales. |

Esta separación facilita el mantenimiento y la organización del código.

## 11. Instrucciones de visualización

1. Descarga o clona el repositorio de EcoMarket desde GitHub.
2. Abre la carpeta del proyecto en Visual Studio Code.
3. Verifica que las carpetas `css/`, `views/` e `img/` mantengan su estructura original.
4. Abre el archivo `index.html` en un navegador web para visualizar la página principal.
5. Utiliza el menú de navegación para acceder a las cuatro páginas del sitio:
   - **Inicio:** `index.html`
   - **Productos:** `views/productos.html`
   - **Sobre nosotros:** `views/sobre-nosotros.html`
   - **Contacto:** `views/contacto.html`
6. Cambia el tamaño de la ventana del navegador para comprobar la adaptación del diseño a computadores, tabletas y celulares.

El proyecto utiliza HTML5 y CSS3, por lo que no requiere instalar dependencias ni ejecutar un servidor para su visualización local.

## 12. Control de versiones y repositorio

El proyecto se gestiona mediante Git y GitHub, utilizando ramas para organizar el desarrollo de las diferentes secciones.

**Repositorio público:**



Ramas de trabajo utilizadas:

- `main`
- `develop`
- `feature/inicio`
- `feature/catalogo`
- `feature/nosotros`
- `feature/contactos`
- `feature/estilos`
- `feature/readme`

## 14. Publicación del proyecto

**Enlace del sitio publicado:**

https://ingyurlygonzalezdulcey-creator.github.io/EcoMarket_YurlyGonzalez/

## 15. Autoría

**Proyecto:** EcoMarket — Tienda de Productos Ecológicos.

**Repositorio:** EcoMarket_YurlyGonzalez.

**Propósito:** proyecto académico de desarrollo web enfocado en HTML5, CSS3, diseño responsive y control de versiones.




