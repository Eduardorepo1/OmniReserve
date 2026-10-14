# Tarea 8: Refactorizar casos de uso con inyeccion de dependencias

## Qué se hizo
CreateRoomCommandHandler y GetRoomByIdQueryHandler ahora reciben IRoomRepository por constructor para guardar y leer habitaciones.

## Archivos de la entrega
- `OmniReserve.Application/Rooms/Commands/CreateRoom/CreateRoomCommandHandler.cs` (encontrado)
- `OmniReserve.Application/Rooms/Queries/GetRoomById/GetRoomByIdQueryHandler.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí a inyectar el repositorio en los Handlers para guardar y leer habitaciones mediante la interfaz.

## Corrección
Agrega verificacion y aprendizaje de la entrega
