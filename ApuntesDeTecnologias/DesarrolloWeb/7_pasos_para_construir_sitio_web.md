Contenido`

1. [Pre-proceso](#1-pre-proceso)
   - [Algunos Roles](#algunos-roles)
2. [Estrategia de contenido](#2-estrategia-de-contenido)
   - [Modelado de contenido](#modelado-de-contenido)
   - [Arquitectura de la información](#arquitectura-de-la-información)
3. [Etapa de Pre-construcción](#3-etapa-de-pre-construcción)
4. [Etapa de construcción](#4-etapa-de-construcción)
5. [Pruebas y revisión](#5-pruebas-y-revisión)
6. [Etapa de optimización](#6-etapa-de-optimización)
7. [Lanzamiento](#7-lanzamiento)

# 1 Pre proceso

Quien estará a cargo de que parte del proyecto.

- El cliente es parte del proyecto
- El cliente comparte su visión y el equipo la lleva a cabo.

## Algunos roles:

- Creador de contenido.
- Arquitectura de la información.
- Pruebas.
- Diseño Grafico.
- Diseñador UI y UX.
- Front End.
- Back End.
- Supervisor de Testing.

# 2 Estrategia de contenido

Planeación, desarrollo y administración de una pagina web.

Con la planeación adecuada tendrás un panorama más claro del proyecto.

Aquí se definen planes de contenido, aun no se ven colores o tecnologías a utilizar.

Es importante porque:

- En esta etapa definimos que es lo más importante para nuestros visitantes.
- Definimos a quienes queremos llegar y quienes son.
- En esta etapa auditamos imágenes, videos, textos, como se relaciona el contenido uno con otro.
- Al finalizar diseño ya sabe con que cuenta.

Otras tareas de esta etapa:

### Modelado de contenido:

Una vez que sabemos que contenido hay listo podemos modelarlo. Por ejemplo **Crearemos un sitio web para una empresa de bienes raíces, por lo tanto requerimos una sección de información, contacto, anuncios**.
Los anuncios tendrán un titulo, precio, descripción, imagen, etc. Es importante “modelar” como deberá mostrarse ese contenido.

- Jerarquía:
  Nos ayuda a definir:
  - Que paginas son las más importantes o principales.
  - Que paginas son soporte a otras páginas.
  - Que páginas complementan el contenido existente.

### Arquitectura de la información.

Es el como se organizan los diferentes componentes del sitio web y como los usuarios navegarán por las diferentes secciones a fin de interactuar en el. **Como se relaciona la información con otra**.

- Wireframing:
  Piensa en un wireframe como un plano de un sitio web.
  Solo va a mostrar como debe verse sin definir aún los colores, fuentes, imágenes, solo donde se ubicarán los elementos
  Podemos realizar anotaciones, comentarios etc.
  Nos ayudará para ver como interactúan los diferentes elementos.
  - `Se puede hacer en un programa o papel`.

# 3 Etapa de Pre-construcción

En esta etapa se realiza una serie de Wireframes y se va definiendo de que sección a que sección será la navegación del sitio web.

También podremos identificar que necesitamos (imágenes, videos, logos y que secciones tendrá que diseñar UX).

Finalmente en esta etapa definimos como será posible ir visitando las otras secciones internas.

# 4 Etapa de construcción

En esta etapa se comienza a crear el sitio web o aplicación.

También se trabaja sobre un diseño, además que tanto Front End como backend comienzan a trabajar

    ‼️ Evitar que diseño termine para que empiece front, evitar que front termine para que empiece back, En realidad las diferentes etapas deben empezar y terminar al mismo tiempo.

# 5 Pruebas y revisión

En esta etapa probamos que todo funcione correctamente en el proyecto, debemos revisar que todos los enlaces funcionen correctamente y que al visitar ciertas páginas la información mostrada sea la correcta y la esperada.

También probamos que no haya enlaces rotos y que se muestren imágenes correctamente

Es importante porque:

- Encontrar errores antes de lanzar el proyecto a producción evita quejas de clientes y usuarios.
- Muchas veces cuando se desarrolla el proyecto se van creando ciertas secciones, y conforme se van creando se prueba que haga lo que se espera.
- El problema es que cuando añades tantas funciones nuevas, usualmente no hay tiempo de volver a probar lo que se hizo al inicio.

## Tipos de pruebas

- `End To End`: Se comporta como usuario, da clicks y llena formularios
- `Integración`: Revisar que varias partes de la aplicación funcionan bien juntas.
- `Unitarias`: Que una parte sola funciona bien.
- `Static`: Identificar errores mientras los vas escribiendo (tipado)

`Como se realiza el Testing?`

- Probando formularios, clicks y revisar cada parte del sitio web
- Existen herramientas que automatizan las pruebas que realizas a tu sitio web como Cypress.
- Cypress te permite crear pruebas End To End, es lo mas cercano al mundo real y te permite crear pruebas para asegurarte que todos los componentes de tu proyecto funcionan bien juntos.

`¿Porque Cypress?`

- Las pruebas se realizan en js
- funciona sobre el HTML y este html viene de cualquier lenguaje de programación

# 6 Etapa de optimización

Se hace una auditoria para saber si el contenido que tiene el sitio web es importante para los usuarios o sin hizo falta añadir algo mas.

Ajustes al diseño como pueden ser mover imágenes, diseño de botones o revisar que el sitio sea responsive.

Desarrollo deberá revisar que no se estén consumiendo recursos adicionales o si no hay “perdidas” en memoria en el Servidor.

# 7 Lanzamiento

Para HTML, CSS y JavaScript va bien netlify.

Pero un sitio web con una base de datos y un lenguaje de programación va a requerir tener base de datos y el lenguaje de programación instalado, usualmente no son gratis.

Hostinger que Soportan PHP y MYSQL

- Vercel
- AWS
- Azure
- BlueHost
- VPS donde tú instalas todo
- etc etc.
a