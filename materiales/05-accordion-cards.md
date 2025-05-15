---
title: 05. Acordeones y tarjetas
---

## Accordion en Bootstrap

El acordeón, o "[Accordion](https://getbootstrap.com/docs/5.3/components/accordion/)", en Bootstrap, es un componente que permite organizar y mostrar contenido de manera colapsable, lo que permite a los usuarios expandir o contraer secciones de contenido según sea necesario. Bootstrap proporciona clases predefinidas para implementar acordeones de manera sencilla y efectiva.

### Estructura Básica

La estructura básica de un acordeón en Bootstrap consiste en un conjunto de elementos de encabezado y contenido que están contenidos dentro de un contenedor principal:

```html
<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button
        class="accordion-button"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#collapseOne"
        aria-expanded="true"
        aria-controls="collapseOne"
      >
        Título de la Sección 1
      </button>
    </h2>
    <div
      id="collapseOne"
      class="accordion-collapse collapse show"
      aria-labelledby="headingOne"
      data-bs-parent="#accordionExample"
    >
      <div class="accordion-body">Contenido de la Sección 1</div>
    </div>
  </div>
  <!-- Más elementos de acordeón aquí -->
</div>
```

### Funcionamiento

- Cada elemento `.accordion-item` contiene un encabezado (`h2` en este caso) y un contenedor de contenido (`div` con la clase `.accordion-collapse`).
- El atributo `data-bs-toggle="collapse"` se utiliza para controlar el comportamiento de expansión y contracción del acordeón.
- El atributo `data-bs-target` especifica el destino del contenido que se debe mostrar o ocultar.
- La clase `.show` en el contenedor de contenido indica que el contenido está expandido inicialmente.


## Tarjetas en Bootstrap

Las tarjetas, o "[Cards](https://getbootstrap.com/docs/5.3/components/card/)", en Bootstrap, son componentes versátiles que permiten presentar contenido de manera visualmente atractiva y organizada. Las tarjetas se utilizan comúnmente para mostrar información de manera modular, como imágenes, texto y enlaces, y son fundamentales para diseñar interfaces de usuario modernas y receptivas.

### Estructura Básica

La estructura básica de una tarjeta en Bootstrap consiste en un contenedor principal con clases predefinidas para estilos y disposición:

```html
<div class="card" style="width: 18rem;">
  <img src="..." class="card-img-top" alt="..." />
  <div class="card-body">
    <h5 class="card-title">Título de la Tarjeta</h5>
    <p class="card-text">Descripción corta de la tarjeta.</p>
    <a href="#" class="btn btn-primary">Ir a algún lugar</a>
  </div>
</div>
```

### Componentes de Tarjeta

- **Imagen Superior:** Se puede incluir una imagen en la parte superior de la tarjeta utilizando la clase `.card-img-top`.
- **Cuerpo de Tarjeta:** El contenido principal de la tarjeta se coloca dentro del elemento `<div>` con la clase `.card-body`.
- **Título y Texto:** Se pueden incluir un título y un texto descriptivo dentro del cuerpo de la tarjeta utilizando las clases `.card-title` y `.card-text`, respectivamente.
- **Botones:** Se pueden agregar botones dentro del cuerpo de la tarjeta utilizando la clase `.btn` junto con otras clases de color de Bootstrap, como `.btn-primary`.

### Estilos y Variaciones

Bootstrap proporciona una variedad de clases y opciones para personalizar el aspecto y la funcionalidad de las tarjetas:

- **Tarjetas con Encabezado y Pie de Página:** Se pueden agregar encabezados (`card-header`) y pies de página (`card-footer`) a las tarjetas para incluir información adicional.
- **Tarjetas de Grupo:** Se pueden agrupar tarjetas horizontalmente o en una cuadrícula utilizando contenedores flexibles o cuadrículas de Bootstrap.
- **Tarjetas con Overlay:** Se pueden crear tarjetas con superposición de texto o imágenes utilizando clases de superposición de Bootstrap, como `.card-img-overlay`.
