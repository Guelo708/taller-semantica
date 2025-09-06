Taller de Investigación: Fundamentos de HTML
Nombre del Estudiante: [Migue Eduardo Hernandez Hernandez]

1. Anatomía de una Etiqueta HTML
Etiqueta de Apertura y Cierre
¿Qué es una etiqueta de apertura?
Etiqueta es la forma basica y estandarizada como se ingresa informacion a una pagina Web: <h1>Contenido</h1>
La etiqueta de apertura: ejemplo <h1> indica el inicio del documento
Contenido: lo que va dentro de la etiqueta, como texto, imágenes, enlaces, etc.

¿Qué es una etiqueta de cierre?

</h1> indica el final del elemento. Se diferencia por la barra /.


Atributos
¿Qué es un atributo y para qué sirve? Da un ejemplo.

Un atributo en HTML es una característica adicional que se agrega a una etiqueta para modificar su comportamiento o apariencia, o para proporcionar información extra. Siempre se coloca dentro de la etiqueta de apertura y sigue esta estructura:
<etiqueta atributo="valor">Contenido</etiqueta>

 <a href="">Google</a>
    <a href="https://www.google.com/" target="_blank"
      >Educación Digital</a
    >

href es un hipervinculo de referencia entonces cuando lo indico en la etiqueta el me lleva directamente a la direccion que le indique ejemplo = https://www.google.com/

2. El Poder de la Semántica
HTML Semántico
¿Qué es el HTML Semántico y por qué es tan importante?

El HTML semántico es una forma de escribir código HTML utilizando etiquetas que describen claramente el propósito del contenido que envuelven. En lugar de usar etiquetas genéricas como <div> o <span> para todo, el HTML semántico emplea elementos como <header>, <nav>, <main>, <article>, <section>, y <footer>, que comunican el significado del contenido tanto a los navegadores como a los usuarios y motores de búsqueda.

¿Por qué es tan importante?
Accesibilidad
Los lectores de pantalla y otras tecnologías asistivas dependen de una estructura clara para ayudar a personas con discapacidades a navegar por una página.
Por ejemplo, si se usa <nav> para la barra de navegación, un lector de pantalla puede anunciar: “Zona de navegación”, permitiendo al usuario saltar directamente a esa sección.
También mejora la experiencia para personas con discapacidades cognitivas, visuales o motoras, al ofrecer una navegación más lógica y predecible.

SEO (Optimización para Motores de Búsqueda)
Los motores de búsqueda como Google utilizan “crawlers” para escanear el contenido de una página. Si el HTML está bien estructurado semánticamente, esos robots pueden entender mejor la jerarquía y relevancia del contenido.
Por ejemplo, usar <article> para un post de blog y <h1> para el título principal ayuda a Google a identificar qué es lo más importante en la página, lo que puede mejorar tu posicionamiento en los resultados de búsqueda.
Además, el uso de etiquetas semánticas facilita la implementación de microdatos y JSON-LD, que enriquecen los resultados con fragmentos destacados como reseñas, eventos o productos.

En resumen, el HTML semántico mejora la accesibilidad, el SEO, la mantenibilidad del código y la experiencia del usuario. Es una práctica esencial para cualquier desarrollador web que quiera construir sitios modernos, inclusivos y bien posicionados en buscadores. Ademas es una forma de escribir codigo de forma estandarizada lo que le da escalabilidad al proyecto que se está desarrollando

Diccionario de Etiquetas Semánticas
1: <header>:
Define la cabecera de una sección o página. Suele contener el logo, título, menú principal o encabezados. 
Explica su propósito aquí.
Ayuda a los lectores de pantalla a identificar el inicio de una sección

2: <nav>:

Representa una zona de navegación, como menús o enlaces internos.

Explica su propósito aquí.
Mejora la accesibilidad permitiendo a los usuarios saltar directamente a la navegación
También ayuda a los motores de búsqueda a entender la estructura del sitio.

3: <main>:

Contiene el contenido principal de la página, excluyendo encabezados, barras laterales y pie de página.

Explica su propósito aquí.
Solo debe haber un <main> por documento.
Es clave para el SEO, ya que indica el núcleo informativo

4: <section>:
Agrupa contenido relacionado dentro de una página.

Explica su propósito aquí.
Ideal para dividir el contenido en bloques temáticos como “Noticias”, “Servicios”, “Contacto
Cada sección puede tener su propio encabezado.

5: <article>:
Define contenido independiente y autónomo, como publicaciones de blog, comentarios o noticias.

Explica su propósito aquí.

Puede ser distribuido por separado y tener sentido por sí solo.
Muy útil para SEO, ya que cada artículo puede indexarse individualmente.

6: <aside>:
Representa contenido complementario o secundario, como barras laterales, enlaces relacionados o anuncios.

Explica su propósito aquí.
Los lectores de pantalla lo interpretan como contenido adicional, no principal

7: <footer>:
Define el pie de página de una sección o documento.

Explica su propósito aquí.
.
Suele incluir información de contacto, derechos de autor, enlaces legales o redes sociales.
.Ayuda a cerrar la estructura semántica de la página
.
.
.

20: 
