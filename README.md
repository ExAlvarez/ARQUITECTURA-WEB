# ARQUITECTURA-WEB
Trabajo Practico de Arquitectura Web (Segundo Cuatrimestre 2025)

API DE BIBLIOTECA

DESCRIPCIÓN  

  Permite gestionar un catálogo de libros. Se pueden consultar todos los libros disponibles, ver los detalles de un libro en particular, agregar nuevos, actualizarlos y eliminarlos.

ENDPOINTS

- GET /libros
  Devuelve la lista de todos los libros.

- GET /libros/{id}
  Devuelve los detalles de un libro específico según su ID.

- POST /libros
  Permite agregar un nuevo libro enviando sus datos (título, autor, año, género, disponibilidad).

- PUT /libros/{id}
  Actualiza los datos de un libro existente según su ID.

- DELETE /libros/{id}
  Elimina un libro del catálogo según su ID.
