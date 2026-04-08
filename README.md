# cmm-api-tests

Repositorio de pruebas API para CMM migradas de Postman a Bruno.

## Requisitos

- Node.js
- Bruno CLI

## Instalacion de Bruno CLI

```bash
npm install -g @usebruno/cli
```

## Ejecucion de tests

Ejecuta los tests con un entorno:

```bash
bru run --env cmm4.0
```

## Estructura de carpetas

- cmm/: pruebas organizadas por modulo/endpoints
- environments/: variables de entorno (cmm3.0, cmm4.0, localhost)
- auth/: peticiones de autenticacion
