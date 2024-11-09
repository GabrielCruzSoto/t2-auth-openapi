# t2authopenapi

t2authopenapi es un proyecto que proporciona una API para la creación y autenticación de usuarios. El proyecto utiliza OpenAPI para definir la interfaz de la API y Spring Boot para implementarla.

## Documentación de la API

La documentación de la API se encuentra en el archivo `src/openapi.yaml`. Esta documentación describe los endpoints disponibles, los parámetros de entrada y salida, y los códigos de estado HTTP esperados.

## Configuración de GitHub

El archivo `settings.xml` contiene la configuración para la autenticación en GitHub Packages. Esto permite al proyecto publicar artefactos en el registro de Maven de GitHub.

## Generación de JAR

El archivo `github/workflows/generate_jar-from_openapi.yml` es un flujo de trabajo de GitHub Actions que se encarga de generar un JAR del proyecto a partir de la definición de OpenAPI. Este flujo de trabajo se activa automáticamente cuando se hace un push o un pull request a la rama master, o cuando se lanza manualmente.

## Uso

Para utilizar este proyecto, simplemente clone el repositorio y ejecute el flujo de trabajo `generate_jar-from_openapi.yml`. Esto generará un JAR que puede ser utilizado en otros proyectos.

## Contribución

Si deseas contribuir a este proyecto, por favor, crea un pull request con tus cambios. Asegúrate de que los cambios sean compatibles con la versión de OpenAPI y Spring Boot utilizadas en este proyecto.

## Licencia

Este proyecto está bajo una licencia de código abierto. Consulta el archivo de licencia para más información.

