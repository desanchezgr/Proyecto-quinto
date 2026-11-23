# Especificación de requisitos (SRS)

## Requisitos funcionales

| Identificador | Requisito | Clase y prioridad |
|---|---|---|
| RF-01 | El productor puede publicar un lote con nombre, precio por libra mayor que cero y existencias no negativas. | Funcional · Debe |
| RF-02 | El comprador puede buscar café por nombre y consultar el precio por libra y las existencias de cada resultado. | Funcional · Debe |
| RF-03 | La ficha muestra «Agotado» cuando el stock es cero y retira la etiqueta cuando vuelve a ser positivo. | Funcional · Debe |

## Requisitos no funcionales

| Identificador | Requisito | Métrica | Umbral |
|---|---|---|---|
| RNF-01 | Rendimiento de la búsqueda | Tiempo de respuesta con 50 usuarios simultáneos y 1.000 lotes | Al menos el 95 % de las búsquedas en 2 segundos o menos |
| RNF-02 | Accesibilidad del formulario | Campos obligatorios con etiqueta accesible y uso completo por teclado | El 100 % de los campos obligatorios |

## Reglas de negocio

- El precio por libra siempre es mayor que cero.
- Las existencias nunca son negativas.
- Un lote con existencias en cero permanece publicado, pero marcado como «Agotado».

## Validación

Los requisitos se validan con los casos de aceptación de [aceptacion.md](aceptacion.md) y con las pruebas registradas en el tablero (issue #5). Los resultados de la validación se anexan a este documento al cierre del sprint.
