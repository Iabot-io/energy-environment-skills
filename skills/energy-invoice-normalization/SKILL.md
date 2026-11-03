---
name: energy-invoice-normalization
description: Consolidar costes y consumos energéticos separando periodos, unidades y conceptos facturados. En IAbot.io, asígnala a un empleado de gestión energética y aporta facturas, contratos, puntos de suministro y lecturas del periodo.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Energía y medioambiente
---

# Normalizar facturas energéticas

## Uso en IAbot.io

Asigna esta skill a **un empleado de gestión energética** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta facturas, contratos, puntos de suministro y lecturas del periodo.

**Ejemplo de encargo:** «Convierte estas facturas en una tabla por suministro y detecta solapes de periodo o lecturas estimadas.»

**Resultado a revisar:** Tabla conciliada de energía y costes con incidencias de facturación.

## Cuándo usarla y qué necesita

Consolidar costes y consumos energéticos separando periodos, unidades y conceptos facturados

Trabaja con facturas, contratos, puntos de suministro y lecturas del periodo. Necesita hojas de cálculo y documentos de consumo o instalación. Los factores, límites y criterios técnicos deben proceder de fuentes identificadas y vigentes para el encargo.

## Procedimiento

1. Identifica suministro, contador, periodo facturado y tipo de lectura de cada documento.
2. Separa energía, potencia, peajes, servicios, impuestos y abonos según su denominación real.
3. Normaliza unidades y conserva el dato original; distingue consumo medido, estimado y regularizado.
4. Detecta periodos solapados, facturas rectificativas y huecos antes de sumar costes o consumos.
5. Concilia total de factura y tabla, explicando diferencias de redondeo o conceptos no energéticos.

## Comprobación del resultado

- No se suma una factura rectificada junto con su sustituta.
- Se distingue kW de kWh y energía de importe monetario.
- Cada fila conserva el documento y periodo originales.

## Entrega

Tabla conciliada de energía y costes con incidencias de facturación.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [IDAE, eficiencia energética en la industria](https://www.idae.es/ayudas-y-financiacion/para-eficiencia-energetica-en-la-industria)
- [Ministerio para la Transición Ecológica](https://www.miteco.gob.es/)
