# Actividad 4: Instalar MediatR e implementar CreateRoomCommand

## Qué se hizo
Se instaló MediatR, se registró en DependencyInjection y se crearon CreateRoomCommand y su handler siguiendo CQRS.

## Archivos de la entrega
- `OmniReserve.Application/DependencyInjection.cs` (encontrado)
- `OmniReserve.Application/Rooms/Commands/CreateRoom/CreateRoomCommand.cs` (encontrado)
- `OmniReserve.Application/Rooms/Commands/CreateRoom/CreateRoomCommandHandler.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí CQRS con MediatR: separar el Command (entrada) del Handler (ejecución) y registrar MediatR en la capa Application.

## Corrección
Agrega verificacion y aprendizaje de la entrega
