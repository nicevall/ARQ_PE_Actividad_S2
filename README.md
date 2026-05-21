# API de Reserva de Citas Médicas — Definición de Contrato

Repositorio de definición de interfaces para la integración entre el Portal del
Paciente (Servicio A) y el Servicio de Agenda Médica (Servicio B).

## Contenido
- `openapi/citas-medicas.yaml` — Contrato REST en formato OpenAPI 3.0
- `diagrams/secuencia-reserva.md` — Diagrama de secuencia en Mermaid
- `actividad_contratos_REST_gRPC.md` — Documento completo con el análisis de REST vs. gRPC

## Cómo visualizar el contrato
1. Accede a https://editor.swagger.io/
2. Pega el contenido de `citas-medicas.yaml`
3. Explora los endpoints interactivamente

## Tecnologías
- REST / OpenAPI 3.0 (Swagger)
- JWT para autenticación
- HTTP/1.1
