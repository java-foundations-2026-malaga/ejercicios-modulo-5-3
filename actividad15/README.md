# JFo 5.3 - Actividad 15

## Demostrador controlado de fall through

Usa un `switch` sobre `level` **sin** `break` entre los casos, de modo que cada nivel recibe su recompensa y las de todos los niveles superiores: `case 1` imprime `Recompensa nivel 1`, `case 2` imprime `Recompensa nivel 2` y `case 3` imprime `Recompensa nivel 3`. Con `level = 2` deben aparecer las recompensas 2 y 3.

## Objetivo

- Leer el código base y corregirlo o completarlo.
- Ejecutar el programa y comprobar el resultado.
- Ejecutar los tests JUnit para confirmar la autocorrección.
- Hacer `git add`, `git commit` y `git push`.

## Salida esperada

```text
Recompensa nivel 2
Recompensa nivel 3
```

## Instrucciones para Eclipse

1. Importa este proyecto como proyecto Maven.
2. Abre `src/main/java/modulo5_3_actividad15/Actividad15.java`.
3. Corrige o completa el código.
4. Ejecuta `Run As > Java Application`.
5. Ejecuta `Actividad15Test.java` con `Run As > JUnit Test`.
6. Haz commit y push cuando la actividad funcione.

## GitHub Actions

- Sube tu trabajo a **tu rama** (no a `main`): el workflow `Autocorrección` compila y ejecuta los tests de cada actividad que hayas modificado.
- En la pestaña **Actions** del repositorio verás ✅ si la actividad está aprobada o ❌ si hay errores de compilación o tests que fallan.
