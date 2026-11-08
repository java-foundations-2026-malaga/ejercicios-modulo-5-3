# JFo 5.3 - Actividad 10

## Número de días de un mes

Usa un `switch` sobre `month` agrupando casos: febrero (2) tiene `28 días`; abril, junio, septiembre y noviembre (4, 6, 9, 11) tienen `30 días`; el resto de meses (1, 3, 5, 7, 8, 10, 12) tienen `31 días`. Para cualquier otro valor imprime `Mes no válido`.

## Objetivo

- Leer el código base y corregirlo o completarlo.
- Ejecutar el programa y comprobar el resultado.
- Ejecutar los tests JUnit para confirmar la autocorrección.
- Hacer `git add`, `git commit` y `git push`.

## Salida esperada

```text
30 días
```

## Instrucciones para Eclipse

1. Importa este proyecto como proyecto Maven.
2. Abre `src/main/java/modulo5_3_actividad10/Actividad10.java`.
3. Corrige o completa el código.
4. Ejecuta `Run As > Java Application`.
5. Ejecuta `Actividad10Test.java` con `Run As > JUnit Test`.
6. Haz commit y push cuando la actividad funcione.

## GitHub Actions

- Sube tu trabajo a **tu rama** (no a `main`): el workflow `Autocorrección` compila y ejecuta los tests de cada actividad que hayas modificado.
- En la pestaña **Actions** del repositorio verás ✅ si la actividad está aprobada o ❌ si hay errores de compilación o tests que fallan.
