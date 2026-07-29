---
tipo: capitulo
parte: "Parte-V"
numero: 29
titulo: "Principios de intervención basada en evidencia"
dg-publish: true
dg-home: false
dg-permalink: /capitulos/principios-intervencion
ultima_actualizacion: "2026-07-29"
version: "1.3"
fuentes_integradas:
  - "[[2025-Wang-understanding-autism]]"
  - "[[2025-Bottema-Beutel-problem-behavior-measurement]]"
  - "[[2025-Aitken-adaptive-behavior-trajectories-ML]]"
estado: revision
resumen_ejecutivo: "No hay fármacos aprobados para síntomas nucleares del TEA. Las intervenciones no farmacológicas (habilidades, comunicación, terapias psicosociales, digitales, ejercicio, etc.) buscan autonomía, comunicación y calidad de vida. La estimulación cerebral no invasiva (tDCS/rTMS) y fármacos experimentales siguen en evaluación; priorizar individualización y etiología. Un estudio de cohorte con machine learning halla que las horas acumuladas de ABA/terapias del desarrollo no mejoran la predicción de la trayectoria de conducta adaptativa, cuestionando la dosis como único parámetro relevante."
preguntas_abiertas:
  - "¿Qué paquetes de intervención son costo-efectivos fuera de EE.UU./Europa?"
  - "¿Cuándo combinar oxitocina u otras moléculas con terapia conductual?"
  - "¿Por qué las horas acumuladas de terapia no predicen mejor trayectoria, y qué variables sí lo hacen?"
tags:
  - tea/capitulo
bibliography: "03-Datos/references.bib"
---

# Capítulo 29 — Principios de intervención basada en evidencia

## Resumen ejecutivo

No hay fármacos aprobados para **síntomas nucleares** del TEA ([@wang2025]; [[2025-Wang-understanding-autism]]). Las intervenciones no farmacológicas buscan autonomía, comunicación y calidad de vida. tDCS/rTMS y fármacos experimentales siguen en evaluación; priorizar **individualización**.

## Contenido

### Principios

1. Apoyar comunicación y participación, no “normalizar” identidad ([@wang2025] enmarca metas de habilidades y calidad de vida)
2. Tratar comorbilidades cuando aporten beneficio funcional (ver [[Cap-36-Farmacoterapia]])
3. Combinar modalidades según perfil (sensorial, lenguaje, DI, salud mental)
4. Evaluar evidencia con RCTs/meta-análisis; desconfiar de curas milagro ([[Cap-37-Complementarios-pseudociencia]])

### No farmacológico (mapa 2025)

Wang et al. agrupan ([@wang2025]):

- Cognitivo-conductual / habilidades sociales / intervenciones psicológicas
- Música, arte, ejercicio, terapias asistidas con animales
- **Terapias digitales** (bajo coste relativo; aún concentradas en países ricos)
- Estimulación no invasiva: en un meta-análisis (16 RCTs, n=709), **atDCS_F3 + ctDCS externo** mejoró síntomas nucleares; **rTMS** sin efecto significativo en ese análisis; resultados mixtos en otros RCTs

### Farmacológico

Ver [[Cap-36-Farmacoterapia]]: psicofármacos para comorbilidades; oxitocina, balovaptan, PPAR, mTOR, etc. en fase experimental con resultados mixtos ([@wang2025]).

### Definir bien el objetivo: la crítica a "conducta problema"

Una revisión sistemática secundaria del corpus Project AIM (102 estudios de intervención temprana no farmacológica) halla que solo el **8%** ofreció una definición conceptual explícita de "conducta problema" antes de intervenir para reducirla, y el 62% describió la reducción de conducta como objetivo sin justificación clara. Casi todas las escalas de medición mezclan conductas con alto potencial de daño (agresión, autolesión) con conductas no normativas pero no dañinas por sí mismas (p. ej. estereotipias, ecolalia). Los autores llaman a definiciones y justificaciones más rigurosas, desarrolladas en colaboración con la comunidad autista, y proponen vocabulario alternativo desde la neurodiversidad —"meltdown" (sobrecarga sensorial), "shutdown" (retirada), "burnout" (agotamiento crónico)— que invita a cambios en el entorno en lugar de solo modificar la conducta del niño ([@bottemabeutel2025]; [[2025-Bottema-Beutel-problem-behavior-measurement]]; ver [[Cap-31-ABA-controversias]]).

### ¿Cuánta terapia es suficiente? Un desafío a la lógica de la dosis

Una cohorte clínica grande (N=1225, 20-90 meses, red Cortica Healthcare) modeló trayectorias de conducta adaptativa (Vineland-3) mediante modelos de mezcla de crecimiento latente (LCGMM), identificando dos clústeres: uno de **mejora** y otro **estable o con mayor deterioro relativo**. En un subconjunto (N=729), un modelo de random forest predijo la trayectoria con **77% de exactitud** usando solo datos disponibles al ingreso (nivel socioeconómico, regresión evolutiva, temperamento, edad paterna, severidad basal, preocupaciones parentales, TDAH). Un hallazgo llamativo: las **horas acumuladas de ABA u otras terapias del desarrollo no mejoraron la predicción** de la trayectoria ([@aitken2025]; [[2025-Aitken-adaptive-behavior-trajectories-ML]]). Esto no implica que la terapia sea inútil —el estudio es observacional y no aleatorizado, y no mide calidad ni tipo de terapia— pero sí cuestiona la asunción implícita de que "más horas es siempre mejor" y sugiere que las características del niño y la familia al ingreso podrían ser más informativas que la dosis acumulada para anticipar el curso evolutivo. Ver aplicación a la evaluación de estas variables en [[Cap-14-Evaluacion-funcional]] y a la intervención temprana en [[Cap-30-Intervencion-temprana]].

### Perspectivas clave

- **Evidencia clínica:** núcleo = apoyos/habilidades; fármacos nucleares = pipeline abierto; rigor conceptual en la definición de objetivos de intervención sigue siendo insuficiente en la literatura; modelos predictivos cuestionan que la dosis acumulada de terapia sea el principal determinante de la trayectoria adaptativa.
- **Experiencia vivida:** priorizar metas definidas por la persona y familia; distinguir entre conductas dañinas y conductas simplemente no normativas; la presión por acumular "más horas" de terapia puede generar sobrecarga familiar sin garantía de mejor resultado.
- **Controversias:** ABA y autonomía — ver [[Cap-31-ABA-controversias]]; si la ausencia de asociación dosis-trayectoria refleja límites reales de la intervención o limitaciones del diseño observacional del estudio.

## Referencias citadas

- [@wang2025] — [[2025-Wang-understanding-autism]]
- [@bottemabeutel2025] — [[2025-Bottema-Beutel-problem-behavior-measurement]]
- [@aitken2025] — [[2025-Aitken-adaptive-behavior-trajectories-ML]]

```dataview
LIST
FROM "01-Fuentes"
WHERE contains(capitulos_relacionados, this.file.link)
SORT fecha_captura DESC
```

## Enlaces relacionados

- [[Cap-36-Farmacoterapia]]
- [[Cap-30-Intervencion-temprana]]
- [[Cap-38-Tecnologia-asistiva]]
- [[Cap-14-Evaluacion-funcional]]
