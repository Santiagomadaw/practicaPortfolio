# Práctica: Fundamentos Web: HTML5, CSS3

Esta práctica consiste en la creación de un **portafolio**, ya sea propio o de un personaje ficticio. En mi caso, he elegido a **Rick Sanchez**, un personaje de la serie **Rick & Morty**.

## Consideraciones generales
- **No se permite** el uso de librerías y frameworks externos como Bootstrap, Spectre.css u otros similares.
- Se debe crear **una o más hojas de estilo CSS** para aplicar el diseño deseado a la web.
- La página web debe visualizarse correctamente en las versiones actuales de Google Chrome, Mozilla Firefox y Microsoft Edge.
- No está permitido el uso de JS.

## Estructura:
- Un encabezado donde disponemos de una barra de navegación con enlaces a las diferentes partes del portafolio. En la versión móvil, esta barra se ha sustituido por un menú de hamburguesa desplegable.
- Dentro del cuerpo del portafolio, tenemos las siguientes secciones:
    - Una sección donde el personaje se presenta.
    - Un banner que deberá tener una imagen de fondo y una frase del personaje.
    - Una sección con una breve biografía del personaje, así como una lista de habilidades representadas por barras de progreso animadas.
        - Para la animación de las barras, se ha usado la propiedad `animation-timeline`, que aún no funciona en todos los navegadores. Por lo tanto, en navegadores como Safari o Firefox, estas animaciones se ejecutarán en el momento de la carga y no serán visibles.

- Formulario de contacto con los campos requeridos por el ejercicio.
- Un pie de página con enlaces a redes sociales.
- Una página con un video que se reproduce al entrar en la web con una animación de fadeIn.
- Una página con una cuadrícula con los proyectos del personaje.
- Adicionalmente, se han maquetado las páginas de error: Página de 404 y 500.
