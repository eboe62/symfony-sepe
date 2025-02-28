# CURSO SYMFONY 5

## Introducción

- [Instalación](./instalacion.md)
- [Estructura de un proyecto symfony](./estructura_directorios.md)
- [Patrón MVC](./mvc.md)
- [Novedades PHP 7.4 y PHP 8.0](./novedades_PHP.md)

## Creación de la página de Home y menú público

- [Introducción a Controllers](./controllers_intro.md)
- [Introducción al Routing](./routing_intro.md)

### Ejercicio empezando con routing

Creación de 3 rutas:
  
- /home
- /login
- /about-us

Cada una de estas rutas debe estar asociadas a una acción y responder con un h1 básico.

## Creación de vistas (Twig)

- [Introducción a Twig](./twig_intro.md)

### Ejercicio empezando con twig

Crear 1 plantilla de Twig para cada una de las páginas del ejercicio anterior.

Enlazar las páginas con un menú.

Inluir algún fichero de css en las páginas (o algún framework como bootstrap, foundation,  tailwind...)

## Introducción al profiler y a los entornos

## La consola de comandos

- El comando make:controller

### Ejercicio

- Usar make:controller para crear un nuevo controlador que tenga la ruta /catalogo

- Enlazar esta nueva página al menú

## Twig

- Variables. Acceso a atributos con (.)
- Variables globales
- Estructuras de control (if, for…)
- Comentarios
- Operadores
- set


https://twig.symfony.com/doc/3.x/templates.html

### Ejercicio Twig 1

- En la página /catálogo, mostrar la lista de fondos del catálogo de la biblioteca.

## Más Twig

- filtros
- funciones
- Named arguments
- include
- extends y block

### Ejemplo

Crear una nueva página de ejemplo de herencia de plantillas.

### Ejercicio Twig 2

Usar la herencia de plantillas con las páginas actuales de la aplicación.

## Debug

- Debug en controladores/servicios
- Debug en Twig

## Acceso a base de datos. Doctrine.

- Entidades simples. Creación con Maker Bundle.
- Entity Manager
- Repository
- Entidades relacionadas

### Ejercicios

- Crear entidades Fondo, Autor, Editorial y Categoría relacionándolas entre ellas.

- Crear datos en la base de datos y mostrar el listado de catálogo.

- Inspeccionar las consultas en el profiler.

## Más doctrine

- DQL y Query Builder
- Native SQL
- Ingeniería inversa
- ArrayCollection
- El problema de las N+1 queries

### Ejercicio Doctrine Problema N+1

Arreglar el problema de las N+1 queries en el listado del catálogo.

## Instalación de Bundles

- Fixtures (Sin bundle y con NelmioAliceBundle)

## Controladores

- El objeto Response
- El objeto Request
- Errores & excepciones
- Páginas de error
- Session
- Mensajes Flash
- CORS
- Redirecting and Forwarding

## Routing avanzado

## Ejercicio routing avanzado

- Creación de página para mostrar ficha de un fondo

## Servicios

- El contenedor de servicios y la inyección de dependencias
- Parameters
- Configuración avanzada de servicios
- Entornos y variables de entorno.
- Archivos de configuración de symfony.

## El componente Security

- Autenticación
- Autorización. Roles.
- Voters
- El bundle FOSUserBundle

## Caché

## Logs

- Cómo logear mensajes en diferentes ubicaciones
- Manejadores de logs nativos
- Cómo rotar los ficheros de log
- Cómo utilizar un blog en un servicio
- Añadir datos extra a los mensajes de log

## La consola de symfony

- Comandos predefinidos.
- Creación de comandos de consola personalizados.

## Ajax

## Creación de APIs REST con Symfony

- JsonResponse
- LexitJwtBundle

## El serializer de symfony

- Cómo manejar referencias circulares
- Cómo manejar la profundidad de la serialización
- Normalizers
- Encoders
- Cómo configurar qué atributos se serializan
- Cómo convertir nombres de propiedades al serializar y des-serializar 

## Twig Avanzado

- Cómo generar otros formatos de salida (css, javascript, xml…)
- Cómo inyectar variables globales
- Sobreescribir plantillas de bundles de terceros
- Crear plantillas sin controladores
- Cómo crear una extensión de twig

## Depuración en Symfony. El profiler

- Cómo crear un Data Collector personalizado
- Cómo acceder a los datos del profiler programáticamente
- Cómo utilizar Matchers para activar o desactivar el profiler programáticamente
- Cómo cambiar la ubicación del Profiler Storage

## Proyecto Final

Programación de un proyecto a elección del alumno.

