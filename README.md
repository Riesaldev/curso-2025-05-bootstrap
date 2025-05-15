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





## Flexbox y Grid

### Breakpoints

Aplican en diferentes clases de utilidad

* xs: 0,
* sm: 576px,
* md: 768px,
* lg: 992px,
* xl: 1200px,
* xxl: 1400px

### Flexbox


### Grid

#### Grid nativo de Bootstrap (12col)

* container
* row
* col

#### CSS Grid (desactivado por defecto)

## Componentes

### Componentes básicos

### Componentes de navegación

### Componentes de notificación y feedback

### Componentes de contenido dinámico

## Formularios