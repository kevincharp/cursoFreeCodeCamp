📚 Documentación Técnica
Estructura del Proyecto
Main Content
El contenido principal de la página estará contenido en un elemento <main> con el id="main-doc". Este elemento abarca toda la documentación técnica.
Secciones
Dentro del elemento #main-doc, habrá varios elementos <section>, cada uno con la clase main-section. Debe haber un mínimo de cinco secciones.
El primer elemento dentro de cada .main-section será un <header>, que describirá el tema de esa sección.
Cada sección .main-section tendrá un id que coincida con el texto de su encabezado, reemplazando los espacios con guiones bajos.
Ejemplo: La sección con el encabezado "JavaScript and Java" tendrá id="JavaScript_and_Java".
Contenido
Los elementos .main-section tendrán al menos diez elementos <p> en total (no cada uno).
Los elementos .main-section tendrán al menos cinco elementos <code> en total (no cada uno).
Los elementos .main-section tendrán al menos cinco elementos <li> en total (no cada uno).
Barra de Navegación
Habrá un elemento <nav> con el id="navbar".
La barra de navegación contendrá un elemento <header>, que describirá el tema de la documentación técnica.
Además, la barra de navegación tendrá elementos de enlace <a> con la clase nav-link. Habrá uno para cada elemento con la clase main-section.
El elemento <header> dentro de #navbar debe ir antes que los elementos <a> de la barra de navegación.
Cada elemento nav-link debe tener texto que corresponda al texto del encabezado de cada sección.
Ejemplo: Si tienes una sección/encabezado "Hello world", tu barra de navegación debe tener un enlace con el texto "Hello world".
Funcionalidad
Al hacer clic en un elemento de la barra de navegación, la página se dirigirá a la sección correspondiente del elemento #main-doc.
Ejemplo: Si haces clic en el elemento .nav-link que contiene el texto "Hello world", la página debe dirigirse al elemento <section> que tenga ese id y contenga el encabezado correspondiente.
Estilos
En dispositivos de tamaño normal (portátiles, computadoras de escritorio), el elemento con id="navbar" se mostrará en el lado izquierdo de la pantalla y siempre será visible para el usuario.
Tu documentación técnica debe usar al menos una media query para asegurar la responsividad.
Historias de Usuario
Completa las historias de usuario y pasa todas las pruebas para finalizar este proyecto.
Dale tu propio estilo personal.