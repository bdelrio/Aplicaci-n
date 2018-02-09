# Aplicación Meteorología

Esta aplicación ofrece:
- API Rest CRUD para entidad Usuarios (JSON/XML).
- Formularios CRUD que consumen el anterior API Rest.

 ## Requisitos
 - Visual Studio 2017

## ¿Cómo ejecutar la aplicación?

 1. Descargar la solución (proyecto). Para ello pulsar en el botón Clone or Download - Download ZIP
 2. Extraer el fichero en la ubicación deseada.
 3. Abrir Visual Studio, Archivo - Abrir Solución y buscar en el directorio descomprimido el fichero Aplicacion_Meteorologia.sln
 4. Workaround para error al ejecutar aplicación desde Visual Studio en modo depuración.
    Herramientas - Opciones - Depuracion - General - Desmarcar la opcion : Habilitar depuracion javascript para ASP.NET
 5. Las migraciones de la base de datos, tanto creacion como precargar se deberían ejecutar automaticamente. Si no se ejecutaran automaticamente, Ejecutar migraciones Base de datos.
 Herramientas - Administrador de Paquetes Nuget - Consola del Administrador de Paquetes
    Enable-Migrations
    Add-Migration Initial
    Update-Database


 6. Lanzar la aplicacion desde Visual Studio pulsando F5 o clicando en el boton de play.
 7. Conectarse con el navegador a http://localhost:54313