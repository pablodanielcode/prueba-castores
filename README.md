DE utilizado:
Visual Studio Code
Visual Studio 2022

Versión del lenguaje de programación utilizado.
Lenguaje: C# 10
Plataforma/Framework: .NET 6

DBMS utilizado y su versión.
DBMS utilizado: Microsoft SQL Server
Versión: SQL Server 2022.

Lista de pasos para correr su aplicación

Descargar el archivo del repositorio "EJERCICIO_PRACTICO", colocar en las carpeta front_end y back_end en la raíz del servidor
Ejecutar el archivo .slq de la carpeta Scripts.
Copia todo el contenido de la carpeta "prueba-castores/EJERCICIO_PRACTICO/BACK_END" a: C:\xampp\htdocs\BACK_END o http://localhost/BACK_END dependiendo el servidor.
de igual manero los archivos "prueba-castores/EJERCICIO_PRACTICO/FRONT_END" a: C:\xampp\htdocs\FRONT_END o http://localhost/FRONT_END dependiendo el servidor.

Buscar los archivos de conexión y modificar la conexion a BD para habilitar el API, su ubicación es: "EJERCICIO_PRACTICO/BACK_END/appsettings.json"
--"CadenaSQL": "Data Source=NombreServer;Initial Catalog=PruebaCastores;Persist Security Info=True;User ID=Nombreusuario;Password=contraseñaUsuario"

Para configurar la conecion del Front_end la ubicacion es: "EJERCICIO_PRACTICO/FRONT_END/js/app.3340a85e.js"
se debe buscar la linea: "http://localhost:5095" y modificar los puertos apuntando a la configuracion del BACK_END (API).

Ir a la ruta "localhost/FRONT_END" o reemplazar "localhost" por el dominio que corresponda para realizar pruebas.
