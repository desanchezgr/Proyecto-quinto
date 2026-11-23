# Plan del sprint 1

## Objetivo del sprint (comprobable)

En la demo, un productor publica café a precio por libra y un comprador encuentra la ficha: con 5 lb ve las existencias y con 0 lb ve «Agotado».

## Capacidad del equipo

| Concepto | Cálculo | Horas |
|---|---|---|
| Capacidad bruta | 3 personas × 5 días × 4 h | 60 h |
| Compromiso del sprint | Historias HU-01 y HU-02 | 48 h |
| Reserva para revisión e integración | Ceremonias, revisión cruzada y fusión | 12 h |

## Historias comprometidas

| Historia | Prioridad | Estimación | Criterio de aceptación |
|---|---|---|---|
| HU-01 · Publicar un lote | Debe | 24 h | [aceptacion.md](aceptacion.md) |
| HU-02 · Buscar café y consultar existencias | Debe | 24 h | [aceptacion.md](aceptacion.md) |

HU-02 puede probarse con lotes de ejemplo cargados por el equipo.

## Tablero y límites de trabajo en proceso

Por hacer → En desarrollo (máx. 2 tarjetas) → En revisión (máx. 1 tarjeta) → Terminado.

Una tarea se considera terminada cuando tiene las pruebas aprobadas, la revisión de otra persona y la fusión en `main`.

El tablero vivo está en [TABLERO.md](../TABLERO.md) y en los issues del repositorio.

## Roles

| Integrante | Rol Scrum | Responsabilidad en el sprint |
|---|---|---|
| Derki | Product Owner | Prioriza el backlog y valida las historias con la cooperativa. |
| Yostin Ruiz | Desarrollador | Implementa las validaciones de precio y stock y prepara los casos de prueba. |
| Santiago | Scrum Master | Facilita la planificación, vigila los límites del tablero y reúne la evidencia de Git. |
