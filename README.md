# JFo 5.3 - Sentencia switch

Esta carpeta contiene 15 actividades autocorregibles.

## Actividades

01. Corrige un switch sin llaves
02. Corrige case mal escritos
03. Corrige un switch sin break accidental
04. Corrige un default mal escrito
05. Corrige un switch usado para rangos
06. Convierte un if/else de cursos a switch
07. Nombre del mes
08. Días de la semana con String
09. Contador por opción char
10. Número de días de un mes
11. Menú de calculadora básica
12. Clasificador de notas por letra
13. Simulador de semáforo
14. Agrupación de niveles de usuario
15. Demostrador controlado de fall through

Cada subcarpeta `actividadNN` es un proyecto Maven independiente con tests JUnit 5 y workflow de GitHub Actions.

## Cómo entregar las actividades

La rama `main` está protegida: contiene los enunciados originales y no se puede modificar.
Cada alumno trabaja en **su propia rama**, con su nombre.

1. Clona el repositorio:
   `git clone https://github.com/java-foundations-2026-malaga/REPOSITORIO.git`
2. Crea tu rama con tu nombre y apellido, en minúsculas y sin tildes ni espacios (por ejemplo `juan-perez`):
   `git checkout -b juan-perez`
   (En Eclipse: botón derecho sobre el proyecto > `Team > Switch To > New Branch...`).
3. Importa en Eclipse la carpeta `actividadNN` que vayas a hacer (`File > Import... > Maven > Existing Maven Projects`), resuélvela y comprueba los tests con `Run As > JUnit Test`.
4. Haz commit y sube **tu rama**:
   `git add .` → `git commit -m "Actividad NN"` → `git push -u origin juan-perez`
   (En Eclipse: `Git Staging` > `Commit and Push...`).
5. En la pestaña **Actions** del repositorio verás el resultado de la autocorrección de cada actividad que hayas modificado: ✅ aprobada o ❌ con los errores.

Si al hacer push te aparece un error sobre `main`, es que estás en la rama equivocada: cambia a tu rama con `git checkout juan-perez`.
