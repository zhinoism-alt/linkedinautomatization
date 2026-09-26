# Lab 02: Datos maestros

**Objetivo:** crear los datos maestros mínimos para comprar materia prima. Varias vacantes (farmacéutica, Grupo México) piden explícitamente gestión de datos maestros.

| # | Dato maestro | Transacción / App Fiori | Qué revisar |
|---|---|---|---|
| 1 | Proveedor como **Business Partner** (en S/4 ya no existe XK01) | `BP`: rol FLVN00 (general) y FLVN01 (proveedor en compras) | Cuenta asociada (AP), condiciones de pago, RFC, grupo de cuentas |
| 2 | Material materia prima (ROH) | `MM01`: vistas Básico, Compras, MRP, Contabilidad, Costos | Clase de valoración (determina OBYC), control de precio **S** vs. **V**, grupo de artículos |
| 3 | Registro info | `ME11` | Precio neto por proveedor-material, tiempo de entrega |
| 4 | Lista de fuentes | `ME01` | Proveedor fijo, bloqueado, relevante para MRP |
| 5 | Contrato marco (opcional) | `ME31K` | Cantidad o valor objetivo |

## Ejercicio clave

Crear **dos materiales iguales**, uno con precio estándar (S) y otro con precio medio variable (V). En el Lab 03, comparar qué asientos genera la factura cuando el precio difiere del pedido.

## Preguntas de entrevista

1. ¿Qué cambió con Business Partner en S/4 y qué es la CVI (Customer/Vendor Integration)?
2. ¿Qué campo del material conecta MM con la determinación de cuentas?
3. ¿Cuándo conviene precio estándar y cuándo precio medio variable en manufactura?
