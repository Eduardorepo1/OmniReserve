# Tarea 2: Encapsulando la inyeccion de dependencias por capas

## Qué se hizo
Se crearon AddApplication y AddInfrastructure como métodos de extensión de IServiceCollection y se conectaron desde Program.cs.

## Archivos de la entrega
- `OmniReserve.Application/DependencyInjection.cs` (encontrado)
- `OmniReserve.Infrastructure/DependencyInjection.cs` (encontrado)
- `OmniReserve.Api/Program.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí a que cada capa registre sus propios servicios con métodos de extensión, dejando Program.cs limpio.

## Corrección
Agrega verificacion y aprendizaje de la entrega
