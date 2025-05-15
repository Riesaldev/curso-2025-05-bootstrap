---
title: 07. Dropdowns y List Group
---

## _Dropdowns_ en Bootstrap

Los [_dropdowns_](https://getbootstrap.com/docs/5.3/components/dropdowns/), o menús desplegables, en Bootstrap, son componentes interactivos que permiten a los usuarios seleccionar una opción de una lista desplegable. Son útiles para presentar opciones y acciones adicionales de manera compacta y accesible en una interfaz de usuario.

## Estructura Básica

La estructura básica de un _dropdown_ en Bootstrap consiste en un botón o enlace que activa el menú desplegable y una lista de opciones que se despliega cuando se hace clic en el botón:

```html
<div class="dropdown">
  <button
    class="btn btn-secondary dropdown-toggle"
    type="button"
    id="dropdownMenuButton"
    data-bs-toggle="dropdown"
    aria-expanded="false"
  >
    Menú desplegable
  </button>
  <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
    <li><a class="dropdown-item" href="#">Opción 1</a></li>
    <li><a class="dropdown-item" href="#">Opción 2</a></li>
    <li><a class="dropdown-item" href="#">Opción 3</a></li>
  </ul>
</div>
```

## Componentes del _Dropdown_

- **Botón o Enlace:** El botón o enlace que activa el _dropdown_ debe tener la clase `.dropdown-toggle` y los atributos `data-bs-toggle="dropdown"` y `aria-haspopup="true"`.
- **Menú desplegable:** El menú desplegable es una lista de opciones que se muestra cuando se activa el _dropdown_. Debe tener la clase `.dropdown-menu` y estar asociado al botón o enlace mediante el atributo `aria-labelledby`.

## Opciones Adicionales

Bootstrap ofrece opciones adicionales para personalizar y mejorar la funcionalidad de los _dropdowns_:

- **Menús desplegables alineados:** Se pueden alinear los menús desplegables a la izquierda o derecha del botón o enlace utilizando clases de alineación como `.dropdown-menu-start` y `.dropdown-menu-end`.
- **Menús desplegables divididos:** Se pueden dividir los menús desplegables en secciones utilizando encabezados y divisiones con la clase `.dropdown-divider`.

## List Group en Bootstrap

Los [_list group_](https://getbootstrap.com/docs/5.3/components/list-group/), o "grupos de listas", en Bootstrap, son componentes que permiten presentar contenido de manera organizada y estructurada en forma de lista. Son útiles para mostrar elementos relacionados, como listas de opciones, elementos de navegación o mensajes, de manera visualmente atractiva y accesible.

## Estructura Básica

La estructura básica de un _list group_ en Bootstrap consiste en un contenedor con una serie de elementos de lista:

```html
<ul class="list-group">
  <li class="list-group-item">Elemento 1</li>
  <li class="list-group-item">Elemento 2</li>
  <li class="list-group-item">Elemento 3</li>
</ul>
```

## Componentes del List Group

- **Elementos de Lista:** Cada elemento de lista (`<li>`) dentro del _list group_ representa un elemento de la lista. Pueden contener texto, enlaces, botones u otros elementos HTML.
- **Clases de Estilo:** Bootstrap proporciona clases predefinidas para estilizar los _list group_ y sus elementos. Por ejemplo, `.list-group` para el contenedor y `.list-group-item` para los elementos de la lista.

## Opciones Adicionales

Bootstrap ofrece opciones adicionales para personalizar y mejorar la funcionalidad de los _list group_:

- **List Group con Enlaces:** Se pueden agregar enlaces a los elementos de lista para crear una lista de navegación interactiva.
- **List Group Activo:** Se puede indicar visualmente un elemento de lista activo agregando la clase `.active` al elemento correspondiente.
- **List Group con Contenido Adicional:** Se pueden agregar elementos adicionales, como encabezados, textos descriptivos o botones, dentro de los elementos de lista para proporcionar más información o acciones relacionadas.
