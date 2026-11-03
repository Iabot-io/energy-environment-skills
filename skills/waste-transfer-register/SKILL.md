---
name: waste-transfer-register
description: Reconciliar entradas, salidas y documentación de residuos por centro y flujo. En IAbot.io, asígnala a un empleado de gestión ambiental y aporta albaranes, documentos de traslado, contratos y catálogo aplicable de residuos.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Energía y medioambiente
---

# Registro documental de residuos

## Uso en IAbot.io

Asigna esta skill a **un empleado de gestión ambiental** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta albaranes, documentos de traslado, contratos y catálogo aplicable de residuos.

**Ejemplo de encargo:** «Revisa los traslados del trimestre y señala cantidades o documentos que no concilian.»

**Resultado a revisar:** Registro por flujo con cantidades, documentos y discrepancias.

## Cuándo usarla y qué necesita

Reconciliar entradas, salidas y documentación de residuos por centro y flujo

Trabaja con albaranes, documentos de traslado, contratos y catálogo aplicable de residuos. Necesita hojas de cálculo y documentos de consumo o instalación. Los factores, límites y criterios técnicos deben proceder de fuentes identificadas y vigentes para el encargo.

## Procedimiento

1. Identifica centro, productor, residuo, gestor y documentos realmente disponibles para cada movimiento.
2. Conserva códigos y clasificaciones aportados; remite dudas de clasificación al responsable competente.
3. Normaliza cantidades y unidades, separando pesos medidos de estimados y documentos rectificados.
4. Reconcilia salidas con aceptación y justificantes, identificando movimientos abiertos o duplicados.
5. Prepara el resumen por periodo y un listado de documentación o aclaraciones pendientes.

## Comprobación del resultado

- Cada movimiento mantiene fecha, origen y destino identificables.
- No se decide peligrosidad a partir de un nombre informal.
- Los justificantes pendientes no se marcan recibidos.

## Entrega

Registro por flujo con cantidades, documentos y discrepancias.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [IDAE, eficiencia energética en la industria](https://www.idae.es/ayudas-y-financiacion/para-eficiencia-energetica-en-la-industria)
- [Ministerio para la Transición Ecológica](https://www.miteco.gob.es/)
