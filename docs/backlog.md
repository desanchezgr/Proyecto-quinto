# Backlog priorizado

Priorización MoSCoW. Cada historia cumple INVEST y tiene criterios de aceptación en [aceptacion.md](aceptacion.md).

## Debe (imprescindible para el sprint 1)

| Historia | Como... | Quiero... | Para... | Estimación | Prioridad |
|---|---|---|---|---|---|
| HU-01 | productor | publicar un lote con nombre, precio por libra y existencias | ofrecer mi café en el marketplace | 24 h | 1 |
| HU-02 | comprador | buscar café por nombre y ver precio y existencias | saber si está disponible | 24 h | 2 |

## Debería (siguiente sprint)

| Historia | Como... | Quiero... | Para... | Estimación |
|---|---|---|---|---|
| HU-03 | comprador | filtrar los lotes por cooperativa | comparar la oferta de mi zona | 12 h |
| HU-04 | productor | editar el precio y las existencias de un lote | mantener la oferta actualizada | 12 h |

## Podría (deseable)

| Historia | Como... | Quiero... | Para... | Estimación |
|---|---|---|---|---|
| HU-05 | comprador | guardar lotes favoritos | volver a ellos rápidamente | 8 h |

## No se hará (fuera del alcance de la Fase I)

- Pagos en línea.
- Logística y seguimiento de entregas.
- Aplicación móvil nativa.

## Trazabilidad

| Historia | Requisitos |
|---|---|
| HU-01 | RF-01, RF-03 |
| HU-02 | RF-02, RNF-01 |
| HU-03 | RF-02 |
| HU-04 | RF-01, RF-03 |
| HU-05 | RF-02 |

## Seguimiento

El estado de cada historia se consulta en el [tablero](../TABLERO.md) y en los issues de GitHub con la etiqueta `tipo/historia`.
