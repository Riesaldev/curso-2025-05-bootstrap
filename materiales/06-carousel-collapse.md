---
title: 06. Carousel y Collapse
---

## Carrusel en Bootstrap

El carrusel, o "[Carousel](https://getbootstrap.com/docs/5.3/components/carousel/)", en Bootstrap, es un componente interactivo que permite a los usuarios desplazarse horizontalmente a través de una serie de elementos, como imágenes, texto o contenido multimedia. Es una herramienta útil para mostrar múltiples elementos de manera dinámica y atractiva en una página web.

## Estructura Básica

La estructura básica de un carrusel en Bootstrap consiste en un contenedor principal con elementos de diapositiva dentro:

```html
<div
  id="carouselExampleSlidesOnly"
  class="carousel slide"
  data-bs-ride="carousel"
>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="..." class="d-block w-100" alt="..." />
    </div>
    <div class="carousel-item">
      <img src="..." class="d-block w-100" alt="..." />
    </div>
    <!-- Más elementos de diapositiva aquí -->
  </div>
</div>
```

## Componentes del Carrusel

- **Contenedor Principal:** El contenedor principal del carrusel debe tener la clase `.carousel` y puede incluir atributos opcionales como `data-bs-ride="carousel"` para habilitar el desplazamiento automático.
- **Elementos de Diapositiva:** Cada elemento de diapositiva debe tener la clase `.carousel-item`. La primera diapositiva debe tener la clase adicional `.active` para indicar que es la diapositiva inicial.

## Controles y Navegación

Bootstrap proporciona controles y navegación prediseñados para permitir a los usuarios interactuar con el carrusel:

- **Controles de Flecha:** Se pueden agregar botones de flecha (`carousel-control-prev` y `carousel-control-next`) para permitir a los usuarios navegar hacia adelante o hacia atrás en el carrusel.
- **Controles de Indicadores:** Se pueden agregar indicadores (`carousel-indicators`) para mostrar visualmente la posición actual del usuario en el carrusel.



## Collapse en Bootstrap

El [_collapse_](https://getbootstrap.com/docs/5.3/components/collapse/), o "colapso", en Bootstrap, es un componente que permite ocultar y mostrar contenido de manera dinámica con un efecto de transición suave. Es útil para mostrar u ocultar secciones de contenido, como menús desplegables o detalles adicionales, de forma interactiva.

## Estructura Básica

La estructura básica de un _collapse_ en Bootstrap consiste en un controlador que activa el colapso y un área de contenido que se oculta o se muestra:

```html
<button
  class="btn btn-primary"
  type="button"
  data-bs-toggle="collapse"
  data-bs-target="#collapseExample"
  aria-expanded="false"
  aria-controls="collapseExample"
>
  Botón de Activación
</button>
<div class="collapse" id="collapseExample">
  <div class="card card-body">Contenido del Colapso</div>
</div>
```

## Componentes del _Collapse_

- **Controlador:** El controlador es un elemento HTML, como un botón, que activa el colapso. Debe tener los atributos `data-bs-toggle="collapse"` y `data-bs-target` para especificar qué área de contenido debe colapsar o expandir.
- **Área de Contenido:** El área de contenido es el elemento HTML que se oculta o se muestra cuando se activa el colapso. Debe tener la clase `.collapse` y un identificador único especificado en el atributo `id`.

## Opciones Adicionales

Bootstrap ofrece opciones adicionales para personalizar el comportamiento y la apariencia del _collapse_:

- **Transiciones:** Se pueden agregar clases de transición CSS para controlar la velocidad y el tipo de efecto de transición al expandir o contraer el _collapse_.
- **Evento JavaScript:** Se puede utilizar JavaScript para activar el colapso programáticamente en respuesta a eventos del usuario u otras acciones.
