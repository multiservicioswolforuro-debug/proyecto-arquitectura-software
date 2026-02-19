# Diseño API REST

## Endpoints principales

GET /usuarios
POST /usuarios
PUT /usuarios/{id}
DELETE /usuarios/{id}

## Formato JSON

{
 "id": integer,
 "nombre": string,
 "email": string
}

## Consideraciones técnicas a tener

- Arquitectura cliente-servidor
- Uso de HTTP status codes
- Documentación OpenAPI
