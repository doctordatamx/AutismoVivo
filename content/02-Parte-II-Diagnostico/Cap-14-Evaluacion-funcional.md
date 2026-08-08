---
tipo: capitulo
parte: "Parte-II"
numero: 14
titulo: "Evaluación funcional: comunicación, adaptativa, sensorial"
dg-publish: false
dg-home: false
dg-permalink: /capitulos/evaluacion-funcional
ultima_actualizacion: "2026-07-29"
version: "1.3"
conocimiento: 6
fuentes_integradas:
  - "[[2026-Han-behavioral-network-comorbidity]]"
  - "[[2025-Chen-anxiety-scales-treatment-outcomes]]"
  - "[[2025-Aitken-adaptive-behavior-trajectories-ML]]"
  - "[[2025-Russo-developmental-approach-IQ-neuroimaging]]"
  - "[[2026-Kolisnyk-sensory-phenotypes-connectome-ML]]"
  - "[[2025-Furnier-ADDM-prevalence-adaptive]]"
estado: borrador
resumen_ejecutivo: "La evaluación funcional en TEA va más allá del diagnóstico categórico: modelos de red (PDDBI) sitúan ansiedad y TDAH como nodos centrales de comorbilidad; la elección de instrumento (interferencia vs. síntoma) determina si se detecta bien el cambio clínico; las Vineland-3 combinadas con machine learning predicen trayectorias de conducta adaptativa (77% exactitud) sin que más horas de terapia mejoren la predicción; y controlar por CI es un prerrequisito metodológico, no solo clínico."
preguntas_abiertas:
  - "¿Qué combinaciones de instrumentos (red conductual + interferencia funcional + adaptativa) ofrecen la evaluación más completa y eficiente?"
  - "¿Cómo integrar predicción de trayectorias (ML) en la planificación clínica sin generar profecías autocumplidas o exclusión de apoyos?"
tags:
  - tea/capitulo
bibliography: "03-Datos/references.bib"
---

# Capítulo 14 — Evaluación funcional: comunicación, adaptativa, sensorial

<!-- sync:version-badge -->
> **v1.3** · conocimiento **6** · actualizado **2026-07-29**
<!-- /sync:version-badge -->

## Resumen ejecutivo

La evaluación funcional en TEA busca capturar cómo una persona se comunica, se adapta y regula su conducta en la vida cotidiana, más allá de la etiqueta diagnóstica. Modelos de red conductual sitúan a la ansiedad y el TDAH como los nodos de comorbilidad más centrales ([@han2026]; [[2026-Han-behavioral-network-comorbidity]]). La elección de instrumento —medidas de **interferencia funcional** frente a medidas de **síntomas**— determina si se detecta bien el cambio clínico tras tratamiento ([@chen2025]; [[2025-Chen-anxiety-scales-treatment-outcomes]]). Las escalas de conducta adaptativa (Vineland-3), combinadas con machine learning, permiten predecir trayectorias individuales con razonable exactitud ([@aitken2025]; [[2025-Aitken-adaptive-behavior-trajectories-ML]]).

## Contenido

### Introducción

La evaluación funcional complementa al diagnóstico categórico (ver [[Cap-09-Herramientas-cribado]], [[Cap-10-Proceso-diagnostico]]) con una mirada dimensional: qué necesita apoyo, en qué dominio, y cómo cambia con el tiempo. Se apoya en instrumentos de comunicación, conducta adaptativa, comorbilidad psiquiátrica y procesamiento sensorial.

### Modelos de red para evaluar comorbilidad

En lugar de tratar cada comorbilidad como categoría aislada, un estudio con la cohorte ABC-CT (N=280, 6-11 años) construyó un modelo de red conductual (PDDBI) que conceptualiza el autismo como sistema de conductas de **aproximación-retirada**. Las asociaciones más fuertes con comorbilidad fueron para **ansiedad** y **TDAH**; los nodos de regulación afectiva se relacionaron con síntomas internalizantes y los de arousal/sensoriales con externalizantes ([@han2026]; [[2026-Han-behavioral-network-comorbidity]]). Este enfoque ayuda a mitigar el "diagnostic overshadowing" (atribuir toda comorbilidad al autismo) al identificar objetivos de evaluación específicos; ver [[Cap-07-Comorbilidades]], [[Cap-47-Salud-mental]].

### La elección del instrumento determina el resultado

Un análisis secundario del ECA TAASD (N=212 niños autistas) comparó escalas de ansiedad frente al estándar de oro (entrevista ADIS/ASA) para detectar recuperación diagnóstica tras tratamiento. La Child Anxiety Impact Scale-Parent (CAIS-P), centrada en **interferencia funcional**, obtuvo AUC=**0,802**, mientras que escalas de síntomas convencionales rindieron con frecuencia por debajo de AUC=0,55 ([@chen2025]; [[2025-Chen-anxiety-scales-treatment-outcomes]]). Este hallazgo es generalizable como principio de evaluación funcional: medir **impacto/interferencia** en la vida diaria puede ser más sensible al cambio clínico que medir solo síntomas, un criterio a considerar al elegir instrumentos para cualquier dominio evaluado (sensorial, comunicación, adaptativo).

### Trayectorias de conducta adaptativa y predicción

Un estudio de cohorte clínica (N=1225, red Cortica Healthcare) usó latent class growth mixture modeling sobre las Vineland Adaptive Behavior Scales-3 (VABS-3) e identificó dos trayectorias de conducta adaptativa: "menor deterioro/mejora" (≥66%) y "mayor deterioro/estable" (≤33%). En un subconjunto (N=729) con datos de ingreso detallados, un modelo de random forest predijo la trayectoria con **77% de exactitud**, usando predictores como nivel socioeconómico, historia de regresión evolutiva, temperamento, severidad basal y preocupaciones parentales. De forma notable, las **horas acumuladas de ABA y terapias del desarrollo no mejoraron la predicción** ([@aitken2025]; [[2025-Aitken-adaptive-behavior-trajectories-ML]]). Esto sugiere que la evaluación funcional de ingreso (más allá de solo diagnóstico) tiene valor pronóstico propio, independiente de la intensidad de intervención planificada; ver [[Cap-29-Principios-intervencion]], [[Cap-30-Intervencion-temprana]].

### Un prerrequisito metodológico: controlar por capacidad cognitiva

Al evaluar funcionalmente a una persona autista —y al interpretar investigación sobre autismo en general— es clínicamente relevante no confundir efectos del autismo con efectos de la capacidad cognitiva (CI). Un comentario metodológico argumenta que autismo y CI son constructos distintos y disociables, con vías genéticas que pueden tener relaciones opuestas con la cognición, y que no controlar por CI (algo que ocurrió en solo 64% de los estudios en un meta-análisis reciente de EEG en reposo) puede generar conclusiones espurias ([@russo2025]; [[2025-Russo-developmental-approach-IQ-neuroimaging]]). Aplicado a la evaluación funcional: los instrumentos y las expectativas de desempeño deben considerar el nivel cognitivo de la persona, sin asumir automáticamente que toda dificultad se debe al autismo per se; ver [[Cap-06-Neurobiologia]], [[Cap-01-Que-es-el-autismo]].

### Perfilado sensorial con correlato neural

El perfilado sensorial no es solo descriptivo: en 146 niños y adolescentes autistas clasificados en cinco fenotipos del *Short Sensory Profile* —adaptativo, diferencias generalizadas, sensibilidad a gusto y olfato, hiporrespuesta y búsqueda, y dificultades de movimiento con baja energía—, modelos de *machine learning* sobre métricas de grafo del conectoma funcional discriminaron por encima del azar en **7 de 10** pares de fenotipos ([@kolisnyk2026]; [[2026-Kolisnyk-sensory-phenotypes-connectome-ML]]). Para la evaluación funcional esto respalda documentar el **perfil sensorial** como dimensión propia y no como apéndice de las conductas repetitivas (ver [[Cap-18-Procesamiento-sensorial]], [[Cap-06-Neurobiologia]]).

### Perspectivas clave

- **Evidencia clínica:** los modelos de red (comorbilidad, irritabilidad) y las medidas de interferencia funcional ofrecen alternativas más sensibles que las categorías diagnósticas o escalas de síntomas puros; la conducta adaptativa (VABS-3) combinada con ML tiene valor predictivo real desde el ingreso.
- **Experiencia vivida:** una evaluación funcional bien hecha puede evitar atribuir toda dificultad al "autismo" cuando en realidad refleja ansiedad, TDAH, o nivel cognitivo específico no considerado.
- **Controversias y debates:** el riesgo de que la predicción de trayectorias (ML) se use para limitar apoyos en lugar de personalizarlos; si "más horas de terapia" sigue siendo un proxy válido de intensidad de intervención cuando no predice mejor resultado en datos observacionales.

### Preguntas abiertas

- ¿Qué combinaciones de instrumentos (red conductual + interferencia funcional + adaptativa) ofrecen la evaluación más completa y eficiente?
- ¿Cómo integrar predicción de trayectorias (ML) en la planificación clínica sin generar profecías autocumplidas o exclusión de apoyos?


### Prevalencia ADDM por nivel adaptativo (leve ↑)

En ADDM, la prevalencia con funcionamiento adaptativo leve pasa de 5,1 a 17,6/1000 mientras moderado–profundo permanece estable: el aumento epidemiológico se concentra en el estrato leve. ([@furnier2025]; [[2025-Furnier-ADDM-prevalence-adaptive]]).

## Referencias citadas

- [@furnier2025] — [[2025-Furnier-ADDM-prevalence-adaptive]]

- [@kolisnyk2026] — [[2026-Kolisnyk-sensory-phenotypes-connectome-ML]]
- [@han2026] — [[2026-Han-behavioral-network-comorbidity]]
- [@chen2025] — [[2025-Chen-anxiety-scales-treatment-outcomes]]
- [@aitken2025] — [[2025-Aitken-adaptive-behavior-trajectories-ML]]
- [@russo2025] — [[2025-Russo-developmental-approach-IQ-neuroimaging]]

```dataview
LIST
FROM "01-Fuentes"
WHERE contains(capitulos_relacionados, this.file.link)
SORT fecha_captura DESC
```

## Enlaces relacionados

- [[Cap-07-Comorbilidades]]
- [[Cap-47-Salud-mental]]
- [[Cap-09-Herramientas-cribado]]
- [[Cap-29-Principios-intervencion]]
- [[Cap-30-Intervencion-temprana]]
- [[Cap-06-Neurobiologia]]
- [[Apendice-A-Glosario]] — conducta adaptativa, Vineland, CI, comorbilidad
