# Actividad 5: Configurar FluentValidation y MediatR Behaviors

## Qué se hizo
Se instaló FluentValidation, se creó ValidationException y el ValidationBehavior del pipeline de MediatR, y se validó CreateRoomCommand.

## Archivos de la entrega
- `OmniReserve.Application/Common/Exceptions/ValidationException.cs` (encontrado)
- `OmniReserve.Application/Common/Behaviors/ValidationBehavior.cs` (encontrado)
- `OmniReserve.Application/DependencyInjection.cs` (encontrado)
- `OmniReserve.Application/Rooms/Commands/CreateRoom/CreateRoomCommandValidator.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí el principio Fail-Fast: validar los datos de entrada con FluentValidation en un Pipeline Behavior antes de ejecutar el Handler.

## Corrección
Agrega verificacion y aprendizaje de la entrega
