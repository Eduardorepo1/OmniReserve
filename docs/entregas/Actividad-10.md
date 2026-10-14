# Actividad 10: Conexion Npgsql y primera migracion

## Qué se hizo
Se instaló Npgsql.EntityFrameworkCore.PostgreSQL y EF Core Design, se configuró la cadena de conexión, se conectó el DbContext y se generó la migración InitialCreate.

## Archivos de la entrega
- `OmniReserve.Infrastructure/OmniReserve.Infrastructure.csproj` (encontrado)
- `OmniReserve.Api/OmniReserve.Api.csproj` (encontrado)
- `OmniReserve.Api/appsettings.json` (encontrado)
- `OmniReserve.Infrastructure/DependencyInjection.cs` (encontrado)
- `OmniReserve.Infrastructure/Migrations/*_InitialCreate.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí a conectar EF Core con PostgreSQL usando Npgsql, a configurar la cadena de conexión y a generar y aplicar la migración inicial con Code-First.

## Corrección
Mueve la contrasena de PostgreSQL fuera de appsettings.json (user-secrets)
