# Ejemplo de plantilla de Issues de GitHub

Este paquete contiene una plantilla de formulario para reportar errores (bugs).

## Cómo instalarla en tu repositorio

1. Descomprime el ZIP.
2. En tu repositorio de GitHub, entra en **Code**.
3. Pulsa **Add file → Upload files**.
4. Sube la carpeta `.github` conservando esta ruta:
   `.github/ISSUE_TEMPLATE/bug_report.yml`
5. Pulsa **Commit changes**.
6. Entra en **Issues → New issue** y selecciona **Reporte de bug**.

Si prefieres crear el archivo manualmente, abre `.github/ISSUE_TEMPLATE/bug_report.yml` y copia el contenido.

## Ejemplo de reporte para probar

- Descripción: La aplicación se cierra al pulsar Guardar.
- Pasos: 1) Abrir la aplicación. 2) Pulsar Guardar.
- Esperado: El archivo se guarda correctamente.
- Real: La aplicación se cierra.
- Sistema: Windows 11.

Nota: la plantilla aparece en el selector de nuevos Issues después de que el archivo se haya subido y guardado en la rama predeterminada del repositorio.
