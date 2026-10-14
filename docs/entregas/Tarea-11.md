# Tarea 11: Uso seguro de FromSql (SQL crudo)

## Qué se hizo
Se agregó GetRoomsByTypeRawAsync que usa FromSql con interpolación, la cual EF Core convierte en parámetros SQL seguros.

## Archivos de la entrega
- `OmniReserve.Application/Common/Interfaces/IRoomRepository.cs` (encontrado)
- `OmniReserve.Infrastructure/Persistence/Repositories/RoomRepository.cs` (encontrado)
