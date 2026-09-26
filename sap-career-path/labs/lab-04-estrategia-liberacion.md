# Lab 04: Estrategia de liberación de pedidos (con clasificación)

**Por qué:** aparece en la mayoría de las vacantes MM (Zucarmex, Grupo México). Es de los tickets más comunes en soporte AMS.

**Escenario:** pedidos de la planta MTY1 de menos de 100,000 MXN los libera el jefe de compras (J1); de 100,000 MXN o más, el jefe de compras y además el gerente de planta (G1).

## Pasos

| # | Paso | Transacción |
|---|---|---|
| 1 | Crear características: `CEKKO-GNETW` (valor neto), `CEKKO-WERKS` (centro) | `CT04` |
| 2 | Crear clase tipo **032** con esas características | `CL02` |
| 3 | Grupo de liberación, códigos (J1, G1), indicadores de liberación, estrategias | SPRO › MM › Purchasing › Purchase Order › Release Procedure for Purchase Orders |
| 4 | Asignar valores de clasificación a cada estrategia | (en la misma estrategia, botón *Classification*) |
| 5 | Probar: crear pedidos de 50k y de 150k | `ME21N` → pestaña *Release strategy* |
| 6 | Liberar | `ME29N` / `ME28` |
| 7 | Revisar la clasificación | `CL24N` |

## Troubleshooting típico (anotar lo que me pase)

- La estrategia no se determina → la moneda de `GNETW` no coincide, o los valores de clasificación se traslapan.
- Cambios al pedido después de liberado → revisar la *tolerancia de modificación* en el indicador de liberación.
- En S/4 también existe **Flexible Workflow** para pedidos. Investigar la diferencia (pregunta frecuente en entrevistas).
