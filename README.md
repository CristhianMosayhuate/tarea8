Ejercicios 1 y 2 que se dejaron en clase, siguiendo las bases de web 7 y 8 y clases de la semana pasada.
Ejercicio 01: Buscador de Personajes de Star Wars
Funcionalidad: Permite ingresar un código numérico (ID) para consultar la información de un personaje.
Datos mostrados: Nombre, estatura, peso, color de cabello y género en un formulario interactivo.
Tabla de Participaciones: Muestra una tabla con tres columnas (Películas, Vehículos y Naves) calculando de forma dinámica la cantidad de elementos mediante la propiedad .length.
Validaciones: Valida que el ID ingresado sea un número válido, gestiona errores de tipo 404 (personaje no encontrado) e incorpora un indicador visual de carga (Loader).

Ejercicio 02: Buscador de Planetas y Residentes
Funcionalidad: Permite ingresar el ID de un planeta para extraer su información geo-demográfica.
Datos mostrados (Lista 1): Nombre, periodo de rotación, diámetro, gravedad, tipo de terreno y cantidad de habitantes dentro de una lista no ordenada (<ul>).
Listado de Residentes (Lista 2): Realiza un segundo consumo de API de forma iterativa (for...of) utilizando las URLs provistas por el JSON del planeta para traducir y listar los nombres reales de los personajes que lo habitan.
Validaciones: Manejo de estados de carga, validación de IDs numéricos y ocultamiento dinámico de los resultados hasta completar la petición.


Tecnologías Utilizadas:
HTML5 (Estructura semántica de formularios, tablas y listas)
CSS3 (Diseño adaptativo, Flexbox y animaciones de carga)
JavaScript (ES6+) (async/await, fetch API, manipulación del DOM, eventos)
API Externa: Star Wars API (SWAPI)

