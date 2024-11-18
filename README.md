# Norton_SQL

## Descripción

**Norton_SQL** es una aplicación sencilla que permite gestionar bases de datos a través de comandos de **backup** y **restore**, similar a la famosa herramienta **Norton** de MS-DOS. Esta aplicación ejecuta los comandos necesarios de forma automática, permitiendo realizar tareas de gestión de bases de datos de forma más rápida y fácil.

Actualmente, la herramienta está disponible como un **archivo ejecutable `.exe`** que puedes descargar y usar sin necesidad de instalar Python ni configurar un entorno. 

### ¿Cómo funciona?

La aplicación utiliza entradas de usuario para realizar operaciones de **backup** y **restore** de bases de datos. A continuación te explicamos cómo usarla.

## Características

- **Backup**: Realiza copias de seguridad de las bases de datos.
- **Restore**: Restaura bases de datos desde archivos de backup.
- **Fácil de usar**: Simplemente introduce los datos necesarios y ejecuta el programa.
- **Interfaz sencilla**: No es necesario tener conocimientos técnicos para usarla.

## Requisitos

- **Sistema operativo**: Windows
- **No es necesario tener Python instalado** ya que se proporciona un ejecutable precompilado.

## Instalación

1. **Descargar el archivo ejecutable**:
   
   Visita la sección de [releases](https://github.com/Deivincci/norton_sql/releases) en el repositorio y descarga el archivo **`NortonSQL.exe`**.

2. **Ejecutar el archivo**:

   Haz doble clic sobre el archivo **`NortonSQL.exe`** para iniciar la aplicación.

## Uso

### Realizar un Backup

1. **Abrir la aplicación**: Haz doble clic en **`NortonSQL.exe`**.
2. **Ingresar la base de datos a respaldar**: En el campo de **Base de datos a respaldar**, introduce el nombre exacto de la base de datos.
3. **Nombrar el archivo de backup**: En el campo **Nombre del archivo de respaldo**, ingresa el nombre que deseas darle al archivo de backup (sin incluir la extensión, el programa la añadirá automáticamente).
4. **Realizar el Backup**: Haz clic en el botón **Realizar Backup** para completar la operación.

### Realizar un Restore

1. **Abrir la aplicación**: Haz doble clic en **`NortonSQL.exe`**.
2. **Seleccionar el archivo de backup**: En el campo **Archivo a restaurar**, introduce el nombre del archivo de backup (sin la extensión).
3. **Nombrar la base de datos destino**: En el campo **Nombre de la base de datos destino**, ingresa el nombre de la base de datos en la que deseas restaurar el backup.
4. **Realizar el Restore**: Haz clic en el botón **Realizar Restore** para completar la operación.

### Seguridad

La aplicación está configurada para funcionar de manera **local**. Si deseas usarla con una base de datos remota, deberás modificar la ruta de conexión en la configuración.

## Captura de Pantalla

![Descripción de la imagen](https://github.com/Deivincci/norton_sql/blob/main/nortonsql.png?raw=true)

## Desarrollo

El código fuente está siendo **reescrito** para agregar nuevas funcionalidades. Si estás interesado en colaborar o ver cómo funciona el código, revisa los archivos en el repositorio y contribuye con sugerencias.

Actualmente, el código fuente incluye:

- Gestión de entradas del usuario (nombre de la base de datos, nombre del archivo de backup).
- Ejecución de comandos de terminal para realizar operaciones de backup y restore.

En futuras actualizaciones, planeamos agregar más características, como soporte para bases de datos remotas y otros tipos de operaciones.

## Licencia

Este proyecto está bajo la **Apache License 2.0**.

