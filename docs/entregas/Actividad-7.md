# Actividad 7: Global Exception Handling y Problem Details

## Qué se hizo
Se creó GlobalExceptionHandlingMiddleware que convierte ValidationException en HTTP 400 y el resto de errores en HTTP 500 con formato Problem Details.

## Archivos de la entrega
- `OmniReserve.Api/Middlewares/GlobalExceptionHandlingMiddleware.cs` (encontrado)
- `OmniReserve.Api/Program.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí a centralizar el manejo de errores en un middleware y a responder con el estándar Problem Details (RFC 7807).

## Corrección
Agrega verificacion y aprendizaje de la entrega
