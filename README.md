# Proyecto Biblioteca. Desarrollo de API y frontend

## Conformado por dos módulos

**Spring boot con base de datos H2**

CRUD completo de todos los objetos

**Spring boot con angular.**

Los listados deben ser tablas paginadas y ordenables por columna

Pantalla de listado de libros 
(filtrable por cada una de las columnas) Columnas [ISBN, Nombre, descripcion, tipo de libro,  Disponible, autor, idioma]

Pantalla formulario de alta de libro

Pantalla de listado de usuarios
(filtrable por cada una de las columnas) Columnas [Nombre, descripcion, tipo de libro, ISBN, Disponible, autor, idioma]

Pantalla formulario de alta de usuario

Pantalla formulario de alta de autores
		
**Objetos/Tablas:**

Libro (Nombre, descripcion, tipo de libro, ISBN, fecha de alquiler, autor, idioma, persona que lo alquila) (Si no tiene fecha no está alquilado) PK ISBN

Autores (DNI, Nombre, apellidos, lengua materna) PK DNI

Usuarios de la biblioteca (DNI, nombre, apellidos, fecha de inscripcion, telefono, email) PK DNI

Tipo de libro [DATOS MAESTROS] Novela negra, Avenvtura, Ciencia y Novela Historica

Se deberán validar que los datos son correctos (nombre letras, dni formato correcto, email, telefono...)

**Test**

Se deben hacer tests que sean "funcionales" y que cubran, al menos, el 75% de las lineas de la lógica de la aplicación

## Dudas

Para cualquier duda o pregunta, contacta con el team leader con el que haces las reuniones diarias o, en su defecto, la persona que te hayan asignado como responsable.