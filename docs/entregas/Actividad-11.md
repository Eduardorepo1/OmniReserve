# Actividad 11: Busqueda segura con LINQ

## Qué se hizo
Se agregó SearchByNumberAsync a IRoomRepository y a RoomRepository usando LINQ (FirstOrDefaultAsync), que genera consultas parametrizadas.

## Archivos de la entrega
- `OmniReserve.Application/Common/Interfaces/IRoomRepository.cs` (encontrado)
- `OmniReserve.Infrastructure/Persistence/Repositories/RoomRepository.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí que LINQ genera consultas parametrizadas, lo que protege contra la inyección SQL.

## Corrección
Agrega verificacion y aprendizaje de la entrega
