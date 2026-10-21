# ¿Qué es un CMS?

Es un software que permite crear, administrar y publicar contenido en un sitio web sin necesidad de saber programación.

Un CMS facilita la gestión de una página web, ya que permite crear y modificar contenidos desde una interfaz de administración, sin tener que editar directamente el código de la página cada vez que se quiera realizar un cambio.

# ¿Cómo funciona un CMS?

Los contenidos se crean y se administran desde un panel de gestión que proporciona el propio CMS. Desde este panel se pueden crear nuevas páginas o entradas, añadir elementos de texto o imágenes, guardar los contenidos como borrador, modificarlos y finalmente publicarlos.

Los contenidos ya existentes también pueden editarse o eliminarse desde ese mismo panel.

Además, algunos CMS permiten gestionar usuarios y sus permisos para controlar quién puede modificar y crear contenidos.

# Tipos de CMS

## Según su enfoque

- **Comercio electrónico:** Shopify.
- **Blogs y webs generales:** WordPress.
- **Educación:** Moodle.

## Según su arquitectura

- **Tradicional o monolítico:** el panel de administración y la parte visual de la web están integrados en un mismo sistema. Algunos ejemplos son WordPress y Drupal.
- **Headless:** el CMS se encarga de almacenar y gestionar el contenido, pero no incluye la parte visual de la web. El contenido se entrega mediante una API a la aplicación o web que queramos utilizar.
- **Desacoplado:** separa el backend, que se encarga de procesar los datos, y el frontend, que es la parte que ve y utiliza el usuario. Esto permite que cada parte pueda desarrollarse y modificarse de manera independiente.

# CMS dinámico vs generador de sitios estáticos

| Aspecto | CMS dinámico | Generador estático |
|---|---|---|
| Forma de crear contenido | Desde un panel de administración | Mediante archivos y plantillas |
| Base de datos | Normalmente sí la utiliza | No necesita BBDD para servir el contenido |
| Generación de HTML | Se genera cuando el usuario solicita la página | Se genera durante el proceso de `build` |
| Servidor necesario | Necesita soporte para el CMS | Solo necesita servir archivos estáticos |
| Panel de administración | Sí | No |
| Conocimientos técnicos | Pocos para gestionar el contenido | Mayores para modificar archivos y plantillas |
| Seguridad | Mayor superficie de ataque y requiere actualizaciones | Menor superficie de ataque |
| Rendimiento | Puede ser menor por el procesamiento dinámico | Normalmente más rápido |
| Actualización del contenido | Se modifica directamente desde el panel | Hay que modificar los archivos y volver a generar la web |
| Ejemplos | WordPress, Drupal | Hugo, Jekyll |

[Vídeo explicativo sobre CMS](https://www.youtube.com/watch?v=sSh5AAmItN0)

[Volver al documento sobre SSG](ssg.md)





