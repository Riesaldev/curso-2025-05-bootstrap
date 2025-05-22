# Bootstrap CSS

Año lanzamiento Bootstrap CSS: 2011

Año lanzamiento Tailwind CSS: 2017

Versión Bootstrap: 5.3.6

Repo: https://github.com/twbs/bootstrap


## Instalación:

https://getbootstrap.com/docs/5.3/getting-started/introduction/

Se importa mediante 2 links: CSS y JavaScript.

El JavaScript es para los componentes interactivos: dropdown, modal, accordion, popovers...

* https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css
* https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/js/bootstrap.bundle.min.js


# Esquema de aprendizaje:

## Utilidades básicas

Bootstrap CSS aplica ciertos estilos ya por defecto sin que los especifiquemos nosotros:

https://getbootstrap.com/docs/5.3/content/reboot/

### Tipografía y textos

* h1, h2, h3, h4, h5, h6
* display-1, display-2, display-3, display-4, display-5, display-6
* lead

* text-center, text-end, text-start
* text-sm-end, text-md-end, text-lg-end, text-xl-end, text-xxl-end

* fs-1, fs-2, fs-3, fs-4, fs-5, fs-6

* text-lowercase, text-uppercase, text-capitalize

* fst-normal, fst-italic

* fw-lighter, fw-light, fw-normal, fw-medium, fw-semibold, fw-bolder, fw-bold

* lh-1, lh-sm, lh-base, lh-lg

* font-monospace

* text-decoration-none, text-decoration-underline, text-decoration-line-through

* text-primary, text-secondary, text-success, text-danger, text-warning, text-info, text-light, text-dark

* text-wrap, text-nowrap

* overflow-auto, overflow-hidden, overflow-visible, overflow-scroll
* overflow-x-auto, overflow-x-hidden, overflow-x-visible, overflow-x-scroll
* overflow-y-auto, overflow-y-hidden, overflow-y-visible, overflow-y-scroll

* text-truncate


### Links

Desde 5.3:

https://getbootstrap.com/docs/5.3/utilities/link/

* link-primary, link-secondary, link-success, link-danger, link-warning, link-info, link-light, link-dark

* stretched-link (hace clicable todo el contenedor que envuelve un link)


### Colores

* Nomenclatura: primary, secondary, success, danger, warning, info, light, dark

* text-primary, text-secondary, text-success, text-danger, text-warning, text-info, text-light, text-dark

* bg-primary, bg-secondary, bg-success, bg-danger, bg-warning, bg-info, bg-light, bg-dark

* border-primary, border-secondary, border-success, border-danger, border-warning, border-info, border-light, border-dark

* btn-primary, btn-secondary, btn-success, btn-danger, btn-warning, btn-info, btn-light, btn-dark

* text-opacity-75, text-opacity-50, text-opacity-25

* text-body

* text-black, text-white, text-black-50, text-white-50

Lo nuevo en boostrap 5.3:

* text-{color}-emphasis para dar mejor contraste en modo claro y oscuro
* bg-{color}-subtle y border-{color}-subtle para hacer más sutil el uso de fondos y bordes
* text-body-secondary, text-body-tertiary
* Se ha quitado text-muted

### Fondo (Background)

El sufijo subtle es nuevo en 5.3 de bootstrap, sirve para quitarle importancia a fondos y bordes para que no resalten tanto, por eso lo de subtle (sutil).

* bg-primary, bg-primary-subtle
* bg-secondary, bg-secondary-subtle
* bg-success, bg-success-subtle
* bg-danger, bg-danger-subtle
* bg-warning, bg-warning-subtle
* bg-info, bg-info-subtle
* bg-light, bg-light-subtle
* bg-dark, bg-dark-subtle
* bg-body-secondary, bg-body-tertiary
* bg-black, bg-white
* bg-transparent

* bg-primary bg-gradient
* bg-secondary bg-gradient
* bg-success bg-gradient
* bg-danger bg-gradient
* bg-warning bg-gradient
* bg-info bg-gradient
* bg-light bg-gradient
* bg-dark bg-gradient
* bg-black bg-gradient

* bg-success bg-opacity-75
* bg-success bg-opacity-50
* bg-success bg-opacity-25



### Bordes

* border
* border-top
* border-end
* border-bottom
* border-start

* border border-1
* border border-2
* border border-3
* border border-4
* border border-5

* border border-primary
* border border-primary-subtle
* border border-secondary
* border border-secondary-subtle
* border border-success
* border border-success-subtle
* border border-secondary-subtle
* border border-danger
* border border-danger-subtle
* border border-warning
* border border-warning-subtle
* border border-info
* border border-info-subtle
* border border-light
* border border-light-subtle
* border border-dark
* border border-dark-subtle
* border border-black
* border border-white

* border border-0
* border border-top-0
* border border-end-0
* border border-bottom-0
* border border-start-0

* border-opacity-75
* border-opacity-50
* border-opacity-25
* border-opacity-10

* rounded
* rounded-top
* rounded-end
* rounded-bottom
* rounded-bottom-1
* rounded-start
* rounded-start-2
* rounded-0
* rounded-1
* rounded-2
* rounded-3
* rounded-4
* rounded-5
* rounded-circle
* rounded-end-circle
* rounded-pill
* rounded-start-pill


### Sombras

* shadow-none
* shadow-sm
* shadow
* shadow-lg


### Tamaño (width y height)


* w-25
* w-50
* w-75
* w-100
* w-auto
* mw-100
* min-vw-100
* vw-100

* h-25
* h-50
* h-75
* h-100
* h-auto
* mh-100
* min-vh-100
* vh-100

### Espaciado (padding y margin)

* {property}{sides}-{size}

donde: 

* property: m, p
* sides: t, b, s, e, x, y
* size: 0, 1, 2, 3, 4, 5, auto

* mt-2
* mb-2

### Visibilidad

* visible
* invisible
* visually-hidden (oculta elementos pero los deja accesibles para tecnologías asistivas como screen readers)


## Flexbox y Grid

### Breakpoints

Aplican en diferentes clases de utilidad

* xs: 0,
* sm: 576px,
* md: 768px,
* lg: 992px,
* xl: 1200px,
* xxl: 1400px

Diferencia con Tailwind CSS:

* sm
* md
* lg
* xl
* 2xl


### Flexbox

Permite anilear elementos en un mismo eje sin entrar a trabajar con filas y columnas bidimensionales, es decir trabajamos en una dimensión.

d viene de display

* d-flex
* d-inline-flex


Diferencia con Tailwind:
* Tailwind CSS: flex
* Bootstrap CSS: d-flex

* d-{breakpoint}-flex
* d-{breakpoint}-inline-flex

* d-flex flex-row
* d-flex flex-row-reverse
* d-flex flex-column
* d-flex flex-column-reverse

Diferencia con Tailwind CSS:

* Tailwind CSS: flex-row, flex-col
* Bootstrap CSS: flex-row, flex-column

* d-flex justify-content-start
* d-flex justify-content-end
* d-flex justify-content-center
* d-flex justify-content-between
* d-flex justify-content-around
* d-flex justify-content-evenly

* d-flex align-items-start
* d-flex align-items-end
* d-flex align-items-center
* d-flex align-items-baseline
* d-flex align-items-stretch

* align-self-start
* align-self-end
* align-self-center
* align-self-baseline
* align-self-stretch

* flex-fill

* flex-grow-1
* flex-shrink-1

* Stacks: son shorthand helpers que usan flexbox por debajo y ayudan a estructurar layouts rápidamente.
    * vstack
    * hstack

```html
<div class="vstack gap-2 col-md-5 mx-auto">
  <button type="button" class="btn btn-secondary">Save changes</button>
  <button type="button" class="btn btn-outline-secondary">Cancel</button>
</div>
```

### Grid

#### Grid nativo de Bootstrap (12col)

* container (es el que se usa normalmente)
* container-sm
* container-md
* container-lg
* container-xl
* container-xxl
* container-fluid

Dentro de un container:

* row
* col

```html
<div class="container">
    <div class="row">
        <div class="col">
                Contenido en columna 1
        </div>
        <div class="col">
                Contenido en columna 2
        </div>
    </div>
</div>
```

Por defecto bootstrap considera el grid con 12 columnas virtuales.

Si no indicamos un ancho, se toma automáticamente de forma equitativa, por ejemplo estas dos columnas ocupan 6 cada una:

```html
<div class="container">
    <div class="row">
        <div class="col"></div>
        <div class="col"></div>
    </div>
</div>
```

Ocuparían ancho 4 cada una:

```html
<div class="container">
    <div class="row">
        <div class="col"></div>
        <div class="col"></div>
        <div class="col"></div>
    </div>
</div>
```

Teniendo en cuenta los breakpoints para responsive:

* Bootstrap: col-{breakpoint}-{1/12}
* Tailwind: grid grid-cols-1 md:grid-cols-3

Ejemplo tailwind: 

```html
<div class="grid grid-cols-4 gap-4">
  <div>01</div>
  <!-- ... -->
  <div>09</div>
</div>
```

Opción similar a tailwind pero con el grid nativo de bootstrap:

```html
<div class="container text-center">
  <div class="row row-cols-1 row-cols-md-3">
    <div class="col">Column</div>
    <div class="col">Column</div>
    <div class="col">Column</div>
    <div class="col">Column</div>
  </div>
</div>
```
Idóneo para cuando estamos agregando divs desde un bucle for y no queremos preocuparnos de cuando abrir y cerrar rows y de diferenciar cada item columna con una clase columna diferente.

Esto se usa habitualmente para crear:

* dashboard de administración
* página de inicio que muestra diferentes progresos
* grid de productos, ecommerce
* grid de features, beneficios, ventajas
* sección de equipo
* footer
* menú de una navbar (Flyout Menus en tailwind)

Este grid es nativo de bootstrap y se creó antes de que se integrara CSS Grid.

#### CSS Grid (desactivado por defecto)

Desde v5.1 de Bootstrap, desactivado por defecto.

https://getbootstrap.com/docs/5.3/layout/css-grid/

```html
<div class="grid text-center">
  <div class="g-col-6">.g-col-6</div>
  <div class="g-col-6">.g-col-6</div>
</div>
```

Más similar a tailwind, pero con la filosofía de bootstrap.


## Componentes

### Componentes básicos

* Button: botones para desencadenar acciones o enviar formulario o navegar entre páginas.

* Button Group: agrupar acciones relacionadas en una sola línea, útil para agrupar acciones masivas.

* Badge: mostrar contadores, estados.

* Tables: mostrar datos tabulares especialmente para la parte de administración, se suelen combinar con botones, 

* Cards: contenedores flexibles para items, card de producto,

* Images: img-fluid

* Listas: List Groups, list-unstyled, list-inline, contenido relacionado o items de una lista de datos que viene de backend

### Componentes de navegación

* Navs & tabs: menús de navegación horizontal o vertical, pestañas que se seleccionan y cambian un contenido
* Navbar: barra de navegación responsive y con menú hamburguesa, distintos colores
* Dropdowns: menús desplegables para agrupar opciones
* Breadcrumb: facilitar la navegación entre mucho contenido agrupado por categorías
* Pagination: botones para pasar de una página a otra, el contenido vendría paginado desde backend (LIMIT, OFFSET, TOP)
* Scrollspy: actualiza menús en base a la posición del scroll

CONSEJO: 

Si queremos posicionar urls se recomienda que tengan slugs claros:


Básico:

* localhost:8080/tutoriales/4
* localhost:8080/tutoriales/33efee79-6a0f-4e5d-be35-c1be3a656477

SEO friendly:

* empresa.com/tutorial-java-oop-polimorfismo-y-herencia
* empresa.com/java/tutorial/oop-polimorfismo-y-herencia

### Componentes de notificación y feedback

* Alerts: mostrar mensajes informativos usando código de color verde éxito, amarillo warning, rojo peligro.

* Toasts: mensajes emergentes temporales no interrumpen la experiencia.

* Close button: botón de cierre con una cruz

* Spinners: indica progreso de carga o acción, con una animación

* Progress: barra de progreso con porcentaje, stripped, animada

* Placeholders: también conocidos como skeleton, representación visual del contenido mientras se termina de cargar.

* Tooltips: información adicional cuando se hace hover sobre un elemento.

* Popovers: es como el tooltip pero más grande y con más contenido, para información contextual más amplia.

* Modal: Crear ventanas que permitan al usuario ver contenido e interactual, por ejemplo login, ofertas, cuando quieres borrar un item o hacer una acción que modifica algo mostramos un modal de confirmación.

### Componentes de contenido dinámico

* Collapse: mostrar y ocultar contenido de forma expandible, FAQs preguntas y respuestas.

* Accordion: paneles colapsables agrupados donde puede estar abierto uno o varios a la vez.

* Offcanvas:  panel lateral oculto se revela al ejecutar una acción o clic para mostrar información adicional.

* Carousel: contenido deslizable como imágenes. CUIDADO: si las imágenes tienen distinta resolución de alto, producirá layout shift moviendo contenido, lo cuál puede quedar mal.


## Modo oscuro

Desde la versión v5.3.

En Bootstrap 5.3, el dark mode se implementa utilizando el atributo ``data-bs-theme`` que puede aplicarse al elemento ``<html>`` para un cambio global, o a componentes específicos para cambios localizados. Por ejemplo:

``<html lang="en" data-bs-theme="dark">``

Bootstrap automáticamente aplica los estilos oscuros a todos los componentes dentro de ese contenedor sin necesidad de añadir clases adicionales ni prefijos ``dark:`` como en tailwind.

También es posible crear temas personalizados por ejemplo para B2B: 

https://getbootstrap.com/docs/5.3/customize/color-modes/#adding-theme-colors


## Formularios



## Boostrap icons

Similar Font Awesome.

## Grid de productos

## Dashboard


## Personalización


## Integración con frameworks:

* Angular: se suele usar NgBootstrap en forma de componentes de Angular.
    * NgBootstrap: usa Bootstrap CSS https://ng-bootstrap.github.io/
    * PrimeNG: que está basado en Tailwind CSS
    * Angular Material: que está basado en Material Design
