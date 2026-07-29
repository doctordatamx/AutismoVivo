---
tipo: capitulo
parte: "Parte-V"
numero: 30
titulo: "Intervención temprana (ESDM, JASPER, modelos naturales)"
dg-publish: false
dg-home: false
dg-permalink: /capitulos/intervencion-temprana
ultima_actualizacion: "2026-07-29"
version: "1.2"
fuentes_integradas:
  - "[[2025-Ziegler-DAN-PACT-protocol]]"
  - "[[2025-Aitken-adaptive-behavior-trajectories-ML]]"
estado: borrador
resumen_ejecutivo: "PACT (Paediatric Autism Communication Therapy), intervención mediada por padres con evidencia previa en Reino Unido, se replica en Dinamarca (DAN-PACT, n=280); protocolo publicado, resultados de eficacia aún pendientes. Un estudio de cohorte con ML en niños pequeños (20-90 meses) no encontró que las horas acumuladas de terapia del desarrollo mejoraran la predicción de la trayectoria adaptativa, sugiriendo que las características de ingreso pesan más que la dosis."
preguntas_abiertas:
  - "¿Los resultados de DAN-PACT replicarán la eficacia de PACT original en un contexto cultural distinto?"
  - "¿Qué variables de ingreso (más allá de la dosis) deberían guiar la intensidad de la intervención temprana?"
tags:
  - tea/capitulo
bibliography: "03-Datos/references.bib"
---

# Capítulo 30 — Intervención temprana (ESDM, JASPER, modelos naturales)

## Resumen ejecutivo

Entre los modelos de intervención temprana mediada por padres destaca **PACT (Paediatric Autism Communication Therapy)**, con evidencia previa de eficacia en el Reino Unido. Un ensayo controlado aleatorizado danés (DAN-PACT, n=280) replica y adapta culturalmente esta intervención; el artículo publicado es solo el **protocolo**, sin resultados de eficacia todavía ([@ziegler2025]; [[2025-Ziegler-DAN-PACT-protocol]]).

## Contenido

### Introducción

Los modelos naturalistas de intervención temprana (ESDM, JASPER, PACT) enfatizan el desarrollo de la comunicación social a través de interacciones cotidianas, a menudo mediadas por padres o cuidadores.

### PACT: réplica danesa (DAN-PACT)

PACT usa videofeedback para ayudar a los padres a identificar y responder a las iniciativas comunicativas de sus hijos. DAN-PACT compara **PACT + manejo habitual** vs. **manejo habitual solo** en n=280 niños autistas daneses, con **ADOS-2 Calibrated Severity Score** como desenlace primario ([@ziegler2025]; [[2025-Ziegler-DAN-PACT-protocol]]). Al ser solo protocolo, debe citarse como "ensayo en curso" y no como evidencia de eficacia adicional.

### ¿Importa cuánta terapia se acumula?

Un hallazgo relevante para el diseño de programas de intervención temprana proviene de una cohorte clínica grande (N=1225, 20-90 meses) que modeló trayectorias de conducta adaptativa (Vineland-3): un modelo predictivo de random forest (77% de exactitud) usando datos de ingreso (nivel socioeconómico, regresión evolutiva, temperamento, severidad basal, TDAH, entre otros) **no mejoró** al incorporar las horas acumuladas de ABA u otras terapias del desarrollo ([@aitken2025]; [[2025-Aitken-adaptive-behavior-trajectories-ML]]). Esto no cuestiona la utilidad de la intervención temprana per se, pero sí sugiere que factores del niño y la familia presentes desde el ingreso podrían ser más predictivos del curso evolutivo que la dosis acumulada de terapia — relevante al discutir intensidad óptima frente a sobrecarga familiar (ver [[Cap-29-Principios-intervencion]]).

### Perspectivas clave

- **Evidencia clínica:** PACT tiene evidencia previa robusta en RU; DAN-PACT aporta réplica cultural, resultados pendientes; datos de ML cuestionan que la dosis de terapia acumulada sea el principal predictor de trayectoria adaptativa.
- **Experiencia vivida:** intervenciones mediadas por padres pueden reducir la carga de "terapia intensiva" fuera del hogar.
- **Controversias y debates:** intensidad y dosis óptima de intervención temprana vs. sobrecarga familiar; qué hacer con evidencia observacional que no confirma el supuesto de "más horas, mejor resultado".

### Preguntas abiertas

- ¿Los resultados de DAN-PACT replicarán la eficacia de PACT original en un contexto cultural distinto?
- ¿Qué variables de ingreso (más allá de la dosis) deberían guiar la intensidad de la intervención temprana?

## Fuentes integradas

```dataview
LIST
FROM "01-Fuentes"
WHERE contains(capitulos_relacionados, this.file.link)
SORT fecha_captura DESC
```

## Referencias citadas

- [@ziegler2025] — [[2025-Ziegler-DAN-PACT-protocol]]
- [@aitken2025] — [[2025-Aitken-adaptive-behavior-trajectories-ML]]

## Enlaces relacionados

- [[Cap-32-Terapia-lenguaje-CAA]]
- [[Cap-35-Habilidades-sociales]]
- [[Cap-29-Principios-intervencion]]

