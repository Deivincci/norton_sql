# NORTON_SQL (Desarrollado en python)

**Norton_SQL** es una aplicación inspirada en el antiguo programa de MS-DOS **Norton**, que permitía gestionar carpetas y archivos mediante una interfaz encargada de ejecutar comandos.

En este caso, el funcionamiento es similar: he comprobado que, en ocasiones, los programas de gestión de bases de datos pueden fallar, pero los **comandos de terminal** suelen ser infalibles (siempre que dispongan de los permisos necesarios).

## Funcionalidad

Para garantizar la funcionalidad, veremos que hay un recuadro de usuario y otro de contraseña. Esto es necesario porque, cuando los comandos requieran autenticación, siempre revisará esos campos en busca de los datos correspondientes.

### Campos de Operación

Podemos apreciar dos campos para cada operación:

- **Backup**: 
  1. El primer campo es el **nombre exacto de la base de datos** de la que se hará el backup.
  2. El segundo campo es el **nombre con el que queremos conservar** el archivo.
  
  **Nota**: Por motivos de seguridad, no incluimos la extensión. El programa la asigna automáticamente.

- **Restore**:
  1. El primer campo es el **archivo** que queremos recuperar (sin la extensión).
  2. El segundo campo es el **nombre** que le queremos dar a la base de datos restaurada.

### Modo Local

El programa está configurado para funcionar en **modo local**. Para conectarse a una base de datos remota, simplemente sería necesario cambiar la ruta en la configuración.

![Descripción de la imagen](https://github.com/Deivincci/norton_sql/blob/main/nortonsql.png?raw=true)

