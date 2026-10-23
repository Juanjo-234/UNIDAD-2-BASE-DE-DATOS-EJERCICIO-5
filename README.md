# UNIDAD-2-BASE-DE-DATOS-EJERCICIO-5
Se debe diseñar un modelo entidad-relación (MER) para representar el funcionamiento de un sistema académico de una facultad, organizando la información de las carreras, materias, profesores, alumnos e inscripciones.

El sistema debe permitir registrar:
- Carreras: código, nombre y plan de estudio vigente.
- Planes de estudio: organizan las asignaturas que corresponden a cada carrera.
- Asignaturas: código, nombre, carga horaria semanal y año dentro de la carrera.
- Correlatividades: materias que deben aprobarse previamente para poder cursar otras.
- Profesores: datos de los docentes responsables de las comisiones.
- Comisiones: materia que se dicta, cupo máximo de alumnos y ciclo lectivo correspondiente.
- Ciclo lectivo: período académico en el que se dicta una comisión.
- Alumnos: datos de los estudiantes que se inscriben.
- Inscripciones: relacionan a los alumnos con las comisiones e incluyen la condición final (Regular, Libre o Promocionado) y las notas de los exámenes parciales.
También se deben establecer las relaciones y cardinalidades entre las entidades, incluyendo la relación recursiva de las correlatividades y la relación muchos a muchos entre alumnos y comisiones.
<img width="2632" height="1572" alt="EJERCICIO 5 drawio" src="https://github.com/user-attachments/assets/aa6c0fdf-1333-4a79-b066-d3f0657571d8" />

