# Actividad 13: IReservationRepository e Include multiple

## Qué se hizo
Se creó IReservationRepository y ReservationRepository, que usa Include para traer el usuario y la habitación en una sola consulta, y se registró en la inyección de dependencias.

## Archivos de la entrega
- `OmniReserve.Application/Common/Interfaces/IReservationRepository.cs` (encontrado)
- `OmniReserve.Infrastructure/Persistence/Repositories/ReservationRepository.cs` (encontrado)
- `OmniReserve.Infrastructure/DependencyInjection.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí a usar Eager Loading con Include para traer el usuario y la habitación en una sola consulta y evitar el problema N+1.

## Corrección
Agrega verificacion y aprendizaje de la entrega
