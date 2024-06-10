# Construye una Página de Documentación Técnica
- [x] 1. Puedes ver un elemento `main` con su correspondiente `id="main-doc"`, el cual abarcará el contenido principal de la página (documentación técnica).
- [x] 2. Dentro del elemento `#main-doc`, se pueden ver varios elementos `section`, cada uno con la clase `main-section`. Debe haber un mínimo de cinco.
- [x] 3. El primer elemento dentro de cada `.main-section` debería ser un elemento `header`, el cual contendrá texto que describa el tema de esa sección.
- [x] 4. Cada elemento `section` con la clase `main-section` debería tener también un `id` que corresponda al texto de cada `header` contenido dentro de él. Cualquier espacio debe ser reemplazado por guiones bajos (Ejemplo: La sección que contiene el encabezado "JavaScript and Java" debe tener un `id="JavaScript_and_Java"`).
- [x] 5. Los elementos `.main-section` deberán tener al menos diez elementos `p` en total (no cada uno).
- [x] 6. Los elementos `.main-section` deberán tener al menos cinco elementos `code` en total (no cada uno).
- [x] 7. Los elementos `.main-section` deben tener al menos cinco items `li` en total (no cada uno).
- [x] 8. Puedes ver un elemento `nav` con su correspondiente `id="navbar"`.
- [x] 9. La barra de navegación debe contener un elemento `header`, el cual contendrá texto que describa el tema de la documentación técnica.
- [x] 10. Además, la barra de navegación debe contener elementos de enlace (`a`) con la clase `nav-link`. Debe haber uno para cada elemento con la clase `main-section`.
- [x] 11. El elemento `header` dentro de la `#navbar` debe ir antes que los elementos (`a`) de la barra de navegación.
- [x] 12. Cada elemento con la clase `nav-link` debe tener texto que corresponda al texto del `header` de cada `section` (Ejemplo: Si tienes una sección/encabezado "Hello world", tu barra de navegación debe tener un elemento que contenga el texto "Hello world").
- [x] 13. Al hacer clic en un elemento de tu barra de navegación, la página debe dirigirse a la sección correspondiente del elemento `#main-doc` (Ejemplo: Si haces clic en el elemento `.nav-link` que contiene el texto "Hello world", la página debe dirigirse al elemento `section` que tenga ese `id` y contenga el encabezado correspondiente).
- [x] 14. En dispositivos de tamaño normal (portátiles, computadoras de escritorio), el elemento con `id="navbar"` debe mostrarse en el lado izquierdo de la pantalla y siempre ser visible para el usuario.
- [x] 15. Tu documentación técnica debe usar al menos una media query.

Completa las historias de usuario y pasa todas las pruebas a continuación para completar este proyecto. Dale tu propio estilo personal. ¡Feliz día programando!

Nota: Asegúrate de agregar `<link rel="stylesheet" href="styles.css">` en tu HTML para enlazar tu hoja de estilos y aplicar tu CSS