---
tipo: capitulo
parte: "Parte-IV"
numero: 24
titulo: "Edad escolar (6–12 años)"
dg-publish: false
dg-home: false
dg-permalink: /capitulos/edad-escolar
ultima_actualizacion: "2026-07-29"
version: "1.3"
fuentes_integradas:
  - "[[2025-Soto-Icaza-classroom-social-networks]]"
  - "[[2025-Ren-adhd-presentation-recharge]]"
  - "[[2025-Aitken-adaptive-behavior-trajectories-ML]]"
estado: borrador
resumen_ejecutivo: "En la etapa escolar (6-12 años), medidas objetivas de redes sociales de aula muestran que los niños autistas ocupan posiciones de menor centralidad y reciprocidad social que sus compañeros, un hallazgo relevante para el diseño de apoyos escolares. Un estudio de cohorte con machine learning en preescolares sugiere que las características al ingreso predicen mejor la trayectoria adaptativa posterior que las horas acumuladas de terapia."
preguntas_abiertas:
  - "¿Cómo cambia la posición en la red social de aula a lo largo de la edad escolar?"
  - "¿Los clústeres de trayectoria adaptativa identificados en preescolar se mantienen estables durante la edad escolar?"
tags:
  - tea/capitulo
bibliography: "03-Datos/references.bib"
---

# Capítulo 24 — Edad escolar (6–12 años)

## Resumen ejecutivo

Durante la edad escolar, la vida social del aula es un componente central del desarrollo. Un estudio con teoría de juegos en aulas de 1° a 4° básico (6–11 años, N=625, 18 autistas) documenta que los niños autistas presentan menor centralidad y reciprocidad en la red social del aula que sus pares sin necesidades educativas especiales ([@sotoicaza2025]; [[2025-Soto-Icaza-classroom-social-networks]]).

## Contenido

### Introducción

La etapa escolar (6–12 años) supone mayor exposición a grupos de pares estructurados (aula, recreo, actividades extracurriculares), donde la posición social del niño autista puede diferir de la de sus compañeros.

### Redes sociales de aula en la etapa escolar

Mediante el juego "Game of Stars", Soto-Icaza et al. midieron redes sociales objetivas en 26 aulas chilenas de 1° a 4° básico. Los niños autistas mostraron menor centralidad (in-degree, PageRank, closeness, betweenness) y menor reciprocidad que compañeros sin NEE, con diferencias más matizadas frente a otros niños con NEE ([@sotoicaza2025]; [[2025-Soto-Icaza-classroom-social-networks]]). Esto sugiere que la etapa escolar temprana es una ventana relevante para intervenciones de inclusión relacional, no solo académica.

### Comorbilidad con TDAH en la edad escolar

El seguimiento longitudinal ReCHARGE (n=645, 8-20 años) muestra que el diagnóstico temprano (2-5 años) de autismo predice fuertemente la aparición de TDAH durante la etapa escolar y posterior: el 46,2% de los niños diagnosticados con autismo en la primera infancia cumplió criterios de TDAH en el seguimiento, con un riesgo relativo de 5,4 para la presentación Combinada/Hiperactiva-Impulsiva ([@ren2025]; [[2025-Ren-adhd-presentation-recharge]]). Esto refuerza la necesidad de cribado activo y longitudinal de síntomas de TDAH durante los años escolares, no solo en el momento del diagnóstico inicial de autismo (ver [[Cap-07-Comorbilidades]]).

### Trayectorias previas de conducta adaptativa y su continuidad escolar

Antes de llegar a la etapa escolar, muchos niños ya han transitado por trayectorias de conducta adaptativa distintas durante la primera infancia. Una cohorte clínica (N=1225, 20-90 meses) identificó dos clústeres de trayectoria (mejora vs. estable/mayor deterioro) mediante Vineland-3, y un modelo predictivo (77% de exactitud) basado en características de ingreso —no en horas acumuladas de terapia— logró anticipar el grupo de trayectoria ([@aitken2025]; [[2025-Aitken-adaptive-behavior-trajectories-ML]]). Aunque el estudio no cubre directamente la edad escolar, sus hallazgos son relevantes para anticipar qué niños podrían necesitar apoyos adaptativos reforzados al ingresar a la escuela, más allá de la sola acumulación de horas de terapia previa (ver [[Cap-14-Evaluacion-funcional]], [[Cap-29-Principios-intervencion]]).

### Perspectivas clave

- **Evidencia clínica:** posición social objetivamente más periférica en el aula desde etapas tempranas de la escolaridad; alta probabilidad de comorbilidad con TDAH que emerge o se hace evidente durante estos años; trayectorias de conducta adaptativa previas a la escolaridad podrían anticipar necesidades de apoyo.
- **Experiencia vivida:** la experiencia escolar social puede diferir marcadamente de la percepción docente de "buena inclusión".
- **Controversias y debates:** intervenir sobre el niño vs. sobre la dinámica del grupo/aula.

### Preguntas abiertas

- ¿Cómo cambia la posición en la red social de aula a lo largo de la edad escolar?
- ¿Los clústeres de trayectoria adaptativa identificados en preescolar se mantienen estables durante la edad escolar?

## Fuentes integradas

```dataview
LIST
FROM "01-Fuentes"
WHERE contains(capitulos_relacionados, this.file.link)
SORT fecha_captura DESC
```

## Referencias citadas

- [@sotoicaza2025] — [[2025-Soto-Icaza-classroom-social-networks]]
- [@ren2025] — [[2025-Ren-adhd-presentation-recharge]]
- [@aitken2025] — [[2025-Aitken-adaptive-behavior-trajectories-ML]]

## Enlaces relacionados

- [[Cap-39-Educacion-inclusiva]]
- [[Cap-35-Habilidades-sociales]]
- [[Cap-16-Interaccion-social]]
- [[Cap-14-Evaluacion-funcional]]
- [[Cap-29-Principios-intervencion]]

