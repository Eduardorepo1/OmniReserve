# Tarea 10: EF Core en RoomRepository

## Qué se hizo
RoomRepository dejó de usar el diccionario en memoria y ahora usa ApplicationDbContext: AddAsync guarda con SaveChangesAsync y GetByIdAsync consulta con FirstOrDefaultAsync.

## Archivos de la entrega
- `OmniReserve.Infrastructure/Persistence/Repositories/RoomRepository.cs` (encontrado)
