---
name: solar-production-monitoring
description: Revisar producción fotovoltaica y anomalías de datos frente a referencias documentadas. En IAbot.io, asígnala a un empleado de operación energética y aporta series de generación, disponibilidad, diseño y alertas de la instalación.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Energía y medioambiente
---

# Seguimiento de producción fotovoltaica

## Uso en IAbot.io

Asigna esta skill a **un empleado de operación energética** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta series de generación, disponibilidad, diseño y alertas de la instalación.

**Ejemplo de encargo:** «Analiza esta producción mensual y diferencia caída de rendimiento, indisponibilidad y falta de datos.»

**Resultado a revisar:** Informe de producción con anomalías, cobertura y comprobaciones sugeridas.

## Cuándo usarla y qué necesita

Revisar producción fotovoltaica y anomalías de datos frente a referencias documentadas

Trabaja con series de generación, disponibilidad, diseño y alertas de la instalación. Necesita hojas de cálculo y documentos de consumo o instalación. Los factores, límites y criterios técnicos deben proceder de fuentes identificadas y vigentes para el encargo.

## Procedimiento

1. Alinea fecha, zona horaria, intervalo, equipo y unidad entre generación, disponibilidad y referencia.
2. Detecta datos ausentes, contadores reiniciados y energía acumulada interpretada erróneamente como potencia.
3. Compara producción con la referencia aportada distinguiendo irradiación, indisponibilidad y cambios de configuración.
4. Relaciona anomalías con alertas reales y plantea comprobaciones al responsable, sin diagnosticar a distancia una avería eléctrica.
5. Resume periodos afectados, energía y confianza del análisis con enlaces a las series de origen.

## Comprobación del resultado

- La referencia corresponde a la instalación y periodo analizados.
- No se cuentan intervalos duplicados por cambios de hora.
- Las propuestas no incluyen maniobras eléctricas ni eludir protecciones.

## Entrega

Informe de producción con anomalías, cobertura y comprobaciones sugeridas.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [IDAE, eficiencia energética en la industria](https://www.idae.es/ayudas-y-financiacion/para-eficiencia-energetica-en-la-industria)
- [Ministerio para la Transición Ecológica](https://www.miteco.gob.es/)
