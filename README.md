# cmm-api-tests

Repositorio de pruebas API para CMM, mantenidas en formato de coleccion que puede abrirse en Bruno.

## Requisitos

- Bruno (aplicacion de escritorio)

## Instalacion de Bruno

1. Descarga e instala Bruno desde https://www.usebruno.com/downloads
2. Abre Bruno y selecciona "Open Collection" para abrir este repositorio

## Ejecucion de tests

1. En Bruno, selecciona el entorno en la barra superior (por ejemplo, `cmm4.0`)
2. En el panel izquierdo, abre la coleccion `cmm` o el endpoint que quieras ejecutar
3. Usa el boton "Run" para ejecutar la coleccion o la peticion seleccionada

## Estructura de carpetas

- cmm/: pruebas organizadas por modulo/endpoints
- environments/: variables de entorno (cmm3.0, cmm4.0, localhost)
- auth/: peticiones de autenticacion
