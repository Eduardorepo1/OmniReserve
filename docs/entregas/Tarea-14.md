# Tarea 14: Value Conversions en EF Core

## Qué se hizo
Se configuró HasConversion para guardar EmailAddress como texto, con longitud máxima de 255 e índice único, y se generó la migración ConfigureEmailAddress.

## Archivos de la entrega
- `OmniReserve.Infrastructure/Persistence/Configurations/UserConfiguration.cs` (encontrado)
- `OmniReserve.Infrastructure/Migrations/*_ConfigureEmailAddress.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí a usar HasConversion para guardar un Value Object como texto en la base de datos y a crear un índice único sobre el correo.

## Corrección
Agrega verificacion y aprendizaje de la entrega
