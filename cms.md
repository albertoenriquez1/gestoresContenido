
# ¿Qué es un CMS?

Un CMS (*Content Management System*), o sistema de gestión de contenidos, es un software que permite crear, administrar y publicar contenido en un sitio web sin necesidad de saber programar.

Un CMS facilita la gestión de una página web, ya que permite crear y modificar contenidos desde una interfaz de administración, sin tener que editar directamente el código de la página cada vez que se quiera realizar un cambio.

Se utiliza, por ejemplo, para crear blogs, páginas corporativas, tiendas online, periódicos digitales y plataformas educativas. Además, muchos CMS permiten ampliar sus funciones mediante temas, extensiones y complementos.

# ¿Cómo funciona un CMS?

Los contenidos se crean y se administran desde un panel de gestión que proporciona el propio CMS. Desde este panel se pueden crear nuevas páginas o entradas, añadir textos e imágenes, guardar contenidos como borradores, modificarlos y finalmente publicarlos.

Los contenidos ya existentes también pueden editarse o eliminarse desde ese mismo panel.

Dependiendo del CMS, los contenidos se almacenan en una base de datos y se combinan con plantillas para mostrar las páginas a los visitantes.

Además, algunos CMS permiten gestionar usuarios y sus permisos para controlar quién puede crear, modificar, revisar o publicar contenidos.

Por ejemplo, en una web de noticias, un redactor puede escribir una noticia y guardarla como borrador, mientras que un editor puede revisarla y publicarla. De esta forma, varias personas pueden colaborar en una misma web sin tener que modificar directamente el código HTML.

# Tipos de CMS

## Según su enfoque

- **Comercio electrónico:** Shopify. Permite crear tiendas online y gestionar productos, pedidos y pagos.
- **Blogs y webs generales:** WordPress. Se utiliza para crear blogs, páginas corporativas y otros tipos de sitios web.
- **Educación:** Moodle. Permite crear plataformas de aprendizaje, organizar cursos y gestionar materiales educativos.

## Según su arquitectura

- **Tradicional o monolítico:** el panel de administración y la parte visual de la web están integrados en un mismo sistema. El CMS gestiona el contenido y proporciona los mecanismos para mostrarlo. Algunos ejemplos son WordPress y Drupal en su configuración tradicional.

- **Headless:** el CMS se encarga de almacenar y gestionar el contenido, pero no necesita incluir la parte visual de la web. El contenido se entrega mediante una API a la aplicación que lo vaya a mostrar. Algunos ejemplos son Strapi, Contentful y Directus. Esta arquitectura permite utilizar el mismo contenido en una web, una aplicación móvil u otros dispositivos.

- **Desacoplado:** separa el backend, que gestiona los datos y el contenido, del frontend, que es la parte que ve y utiliza el usuario. Ambas partes pueden desarrollarse de forma independiente. Drupal, por ejemplo, puede utilizarse con una arquitectura desacoplada.

# Ranking de los CMS más utilizados

Según los datos de W3Techs, estos son cinco de los CMS con mayor cuota de mercado entre las páginas web que utilizan un CMS identificado.

| Posición | CMS | Cuota de mercado |
|---|---|---:|
| 1 | WordPress | 58,3 % |
| 2 | Shopify | 7,9 % |
| 3 | Wix | 6,2 % |
| 4 | Squarespace | 3,6 % |
| 5 | Joomla | 1,6 % |

**Fuente:** [W3Techs - Usage statistics of content management systems](https://w3techs.com/).

**Fecha de consulta:** 28 de octubre de 2026.

**Nota:** los porcentajes representan la cuota de cada plataforma entre los sitios web que utilizan un CMS identificado por W3Techs. No representan el porcentaje sobre el total de páginas web existentes. Estos datos pueden cambiar con el tiempo.

WordPress destaca por su amplia presencia en la web. Shopify está especialmente orientado al comercio electrónico, mientras que Wix y Squarespace facilitan la creación de páginas web. Joomla también es una alternativa para gestionar contenidos.

# CMS dinámico vs generador de sitios estáticos

Un CMS dinámico y un generador de sitios estáticos permiten crear páginas web, pero funcionan de forma diferente. En un CMS dinámico, el contenido puede procesarse cuando un usuario solicita una página. En un generador estático, las páginas se generan previamente durante el proceso de construcción o `build`.

| Aspecto | CMS dinámico | Generador estático |
|---|---|---|
| Forma de crear contenido | Normalmente, desde un panel de administración | Habitualmente, mediante archivos y plantillas |
| Base de datos | Suele utilizar una base de datos | No necesita una base de datos para servir los archivos generados |
| Generación de HTML | Puede generarse cuando el usuario solicita la página | Se genera durante el proceso de `build` |
| Servidor necesario | Necesita un entorno compatible con el CMS | Puede utilizar un servidor que sirva archivos estáticos |
| Panel de administración | Habitualmente, sí | Normalmente, no incluye uno propio |
| Conocimientos técnicos | La gestión básica puede ser sencilla para usuarios no técnicos | Puede requerir conocimientos de archivos, plantillas y herramientas de construcción |
| Seguridad | Requiere mantener actualizado el CMS, sus extensiones y el servidor | Reduce algunos riesgos al no necesitar ejecutar un CMS dinámico en cada petición |
| Rendimiento | Depende del procesamiento, la caché y la configuración | Puede ofrecer tiempos de respuesta rápidos al servir archivos ya generados |
| Actualización del contenido | Puede modificarse desde el panel de administración | Normalmente, hay que modificar el contenido y volver a generar y publicar la web |
| Ejemplos | WordPress, Drupal | Hugo, Jekyll |

Ninguna de las dos opciones es siempre mejor. Un CMS dinámico puede ser más práctico para una web con muchos usuarios que publican contenido desde un panel. Un generador estático puede resultar adecuado para una web de documentación o un blog que no necesita generar las páginas en cada petición.

## Ventajas de los CMS

- **Facilidad de uso:** permiten gestionar contenidos mediante una interfaz gráfica.
- **Trabajo en equipo:** pueden incluir usuarios, roles y permisos.
- **Personalización:** los temas y complementos permiten añadir diseños y funciones.
- **Gestión del contenido:** facilitan modificar y organizar páginas sin editar manualmente cada archivo HTML.

## Limitaciones de los CMS

- **Actualizaciones:** es necesario mantener el CMS, las extensiones y el entorno en el que funciona.
- **Seguridad:** los complementos vulnerables o las versiones desactualizadas pueden generar riesgos.
- **Rendimiento:** una instalación con muchos complementos o una configuración inadecuada puede ralentizar la web.
- **Migración:** cambiar de CMS puede requerir trasladar contenidos, diseños y funcionalidades.

[Vídeo explicativo sobre CMS](https://www.youtube.com/watch?v=sSh5AAmItN0)

[Volver al documento sobre SSG](ssg.md)





