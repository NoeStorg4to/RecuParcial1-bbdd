# RecuParcial1-bbdd

Crear una base de datos llamada libreria con una colección de libros especiales que tenga los siguientes datos:
1. Crea una base de datos llamada libreria.
2. Dentro de esta base de datos, crea una colección llamada librosEspeciales.
3. Inserta documentos con la siguiente estructura:
 título (string)
 genero (aventura, ciencia ficcion, romance, terror, etc.)
 array de autores (nombre completo de los autores)
 numero de paginas (entero)
 nivel de lectura (infantil, juvenil, adulto)
 array de objetos de precio:
o tipo: físico, precio: 3500
o tipo: digital, precio: 2500
 disponible en stock (booleano)
 objeto editorial:
o nombre (string)
o pais (string)
o anioFundacion (entero)
Cargar 10 libros especiales.
Los datos a cargar en cada entidad deben ser útiles a las consultas que se detallan a continuación.
Objetivos de Aprobación No Directa (Calificación de 4 a 5 puntos):
1) Crear el script .js con la creación de la base de datos y las colecciones.
2) Buscar cuántos libros tienen a "Carlos Gómez" entre sus autores
3) Buscar cuántos libros son de género "romance" y tienen "Lucía Herrera" entre los autores.
4) Listar el título y número de páginas de los libros con nivel de lectura "juvenil".
5) Obtener título, número de páginas y nivel de lectura de los libros que tengan entre 200 y 400
páginas (inclusive).
