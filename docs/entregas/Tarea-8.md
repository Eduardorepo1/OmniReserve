# Tarea 8: Refactorizar casos de uso con inyeccion de dependencias

## Qué se hizo
CreateRoomCommandHandler y GetRoomByIdQueryHandler ahora reciben IRoomRepository por constructor para guardar y leer habitaciones.

## Archivos de la entrega
- `OmniReserve.Application/Rooms/Commands/CreateRoom/CreateRoomCommandHandler.cs` (encontrado)
- `OmniReserve.Application/Rooms/Queries/GetRoomById/GetRoomByIdQueryHandler.cs` (encontrado)
