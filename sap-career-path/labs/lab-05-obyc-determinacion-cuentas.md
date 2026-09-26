# Lab 05: Determinación automática de cuentas (OBYC)

**Por qué:** es el punto exacto donde MM se encuentra con FI, y donde mi experiencia en finanzas se vuelve una ventaja.

## Cadena de determinación

```
Centro → Área de valoración → Agrupación de valoración (OMWD)
Material → Tipo de material → Referencia de categoría de cuenta → Clase de valoración (OMSK)
Tipo de movimiento → Modificador de cuenta (OMWN)
          ↓
OBYC: Plan de cuentas + Operación (BSX, WRX, PRD, GBB…) + Agrup. valoración + Modificador + Clase de valoración → Cuenta de mayor
```

## Operaciones que debo saber explicar

| Clave | Significado | Ejemplo |
|---|---|---|
| **BSX** | Inventario | Entrada 101 |
| **WRX** | Cuenta puente GR/IR | Entrada 101 / MIRO |
| **PRD** | Diferencias de precio | MIRO con precio distinto (precio S) |
| **GBB** | Contrapartida de inventario (modificadores VBR consumo, VAX/VAY ventas, VNG desguace, INV inventario físico, ZOB entrada sin pedido) | Consumo 201/261, desguace 551 |
| **UMB** | Revaluación | Cambio de precio estándar |
| **KDM** | Diferencias por tipo de cambio | Compras en USD |

## Ejercicio

1. Usar `OMWB` → *Simulation* para un movimiento 101 y uno 261 del material ROH.
2. Crear una clase de valoración nueva (p. ej. para "empaque") que vaya a una cuenta de inventario distinta. Probar con `MIGO` y revisar el asiento en `FB03`.
3. Documentar el caso en el portafolio con la tabla "movimiento → operación → cuenta".

## Pregunta de entrevista

> "Una entrada de mercancía da el error *Account determination for entry XXXX BSX 0001 ROH not possible*. ¿Cómo lo resuelves?"
