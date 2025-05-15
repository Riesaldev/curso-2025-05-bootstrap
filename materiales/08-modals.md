---
title: 08. Modales
---

## Modal en Bootstrap

Los [modales](https://getbootstrap.com/docs/5.3/components/modal/) en Bootstrap son componentes que se superponen sobre el contenido principal de una página para mostrar información adicional, solicitar confirmaciones del usuario o realizar interacciones específicas. Son útiles para mantener el enfoque del usuario en una tarea específica mientras se muestra contenido secundario de manera temporal.

## Estructura Básica

La estructura básica de un modal en Bootstrap consiste en un contenedor principal con encabezado, cuerpo y pie de modal:

```html
<div
  class="modal fade"
  id="exampleModal"
  tabindex="-1"
  aria-labelledby="exampleModalLabel"
  aria-hidden="true"
>
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Título del Modal</h5>
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="modal"
          aria-label="Close"
        ></button>
      </div>
      <div class="modal-body">Contenido del Modal</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">
          Cerrar
        </button>
        <button type="button" class="btn btn-primary">Guardar cambios</button>
      </div>
    </div>
  </div>
</div>
```

## Componentes del Modal

- **Encabezado:** El encabezado del modal contiene el título y, opcionalmente, un botón para cerrar el modal.
- **Cuerpo:** El cuerpo del modal contiene el contenido principal, como texto, formularios o componentes adicionales.
- **Pie de Modal:** El pie de modal contiene botones u acciones adicionales, como cerrar el modal o confirmar cambios.

## Modal con Fondo Estático en Bootstrap

Los modales con fondo estático en Bootstrap son una variante de los modales estándar que mantienen el fondo oscurecido y deshabilitado, lo que impide al usuario interactuar con el contenido detrás del modal mientras este está abierto. Son útiles cuando se desea enfocar la atención del usuario exclusivamente en el contenido del modal sin permitir interacciones con el resto de la página.

## Estructura Básica

La estructura básica de un modal con fondo estático en Bootstrap es similar a la de un modal estándar:

```html
<div
  class="modal"
  tabindex="-1"
  role="dialog"
  aria-labelledby="staticBackdropLabel"
  aria-hidden="true"
>
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="staticBackdropLabel">Título del Modal</h5>
        <button
          type="button"
          class="close"
          data-dismiss="modal"
          aria-label="Close"
        >
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">Contenido del Modal</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">
          Cerrar
        </button>
        <button type="button" class="btn btn-primary">Guardar cambios</button>
      </div>
    </div>
  </div>
</div>
```

## Características del Modal con Fondo Estático

- **Fondo Estático:** El fondo del modal permanece oscurecido y deshabilitado mientras el modal está abierto, lo que impide la interacción con el contenido detrás del modal.
- **Atención al Usuario:** Este tipo de modal se utiliza cuando se desea mantener la atención exclusivamente en el contenido del modal, sin distracciones o interacciones con el resto de la página.
- **Funcionalidad Similar:** En términos de estructura y funcionamiento, los modales con fondo estático son similares a los modales estándar de Bootstrap.

## Modal con Contenido Largo Desplazable en Bootstrap

Los modales con contenido largo desplazable en Bootstrap son útiles cuando se necesita mostrar una gran cantidad de contenido dentro de un modal y se desea que el usuario pueda desplazarse verticalmente a través de dicho contenido. Este tipo de modales facilita la presentación de información detallada sin sacrificar la experiencia del usuario.

## Estructura Básica

La estructura básica de un modal con contenido largo desplazable en Bootstrap es similar a la de un modal estándar:

```html
<div
  class="modal fade"
  id="exampleModalScrollable"
  tabindex="-1"
  aria-labelledby="exampleModalScrollableTitle"
  aria-hidden="true"
>
  <div class="modal-dialog modal-dialog-scrollable">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalScrollableTitle">
          Título del Modal
        </h5>
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="modal"
          aria-label="Close"
        ></button>
      </div>
      <div class="modal-body">Contenido largo del Modal aquí...</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">
          Cerrar
        </button>
        <button type="button" class="btn btn-primary">Guardar cambios</button>
      </div>
    </div>
  </div>
</div>
```

## Características del Modal con Contenido Largo Desplazable

- **Contenido Desplazable:** El contenido del modal puede extenderse más allá del área visible y el usuario puede desplazarse verticalmente para ver todo el contenido.
- **Optimización de Espacio:** Este tipo de modal es útil cuando se necesita mostrar una gran cantidad de información de manera compacta y sin ocupar demasiado espacio en la pantalla.
- **Funcionalidad Similar:** En términos de estructura y funcionamiento, los modales con contenido largo desplazable son similares a los modales estándar de Bootstrap.

## Modal Centrado Verticalmente en Bootstrap

Los modales centrados verticalmente en Bootstrap son una variante de los modales estándar que se muestran en el centro vertical de la ventana del navegador. Esto proporciona una apariencia más estética y centrada, lo que puede mejorar la experiencia del usuario al interactuar con el modal.

## Estructura Básica

La estructura básica de un modal centrado verticalmente en Bootstrap es similar a la de un modal estándar:

```html
<div
  class="modal fade"
  id="exampleModalCenter"
  tabindex="-1"
  role="dialog"
  aria-labelledby="exampleModalCenterTitle"
  aria-hidden="true"
>
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalCenterTitle">
          Título del Modal
        </h5>
        <button
          type="button"
          class="close"
          data-dismiss="modal"
          aria-label="Close"
        >
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">Contenido del Modal</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">
          Cerrar
        </button>
        <button type="button" class="btn btn-primary">Guardar cambios</button>
      </div>
    </div>
  </div>
</div>
```

## Características del Modal Centrado Verticalmente

- **Centrado Vertical:** El modal se muestra en el centro vertical de la ventana del navegador, lo que proporciona una apariencia más equilibrada y centrada.
- **Mejora Estética:** Este tipo de modal puede mejorar la apariencia estética de la interfaz de usuario al mantener el foco en el contenido centralizado.
- **Funcionalidad Similar:** En términos de estructura y funcionamiento, los modales centrados verticalmente son similares a los modales estándar de Bootstrap.

## Modal de Pantalla Completa en Bootstrap

Los modales de pantalla completa en Bootstrap son una variante de los modales estándar que ocupan toda la ventana del navegador, proporcionando una experiencia inmersiva para el usuario al enfocar su atención en el contenido del modal y ocultar el resto de la interfaz.

## Estructura Básica

La estructura básica de un modal de pantalla completa en Bootstrap es similar a la de un modal estándar, pero con una clase adicional para habilitar el modo de pantalla completa:

```html
<div
  class="modal fade"
  id="exampleModalFullscreen"
  tabindex="-1"
  aria-labelledby="exampleModalFullscreenLabel"
  aria-hidden="true"
>
  <div class="modal-dialog modal-fullscreen">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalFullscreenLabel">
          Título del Modal
        </h5>
        <button
          type="button"
          class="btn-close"
          data-bs-dismiss="modal"
          aria-label="Close"
        ></button>
      </div>
      <div class="modal-body">Contenido del Modal</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">
          Cerrar
        </button>
        <button type="button" class="btn btn-primary">Guardar cambios</button>
      </div>
    </div>
  </div>
</div>
```

## Características del Modal de Pantalla Completa

- **Ocupa Toda la Pantalla:** El modal se expande para ocupar toda la ventana del navegador, proporcionando una experiencia inmersiva para el usuario.
- **Enfoque en el Contenido:** Al ocupar toda la pantalla, el modal resalta el contenido y oculta el resto de la interfaz, enfocando la atención del usuario.
- **Funcionalidad Similar:** En términos de estructura y funcionamiento, los modales de pantalla completa son similares a los modales estándar de Bootstrap.
