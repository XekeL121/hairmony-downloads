# Hairmony — descargas

Canal de instaladores de Hairmony, una aplicación de ArmonyFlow. El código del CRM permanece privado; este repositorio publica instaladores, comprobaciones de integridad y notas de versión.

## Piloto para Windows

El piloto necesita Windows x64, internet y una cuenta de Hairmony. Todavía no es la v1 definitiva ni permite trabajar sin conexión. El instalador del piloto no tiene firma digital Authenticode; ese requisito continúa pendiente para la distribución v1.

[Descargar el último instalador para Windows](https://github.com/XekeL121/hairmony-downloads/releases/latest/download/Hairmony-Setup.exe)

El enlace conserva el mismo nombre y apunta al último instalador publicado. Cada versión conserva su descarga propia en Releases, junto con SHA256SUMS.txt y release-manifest.json.

## Actualizar conservando datos

Guarda el trabajo y cierra Hairmony antes de ejecutar el instalador nuevo. Usa la misma cuenta de Windows. El programa mantiene el perfil y la sesión fuera del directorio de instalación; los datos de negocio del piloto conectado permanecen en la nube. No hace falta desinstalar primero ni crear otra peluquería.

Las futuras migraciones de una base local necesitan sus propias pruebas y copias de recuperación. La base local y la sincronización todavía no están implementadas en este piloto.

GitHub Actions permanece desactivado. Las compilaciones y comprobaciones se realizan en local. Este repositorio no contiene el código privado del CRM, cuentas, datos de peluquerías, claves ni copias de seguridad.
