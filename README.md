\# OmniReserve



\## Descripción



OmniReserve es una API para la gestión de habitaciones, usuarios y reservaciones de un hotel.



El proyecto está desarrollado con C# y .NET 10, utilizando Clean Architecture y Entity Framework Core.



\## Tecnologías



\- C#

\- .NET 10

\- ASP.NET Core Web API

\- Entity Framework Core

\- PostgreSQL

\- MediatR

\- Swagger



\## Estructura del proyecto



\### OmniReserve.Api

Contiene la API, los controladores y la configuración de la aplicación.



\### OmniReserve.Application

Contiene los casos de uso, consultas, DTO e interfaces de la aplicación.



\### OmniReserve.Domain

Contiene las entidades, enumeraciones y objetos de valor del dominio.



\### OmniReserve.Infrastructure

Contiene la persistencia, las configuraciones de Entity Framework Core, los repositorios y las migraciones.



\## Requisitos



\- .NET SDK 10

\- PostgreSQL

\- Herramientas de Entity Framework Core



\## Configuración



1\. Clonar el repositorio.

2\. Abrir la solución OmniReserve.slnx.

3\. Configurar la cadena de conexión a PostgreSQL.

4\. Restaurar las dependencias.

5\. Aplicar las migraciones.

6\. Ejecutar la API.



\## Restaurar dependencias



Desde la carpeta raíz del proyecto:



&#x20;   dotnet restore .\\OmniReserve.slnx



\## Compilar la solución



&#x20;   dotnet build .\\OmniReserve.slnx



\## Consultar las migraciones



&#x20;   dotnet ef migrations list --project .\\OmniReserve.Infrastructure --startup-project .\\OmniReserve.Api



\## Aplicar las migraciones



Una vez configurada la conexión a PostgreSQL:



&#x20;   dotnet ef database update --project .\\OmniReserve.Infrastructure --startup-project .\\OmniReserve.Api



\## Ejecutar la API



&#x20;   dotnet run --project .\\OmniReserve.Api



Cuando la aplicación esté iniciada, consulta la salida de la consola para conocer la dirección local y acceder a Swagger, si está habilitado.



\## Control de versiones



El código fuente se administra con Git y se publica en GitHub.



Los cambios se registran mediante commits descriptivos para mantener un historial claro del desarrollo.

