- [Luego Del deployment](#una-vez-hecho-el-deployment)

## Una vez hecho el Deployment

Debemos revisar nuestro sitio constantemente para realizar mejoras de seguridad, performance, diseño o introducir nuevas funciones.
Muchos clientes se equivocan al pensar que si hemos terminado su sitio web entonces ya no hay nada más por hacer.
Para añadir nuevas funciones, revisa los 7 pasos, estos se deben repetir siempre.

Añade `Analytics` entre los mas comunes se encuentra `Google Analytics` o `Fathom` que es gratis. Podemos saber que pagina es la siguiente, de donde son, y donde pasan mas tiempo los usuarios.

### Otras consideraciones de mejora

PHP, Node.js, Python, C#, Ruby, Java son lenguajes que pueden soportar miles de usuarios al mismo tiempo.

- Cuanto tienes miles o millones de usuarios tu problema no será el lenguaje de programación, sino la base de datos y el servidor.
- Existe una serie de instrucciones que deberá seguir tu proyecto en caso de que comience a tener miles o millones de visitas

### Consideraciones si tu sitio tiene miles o millones de visitas

- Hospedar la base de datos en un servidor aparte (tendras 2 servidores, uno con el código y otro con la BD)
- Cachear el contenido, esto quiere decir que en lugar de consultar la base de datos en cada vista, creamos una version HTML y cada que hay cambios se regenera este HTML.
- Hospedar impágenes y archivos similares en otro servidor como puede ser un CDN
- Hospedar el sitio web en diferentes servidores.
