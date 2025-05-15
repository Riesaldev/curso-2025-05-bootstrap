---
title: 04. Formularios
---

## Formularios en Bootstrap

Los [formularios](https://getbootstrap.com/docs/5.3/forms/overview/) en Bootstrap son componentes HTML que permiten recopilar y enviar datos de manera estructurada en una página web. Bootstrap proporciona estilos predefinidos, elementos de formulario mejorados y opciones de diseño para crear formularios atractivos y funcionales.

## Clases Básicas de Formulario

Bootstrap ofrece clases predefinidas para estilizar formularios básicos:

```html
<form>
  <div class="mb-3">
    <label for="exampleInputName" class="form-label">Nombre</label>
    <input type="text" class="form-control" id="exampleInputName" />
  </div>
  <div class="mb-3">
    <label for="exampleInputEmail" class="form-label">Correo electrónico</label>
    <input type="email" class="form-control" id="exampleInputEmail" />
  </div>
  <button type="submit" class="btn btn-primary">Enviar</button>
</form>
```

## Elementos de Formulario

Bootstrap mejora los elementos de formulario estándar de HTML al proporcionar estilos consistentes y funcionalidades adicionales, como:

- **Inputs:** Los estilos de los campos de entrada (`input`), áreas de texto (`textarea`) y selecciones (`select`) son consistentes y responsivos.

- **Checks y Radios:** Los botones de selección (`checkbox` y `radio`) son más atractivos y fáciles de usar.

- **File Inputs:** Los campos de carga de archivos (`input type="file"`) se pueden personalizar con Bootstrap para que coincidan con el diseño del formulario.

- **Form Feedback:** Bootstrap incluye clases para proporcionar retroalimentación visual sobre la validez de los campos del formulario.

## Diseño de Formularios

Bootstrap permite crear formularios horizontales, verticales y en línea para adaptarse a diferentes diseños y necesidades de diseño:

- **Formularios Verticales:** Los elementos del formulario se apilan verticalmente, lo que los hace adecuados para diseños de una columna.

- **Formularios Horizontales:** Los elementos del formulario se alinean horizontalmente, lo que es útil para diseños de varias columnas.

- **Formularios en Línea:** Los elementos del formulario se alinean en línea con el texto circundante, lo que ahorra espacio en la página.

## Select en Bootstrap

Los elementos de selección, o "_select_", en Bootstrap son una parte importante de los formularios y permiten a los usuarios elegir una opción de una lista desplegable. Bootstrap proporciona estilos predefinidos para los elementos de selección y opciones adicionales para personalizar su apariencia y comportamiento.

## Estilos Básicos de Select

Bootstrap aplica estilos predefinidos a los elementos de selección para que se integren visualmente con otros componentes de formulario:

```html
<select class="form-select" aria-label="Default select example">
  <option selected>Open this select menu</option>
  <option value="1">One</option>
  <option value="2">Two</option>
  <option value="3">Three</option>
</select>
```

## Tamaño de Select

Los elementos de selección en Bootstrap pueden tener diferentes tamaños aplicando las clases de tamaño correspondientes:

- `.form-select-lg` para un select de tamaño grande.
- `.form-select-sm` para un select de tamaño pequeño.

```html
<select class="form-select form-select-lg" aria-label="Large select example">
  <option value="1">One</option>
  <option value="2">Two</option>
  <option value="3">Three</option>
</select>
```

## Estado Activo y Desactivado

Bootstrap permite desactivar un elemento de selección para que no sea seleccionable y aplicar estilos a un elemento de selección activo:

```html
<select class="form-select" aria-label="Disabled select example" disabled>
  <option selected>Open this select menu</option>
  <option value="1">One</option>
  <option value="2">Two</option>
  <option value="3">Three</option>
</select>
```


