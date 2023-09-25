# Proof of Concept Microfrontends Architecture

Este repo es una prueba de concepto, paso a paso, desde la creación de proyectos hasta la puesta en producción de una arquitectura de microfrontends. Cada paso de la POC está dividida en los branchs, se listan a continuación cada uno de los steps:

1. `initial_projects`: Inicialización de los proyectos para simular un entorno donde tengamos equipos desarrollando herramientas independientes sin ningún tipo de implementación de microfronts, desarrollados con frameworks y estructuras distintas, React: `/app-react`, Angularjs:`/app-angularjs`, Angular: `/app-angular` y Svelte: `/app-react`.

2. `adding_projects_exports`: Añadiendo la exportación de módulos a las aplicaciones.

3. `host_creation`: Creación de un orquestador que invoque las aplicaciones creadas.

4. `template_new_mf_module`: Templates para nuevas aplicaciones.

5. `adding_complexity`: Añadido de complejidad en ciertas apps. Agregado de Comunicación bidireccional.

6. `auth_module`: Creación de módulo de autenticación para el proyecto

7. `auth_in_host`: Añadidas rutas privadas y autenticación en el proyecto host

8. `main`: Resultado
