# Hairmony — descargas

Instaladores de Hairmony, una aplicación de ArmonyFlow. El código del CRM permanece privado; este repositorio publica instaladores, comprobaciones de integridad y notas de versión.

## Windows 0.1.6

Requiere Windows x64 y una cuenta de Hairmony. La preparación inicial necesita conexión y autorización desde la web. Cada peluquería puede vincular un PC Windows activo; otros ordenadores, móviles y tablets acceden mediante la web.

[Descargar Hairmony para Windows](https://github.com/XekeL121/hairmony-downloads/releases/latest/download/Hairmony-Setup.exe)

El instalador permite elegir la carpeta del programa. La preparación de la copia local elige por separado la carpeta de datos cifrados `HairmonyData/<peluquería>/<usuario>/`. La sesión y las claves protegidas por Windows permanecen en `%APPDATA%/ArmonyFlow/Hairmony`. Copiar los archivos no autoriza otro PC.

La copia local permite las operaciones de negocio admitidas sin conexión y sincroniza al volver a conectarse. Los conflictos requieren revisión. Los formularios sin guardar y las sesiones son propios de cada dispositivo.

## Actualizar conservando datos

Guarda el trabajo, sincroniza los cambios pendientes y cierra Hairmony antes de ejecutar el instalador nuevo. Usa la misma cuenta de Windows. No hace falta desinstalar primero. Conserva el perfil, la carpeta de datos y el material de recuperación; el instalador no los elimina al actualizar o reinstalar.

Antes de cambiar de PC, sincroniza y revoca la vinculación anterior desde la web. Si quedan datos sin sincronizar o el equipo falla, utiliza la recuperación verificada antes de liberar la vinculación.

## Integridad y canal

Cada versión conserva su descarga en Releases junto con `SHA256SUMS.txt` y `release-manifest.json`. El enlace de descarga anterior apunta a la última versión publicada.

Esta entrega mantiene el canal piloto y todavía no dispone de firma Authenticode. La verificación de integridad no sustituye esa firma.

GitHub Actions permanece desactivado. Las compilaciones y comprobaciones se realizan en local. Este repositorio no contiene el código privado del CRM, cuentas, datos de peluquerías, claves ni copias de seguridad.
