# Tarea 11: Uso seguro de FromSql (SQL crudo)

## Qué se hizo
Se agregó GetRoomsByTypeRawAsync que usa FromSql con interpolación, la cual EF Core convierte en parámetros SQL seguros.

## Archivos de la entrega
- `OmniReserve.Application/Common/Interfaces/IRoomRepository.cs` (encontrado)
- `OmniReserve.Infrastructure/Persistence/Repositories/RoomRepository.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí que FromSql recibe una cadena interpolada como FormattableString y la convierte en parámetros SQL seguros, a diferencia de FromSqlRaw con concatenación.

## Corrección
Corrige la indentacion de GetRoomsByTypeRawAsync en RoomRepository
