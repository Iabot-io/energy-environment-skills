# Energía y medioambiente · Skills para empleados IA de IAbot.io

Facturas y consumos, producción energética, datos de emisiones, residuos y obligaciones documentadas de instalaciones.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Normalizar facturas energéticas](skills/energy-invoice-normalization/SKILL.md) | un empleado de gestión energética | Tabla conciliada de energía y costes con incidencias de facturación. |
| [Revisar una línea base de consumo](skills/energy-baseline-review/SKILL.md) | un empleado de análisis de eficiencia | Comparación de consumos, indicadores normalizados y límites de la atribución. |
| [Seguimiento de producción fotovoltaica](skills/solar-production-monitoring/SKILL.md) | un empleado de operación energética | Informe de producción con anomalías, cobertura y comprobaciones sugeridas. |
| [Inventario de datos de emisiones](skills/emissions-activity-inventory/SKILL.md) | un empleado de sostenibilidad | Registro de actividad, factores aplicados, emisiones calculadas y exclusiones. |
| [Registro documental de residuos](skills/waste-transfer-register/SKILL.md) | un empleado de gestión ambiental | Registro por flujo con cantidades, documentos y discrepancias. |
| [Seguimiento de obligaciones ambientales](skills/environmental-permit-obligations/SKILL.md) | un empleado de cumplimiento ambiental | Matriz de obligaciones con fuente, condición, plazo y evidencia requerida. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/energy-environment-skills --list
npx skills add Iabot-io/energy-environment-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Normalizar facturas energéticas:** «Convierte estas facturas en una tabla por suministro y detecta solapes de periodo o lecturas estimadas.»
- **Revisar una línea base de consumo:** «Compara el consumo antes y después de esta actuación y explica qué cambios impiden atribuir todo a ahorro.»
- **Seguimiento de producción fotovoltaica:** «Analiza esta producción mensual y diferencia caída de rendimiento, indisponibilidad y falta de datos.»

## Herramientas y límites

Necesita hojas de cálculo y documentos de consumo o instalación. Los factores, límites y criterios técnicos deben proceder de fuentes identificadas y vigentes para el encargo.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [IDAE, eficiencia energética en la industria](https://www.idae.es/ayudas-y-financiacion/para-eficiencia-energetica-en-la-industria)
- [Ministerio para la Transición Ecológica](https://www.miteco.gob.es/)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
