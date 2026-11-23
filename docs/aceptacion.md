# Criterios de aceptación

Cada historia se acepta solo si pasan los cuatro tipos de caso: flujo normal, excepción, límite y no funcional.

## HU-01 · Publicar un lote

| Tipo | Caso | Resultado esperado |
|---|---|---|
| Normal | El productor publica un lote de café con 5 lb y precio mayor que cero. | El lote aparece publicado con sus 5 lb y su precio por libra. |
| Excepción | El productor intenta guardar precio 0 o existencias negativas. | El formulario rechaza el guardado y muestra el mensaje de validación. |
| Límite | El lote queda con 0 lb. | La ficha muestra «Agotado» y retira la etiqueta al volver a un valor positivo (RF-03). |
| No funcional | Formulario de publicación con teclado y lector de pantalla. | El 100 % de los campos obligatorios tiene etiqueta accesible y se completa con teclado (RNF-02). |

## HU-02 · Buscar café

| Tipo | Caso | Resultado esperado |
|---|---|---|
| Normal | El comprador busca «café» y hay lotes que coinciden. | Se listan los resultados con precio por libra y existencias. |
| Excepción | La búsqueda no tiene coincidencias. | Se muestra un mensaje claro de «sin resultados», sin errores. |
| Límite | Lote con 0 lb en los resultados. | El resultado se muestra marcado como «Agotado». |
| No funcional | 50 usuarios simultáneos y 1.000 lotes. | Al menos el 95 % de las búsquedas responde en 2 segundos o menos (RNF-01). |

## Evidencia

Los resultados de ejecución se registran en el issue de pruebas del tablero y se anexan a este documento al cierre del sprint.
