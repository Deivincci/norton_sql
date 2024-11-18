# Norton_SQL

## Descripción

**Norton_SQL** es una aplicación desarrollada en Python que permite gestionar bases de datos mediante comandos de **backup** y **restore**. Inspirada en el antiguo **Norton** de MS-DOS, esta herramienta está diseñada para ser eficiente y fácil de usar. Incluye un **ejecutable (.exe)** para que puedas usarla sin necesidad de instalar Python ni dependencias.

## Características

- Realiza copias de seguridad (**backup**) de bases de datos.
- Restaura bases de datos desde archivos de **backup**.
- Soporta autenticación de usuario mediante campos de nombre de usuario y contraseña.
- Fácil de usar, solo necesitas ejecutar el archivo `.exe`.

**Ejecuta el archivo .exe**:
   
   Después de la descarga, simplemente haz doble clic en el archivo **`NortonSQL.exe`** para iniciar la aplicación.

## Uso

### Backup

1. Abre el ejecutable **NortonSQL.exe**.
2. En el cuadro de **Base de datos a respaldar**, ingresa el nombre exacto de la base de datos.
3. En el cuadro de **Nombre del archivo de respaldo**, ingresa el nombre con el que quieres guardar el archivo de backup (sin extensión, el programa la añadirá automáticamente).
4. Haz clic en **Realizar Backup** para crear una copia de seguridad.

### Restore

1. Abre el ejecutable **NortonSQL.exe**.
2. En el cuadro de **Archivo a restaurar**, ingresa el nombre del archivo de backup (sin extensión).
3. En el cuadro de **Nombre de la base de datos destino**, ingresa el nombre de la base de datos donde quieres restaurar la copia de seguridad.
4. Haz clic en **Realizar Restore** para restaurar la base de datos.

### Nota de seguridad

Recuerda que esta aplicación está configurada para trabajar de manera local. Actualmente al no disponer de codigo fuente no se puede cambiar el host,pero en cambio
si tenemos pgadmin4 configurado,el programa detectara gracias a eso la ruta.
No he incluido el codigo fuente porque aun estoy trabajando en ello,la intencion es añadir mas funcionalidades de manipulacion de bases de datos.

## Capturas de pantalla

![Descripción de la imagen](https://github.com/Deivincci/norton_sql/blob/main/nortonsql.png?raw=true)

## Licencia

Este proyecto está bajo la **Apache License 2.0**.

