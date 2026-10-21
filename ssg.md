# Generadores de sitios estáticos

## ¿Qué es un SSG?

Un generador de sitios estáticos, por sus siglas SSG, es un software que se encarga de generar automáticamente las páginas HTML de una página web teniendo como referencia unos archivos y plantillas ya definidas.

La característica principal de estos sitios web es que las páginas vienen prefabricadas antes siquiera de que un usuario haya hecho la petición para acceder a ellas. Así, cuando alguien haga una petición, el servidor puede entregar directamente la página ya montada, sin tener que generar todo desde cero.

El generador puede utilizar diferentes archivos como contenido en Markdown, plantillas, archivos de configuración, hojas de estilos, JavaScript o imágenes. Todos estos elementos se procesan durante el proceso de construcción para generar los archivos que formarán nuestra página web estática.

## Comparación entre Jekyll, Hugo y Astro

| Aspecto | Jekyll | Hugo | Astro |
|---|---|---|---|
| Tecnología principal | Ruby | Go | JavaScript |
| Formato utilizado | Markdown/HTML y plantillas Liquid | Markdown y plantillas Go | Componentes `.astro` y Markdown |
| Funcionamiento | Convierte contenido y plantillas en páginas estáticas | Convierte contenido y plantillas en una web estática | Genera páginas HTML durante el proceso de construcción |
| Ventaja principal | Configuración sencilla | Muy rápido y escalable | Muy enfocado en rendimiento |
| Inconveniente | Depende de Ruby y herramientas asociadas | Las plantillas Go pueden resultar tediosas | Requiere Node.js y entorno JavaScript |
| GitHub Pages | Sí, tiene soporte integrado | Sí | Sí, mediante GitHub Actions |

[Vídeo explicativo sobre generadores de sitios estáticos](https://www.youtube.com/watch?v=osWfEtbP_sk)

[Ir al documento sobre CMS](cms.md)

