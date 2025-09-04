
# Temario-de-App-Web

#Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.

<img width="231" height="167" alt="image" src="https://github.com/user-attachments/assets/eb69f95a-37a7-49df-b2ef-b6632afbb21c" />

1. Introducción al desarrollo web  
   Historia y evolución del desarrollo web  
   _La web comenzó como un sistema de documentos enlazados (HTML estático) y evolucionó hacia aplicaciones interactivas gracias a tecnologías como JavaScript, AJAX y frameworks modernos. La web actual permite experiencia de usuario rica, acceso móvil y aplicaciones complejas._

<img width="279" height="158" alt="image" src="https://github.com/user-attachments/assets/791bb770-af95-413f-961c-00260e2885fd" />    


   Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)  
   _Estáticas: solo HTML/CSS, sin interacción dinámica._  
   _Dinámicas: generan contenido en el servidor (PHP, Node.js)._  
   _SPA (Single Page Application): cargan una sola página y actualizan contenido dinámicamente (React, Angular)._  
   _PWA (Progressive Web App): aplicaciones web que funcionan offline y pueden instalarse como apps móviles._

2. Arquitectura de aplicaciones web  
   Cliente-Servidor  
   _El cliente (navegador) solicita recursos y el servidor los responde; ambos se comunican mediante HTTP/S._  
   Arquitectura de tres capas (presentación, lógica, datos)  
   _Separación en capa de presentación (UI), lógica de negocio (backend) y datos (base de datos)._  
   REST y API-first design  
   _REST define reglas para construir APIs que usan HTTP para operar recursos (GET, POST, PUT, DELETE). El API-first design prioriza la creación de la API antes que el frontend o backend._

3. Arquitectura de aplicaciones web  
   Cliente-Servidor  
   _El cliente (navegador) solicita recursos y el servidor los responde; ambos se comunican mediante HTTP/S._  
   Arquitectura de tres capas (presentación, lógica, datos)  
   _Separación en capa de presentación (UI), lógica de negocio (backend) y datos (base de datos)._  
   REST y API-first design  
   _REST define reglas para construir APIs que usan HTTP para operar recursos (GET, POST, PUT, DELETE). El API-first design prioriza la creación de la API antes que el frontend o backend._

<img width="315" height="173" alt="image" src="https://github.com/user-attachments/assets/69c62ba2-e5c7-4343-b34d-1c23369fda8d" />

   

5. Lenguajes y tecnologías fundamentales  
   HTML, CSS, JavaScript, PHP, MySQL  
   _HTML estructura la web, CSS la diseña visualmente, JavaScript añade interactividad. PHP es lenguaje de backend y MySQL sistema de gestión de bases de datos relacionales._

<img width="294" height="167" alt="image" src="https://github.com/user-attachments/assets/30677523-1362-4627-bf83-6640ef1ba6d9" />

   

7. Control de versiones  
   Git y GitHub  
   _Git permite gestionar versiones del código; GitHub es una plataforma para alojar repositorios y colaborar._  
   Flujo de trabajo con ramas (branching, merge, pull requests)  
   _El branching permite desarrollar nuevas funciones sin afectar el código principal; los cambios se integran mediante merge y pull requests para revisión._

---

Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web

1. Diseño e implementación del frontend  
   Maquetación/Wireframe/Mockup  
   _Wireframes y mockups son esquemas visuales de la interfaz; la maquetación convierte estos diseños en código (HTML/CSS)._  
   API  
   _El frontend consume APIs para mostrar o enviar datos, normalmente usando fetch o AJAX._

2. Diseño e implementación del backend  
   Servidor  
   _El backend es el programa que responde a las solicitudes del cliente, generalmente ejecutándose en un servidor._  
   Manejo de peticiones y respuestas HTTP  
   _Recibe solicitudes (requests), procesa datos y devuelve respuestas (responses) usando protocolos HTTP._  
   Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)  
   _El backend consulta y actualiza la información en sistemas de bases de datos relacionales (MySQL, PostgreSQL) o NoSQL (MongoDB)._

3. Bases de datos  
   Modelado de datos y relaciones  
   _Se diseñan tablas y relaciones (uno a uno, uno a muchos, muchos a muchos) según las necesidades de la app._  
   ORM (Object Relational Mapping)  
   _ORMs permiten manipular datos de la base desde código orientado a objetos, facilitando el trabajo con bases de datos._  
   CRUD desde el backend  
   _El backend implementa operaciones CRUD: Crear, Leer, Actualizar y Borrar registros en la base de datos._

4. Seguridad básica en aplicaciones web  
   Validación de formularios  
   _Evita que los usuarios envíen datos incorrectos, incompletos o maliciosos._  
   Autenticación y autorización  
   _La autenticación verifica la identidad del usuario; la autorización controla qué acciones puede realizar cada usuario._

---

Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional

1. Integración de frontend y backend  
   - Conectar la interfaz de usuario (frontend) con el backend utilizando APIs.  
     _El frontend utiliza HTTP (fetch/AJAX) para enviar y recibir datos del backend._  
   - Manejar correctamente las solicitudes (requests) y respuestas (responses) entre el cliente y el servidor.  
     _El backend procesa solicitudes y responde con datos o mensajes de éxito/error._  
   - Ejemplo: El frontend realiza una petición HTTP (fetch/AJAX) para obtener o enviar datos al backend, y este responde con los datos solicitados o el resultado de la operación.  
     _Por ejemplo, al enviar un formulario de registro, el frontend manda los datos al backend, que guarda la información y responde si fue exitoso._

2. Almacenamiento en servidor  
   - Conocer los diferentes tipos de servidores (dedicados, compartidos, cloud, VPS, etc.).  
     _Dedicados: hardware exclusivo, caro y potente._  
     _Compartidos: varios sitios comparten un mismo servidor (más económico)._  
     _VPS: servidor virtual privado, ofrece mayor control._  
     _Cloud: servidores bajo demanda en la nube (AWS, Azure)._  
   - Entender cómo funcionan los servicios de hosting web para alojar aplicaciones.  
     _El hosting provee el espacio y recursos para que la aplicación esté disponible en internet._  
   - Identificar algunos proveedores populares de servicios de almacenamiento y hosting (como Heroku, Vercel, Netlify, AWS, Azure, Google Cloud).  
     _Heroku, Vercel y Netlify simplifican el despliegue de apps; AWS, Azure y Google Cloud ofrecen soluciones completas para grandes proyectos._

3. Optimización y rendimiento  
   - Optimizar recursos como imágenes y scripts para acelerar la carga de la aplicación.  
     _Reducir tamaño de imágenes, minificar archivos JS/CSS, usar formatos modernos como WebP._  
   - Implementar técnicas para mejorar el rendimiento, como la minificación de archivos o el uso de cachés.  
     _Minificar elimina espacios y comentarios innecesarios; las cachés almacenan información para responder más rápido._  
   - Desplegar la aplicación web en un entorno real (producción).  
     _El despliegue consiste en subir la app a un servidor para que sea accesible públicamente._  
   - Introducción al uso de pipelines de integración y despliegue continuo (CI/CD) para automatizar las pruebas y el despliegue.  
     _CI/CD automatiza pruebas y despliegue tras cada cambio en el código, reduciendo errores._  
   - Documentar correctamente el proyecto para facilitar su mantenimiento y colaboración futura.  
     _Una buena documentación explica cómo instalar, usar y contribuir al proyecto._

---

Resumen:  
- El aprendizaje 3 se centra en llevar una aplicación web desde el desarrollo local hasta su funcionamiento real en internet, asegurando su integración, almacenamiento, optimización y disponibilidad.
