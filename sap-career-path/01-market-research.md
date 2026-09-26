# Market research: qué piden realmente las empresas (México, septiembre 2026)

Fuente principal: vacantes de Indeed México leídas completas el 26-sep-2026, más búsquedas web (Glassdoor y LinkedIn vía buscador). LinkedIn y JobLeads no se pudieron consultar directo (acceso bloqueado desde el entorno), así que los datos de ahí son indirectos. Volver a hacer este análisis cada trimestre.

## 1. Vacantes analizadas

| Vacante | Empresa | Ciudad | Sueldo publicado | Lo que más piden |
|---|---|---|---|---|
| [Consultor SAP MM (híbrido)](https://to.indeed.com/aa99bxqqvqvd) | MovIT / Asociados Web | Santa Catarina, NL | **55k–60k MXN** | Config de org. de compras, centros, almacenes; portal de proveedores (pedido → factura); integración FI/PP/PM; pruebas; soporte N2 |
| [Especialista SAP MM](https://to.indeed.com/aa2ybcnwfhx2) | Grupo México | CDMX | n/d | 4+ años técnico-funcional MM **y WM**; ECC y/o S4; valoración de materiales; stock especial; MRP por consumo; liberaciones; AMS + implementación; ASAP/Activate. Deseable: SRM, CLM, PM, ITIL |
| [Consultor SAP MM Senior](https://to.indeed.com/aay6wngxfwmn) | Netpartners (farmacéutica) | CDMX, remoto | n/d | **Certificación SAP**; datos maestros y reportes de datos maestros; compras; AMS 1 año |
| [Consultor SAP (MM / P2P S/4HANA)](https://to.indeed.com/aa4lvqck8xp8) | Zucarmex (manufactura azúcar) | Culiacán | n/d (prestaciones superiores) | Esquemas de cálculo de condiciones, **impuestos**, estrategias de liberación; integración con FI, CO, SD, PP (MRP, BOM); specs ABAP (formularios, **interfaces con portal de proveedores y básculas**); **inventario físico y cierre de mes logístico** |
| [Senior SAP CO / CO-PA](https://to.indeed.com/aaqfhbwgfh9g) | Emperia MX | San Nicolás, NL | **75k–90k MXN** | CO-PA, **Material Ledger / Actual Costing**, centros de costo y beneficio, órdenes internas, **Product Costing**; 2+ implementaciones; inglés avanzado |
| [SAP CO Specialist](https://to.indeed.com/aavftzhnrzft) | Yazaki (automotriz) | San Nicolás, NL | n/d | CO-PA + Material Ledger; 5+ años CO; 3 implementaciones; specs ABAP; integración FI/MM/SD |
| [SAP Superuser FI/CO](https://to.indeed.com/aac4t8vxqdgv) | Red Ring / Selecta | CDMX híbrido | **70k MXN** | FICO sólido, **2 implementaciones end-to-end**, S/4HANA |
| [Consultor SAP FI](https://to.indeed.com/aaj8gyndd7c2) | R&R IT Consulting | CDMX | n/d | GL/AP/AR/AA/bancos; **CFDI, SAT, contabilidad electrónica**; integración CO/MM/SD; S/4 y New GL; inglés intermedio |
| [Consultor SAP BTP](https://to.indeed.com/aaxjkvsvvkk6) | Northware | Monterrey | a negociar | **Clean Core**, RAP, ABAP Cloud, CDS, OData, Fiori Elements, Integration Suite (CPI); deseable conocer FI/CO/MM |
| [Consultor(a) SAP FI/CO temporal](https://to.indeed.com/aa4rvvdr6wk8) | Deloitte | Querétaro | n/d | (proyecto temporal FI/CO) |
| [Consultores SAP ECC Senior](https://to.indeed.com/aatfqqqr2fwt) | Netpartners | CDMX | n/d | ECC senior (hay mucho soporte AMS de ECC hasta la migración) |

## 2. Patrones: lo que se repite

### MM: temas que aparecen en 3 o más vacantes

1. **Configuración de estructura organizativa**: org. de compras, centros, almacenes.
2. **Estrategias de liberación** (release strategy) de solicitudes y pedidos.
3. **Verificación de facturas (MIRO)** e **integración con FI**: determinación de cuentas, cuentas por pagar.
4. **Valoración de materiales**: precio estándar vs. medio variable, OBYC, Material Ledger en S/4.
5. **Datos maestros**: material, Business Partner (proveedor), registros info, listas de fuentes.
6. **Gestión de inventarios**: tipos de movimiento, traspasos, reservas, **stock especial** (consignación, subcontratación), **inventario físico**.
7. **Integración con PP** (MRP, BOM) y con **CO** (costos).
8. **Especificaciones funcionales para ABAP**: formularios, reportes, interfaces.
9. **Soporte AMS nivel 2** + **pruebas** (unitarias, integrales, UAT).
10. **Metodología SAP Activate**.

### Lo que marca la diferencia en sueldo

| Factor | Evidencia |
|---|---|
| **CO / Material Ledger / Product Costing** | Las vacantes que más pagan (75–90k) son de CO en manufactura (Yazaki, Emperia) |
| **FI + CO combinados + S/4** | 70k MXN (Selecta) |
| **Inglés** | Aparece en las vacantes de más de 70k |
| **Implementaciones completas (2–3)** | Filtro frecuente para los puestos senior |
| **Certificación SAP** | Piden requisito explícito en farmacéutica/AMS |
| **Localización México** (CFDI, SAT, retenciones, IVA) | Pedido en FI y, en MM, en impuestos de compras |
| **Clean Core / BTP** | Tendencia fuerte en proyectos RISE with SAP |

### Sueldos observados (publicados)

- MM semi-senior, híbrido NL: **55k–60k**
- FI/CO con S/4: **70k**
- CO-PA / Material Ledger senior + inglés: **75k–90k**

**Conclusión:** 50k+ es alcanzable con un perfil **MM + integración FI**. Con **CO de manufactura + inglés** se pasa de 70k.

## 3. Brechas contra mi perfil (a trabajar)

- [ ] Pasar de ECC a **S/4HANA**: Business Partner, Universal Journal (ACDOCA), Fiori, Material Ledger obligatorio.
- [ ] Configuración MM real, no solo uso de transacciones.
- [ ] Nivel de "consultor": levantar requerimientos, escribir specs funcionales, diseñar pruebas.
- [ ] Evidencia de **proyecto**: si no hay implementación real todavía, documentar proyectos simulados end-to-end en `portfolio/`.
- [ ] Inglés conversacional para entrevistas.

## 4. Empresas y hubs a seguir

- **Hubs:** Monterrey (manufactura/automotriz), CDMX, Guadalajara, Querétaro.
- **Consultoras / partners:** Deloitte, Accenture, EY, NTT Data, Inetum, EPAM, Northware, Netpartners, MovIT, Emperia.
- **Usuarios finales manufactura:** Yazaki, Grupo México, Zucarmex, y en general armadoras y proveedores Tier 1/2 en el Bajío y NL.

## Fuentes adicionales

- [Glassdoor: SAP MM jobs in Mexico](https://www.glassdoor.com/Job/mexico-sap-mm-jobs-SRCH_IL.0,6_IN169_KO7,13.htm)
- [Glassdoor: SAP consultant jobs in Monterrey](https://www.glassdoor.com/Job/monterrey-mexico-sap-consultant-jobs-SRCH_IL.0,16_IM1579_KO17,31.htm)
- [LinkedIn: SAP MM (P2P) Consultant – ECC to S/4HANA](https://www.linkedin.com/jobs/view/sap-mm-p2p-consultant-%E2%80%93-ecc-to-s-4hana-at-jobs-via-dice-4430060184)
- [iTech: SAP Consulting México 2026](https://itechdev.com.mx/en/blog/sap-consulting-mexico): manufactura y retail son cerca del 55% de las instalaciones SAP en México (dato del proveedor, no verificado)
