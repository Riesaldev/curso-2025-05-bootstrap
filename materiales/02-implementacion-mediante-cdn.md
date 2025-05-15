---
title: 02. Implementación mediante CDN
---

## Implementación mediante CDN

### Paso 1: Agregar el Enlace al CSS de Bootstrap

Para empezar, debes agregar el enlace al archivo CSS de Bootstrap en la sección `<head>` de tu documento HTML. Este enlace se encarga de cargar los estilos de Bootstrap en tu página web. Puedes encontrar el enlace al archivo CSS de Bootstrap en la [página oficial de Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/#quick-start) o en la documentación del CDN que elijas utilizar.

```html
<head>
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN"
    crossorigin="anonymous"
  />
</head>
```

### Paso 2: Agregar el Enlace al JavaScript de Bootstrap (Opcional)

Si planeas utilizar componentes interactivos de Bootstrap que requieren JavaScript, como modales o carruseles, también necesitarás agregar el enlace al archivo JavaScript de Bootstrap al final de tu documento HTML, justo antes de cerrar el cuerpo (`</body>`).

```html
<body>
  <!-- Contenido de tu página -->

  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL"
    crossorigin="anonymous"
  ></script>
</body>
```

## Ventajas del Uso mediante CDN

- **Facilidad de Implementación:** Utilizar Bootstrap mediante CDN es rápido y sencillo, ya que solo necesitas agregar enlaces a los archivos CSS y JavaScript en tu documento HTML.
- **Actualizaciones Automáticas:** Al utilizar Bootstrap a través de un CDN, obtienes automáticamente las últimas actualizaciones y mejoras del _framework_ sin necesidad de descargar o actualizar archivos manualmente.

- **Optimización de la Carga:** Los archivos de Bootstrap se almacenan en servidores distribuidos globalmente, lo que puede optimizar la velocidad de carga de tu sitio web al servir los archivos desde ubicaciones cercanas a los usuarios.

- **Ahorro de Espacio:** No necesitas almacenar los archivos de Bootstrap en tu servidor, lo que puede ayudar a ahorrar espacio y reducir la carga de tu servidor.

## Consideraciones

- **Dependencia de Internet:** El uso de un CDN requiere una conexión a Internet activa para cargar los archivos de Bootstrap. Si hay problemas de conectividad, tu sitio web podría no cargar correctamente.

- **Privacidad y Seguridad:** Al utilizar un CDN, estás confiando en un tercero para servir los archivos de Bootstrap. Aunque los CDNs suelen ser confiables, debes considerar la privacidad y seguridad de tus datos.

- **Compatibilidad:** Asegúrate de utilizar enlaces a versiones estables y compatibles de Bootstrap a través del CDN para evitar problemas de compatibilidad y posibles errores en tu sitio web.



# Breakpoints en Bootstrap

Los [_breakpoints_](https://getbootstrap.com/docs/5.3/layout/breakpoints/) en Bootstrap son puntos de interrupción predefinidos que marcan los límites en los cuales el diseño de un sitio web o una aplicación cambia su apariencia para adaptarse a diferentes tamaños de pantalla. Estos _breakpoints_ permiten crear diseños responsivos que se ajusten automáticamente a dispositivos de escritorio, tabletas y dispositivos móviles. A continuación, se explica en detalle cómo funcionan los _breakpoints_ en Bootstrap, junto con ejemplos prácticos:

## Breakpoints Predefinidos en Bootstrap

Bootstrap define una serie de _breakpoints_ predefinidos que corresponden a tamaños comunes de dispositivos. Estos _breakpoints_ se basan en el ancho del _viewport_ (ventana gráfica del navegador) y son los siguientes:

- **Extra Small (xs):** Menos de 576px
- **Small (sm):** 576px o más
- **Medium (md):** 768px o más
- **Large (lg):** 992px o más
- **Extra Large (xl):** 1200px o más

Estos breakpoints permiten adaptar el diseño de la página web en función del tamaño de la pantalla del dispositivo del usuario.

## Uso de Breakpoints en Clases de Bootstrap

Bootstrap utiliza clases específicas para aplicar estilos condicionales en función de los breakpoints. Estas clases están precedidas por prefijos que indican el tamaño del breakpoint al que se aplican. Por ejemplo:

- `.col-sm-6`: Se aplica a dispositivos de tamaño "sm" (576px o más) y asigna una anchura de columna de la mitad (6 de 12 columnas).
- `.d-lg-none`: Se aplica a dispositivos de tamaño "lg" (992px o más) y oculta el elemento.

## Ejemplos Prácticos

### Ajuste de la Rejilla (Grid System)

```html
<div class="container">
  <div class="row">
    <div class="col-md-6 col-lg-4">Columna 1</div>
    <div class="col-md-6 col-lg-4">Columna 2</div>
    <div class="col-md-12 col-lg-4">Columna 3</div>
  </div>
</div>
```

En este ejemplo, las columnas se distribuirán en una rejilla de 2 columnas en dispositivos medianos (md) y de 3 columnas en dispositivos grandes (lg) y superiores.

### Mostrar u Ocultar Elementos

```html
<div class="d-none d-md-block">
  Este texto solo se muestra en dispositivos medianos o superiores.
</div>
<div class="d-md-none">
  Este texto solo se muestra en dispositivos pequeños.
</div>
```

En este caso, el primer elemento solo será visible en dispositivos medianos (md) o superiores, mientras que el segundo solo será visible en dispositivos pequeños.


# Sistema de Rejillas en Bootstrap

El [sistema de rejillas](https://getbootstrap.com/docs/5.3/layout/grid/) en Bootstrap es una de las características más fundamentales y poderosas del _framework_. Permite crear diseños responsivos y adaptables mediante la distribución de contenido en columnas y filas. A continuación, se explica en detalle cómo funciona el sistema de rejillas en Bootstrap, junto con ejemplos prácticos:

## Funcionamiento del Sistema de Rejillas

El sistema de rejillas de Bootstrap se basa en un sistema de 12 columnas. Esto significa que cada fila puede contener hasta 12 columnas, y estas columnas pueden combinarse y distribuirse de diversas maneras para crear diseños complejos y flexibles.

## Uso de Clases de Columnas

Para utilizar el sistema de rejillas, se utilizan clases específicas de Bootstrap que definen el comportamiento de las columnas en diferentes tamaños de pantalla. Algunas de las clases más comunes son:

- `.col-`: clase base para definir una columna.
- `.col-{breakpoint}-{n}`: define el número de columnas que una columna ocupará en un determinado _breakpoint_.

## Ejemplos Prácticos

### Distribución de Columnas

```html
<div class="container">
  <div class="row">
    <div class="col-md-6">Columna 1</div>
    <div class="col-md-6">Columna 2</div>
  </div>
</div>
```

En este ejemplo, hay dos columnas que ocupan cada una la mitad del ancho del contenedor en dispositivos medianos (md) y superiores.

### Columnas Responsivas

```html
<div class="container">
  <div class="row">
    <div class="col-md-4 col-lg-3">Columna 1</div>
    <div class="col-md-8 col-lg-9">Columna 2</div>
  </div>
</div>
```

En este caso, la primera columna ocupa 4 columnas en dispositivos medianos (md) y 3 columnas en dispositivos grandes (lg) y superiores, mientras que la segunda columna ocupa 8 columnas en dispositivos medianos y 9 columnas en dispositivos grandes y superiores.
