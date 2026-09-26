# Recursos

## Aprender (gratis)

| Recurso | Para qué |
|---|---|
| [learning.sap.com](https://learning.sap.com) | Cursos oficiales gratuitos (openSAP se integró aquí). Buscar: *Sourcing and Procurement*, *Financial Accounting*, *Management Accounting*, *ABAP Cloud* |
| [help.sap.com](https://help.sap.com) | Documentación oficial de cada proceso y transacción |
| [community.sap.com](https://community.sap.com) | Blogs, casos reales, preguntas. Seguir tags *MM (Materials Management)*, *S/4HANA Sourcing and Procurement* |
| [SAP Best Practices Explorer](https://me.sap.com/processnavigator) | Scope items (p. ej. **J45** Procurement of Direct Materials, **2XT** Invoice Processing) con documentos de prueba paso a paso |
| YouTube | Buscar "SAP MM configuration step by step", "OBYC", "release strategy S4HANA" |

## Aprender (de pago, buena relación costo-beneficio)

- **Udemy:** cursos de S/4HANA Sourcing and Procurement y simulacros **C_TS452** (comprar en oferta, ~200–300 MXN).
- **Libros SAP Press:** *Materials Management with SAP S/4HANA* (Jawad Akhtar) y *Product Costing with SAP S/4HANA*.
- **Michael Management:** libros y cursos cortos muy prácticos.
- **SAP Learning Hub / SAP Learning subscription:** caro, pero incluye sistemas de práctica y exámenes. Evaluar en Fase 2 si conviene frente a pagar solo el examen.

## Practicar (hands-on)

| Opción | Costo aprox. | Notas |
|---|---|---|
| **SAP Cloud Appliance Library (CAL)**: S/4HANA Fully-Activated Appliance | Trial de 30 días de la licencia + pago por hora a AWS/Azure/GCP | Sistema completo con datos de ejemplo. **Apagar la instancia al terminar cada sesión.** Es la opción más "real" |
| Renta de acceso a servidor S/4 IDES | ~30–60 USD/mes | Revisar reseñas; preferir proveedores con sistema S/4 reciente (2022+) |
| **SAP BTP Trial** + **ABAP Cloud Trial** | Gratis | Para la Fase 4 (RAP, CDS, Fiori) |
| SAP Learning Hub (con sistema de práctica) | Suscripción anual | Incluye sistemas de laboratorio |

No usar sistemas piratas: tienen riesgos legales y de seguridad, y en entrevistas se nota.

## Tablas clave de MM (para entender datos y specs)

`EKKO`/`EKPO` (pedidos) · `EBAN` (solicitudes) · `MATDOC` (documentos de material en S/4; en ECC `MKPF`/`MSEG`) · `MARA`/`MARC`/`MARD` (material) · `MBEW` (valoración) · `RBKP`/`RSEG` (facturas) · `EINA`/`EINE` (info records) · `EORD` (lista de fuentes) · `T030` (OBYC) · `ACDOCA` (Universal Journal)
