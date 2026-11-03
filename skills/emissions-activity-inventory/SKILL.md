---
name: emissions-activity-inventory
description: Organizar datos de actividad y cálculos de emisiones con factores, unidades y alcance trazables. En IAbot.io, asígnala a un empleado de sostenibilidad y aporta consumos, viajes, compras, límites del inventario y factores de emisión identificados.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Energía y medioambiente
---

# Inventario de datos de emisiones

## Uso en IAbot.io

Asigna esta skill a **un empleado de sostenibilidad** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta consumos, viajes, compras, límites del inventario y factores de emisión identificados.

**Ejemplo de encargo:** «Prepara el inventario de actividad de este año y separa resultados calculados de fuentes incompletas.»

**Resultado a revisar:** Registro de actividad, factores aplicados, emisiones calculadas y exclusiones.

## Cuándo usarla y qué necesita

Organizar datos de actividad y cálculos de emisiones con factores, unidades y alcance trazables

Trabaja con consumos, viajes, compras, límites del inventario y factores de emisión identificados. Necesita hojas de cálculo y documentos de consumo o instalación. Los factores, límites y criterios técnicos deben proceder de fuentes identificadas y vigentes para el encargo.

## Procedimiento

1. Fija entidad, periodo, límites organizativos y categorías incluidas en el método solicitado.
2. Concilia actividad con documentos y elimina duplicados entre registros de compra y consumo.
3. Vincula cada factor a fuente, año, geografía, unidad y versión; no mezcles factores incompatibles.
4. Calcula actividad por factor con conversiones explícitas y distingue emisiones calculadas de estimaciones.
5. Resume cobertura, exclusiones y revisión necesaria antes de cualquier declaración pública.

## Comprobación del resultado

- Las unidades del factor y la actividad son compatibles.
- Se evita el doble cómputo de una misma fuente.
- Un inventario preparado no se presenta como verificación independiente.

## Entrega

Registro de actividad, factores aplicados, emisiones calculadas y exclusiones.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [IDAE, eficiencia energética en la industria](https://www.idae.es/ayudas-y-financiacion/para-eficiencia-energetica-en-la-industria)
- [Ministerio para la Transición Ecológica](https://www.miteco.gob.es/)
