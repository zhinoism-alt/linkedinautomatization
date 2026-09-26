# Roadmap oct 2026 → dic 2027

Ritmo sugerido: **8–10 h/semana** (1 h entre semana y 3–4 h el fin de semana). Cada semana: una entrada en `journal/` y, cuando termine un lab, un commit.

---

## Fase 1: Fundamentos S/4HANA + P2P end-to-end (oct–dic 2026)

**Meta:** ejecutar el ciclo P2P completo en S/4 y explicar cada asiento contable que genera.

- [ ] Curso gratuito "Discovering SAP S/4HANA" / "Sourcing and Procurement" en learning.sap.com
- [ ] Diferencias ECC vs. S/4: Business Partner, ACDOCA, Material Ledger obligatorio, MATDOC, Fiori
- [ ] Conseguir un sistema de práctica (ver [04-resources.md](04-resources.md))
- [ ] [Lab 01: Estructura organizativa](labs/lab-01-estructura-organizativa.md)
- [ ] [Lab 02: Datos maestros](labs/lab-02-datos-maestros.md)
- [ ] [Lab 03: P2P end-to-end con asientos](labs/lab-03-p2p-end-to-end.md)
- [ ] Portafolio: caso "P2P de materia prima en planta manufacturera" (diagrama + asientos)

## Fase 2: Configuración MM a fondo + certificación (ene–mar 2027)

**Meta:** aprobar **C_TS452** y dominar los 10 temas que se repiten en las vacantes.

- [ ] [Lab 04: Estrategias de liberación](labs/lab-04-estrategia-liberacion.md)
- [ ] [Lab 05: Determinación de cuentas (OBYC)](labs/lab-05-obyc-determinacion-cuentas.md)
- [ ] Lab 06: Esquema de cálculo de condiciones de compra + impuestos MX (IVA 16%, retenciones)
- [ ] Lab 07: Stock especial: consignación y subcontratación
- [ ] Lab 08: Inventario físico (MI01/MI04/MI07) + cierre de periodo MM (MMPV)
- [ ] Lab 09: MRP basado en consumo (MD01N / MD04)
- [ ] Lab 10: MIRO con diferencias de precio/cantidad y bloqueo de pago (MRBR)
- [ ] 2 simulacros completos de C_TS452 (70%+ antes de presentar)
- [ ] **Presentar C_TS452**

## Fase 3: Integración CO / costos de manufactura (abr–jun 2027)

**Meta:** convertirme en "el de MM que entiende costos". Es lo que más paga en manufactura.

- [ ] Centros de costo, centros de beneficio, órdenes internas en S/4
- [ ] Product Costing: estimación de costo estándar (CK11N/CK24), BOM y rutas
- [ ] Órdenes de producción: consumo (261), notificación, entrada (101), liquidación (KO88/CO88), variaciones (KKS2)
- [ ] **Material Ledger / Actual Costing** (CKMLCP)
- [ ] CO-PA basado en márgenes (conceptos básicos)
- [ ] Portafolio: caso "Cierre de mes en planta: de la orden de producción al P&L"
- [ ] (Opcional) Certificación **Financial Accounting** o **Management Accounting**

## Fase 4: Diferenciador técnico (abr–sep 2027, en paralelo)

**Meta:** escribir specs funcionales que un ABAPer no tenga que corregir y hacer mis propios reportes y apps sencillas.

- [ ] ABAP Cloud Trial en BTP: sintaxis básica, SELECT sobre tablas MM (EKKO, EKPO, MSEG/MATDOC, MARA, MARC, MBEW)
- [ ] CDS view de pedidos abiertos por proveedor + app Fiori Elements (RAP)
- [ ] Conceptos de Clean Core y extensibilidad in-app vs. side-by-side
- [ ] Spec funcional de ejemplo: interfaz báscula → entrada de mercancía (MIGO)
- [ ] Spec funcional de ejemplo: portal de proveedores (pedido → factura CFDI)
- [ ] SAP Activate: fases, Fit-to-Standard, Cloud ALM (certificación C_ACT opcional)

## Fase 5: Salida al mercado (jul–dic 2027)

- [ ] CV y LinkedIn con el posicionamiento del README y las palabras clave de [01-market-research.md](01-market-research.md)
- [ ] Portafolio público con 4 o más casos documentados
- [ ] 20 postulaciones dirigidas (consultoras + manufactureras en NL/CDMX/Bajío)
- [ ] Práctica de entrevistas: preguntas de escenario (ver `portfolio/`)
- [ ] Inglés: 30 min diarios de conversación desde abril 2027
- [ ] **Oferta de 50k+ MXN**
