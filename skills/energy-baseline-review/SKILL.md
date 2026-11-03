---
name: energy-baseline-review
description: Preparar una comparación energética normalizada distinguiendo variaciones operativas y ahorro estimado. En IAbot.io, asígnala a un empleado de análisis de eficiencia y aporta series de consumo, producción, ocupación y cambios conocidos de la instalación.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Energía y medioambiente
---

# Revisar una línea base de consumo

## Uso en IAbot.io

Asigna esta skill a **un empleado de análisis de eficiencia** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta series de consumo, producción, ocupación y cambios conocidos de la instalación.

**Ejemplo de encargo:** «Compara el consumo antes y después de esta actuación y explica qué cambios impiden atribuir todo a ahorro.»

**Resultado a revisar:** Comparación de consumos, indicadores normalizados y límites de la atribución.

## Cuándo usarla y qué necesita

Preparar una comparación energética normalizada distinguiendo variaciones operativas y ahorro estimado

Trabaja con series de consumo, producción, ocupación y cambios conocidos de la instalación. Necesita hojas de cálculo y documentos de consumo o instalación. Los factores, límites y criterios técnicos deben proceder de fuentes identificadas y vigentes para el encargo.

## Procedimiento

1. Define periodos comparables y registra cambios en clima, horarios, producción, ocupación o equipos.
2. Depura huecos y lecturas anómalas sin sustituirlas silenciosamente; conserva la cobertura de cada serie.
3. Calcula indicadores por unidad de actividad solo cuando numerador y denominador comparten periodo y alcance.
4. Compara escenarios y separa reducción observada de ahorro atribuible al proyecto según el método acordado.
5. Entrega sensibilidad y causas alternativas cuando los datos no permiten una atribución suficiente.

## Comprobación del resultado

- La línea base no mezcla edificios o procesos diferentes.
- Las exclusiones y estimaciones figuran en el informe.
- No se presenta una comparación simple como certificación de ahorro.

## Entrega

Comparación de consumos, indicadores normalizados y límites de la atribución.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [IDAE, eficiencia energética en la industria](https://www.idae.es/ayudas-y-financiacion/para-eficiencia-energetica-en-la-industria)
- [Ministerio para la Transición Ecológica](https://www.miteco.gob.es/)
