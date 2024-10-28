# CRUD

Descripcion funcionalidades CRUD (Crear, Leer, Actualizar, Eliminar) utilizando una base de datos SQL.

Funcionalidades

1. Crear (Create)
   Descripción**: Permite a los usuarios crear nuevos registros en la base de datos.
   Método SQL: INSERT INTO
   Ejemplo de uso:
   INSERT INTO registros (nombre, edad) VALUES ('Ejemplo', 30);
  
2. Leer (Read)
   Descripción: Permite a los usuarios obtener registros existentes.
   Método SQL: SELECT * FROM "tabla" WHERE id = id;

   Ejemplo de uso:
   SELECT * FROM registros WHERE id = 1;

3. Actualizar (Update)
   Descripción: Permite a los usuarios actualizar un registro existente.
   Método SQL: UPDATE
   Ejemplo de uso:
   UPDATE registros SET nombre = 'Ejemplo Actualizado', edad = 31 WHERE id = 1;

4. Eliminar (Delete)
   Descripción: Permite a los usuarios eliminar un registro existente.
   Método SQL: DELETE

   Ejemplo de uso:
   DELETE FROM registros WHERE id = 1;
