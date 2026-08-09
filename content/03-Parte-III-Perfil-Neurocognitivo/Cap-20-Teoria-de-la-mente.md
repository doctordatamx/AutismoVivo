---
tipo: capitulo
parte: "Parte-III"
numero: 20
titulo: "Teoría de la mente, empatía y perspectiva autista"
dg-publish: false
dg-home: false
dg-permalink: /capitulos/teoria-de-la-mente
ultima_actualizacion: "2026-08-08"
version: "1.7"
conocimiento: 10
fuentes_integradas:
  - "[[2025-Cusson-empathy-measures-meta-analysis]]"
  - "[[2025-Bai-biological-motion-systematic-review]]"
  - "[[2025-Sapey-Triomphe-MMN-meta-analysis]]"
  - "[[2025-Ghiglino-humanoid-robot-ToM-RCT]]"
  - "[[2024-Cheang-empathic-accuracy-double-empathy]]"
  - "[[2024-Brett-Perth-Empathy-Scale]]"
  - "[[2025-Poglitsch-GPT4o-ToM-gamified]]"
  - "[[2025-Koelkebeck-body-facial-emotion]]"
  - "[[2026-Marsicano-causality-judgment-autism-schizotypy]]"
  - "[[2025-Liu-multimodal-metaphors-neural]]"
estado: revision
resumen_ejecutivo: "La empatía es multidimensional (cognitiva vs afectiva). Meta-análisis 2025 (226 estudios): reducción grande en empatía cognitiva (g≈−0.85) y en medidas unidimensionales tipo EQ (g≈−1.70); afectiva solo ligeramente menor (g≈−0.17) y no significativa en estudios de alta calidad. IRI: menos concern pero más distress personal. El instrumento determina el hallazgo; no tratar el autismo como ‘trastorno de empatía’ global. Un ECA cruzado muestra que el entrenamiento de ToM con el robot humanoide iCub mejora NEPSY-II ToM más que terapia estándar y más que el mismo protocolo con un clínico humano."
preguntas_abiertas:
  - "¿Qué medidas de empatía tienen invariancia de medición en muestras autistas?"
  - "¿Cómo operacionalizar doble empatía en diseños experimentales de díadas mixtas?"
  - "¿Los beneficios del entrenamiento de ToM asistido por robot se generalizan más allá del contexto de rol-playing entrenado?"
tags:
  - tea/capitulo
bibliography: "03-Datos/references.bib"
---

# Capítulo 20 — Teoría de la mente, empatía y perspectiva autista

<!-- sync:version-badge -->
> **v1.7** · conocimiento **10** · actualizado **2026-08-08**
<!-- /sync:version-badge -->

## Resumen ejecutivo

La empatía es **multidimensional**. Un meta-análisis PRISMA de 226 estudios ([@cusson2025]; [[2025-Cusson-empathy-measures-meta-analysis]]) muestra reducción **grande** en empatía cognitiva y en scores unidimensionales (EQ), pero solo un efecto **pequeño/no robusto** en empatía afectiva. El perfil encaja mejor con **desequilibrio empático** (perspectiva ↓, distress ↑) que con ausencia de afecto.

## Contenido

### Empatía cognitiva vs afectiva

Cusson et al. ([@cusson2025]) sintetizan ~**13 278** participantes autistas y ~**44 218** típicos:

| Componente | Hedges' *g* | Interpretación |
|------------|-------------|----------------|
| Cognitiva | **−0.85** | Efecto grande (menor en autistas) |
| Afectiva | **−0.17** | Efecto pequeño; **ns** si solo estudios alta calidad |
| Unidimensional (p. ej. EQ) | **−1.70** | Efecto muy grande; alta heterogeneidad (*I*²≈94%) |

La diferencia cognitiva ≫ afectiva (*p* <.0001). Esto apoya la hipótesis de **desequilibrio empático**: dificultad de perspectiva / ToM afectiva, con sensibilidad afectiva relativamente preservada que puede desbordarse en **distress personal** más que en *concern* orientado al otro ([@cusson2025]).

### El instrumento lo decide

| Medida | *g* (aprox.) | Nota |
|--------|--------------|------|
| RMET / RMET-C | −0.76 / −0.71 | A menudo tratado como empatía cognitiva; crítica: reconocimiento emocional |
| EQ / EQ-C | −1.70 / −1.84 | Mezcla skills sociales + empatía; infla el “déficit” |
| IRI-PT (perspectiva) | −0.99 | Cognitiva |
| IRI-EC (concern) | −0.59 | Afectiva other-oriented |
| IRI-PD (distress) | **+0.67** | Más distress en autistas |

Conclusión de los autores: medir empatía como **constructo unidimensional distorsiona e infla** la idea de déficit ([@cusson2025]). Revisiones COSMIN cuestionan EQ/IRI en muestras autistas.

### Moderadores

No moderaron de forma significativa: año de publicación, calidad del estudio, alexitimia (en meta-regresión), CI verbal ni edad (niños vs adultos). **Sexo** sí en empatía unidimensional: mayor gap en mujeres autistas vs típicas que en varones ([@cusson2025]; ver [[Cap-11-Diagnostico-mujeres]]).

Mayor **variabilidad** relativa de scores en el grupo autista → muchos individuos dentro de 1 DE del grupo típico pese a *g* grandes a nivel de grupo. Utilidad diagnóstica de “empatía” limitada.

### Tareas ecológicas y doble empatía

Revisión cualitativa: distress fingido, *empathic accuracy*, empatía al dolor y self-other suelen mostrar **diferencias mínimas o mixtas** ([@cusson2025]). El **problema de la doble empatía** (neurotipos distintos) sugiere que las medidas hechas por/para neurotipicos sesgan el resultado; ver [[Cap-51-Autodefensa-neurodiversidad]].

### Percepción de acciones: ¿mentalizar o percibir?

Una revisión sistemática de 51 estudios sobre percepción de movimiento biológico y acciones halla que las diferencias autistas son más consistentes en tareas de **identificación/interpretación** de la acción que en la mera **detección** del movimiento ([@bai2025]; [[2025-Bai-biological-motion-systematic-review]]). Esto matiza los modelos puramente "mentalistas" de teoría de la mente: parte de la dificultad para inferir intenciones ajenas podría tener raíz en el procesamiento **perceptivo global**, no solo en la atribución mental en sí ([[Cap-18-Procesamiento-sensorial]]).

### Codificación predictiva: evidencia electrofisiológica

Un meta-análisis de 38 estudios de mismatch negativity (MMN) auditiva —índice electrofisiológico de error de predicción— halla un patrón dependiente de la edad: niños/adolescentes autistas muestran MMN reducida en paradigmas de mayor incertidumbre (multifeature), mientras que los adultos autistas muestran MMN aumentada, sin diferencias de latencia ([@sapeytriomphe2025]; [[2025-Sapey-Triomphe-MMN-meta-analysis]]). Este hallazgo aporta evidencia electrofisiológica concreta a los marcos de codificación predictiva que buscan explicar diferencias en la atribución de estados mentales e intenciones ajenas, sugiriendo que el "error de predicción" alterado no es estático sino que cambia a lo largo del desarrollo (ver también [[Cap-18-Procesamiento-sensorial]]).

### Entrenamiento de ToM asistido por robot humanoide (ECA)

Un ensayo controlado aleatorizado cruzado (N=32 niños autistas, 7,53±1,32 años) comparó el entrenamiento de teoría de la mente asistido por el robot humanoide **iCub** (Robot-Assisted Training, RAT) con la terapia estándar en curso (ST), usando la subescala de Percepción Social del NEPSY-II como desenlace. El grupo RAT mostró mejoras significativamente mayores que ST (interacción F(1,62)=43,6, p<.001). Para aislar la contribución específica del robot, un grupo de control humano activo (N=14) replicó el mismo protocolo de rol-playing con un clínico entrenado en lugar del robot, y **no mostró mejora significativa** (d=-1,99 favoreciendo a RAT, p<.001) — evidencia de que la presencia física y consistencia del robot, no solo el protocolo de entrenamiento, impulsó la mejora ([@ghiglino2025]; [[2025-Ghiglino-humanoid-robot-ToM-RCT]]). Las mejoras se mantuvieron en el seguimiento sin regresión observable. Ver aplicaciones tecnológicas más amplias en [[Cap-38-Tecnologia-asistiva]] y su relación con habilidades sociales en [[Cap-35-Habilidades-sociales]].

### La lectura mental también falla en dirección contraria

Una tarea de precisión empática con narradores autistas y no autistas mostró que 81 adultos de población general fueron **significativamente menos precisos** al inferir las emociones de los narradores **autistas**, especialmente alegría y tristeza, pese a experimentar una **intensidad corporal mayor** ante ellos, sobre todo para ira y miedo ([@cheang2024]; [[2024-Cheang-empathic-accuracy-double-empathy]]). La atribución de estados mentales entre personas autistas y no autistas falla en **ambas direcciones**, lo que exige reformular la teoría de la mente como problema relacional y no como déficit unilateral (ver [[Cap-16-Interaccion-social]], [[Cap-51-Autodefensa-neurodiversidad]]).


### Inferencia causal y priors (continuum autismo–esquizotipia)

En adultos neurotípicos a lo largo de rasgos autistas y esquizotípicos, los juicios de causalidad en colisiones dependen del timing físico y de la dependencia serial de decisiones previas: perfiles **SSD-like** pesan más los priors; **ASD-like**, menos ([@marsicano2026causal]; [[2026-Marsicano-causality-judgment-autism-schizotypy]]; ver [[Cap-13-Diagnostico-diferencial]], [[Cap-06-Neurobiologia]]). Útil para pensar estilos predictivos divergentes sin asumir déficit social monolítico.

### Perspectivas clave

- **Evidencia clínica:** perfil cognitivo ↓ / afectivo ≈; no “cero empatía”; evidencia electrofisiológica (MMN) de errores de predicción alterados de forma dependiente de la edad; evidencia experimental (ECA) de que el entrenamiento de ToM asistido por robot humanoide supera a terapia estándar y a un control humano activo equivalente.
- **Experiencia vivida:** parecer frío puede ser sobrecarga afectiva o malentendido mutuo; la consistencia y previsibilidad de un robot puede reducir la ansiedad social durante el entrenamiento de habilidades de ToM.
- **Controversias:** EQ como cribado de “rasgos”; extreme male brain; ToM como mito totalizador; si la tecnología robótica en terapia complementa o distrae de la relación terapéutica humana.

### Preguntas abiertas

- ¿Qué baterías multi-método son válidas en TEA?
- ¿Cómo integrar alexitimia y rasgos callous-unemotional sin confundir perfiles?

## Fuentes integradas

```dataview
LIST
FROM "01-Fuentes"
WHERE contains(capitulos_relacionados, this.file.link)
SORT fecha_captura DESC
```


### Perth Empathy Scale y heterogeneidad empática

Con la Perth Empathy Scale en N=239 personas autistas se confirma que la empatía no es un déficit unitario sino un conjunto heterogéneo de manifestaciones: el mito de la «falta de empatía» no encaja con la estructura empírica de la PES. ([@brett2024]; [[2024-Brett-Perth-Empathy-Scale]]).

### GPT-4o y evaluación gamificada de teoría de la mente

GPT-4o iguala aproximadamente a expertos humanos al calificar tareas de teoría de la mente en un entorno gamificado: prometedor para evaluación asistida escalable, pendiente de validación ética y ecológica. ([@poglitsch2025]; [[2025-Poglitsch-GPT4o-ToM-gamified]]).

### Cuerpo y rostro en percepción emocional (autismo/SAD)

En N=107 (autismo, ansiedad social y NT), la percepción emocional alterada involucra rostro y cuerpo: el perfil multimodal ayuda a distinguir y solapar contribuciones del autismo y de la ansiedad social. ([@koelkebeck2025]; [[2025-Koelkebeck-body-facial-emotion]]).


### Metáfora, cognición social y multimodalidad

El procesamiento metafórico multimodal informa cómo se reconstruye significado cuando fallan vías verbales ([@liu2025metaphor]; [[2025-Liu-multimodal-metaphors-neural]]).

## Referencias citadas

- [@liu2025metaphor] — [[2025-Liu-multimodal-metaphors-neural]]

- [@marsicano2026causal] — [[2026-Marsicano-causality-judgment-autism-schizotypy]]

- [@brett2024] — [[2024-Brett-Perth-Empathy-Scale]]
- [@poglitsch2025] — [[2025-Poglitsch-GPT4o-ToM-gamified]]
- [@koelkebeck2025] — [[2025-Koelkebeck-body-facial-emotion]]

- [@cheang2024] — [[2024-Cheang-empathic-accuracy-double-empathy]]
- [@bai2025] — [[2025-Bai-biological-motion-systematic-review]]
- [@cusson2025] — [[2025-Cusson-empathy-measures-meta-analysis]]
- [@sapeytriomphe2025] — [[2025-Sapey-Triomphe-MMN-meta-analysis]]
- [@ghiglino2025] — [[2025-Ghiglino-humanoid-robot-ToM-RCT]]

## Enlaces relacionados

- [[Cap-16-Interaccion-social]]
- [[Cap-15-Comunicacion-social]]
- [[Cap-01-Que-es-el-autismo]]
- [[Cap-51-Autodefensa-neurodiversidad]]
- [[Cap-18-Procesamiento-sensorial]]
- [[Cap-38-Tecnologia-asistiva]]
- [[Cap-35-Habilidades-sociales]]
- [[Apendice-A-Glosario]] — ToM, doble empatía, alexitimia, codificación predictiva
