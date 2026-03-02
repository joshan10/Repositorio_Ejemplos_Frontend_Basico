# Repositorio de Ejemplos Frontend Basico

**Plan de Trabajo 3406211 — SENA 2026**

Coleccion de ejemplos practicos de construccion de sitios y aplicaciones web con HTML y CSS, organizados por clase y nivel de complejidad progresiva.

---

## Indice del proyecto

- [Descripcion general](#descripcion-general)
- [Estructura del repositorio](#estructura-del-repositorio)
- [Indice de ejemplos](#indice-de-ejemplos)
- [Como usar este repositorio](#como-usar-este-repositorio)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Progresion de aprendizaje](#progresion-de-aprendizaje)

---

## Descripcion general

Este repositorio contiene los ejemplos de codigo trabajados durante las clases del programa de formacion en Desarrollo de Aplicaciones Web del SENA 2026. Cada carpeta corresponde a una clase o sesion especifica y demuestra conceptos concretos de HTML y CSS aplicados en proyectos reales.

El repositorio cuenta con una **pagina indice** (`index.html`) con interfaz visual que permite navegar hacia cada uno de los ejemplos directamente desde el navegador.

---

## Estructura del repositorio

```
Repositorio_Ejemplos_Frontend_Basico/
│
├── index.html                  # Pagina indice principal con Material Design
├── README.md                   # Este archivo
│
├── css/
│   └── index-styles.css        # Estilos del indice principal
│
├── 2.Clase2/                   # Clase 2: Estructura HTML y Multimedia
│   ├── README.md
│   ├── index.html
│   ├── cancion.html
│   ├── pelicula.html
│   ├── docs/
│   ├── img/
│   └── media/
│
├── 3.Clase3/                   # Clase 3: Formularios HTML
│   ├── README.md
│   └── index.html
│
├── 4.Clase4/                   # Clase 4: Introduccion a CSS
│   ├── README.md
│   ├── index.html
│   ├── contacto.html
│   └── css/
│       └── styles.css
│
├── 5.Clase5/                   # Clase 5: Selectores CSS y Modelo de Caja
│   ├── README.md
│   ├── index.html
│   ├── css/
│   │   └── styles-app.css
│   └── img/
│
├── 6.Clase6/                   # Clase 6: Posicionamiento CSS
│   ├── README.md
│   ├── index.html
│   └── css/
│       └── styles.css
│
├── 7.Clase7_Flex/              # Clase 7A: Flexbox - Catalogo de Productos
│   ├── README.md
│   ├── index.html
│   ├── css/
│   │   └── styles.css
│   └── img/
│
├── 8.clase7_flex_b/            # Clase 7B: Flexbox - Barra de Navegacion
│   ├── README.md
│   ├── index.html
│   ├── css/
│   │   └── styles.css
│   └── img/
│
├── 9.clase7_flex_c/            # Clase 7C: Flexbox - Propiedades Avanzadas
│   ├── README.md
│   ├── index.html
│   └── css/
│       └── styles.css
│
├── 10.Clase8_Grid/             # Clase 8A: CSS Grid - Layout Avanzado
│   ├── README.md
│   ├── index.html
│   └── css/
│       └── styles.css
│
└── 10.Clase_8_flex/            # Clase 8B: Proyecto Tienda Online
    ├── README.md
    ├── index.html
    ├── css/
    │   └── styles.css
    └── img/
```

---

## Indice de ejemplos

### Nivel 1 — Estructura HTML y Contenido

#### Clase 2 — Estructura HTML y Multimedia
**Carpeta:** `2.Clase2/`

Sitio web multipagina con tres vistas: pagina principal, pagina de audio y pagina de video. Introduce la estructura semantica de HTML5 y elementos multimedia.

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Pagina principal con tabla de datos, inputs y navegacion |
| `cancion.html` | Reproductor de audio con elemento `<audio>` |
| `pelicula.html` | Reproductor de video con elemento `<video>` |

**Conceptos:** estructura semantica, `<table>`, `<audio>`, `<video>`, inputs, navegacion entre paginas

---

#### Clase 3 — Formularios HTML
**Carpeta:** `3.Clase3/`

Formulario de registro completo con todos los tipos de campos de entrada disponibles en HTML5.

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Formulario con select, text, email, radio, checkbox y submit |

**Conceptos:** `<form>`, `<select>`, `<input>` (todos los tipos), `<label>`, `required`, `placeholder`, validacion HTML5

---

### Nivel 2 — CSS: Fundamentos y Selectores

#### Clase 4 — Introduccion a CSS
**Carpeta:** `4.Clase4/`

Demostracion de las tres formas de aplicar CSS (externo, interno e inline) y como funciona la cascada cuando hay conflicto de estilos.

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Pagina con CSS externo aplicado |
| `contacto.html` | Misma pagina con CSS interno que sobrescribe el externo |
| `css/styles.css` | Hoja de estilos externa con selectores de elemento y clase |

**Conceptos:** CSS externo, CSS interno, selectores de elemento, selectores de clase, cascada, especificidad, `font-family`, `font-size`, `color`, `width`

---

#### Clase 5 — Selectores CSS y Modelo de Caja
**Carpeta:** `5.Clase5/`

Pagina de articulo de noticias que demuestra selectores avanzados y propiedades del modelo de caja.

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Articulo de noticias con imagen y parrafos |
| `css/styles-app.css` | Estilos con selector hijo directo y modelo de caja |

**Conceptos:** selector hijo directo (`>`), `padding`, `margin`, `width`, `border-left`, `box-shadow`, `border-radius`, `font-weight`, elemento `<span>`

---

#### Clase 6 — Posicionamiento CSS
**Carpeta:** `6.Clase6/`

Pagina con contenido largo que demuestra el efecto de `position: fixed` para un header que permanece visible durante el scroll.

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Pagina con header fijo y contenido largo |
| `css/styles.css` | Estilos de posicionamiento fijo y compensacion de contenido |

**Conceptos:** `position: fixed`, `width: 100%`, `z-index`, compensacion con `padding-top`, selector descendiente

---

### Nivel 3 — CSS Flexbox

#### Clase 7A — Flexbox: Catalogo de Productos
**Carpeta:** `7.Clase7_Flex/`

Catalogo de tarjetas de producto con layout responsive usando `flex-wrap`. Cada tarjeta es un contenedor flex vertical con badge de descuento posicionado absolutamente.

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Catalogo con 6 tarjetas de producto |
| `css/styles.css` | Flexbox con wrap, direction column y position absolute |

**Conceptos:** `display: flex`, `flex-wrap: wrap`, `flex-direction: column`, `justify-content`, `align-items`, `gap`, `position: absolute`, `transform: rotate()`

---

#### Clase 7B — Flexbox: Barra de Navegacion tipo LinkedIn
**Carpeta:** `8.clase7_flex_b/`

Replica del header de LinkedIn que demuestra Flexbox anidado: un contenedor principal que separa logo+busqueda del menu de navegacion.

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Header con logo, barra de busqueda y menu de iconos |
| `css/styles.css` | Flexbox anidado con unidades viewport |

**Conceptos:** Flexbox anidado, `justify-content: space-between`, `flex-direction: column` (iconos con texto), unidades `vh` y `vw`, `border-radius`, `outline: none`

---

#### Clase 7C — Flexbox: Propiedades Avanzadas
**Carpeta:** `9.clase7_flex_c/`

Ejemplo minimalista de 4 cajas que demuestra propiedades avanzadas de Flexbox: inversion del orden y alineacion individual de elementos.

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Cuatro cajas numeradas en un contenedor flex |
| `css/styles.css` | column-reverse y align-self con nth-child |

**Conceptos:** `flex-direction: column-reverse`, `align-self`, selector `:nth-child()`, alineacion individual vs alineacion del contenedor

---

### Nivel 4 — CSS Grid y Proyectos Completos

#### Clase 8A — CSS Grid: Layout Avanzado
**Carpeta:** `10.Clase8_Grid/`

Grid de 7 elementos con celdas de diferentes tamanos usando `span`. Combina Grid para el layout externo con Flexbox para el contenido interno. Incluye un efecto visual de rotacion.

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Grid con elementos que ocupan multiples celdas |
| `css/styles.css` | Grid template, span de filas/columnas y transform |

**Conceptos:** `display: grid`, `grid-template-columns`, `grid-template-rows`, `grid-row: span`, `grid-column: span`, `column-gap`, `row-gap`, `transform: rotate()`, Grid + Flexbox combinados

---

#### Clase 8B — Tienda Online con Flexbox
**Carpeta:** `10.Clase_8_flex/`

Proyecto completo de tienda de juguetes con header de navegacion y galeria de 20 productos. Demuestra la integracion de Google Fonts y un diseno de producto profesional.

| Archivo | Contenido |
|---------|-----------|
| `index.html` | Tienda con header y galeria de 20 productos |
| `css/styles.css` | Estilos completos con Google Fonts Inter |

**Conceptos:** Google Fonts (`preconnect`, `@import`), `flex-wrap: wrap` para galeria, elemento `<picture>`, unidades `vh`/`vw`, `text-transform: uppercase`, diseno de header con nav

---

## Como usar este repositorio

### Opcion 1 — Pagina indice (recomendado)
Abrir el archivo `index.html` en la raiz del proyecto con cualquier navegador moderno. Desde ahi se puede navegar a todos los ejemplos haciendo clic en "Ver ejemplo".

### Opcion 2 — Acceso directo
Navegar a la carpeta del ejemplo deseado y abrir su `index.html` directamente en el navegador.

### Opcion 3 — Servidor local
Si se tiene Node.js instalado:
```bash
npx serve .
```
O con Python:
```bash
python3 -m http.server 8080
```
Luego abrir `http://localhost:8080` en el navegador.

### Leer la documentacion
Cada carpeta tiene un archivo `README.md` con:
- Descripcion del ejemplo
- Explicacion de cada archivo HTML y CSS
- Fragmentos de codigo comentados
- Lista de conceptos aprendidos

---

## Tecnologias utilizadas

| Tecnologia | Uso |
|------------|-----|
| HTML5 | Estructura y semantica de todos los ejemplos |
| CSS3 | Estilos, layout y animaciones |
| CSS Flexbox | Layout unidimensional (Clases 7 y 8B) |
| CSS Grid | Layout bidimensional (Clase 8A) |
| Google Fonts | Tipografias externas (Inter, Google Sans) |
| Material Design | Guia visual del indice principal |

---

## Progresion de aprendizaje

```
Clase 2          Clase 3          Clase 4          Clase 5
HTML semantico   Formularios      CSS externo      Selectores
Multimedia       Inputs           CSS interno      Modelo de caja
Tablas           Validacion       Cascada          Box-shadow

      Clase 6          Clase 7A         Clase 7B         Clase 7C
      Position fixed   Flexbox basico   Flexbox anidado  Flex avanzado
      Scroll           flex-wrap        space-between    column-reverse
      z-index          Catalogos        Navegacion       align-self

                  Clase 8A              Clase 8B
                  CSS Grid              Proyecto completo
                  grid-template         Google Fonts
                  span filas/cols       Tienda online
```

---

*Repositorio creado para el programa de formacion Frontend Basico — SENA 2026*
