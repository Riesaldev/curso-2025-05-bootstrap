---
title: 09. Navbar
---

## Navbar en Bootstrap

La [Navbar](https://getbootstrap.com/docs/5.3/components/navbar/), o barra de navegación, en Bootstrap es un componente fundamental que permite la navegación entre diferentes secciones o páginas de un sitio web. Es altamente personalizable y adaptable a diferentes dispositivos, lo que la convierte en una herramienta poderosa para la creación de interfaces de usuario.

## Estructura Básica

La estructura básica de una Navbar en Bootstrap se compone de un contenedor principal `<nav>` y elementos de navegación como enlaces `<a>` dentro de listas `<ul>`:

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Logo</a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Inicio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Acerca</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Servicios</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contacto</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
```

## Características de la Navbar

- **Responsiva:** La Navbar de Bootstrap es totalmente responsiva y se adapta automáticamente a diferentes tamaños de pantalla.
- **Personalizable:** Se puede personalizar fácilmente utilizando clases predefinidas de Bootstrap o agregando estilos personalizados.
- **Interactiva:** Puede contener elementos interactivos como botones, formularios, menús desplegables, etc.
- **Versátil:** Es adecuada para una variedad de aplicaciones, desde sitios web simples hasta aplicaciones web complejas.

## Navbar Fixed Top en Bootstrap

La Navbar Fixed Top en Bootstrap es una variante de la barra de navegación que se mantiene fija en la parte superior de la ventana del navegador mientras el usuario se desplaza por la página. Esto proporciona una navegación consistente y accesible en todo momento, lo que mejora la experiencia del usuario.

## Estructura Básica

La estructura básica de una Navbar Fixed Top en Bootstrap es similar a la de una barra de navegación estándar, pero con una clase adicional para fijarla en la parte superior:

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Logo</a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Inicio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Acerca</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Servicios</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contacto</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
```

## Características de la Navbar Fixed Top

- **Fijada en la Parte Superior:** La Navbar se mantiene fija en la parte superior de la ventana del navegador, incluso al desplazarse por la página.
- **Accesibilidad Mejorada:** Proporciona una navegación consistente y accesible en todo momento, lo que mejora la experiencia del usuario.
- **Funcionalidad Similar:** En términos de estructura y funcionamiento, la Navbar Fixed Top es similar a la barra de navegación estándar de Bootstrap.

## Navbar Fixed Bottom en Bootstrap

La Navbar Fixed Bottom en Bootstrap es una variante de la barra de navegación que se mantiene fija en la parte inferior de la ventana del navegador mientras el usuario se desplaza por la página. Proporciona una navegación persistente y accesible, lo que mejora la experiencia del usuario al facilitar el acceso a las opciones de navegación en todo momento.

## Estructura Básica

La estructura básica de una Navbar Fixed Bottom en Bootstrap es similar a la de una barra de navegación estándar, pero con una clase adicional para fijarla en la parte inferior:

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light fixed-bottom">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Logo</a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Inicio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Acerca</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Servicios</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contacto</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
```

## Características de la Navbar Fixed Bottom

- **Fijada en la Parte Inferior:** La Navbar se mantiene fija en la parte inferior de la ventana del navegador, incluso al desplazarse por la página.
- **Accesibilidad Mejorada:** Proporciona una navegación persistente y accesible en todo momento, lo que mejora la experiencia del usuario.
- **Funcionalidad Similar:** En términos de estructura y funcionamiento, la Navbar Fixed Bottom es similar a la barra de navegación estándar de Bootstrap.

## Navbar Sticky Top en Bootstrap

La Navbar Sticky Top en Bootstrap es una variante de la barra de navegación que se adhiere en la parte superior de la ventana del navegador cuando el usuario se desplaza por la página. Esto proporciona una navegación persistente y accesible, manteniendo siempre visible la barra de navegación para facilitar la interacción del usuario.

## Estructura Básica

La estructura básica de una Navbar Sticky Top en Bootstrap es similar a la de una barra de navegación estándar, pero con una clase adicional para fijarla en la parte superior con posición fija:

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Logo</a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Inicio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Acerca</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Servicios</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contacto</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
```

## Características de la Navbar Sticky Top

- **Adherida en la Parte Superior:** La Navbar se mantiene adherida en la parte superior de la ventana del navegador, incluso al desplazarse por la página.
- **Accesibilidad Mejorada:** Proporciona una navegación persistente y accesible en todo momento, lo que mejora la experiencia del usuario.
- **Funcionalidad Similar:** En términos de estructura y funcionamiento, la Navbar Sticky Top es similar a la barra de navegación estándar de Bootstrap.
