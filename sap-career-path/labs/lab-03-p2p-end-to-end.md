# Lab 03: Procure-to-Pay end-to-end con asientos contables

**Objetivo:** ejecutar el ciclo completo y **explicar cada asiento**. Esto es lo que más aprovecha mi experiencia FI.

| # | Paso | Transacción | Documento generado | Asiento FI esperado |
|---|---|---|---|---|
| 1 | Solicitud de pedido | `ME51N` | SolPed | — |
| 2 | Liberar SolPed (si aplica) | `ME54N` / `ME55` | — | — |
| 3 | Pedido | `ME21N` (con referencia a la SolPed) | Pedido | — (compromiso opcional) |
| 4 | Liberar pedido | `ME29N` | — | — |
| 5 | Entrada de mercancía (mov. 101) | `MIGO` | Doc. material + doc. contable | Cargo **Inventario (BSX)** / Abono **GR/IR (WRX)** |
| 6 | Factura | `MIRO` | Doc. factura + doc. contable | Cargo **GR/IR (WRX)** / Abono **Proveedor**; diferencias → **PRD** (precio S) o inventario (precio V) |
| 7 | Pago | `F110` (o `F-53`) | Doc. pago | Cargo Proveedor / Abono Banco |
| 8 | Revisión | `ME2N`, `ME80FN`, `MB51`, `FBL1N`, `MB5S` (GR/IR) | — | — |

## Variantes a probar

- [ ] Factura con precio mayor al del pedido, material con precio **S** → ver cuenta **PRD**
- [ ] Mismo caso con material en precio **V** → ver cómo se ajusta el valor del inventario
- [ ] Factura con cantidad mayor a la recibida → bloqueo de pago, liberar con `MRBR`
- [ ] Devolución al proveedor (mov. 122)
- [ ] Pedido con imputación a centro de costo (K) → gasto directo, sin inventario

## Entregable de portafolio

`portfolio/caso-01-p2p-manufactura.md` con: diagrama del flujo, tabla de documentos y asientos, y una explicación de 5 líneas escrita para un usuario de finanzas.
