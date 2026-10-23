# PediloYa: actualizaciones de pruebas

Este repositorio distribuye únicamente APKs de pruebas y su información de versión.
El código fuente de la aplicación permanece privado.

- Descargar la versión actual: [Releases](https://github.com/C1r0L/pediloya-updates/releases/latest).
- La aplicación consulta `latest.json` al volver a primer plano, como máximo cada 15 minutos.
- Cada APK requiere confirmación de instalación en Android y conserva los datos existentes.
- Los builds se firman con la clave estable de las primeras pruebas.

El workflow del repositorio privado ejecuta pruebas y lint antes de enviar el APK a
`.incoming/`. Este repositorio publica el APK como release y recién después anuncia
la nueva versión en `latest.json`. Nunca subir claves, credenciales ni datos de usuarios.
