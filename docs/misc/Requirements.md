## ✅ Requisitos Obligatorios

### 1. Estructura HTML (html-structure.html)
#### [x] 1. DOCTYPE y Estructura Base
- [x] Declaración `<!DOCTYPE html>` correcta
- [x] Etiqueta `<html>` con atributo `lang="es"`
- [x] Sección `<head>` completa con:
  - Meta charset UTF-8
  - Meta viewport para diseño responsivo
  - Título descriptivo de la página
  - Enlace a hoja de estilos CSS externa
  - (Opcional) Favicon
- [x] Estructura de `<body>` bien organizada

### [x] 2. HTML Semántico (semantic-html.html)
El sitio debe utilizar las siguientes etiquetas semánticas:
- [x] `<header>` - Cabecera principal con navegación
- [x] `<nav>` - Menú de navegación con enlaces a secciones
- [x] `<main>` - Contenido principal del sitio
- [x] `<section>` - Mínimo 4 secciones diferentes:
  - Sección "Hero" o presentación
  - Sección "Sobre mí"
  - Sección "Habilidades"
  - Sección "Proyectos"
  - Sección "Contacto"
- [x] `<article>` - Para cada proyecto individual
- [x] `<aside>` - Información complementaria (opcional)
- [x] `<footer>` - Pie de página con información de copyright y redes sociales
- [x] `<figure>` y `<figcaption>` - Para imágenes con descripciones

### [x] 3. Selectores CSS (css-selectors.html)
Debe demostrar el uso de diversos selectores, utilizar al menos 2 que no sean tipo, clase o ID:
- [x] **Selectores de tipo**: `h1`, `p`, `section`
- [x] **Selectores de clase**: `.card`, `.button`, `.container`
- [x] **Selectores de ID**: `#hero`, `#about`, `#contact`
- [x] **Selectores descendientes**: `nav a`, `.card p`
- [x] **Selectores de hijo directo**: `nav > ul > li`
- [x] **Selectores de hermano adyacente**: `h2 + p`
- [x] **Selectores de atributo**: `a[href^="https"]`, `input[type="email"]`
- [x] **Pseudo-clases**: `:hover`, `:focus`, `:nth-child()`, `:first-child`, `:last-child`
- [x] **Pseudo-elementos**: `::before`, `::after`, `::first-line`

iconos en SVG
### [x] 4. Propiedades CSS (css-properties.html)
Aplicar una variedad de propiedades CSS:

#### [X] Tipografía
- [x] `font-family` con fallback fonts
- [x] `font-size`, `font-weight`, `font-style`
- [x] `line-height` para mejorar legibilidad
- [x] `text-align`, `text-decoration`, `text-transform`
- [x] `letter-spacing` o `word-spacing`

#### [X] Colores y Fondos
- [x] `color` en diferentes formatos (hex, rgb, rgba)
- [x] `background-color`
- [x] `background-image` con gradientes
- [x] `background-size`, `background-position`

#### [x] Box model
- [x] `margin` y `padding` (con diferentes unidades)
- [x] `border` con estilos variados
- [x] `border-radius` para esquinas redondeadas
- [x] `box-shadow` para sombras
- [x] `width`, `height`, `max-width`, `min-height`

#### [ ] Efectos Visuales
- [x] `opacity` o `rgba` para transparencias
- [x] `transform` (scale, rotate, translate)
- [x] `transition` para animaciones suaves
- [ ] Opcional: `animation` con `@keyframes`

### [ ] 5. Unidades de Medida (measurements.html)
Utilizar diferentes unidades de medida apropiadamente:
- [x] **Unidades absolutas**: `px` para bordes y detalles precisos
- [x] **Unidades relativas**:
  - [x] `em` o `rem` para tipografía
  - [x] `%` para anchos y layouts
  - [x] `vh` y `vw` para secciones de altura completa
- [x] **Calculaciones**: `calc()` para dimensiones dinámicas
- [ ] Justificar el uso de cada unidad según el contexto

### [x] 6. Flexbox (flexbox.html)
Implementar Flexbox en múltiples secciones:
- [x] **Navegación horizontal** con Flexbox
  - `display: flex`
  - `justify-content` y `align-items`
  - Espaciado entre elementos

- [x] **Galería de proyectos** con tarjetas flexibles
  - Contenedor flex con `flex-wrap: wrap`
  - Tarjetas con `flex: 1` o proporciones específicas
  - `gap` para espaciado entre elementos

- [x] **Sección de habilidades** con iconos/badges
  - Distribución uniforme con `justify-content: space-around`
  - Alineación vertical y horizontal

- [x] **Footer** con layout flex
  - Múltiples columnas usando flex
  - Alineación de contenido

#### [x] Propiedades Flexbox Requeridas:
- [x] `display: flex`
- [x] `flex-direction` (row, column)
- [x] `justify-content` (diferentes valores)
- [x] `align-items` (diferentes valores)
- [x] `flex-wrap`
- [x] `gap` o `margin` para espaciado
- [x] `flex` en elementos hijos (flex-grow, flex-shrink, flex-basis)

### [x] 7. Z-Index y Contexto de Apilamiento (z-index.html)
Demostrar comprensión del contexto de apilamiento:
- [x] **Navegación fija** con z-index alto
  - `position: fixed` o `sticky`
  - `z-index` para mantenerla sobre el contenido

- [x] **Efectos de hover con elevación**
  - Tarjetas que se elevan al hacer hover
  - Uso de `box-shadow` y `transform`
  - Z-index para controlar superposición
- [x] **Elementos decorativos**
  - Elementos con `::before` o `::after`
  - Posicionamiento y z-index controlado

### [ ] 8. Diseño Responsivo (responsive-web.html)
Crear un diseño completamente adaptable:
#### [x] Media Queries
- [x] **Mobile First**: Estilos base para móviles
- [x] **Tablet** (min-width: 768px):
  - Ajustar navegación
  - Cambiar layout de 1 columna a 2 columnas
  - Aumentar tamaños de fuente
- [x] **Desktop** (min-width: 1024px):
  - Layout de 3 columnas para galería
  - Navegación expandida
  - Espaciado mejorado
- [x] **Desktop grande** (min-width: 1440px):
  - Max-width para contenedor principal
  - Ajustes de tipografía

#### [x] Técnicas Responsivas
- [x] Imágenes responsivas con `max-width: 100%`
- [x] Unidades relativas (rem, em, %) en lugar de px fijos
- [x] Flexbox con `flex-wrap` para adaptabilidad
- [x] Mostrar un menú diferente en móvil

#### [x] Breakpoints Mínimos Requeridos:
```css
/* Mobile: 320px - 767px (estilos por defecto) */
/* Tablet */
@media (min-width: 768px) {
  /* Estilos para tablet */
}

/* Desktop */
@media (min-width: 1024px) {
  /* Estilos para desktop */
}
/* Desktop Grande */
@media (min-width: 1440px) {
  /* Estilos para pantallas grandes */
}

```
## ✅ Checklist Final Antes de Entregar
- [x] HTML validado sin errores
- [x] CSS validado sin errores
- [X] Probado en Chrome, Firefox, y Safari
- [X] Responsivo en móvil, tablet y desktop
- [X] Todas las imágenes tienen atributo alt
- [X] Navegación funciona correctamente
- [X] Enlaces se abren apropiadamente (externos en nueva pestaña)
- [X] Formulario tiene validación básica
- [X] Código comentado donde es necesario
- [X] Sin errores en la consola del navegador
- [X] Archivos organizados correctamente
---