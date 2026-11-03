---
name: environmental-permit-obligations
description: Extraer obligaciones documentadas de permisos ambientales y convertirlas en un calendario revisable. En IAbot.io, asígnala a un empleado de cumplimiento ambiental y aporta permisos, resoluciones, modificaciones y calendario de la instalación.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Energía y medioambiente
---

# Seguimiento de obligaciones ambientales

## Uso en IAbot.io

Asigna esta skill a **un empleado de cumplimiento ambiental** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta permisos, resoluciones, modificaciones y calendario de la instalación.

**Ejemplo de encargo:** «Extrae las obligaciones de esta autorización y vincula cada vencimiento con su condición y responsable.»

**Resultado a revisar:** Matriz de obligaciones con fuente, condición, plazo y evidencia requerida.

## Cuándo usarla y qué necesita

Extraer obligaciones documentadas de permisos ambientales y convertirlas en un calendario revisable

Trabaja con permisos, resoluciones, modificaciones y calendario de la instalación. Necesita hojas de cálculo y documentos de consumo o instalación. Los factores, límites y criterios técnicos deben proceder de fuentes identificadas y vigentes para el encargo.

## Procedimiento

1. Fija instalación, versiones y relación entre autorización original y modificaciones.
2. Extrae obligaciones literales con número de condición y distingue periodicidad de plazo puntual.
3. Calcula fechas solo cuando el hito de inicio y la regla estén confirmados; señala interpretaciones pendientes.
4. Relaciona cada obligación con responsable y documento acreditativo, conservando las excepciones concedidas.
5. Entrega un calendario propuesto para validación sin registrar ni presentar trámites por sí mismo.

## Comprobación del resultado

- Las modificaciones prevalentes están identificadas.
- Cada fecha se puede reconstruir desde su condición de origen.
- La tabla no sustituye una interpretación jurídica o técnica necesaria.

## Entrega

Matriz de obligaciones con fuente, condición, plazo y evidencia requerida.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [IDAE, eficiencia energética en la industria](https://www.idae.es/ayudas-y-financiacion/para-eficiencia-energetica-en-la-industria)
- [Ministerio para la Transición Ecológica](https://www.miteco.gob.es/)
