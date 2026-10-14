# Tarea 7: Interceptar excepciones de dominio

## Qué se hizo
El middleware ahora también captura DomainException y responde HTTP 400 con el título Error de Dominio.

## Archivos de la entrega
- `OmniReserve.Api/Middlewares/GlobalExceptionHandlingMiddleware.cs` (encontrado)

## Verificación
La solución compila correctamente (`dotnet build`).

## Qué aprendí
Aprendí a traducir las excepciones del dominio a respuestas HTTP 400 sin usar try/catch en los controladores.

## Corrección
Agrega verificacion y aprendizaje de la entrega
