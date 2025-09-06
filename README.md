README - Sitio Web Energía Azul
Descripción del Proyecto
Este proyecto consiste en un sitio web informativo sobre aerogeneradores marinos para "Energía Azul", una organización tipo ONG dedicada a promover la energía eólica marina como fuente de energía sostenible. El sitio web está desarrollado completamente en HTML y CSS, sin JavaScript, manteniendo un diseño limpio y profesional.

Estructura del Proyecto

Line Wrapping

Collapse
Copy
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
proyecto/
├── index.html              # Página principal del sitio
├── galeria.html            # Página de galería multimedia
├── css/
│   ├── style.css          # Estilos principales
│   └── style_galeria.css  # Estilos específicos para la galería
└── img/                   # Carpeta de imágenes y videos
    ├── logo.jpg
    ├── content_principal2.jpg
    ├── imagen1.jpg
    ├── imagen2.jpg
    ├── imagen3.jpg
    ├── imagen4.jpg
    ├── imagen5.jpg
    ├── video.mp4
    └── video-poster.jpg
Características Principales
Página Principal (index.html)
Encabezado fijo: Con logo, nombre de la organización y barra de búsqueda.
Menú de navegación: Con enlaces a secciones internas mediante anclas.
Sección Hero: Imagen destacada con título y descripción.
Contenido informativo: Secciones detalladas sobre:
¿Qué son los aerogeneradores marinos?
Beneficios de la energía eólica marina
Funcionamiento de los aerogeneradores
Impacto ambiental
Retos y futuro de la tecnología
Formulario de contacto: Para consultas y colaboraciones.
Barra lateral: Con noticias recientes, artículos destacados y categorías.
Pie de página: Con información de contacto, navegación y redes sociales.
Página de Galería (galeria.html)
Misma estructura visual que la página principal para mantener consistencia.
Galería de imágenes: 5 imágenes en formato grid con efecto hover.
Lightbox CSS: Al hacer clic en una imagen, se abre en tamaño completo.
Sección de video: Video de 2 minutos con controles nativos.
Mismo encabezado y pie de página que la página principal.
Paleta de Colores
Azul océano (#00587A): Profesionalismo y mar.
Verde azulado (#00B3A6): Sostenibilidad.
Blanco/gris claro (#F4F4F4 / #CCCCCC): Limpieza y tecnología.
Amarillo solar (#FFD700): Energía y futuro.
Funcionalidades
Navegación Interna
Los enlaces del menú de navegación en la página principal llevan a las secciones correspondientes mediante anclas (anchors).
Los enlaces a "Galería" redirigen a la página secundaria.
El botón "Explora nuestra galería" también redirige a la página de galería.
Diseño Responsivo
El sitio se adapta a diferentes tamaños de pantalla mediante media queries.
En dispositivos móviles, el menú se reorganiza verticalmente.
Galería Multimedia
Las imágenes se muestran en una cuadrícula que se ajusta según el tamaño de la pantalla.
Al pasar el cursor sobre las imágenes, aparece un título descriptivo.
El lightbox para ver imágenes ampliadas funciona con CSS puro (sin JavaScript).
El video se reproduce con los controles nativos del navegador.
Tecnologías Utilizadas
HTML5: Estructura semántica del contenido.
CSS3: Estilos y diseño responsivo.
Font Awesome: Iconos para redes sociales y otros elementos.
Google Fonts: Tipografías Playfair Display (para títulos) y Roboto (para texto).
Instalación y Uso
Clonar o descargar los archivos del proyecto.
Asegurarse de que todos los archivos estén en la estructura correcta.
Colocar las imágenes y videos en la carpeta img/ con los nombres especificados.
Abrir index.html en un navegador web para ver la página principal.
Navegar a galeria.html para ver la galería multimedia.
Personalización
Para cambiar los colores, modificar las variables de color en el archivo CSS.
Para agregar más imágenes a la galería, duplicar la estructura de un elemento .galeria-item y ajustar los IDs del lightbox.
Para modificar el contenido, editar directamente los archivos HTML.
Notas Adicionales
El formulario de contacto no tiene funcionalidad de backend; solo es la interfaz visual.
El diseño sigue los principios de una organización tipo ONG, con énfasis en la sostenibilidad y el impacto ambiental.
El sitio está optimizado para una experiencia de usuario fluida y accesible.
Este proyecto demuestra cómo crear un sitio web informativo y visualmente atractivo utilizando únicamente HTML y CSS, manteniendo la coherencia visual entre todas las páginas y proporcionando una experiencia de usuario optimizada
