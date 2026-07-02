# Ej.---Students-Classrooms-Courses

## Descripción del ejercicio
Este ejercicio consiste en normalizar una tabla de datos sin estructurar que relaciona estudiantes, aulas y cursos de un bootcamp. A partir de una tabla original con grupos repetitivos y dependencias transitivas, se ha aplicado el proceso de normalización (1FN, 2FN y 3FN) hasta obtener 4 tablas independientes: `Estudiante`, `Aula`, `Curso` y `Aula_Curso` (tabla puente para la relación muchos a muchos entre aulas y cursos).

Además de la normalización, se han diseñado dos diagramas de la base de datos resultante:
- Un diagrama entidad-relación en notación de Chen.
- Un diagrama de base de datos en notación UML "patas de gallo" (crow's foot), con las tablas, campos y relaciones.

## Normalización de la base de datos
Las tablas normalizadas (Estudiante, Aula, Curso, Aula_Curso) con los datos reales están disponibles aquí:
👉 [Ver Google Sheets](https://docs.google.com/spreadsheets/d/14i4glWBA4o_msboFtn__pglV3td1lV2RcXYbcZ4BmwM/edit?usp=sharing)

## Diagrama entidad-relación (Chen)
![Diagrama ER de Chen](./assets/diagrama-chen.png)

## Diagrama de base de datos (patas de gallo / UML)
![Diagrama patas de gallo](./assets/diagrama-patas-de-gallo.png)