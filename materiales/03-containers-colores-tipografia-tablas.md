---
title: 03. Containers, colores, tipos y tablas
---

# Explicación de "_containers_" en Bootstrap

Los "[containers](https://getbootstrap.com/docs/5.3/layout/containers/)" en Bootstrap son elementos fundamentales para la maquetación y alineación del contenido en páginas web responsivas. Estos contenedores permiten controlar cómo se distribuye y presenta el contenido en diferentes tamaños de pantalla y dispositivos.

En Bootstrap, hay dos tipos principales de containers: `.container` y `.container-fluid`.

- **`.container`:** Este tipo de contenedor tiene un ancho fijo y se centra en la página. Es ideal para alinear y estructurar el contenido en dispositivos de escritorio. Proporciona márgenes laterales consistentes y ayuda a mantener la legibilidad del contenido.

- **`.container-fluid`:** A diferencia del contenedor estándar, este tipo de contenedor ocupa todo el ancho disponible del viewport sin ningún margen lateral. Se adapta dinámicamente al ancho de la pantalla del dispositivo, lo que lo hace perfecto para diseños que necesitan ocupar todo el espacio disponible horizontalmente.

Además de estos contenedores estándar, Bootstrap proporciona clases adicionales que permiten ajustar el comportamiento del contenedor en diferentes tamaños de pantalla mediante los prefijos `container-`, seguidos de las abreviaturas de tamaños: `sm`, `md`, `lg`, `xl`, y `xxl`. Estos prefijos permiten definir el ancho del contenedor para diferentes tamaños de dispositivos.

## Ejemplos de Uso:

### Container

```html
<div class="container">
  <!-- Contenido del contenedor -->
</div>
```

### Container-fluid

```html
<div class="container-fluid">
  <!-- Contenido del contenedor fluido -->
</div>
```

### Containers con especificación de tamaño

```html
<div class="container-sm">
  <!-- Contenido del contenedor para dispositivos pequeños -->
</div>

<div class="container-md">
  <!-- Contenido del contenedor para dispositivos medianos -->
</div>

<div class="container-lg">
  <!-- Contenido del contenedor para dispositivos grandes -->
</div>

<div class="container-xl">
  <!-- Contenido del contenedor para dispositivos extra grandes -->
</div>

<div class="container-xxl">
  <!-- Contenido del contenedor para dispositivos extra extra grandes -->
</div>
```

Estos contenedores son esenciales para crear diseños responsivos y adaptativos en Bootstrap, proporcionando una estructura sólida para el contenido web en una variedad de dispositivos y tamaños de pantalla.

## Colores en Bootstrap

Los [colores](https://getbootstrap.com/docs/5.3/utilities/colors/) en Bootstrap son una parte importante del sistema de diseño que proporciona el _framework_. Estos colores predefinidos facilitan la consistencia y la personalización en el diseño de interfaces de usuario.

Bootstrap define una serie de colores principales y secundarios que se pueden aplicar a diferentes componentes y elementos en una página web.

## Colores Principales

Los colores principales en Bootstrap son:

- **Primary:** Este color se utiliza comúnmente para resaltar elementos importantes y acciones principales en la interfaz.

- **Secondary:** Ofrece una alternativa al color primario y se puede utilizar para acciones secundarias o elementos menos importantes.

- **Success:** Indica éxito o confirmación de una acción.

- **Danger:** Se utiliza para resaltar elementos que requieren atención o indicar un error.

- **Warning:** Indica advertencias o acciones que requieren precaución.

- **Info:** Proporciona información adicional o detalles contextuales.

- **Light:** Un color claro que se puede utilizar para fondos o áreas de contenido que necesitan destacarse sutilmente.

- **Dark:** Un color oscuro que se puede utilizar para texto sobre fondos claros o elementos que necesitan contrastar.

## Uso de los Colores

Los colores en Bootstrap se aplican mediante clases específicas que se pueden agregar a elementos HTML. Por ejemplo:

```html
<button class="btn btn-primary">Botón Primario</button>
<button class="btn btn-secondary">Botón Secundario</button>
<span class="badge bg-success">Éxito</span>
<span class="badge bg-danger">Peligro</span>
<span class="badge bg-warning text-dark">Advertencia</span>
<span class="badge bg-info text-dark">Información</span>
```

En el código anterior, `btn-primary`, `btn-secondary`, `bg-success`, `bg-danger`, `bg-warning`, y `bg-info` son clases predefinidas en Bootstrap que aplican los colores correspondientes a los elementos.

## Tipografía en Bootstrap

La [tipografía](https://getbootstrap.com/docs/5.3/content/typography/) en Bootstrap es una parte fundamental del diseño de interfaces de usuario. Bootstrap proporciona un conjunto de clases predefinidas que permiten aplicar estilos de texto coherentes y atractivos en una página web.

## Encabezados (h1, h2, h3, h4, h5, h6)

Bootstrap ofrece estilos para los [encabezados](https://getbootstrap.com/docs/5.3/content/typography/#headings) HTML (`h1` a `h6`) que permiten establecer jerarquías visuales en el contenido de la página. Estos estilos están diseñados para ser legibles y estéticamente agradables.

```html
<h1>Encabezado de nivel 1</h1>
<h2>Encabezado de nivel 2</h2>
<h3>Encabezado de nivel 3</h3>
<h4>Encabezado de nivel 4</h4>
<h5>Encabezado de nivel 5</h5>
<h6>Encabezado de nivel 6</h6>
```

## Clases de Display

Bootstrap también proporciona [clases de visualización](https://getbootstrap.com/docs/5.3/content/typography/#display-headings) (`display-1`, `display-2`, `display-3`, `display-4`) que permiten aplicar estilos de texto grandes y llamativos para títulos destacados o secciones importantes.

```html
<span class="display-1">Título Grande</span>
<span class="display-2">Título Grande 2</span>
<span class="display-3">Título Grande 3</span>
<span class="display-4">Título Grande 4</span>
```

## Clases de Texto

Además de los estilos de encabezado y visualización, Bootstrap proporciona [clases para estilizar el texto](https://getbootstrap.com/docs/5.3/content/typography/#lead) de manera consistente, como `lead` para texto destacado y `blockquote` para citas.

```html
<p class="lead">Este es un texto destacado.</p>
<blockquote class="blockquote">
  <p>Esta es una cita con estilo.</p>
  <footer class="blockquote-footer">Autor de la cita</footer>
</blockquote>
```

## Tablas en Bootstrap

Las [tablas](https://getbootstrap.com/docs/5.3/content/tables/#overview) en Bootstrap son componentes HTML que permiten mostrar datos de manera organizada y legible en una página web. Bootstrap proporciona estilos predefinidos y funcionalidades adicionales para mejorar la apariencia y la usabilidad de las tablas.

## Clases Básicas de Tabla

Bootstrap ofrece clases predefinidas para estilizar tablas básicas:

```html
<table class="table">
  <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">Encabezado</th>
      <th scope="col">Encabezado</th>
      <th scope="col">Encabezado</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Dato</td>
      <td>Dato</td>
      <td>Dato</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Dato</td>
      <td>Dato</td>
      <td>Dato</td>
    </tr>
  </tbody>
</table>
```

## Estilos Alternativos de Tabla

Bootstrap también proporciona estilos alternativos para las tablas:

- `table-striped`: para tablas con filas alternadas sombreadas.
- `table-bordered`: para tablas con bordes en todas las celdas y encabezados.
- `table-hover`: para resaltar filas al pasar el cursor sobre ellas.
- `table-dark`: para tablas con un fondo oscuro y texto claro.

## Funcionalidades Adicionales

Bootstrap incluye características adicionales para mejorar la funcionalidad de las tablas, como:

- **Responsive Tables:** Las tablas pueden hacerse responsivas agregando la clase `.table-responsive` al contenedor de la tabla. Esto permite que las tablas se desplacen horizontalmente en dispositivos de pantalla pequeña.

- **Reordering Columns:** Se pueden habilitar funcionalidades de reordenamiento de columnas utilizando JavaScript y complementos de terceros compatibles con Bootstrap.
