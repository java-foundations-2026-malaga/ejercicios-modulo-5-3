# JFo 5.3 - Actividad 06

## Convierte un if/else de cursos a switch

Usa un `switch` sobre `grade` para mostrar: 9 → `Es alumno de primer año`; 10 → `Es alumno de segundo año`; 11 → `Es alumno de tercer año`; 12 → `Es alumno de cuarto año`; cualquier otro valor → `No es alumno de secundaria`.

## Objetivo

- Leer el código base y corregirlo o completarlo.
- Ejecutar el programa y comprobar el resultado.
- Ejecutar los tests JUnit para confirmar la autocorrección.
- Hacer `git add`, `git commit` y `git push`.

## Salida esperada

```text
Es alumno de tercer año
```

## Instrucciones para Eclipse

1. Importa este proyecto como proyecto Maven.
2. Abre `src/main/java/modulo5_3_actividad06/Actividad06.java`.
3. Corrige o completa el código.
4. Ejecuta `Run As > Java Application`.
5. Ejecuta `Actividad06Test.java` con `Run As > JUnit Test`.
6. Haz commit y push cuando la actividad funcione.

## GitHub Actions

- Sube tu trabajo a **tu rama** (no a `main`): el workflow `Autocorrección` compila y ejecuta los tests de cada actividad que hayas modificado.
- En la pestaña **Actions** del repositorio verás ✅ si la actividad está aprobada o ❌ si hay errores de compilación o tests que fallan.
