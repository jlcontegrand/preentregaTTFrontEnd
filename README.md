# UwRI

UwRI es una tienda ficticia de relojes inteligentes creada por **José Conte-Grand** como preentrega del curso de Front End de **Talento Tech**. El objetivo del proyecto es practicar la estructura de una página con HTML y su presentación adaptable con CSS.

## Qué incluye

- Portada, menú y secciones de productos, reseñas y contacto.
- Catálogo visual de tres relojes con tarjetas, descripciones y precios de ejemplo.
- Menú de categorías y distribución adaptable a distintos anchos de pantalla.
- Reseñas ficticias y formulario de contacto.

El sitio es una **demostración académica**: los productos, precios y testimonios son simulados. Los botones «Agregar al carrito» son parte de la interfaz y todavía no implementan un carrito ni procesan compras.

## Demo en línea

[Ver UwRI en GitHub Pages](https://jlcontegrand.github.io/preentregaTTFrontEnd/) — disponible una vez habilitada la publicación desde la rama `main` y la carpeta `/(root)`.

## Tecnologías

- **HTML5** para la estructura y los formularios.
- **CSS3** para estilos, variables de color, Flexbox y media queries.
- **Google Fonts (Asap)** y **Material Symbols** para la tipografía y el ícono de las reseñas.

## Cómo abrir el proyecto

1. Descargá el repositorio o clonalo con `git clone https://github.com/jlcontegrand/preentregaTTFrontEnd.git`.
2. Abrí `index.html` en un navegador.

No se requiere instalar dependencias ni ejecutar un servidor para ver la página. La fuente y el ícono externos necesitan conexión a internet para cargarse.

## Estructura principal

```text
├── index.html          # Contenido de la página
├── css/
│   └── style.css       # Estilos y reglas responsivas
├── assets/
│   └── img/            # Imágenes del sitio
└── README.md           # Documentación del proyecto
```

## Formulario de contacto

El formulario está preparado para enviar datos mediante Formspree, pero en `index.html` el atributo `action` todavía contiene `TU_ID`. Para habilitar el envío, hay que crear un formulario en Formspree y reemplazar ese valor por el identificador real del endpoint. Hasta entonces, el formulario no recibe mensajes.

## Autor

**José Conte-Grand** · Preentrega de Front End, Talento Tech.
