# Guía — Nómina 2026 · Empresas HC LLC (Puerto Rico)

Entregables para el reporte de pago de nómina, alineado al contrato y a la normativa
laboral y contributiva de Puerto Rico.

## Archivos

| Archivo | Qué es | Cómo se usa |
|---|---|---|
| `Nomina_2026_Empresas_HC_LLC.xlsx` | Plantilla de cálculo con fórmulas | Se llena cada período de pago |
| `reporte-nomina-hc-llc.html` | Reporte visual / dashboard | Para revisar y compartir (abre en el navegador) |
| `GUIA_Nomina_2026.md` | Este documento | Referencia |

## La plantilla Excel (5 hojas)

1. **Parámetros 2026** — Todas las tasas en un solo lugar (celdas **amarillas** editables).
   Las demás hojas leen estos valores por nombre, así que si una tasa cambia, se actualiza
   una sola vez aquí.
2. **Nómina W-2** — Registro de empleados. Ingrese las celdas amarillas
   (tarifa, horas regulares, horas extra, bruto acumulado del año y retención 499R);
   las columnas azules se calculan solas (bruto, Seguro Social, Medicare, SINOT, neto y
   costo patronal).
3. **Contratistas 1099** — Retención automática de 10% sobre servicios. Primeros $500/año
   exentos; escriba `S` en "Relevo total" para poner la retención en 0%.
4. **Bono Navidad** — Calcula el bono (Ley 148): 6% del salario con tope de $600, solo si el
   empleado trabajó ≥ 1,350 horas (1-oct a 30-sep).
5. **Resumen y Cumplimiento** — Totales del período + lista de verificación legal.

> Los topes anuales (Seguro Social, SINOT, desempleo) se aplican con la columna
> **"Bruto YTD anterior"**: escriba ahí lo acumulado del año antes de este período y la
> fórmula deja de retener al llegar al tope.

## Tasas y reglas aplicadas (2026)

| Concepto | Valor | Base legal |
|---|---|---|
| Salario mínimo | $10.50/h | Ley 47-2021 |
| Horas extra | 2× (doble) si >8h/día ó >40h/sem | Ley 379-1948 |
| Seguro Social (c/u) | 6.2% (base $176,100 — **verificar 2026**) | FICA |
| Medicare (c/u) | 1.45% (sin tope; +0.9% empleado sobre $200k) | FICA |
| SINOT (c/u) | 0.3% sobre primeros $9,000 | DTRH |
| FUTA neto | 0.6% sobre primeros $7,000 | Federal |
| SUTA | Tasa asignada por el DTRH (editar) | PR |
| Retención contratistas | 10% servicios; $500/año exento | Hacienda |
| Bono de Navidad | 6% (tope $600) si patrono >15 empl. | Ley 148 / Ley 4-2017 |

## Calendario de cumplimiento

- **Cada nómina:** salario mínimo, horas extra 2×, retener FICA + 499R.
- **Trimestral:** SINOT, Seguro por Desempleo (FUTA/SUTA), CFSE según póliza.
- **15-nov a 15-dic:** pagar Bono de Navidad.
- **31-ene:** emitir W-2PR (499R-2) a empleados y 480.6 a contratistas.

## Aviso

Cifras de ejemplo con fines ilustrativos. Verifique la base de Seguro Social 2026, la tasa
SUTA asignada a HC LLC y las tablas de retención 499R con el **Departamento de Hacienda** y el
**DTRH** antes de cada corrida. Esta plantilla no sustituye asesoría contributiva o legal profesional.

## Fuentes

- [Ley 47-2021 — Salario Mínimo](https://bvirtualogp.pr.gov/ogp/bvirtual/leyesreferencia/pdf/47-2021.pdf)
- [Ley 379-1948 — Jornada de Trabajo / Horas Extra](https://www.trabajo.pr.gov/docs/Leyes/Ley_379_-_Jornada_de_Trabajo.pdf)
- [Ley 148 — Bono de Navidad](https://www.trabajo.pr.gov/bono_empresa_privada.asp)
- [DTRH — SINOT](https://www.trabajo.pr.gov/sinot.asp)
- [Guía de nómina PR para patronos (2025)](https://praaccounting.com/nomina-en-puerto-rico-2025-guia-completa-para-empleadores/)
