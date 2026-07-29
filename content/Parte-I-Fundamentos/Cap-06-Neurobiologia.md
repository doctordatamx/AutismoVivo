---
tipo: capitulo
parte: "Parte-I"
numero: 6
titulo: "Neurobiología: cerebro, conectividad, biomarcadores"
dg-publish: true
dg-home: false
dg-permalink: /capitulos/neurobiologia
ultima_actualizacion: "2026-07-28"
version: "1.2"
fuentes_integradas:
  - "[[2012-Chaste-Leboyer-autism-risk-factors]]"
  - "[[2025-Wang-understanding-autism]]"
estado: revision
resumen_ejecutivo: "Convergencia en disfunción sináptica, glía/inmunidad y, en revisiones recientes, estrés oxidativo y disfunción mitocondrial. Transcriptómica: genes sinápticos infraexpresados y módulos inmunes sobreexpresados. Organoides y single-cell muestran efectos en neuronas excitatorias y GABAérgicas."
preguntas_abiertas:
  - "¿La activación microglial es causa, consecuencia o ambas?"
  - "¿Qué paneles (genética + metabolómica + imagen) predicen subtipos útiles clínicamente?"
tags:
  - tea/capitulo
bibliography: "03-Datos/references.bib"
---

# Capítulo 06 — Neurobiología: cerebro, conectividad, biomarcadores

## Resumen ejecutivo

Convergencia en disfunción sináptica, glía/inmunidad y, en revisiones recientes, **estrés oxidativo** y **disfunción mitocondrial** ([@wang2025]; [[2025-Wang-understanding-autism]]). Transcriptómica: genes sinápticos infraexpresados y módulos inmunes sobreexpresados ([@chaste2012]).

## Contenido

### Sinapsis y convergencia genética

Vías NLGN–NRXN–SHANK y cientos de genes SFARI convergen en desarrollo neuronal, glía y sinapsis ([@chaste2012]; [@wang2025]). Organoides con mutaciones (*SUV420H1*, *ARID1B*, *CHD8*) alteran neuronas GABAérgicas y proyecciones excitatorias profundas ([@wang2025]).

### Estrés oxidativo y mitocondria (actualización 2025)

Wang et al. sitúan un eje común a exposiciones ambientales (p. ej. diabetes materna) ([@wang2025]):

1. ROS ↑ / SOD2 ↓  
2. Disfunción mitocondrial y liberación de mtDNA como DAMP  
3. Neuroinflamación  
4. Fenotipos tipo TEA en modelos  

Mutaciones/heteroplasmia de **mtDNA** (incl. de novo ligadas a edad materna) emergen como factor de riesgo adicional ([@wang2025]).

### Inmunidad y transcriptoma

Activación microglial/astroglial y citocinas ([@chaste2012]); en ASD, upregulation de genes gliales/inmunes y downregulation neuronal/sináptica, con cambios epigenéticos ([@wang2025]; [@chaste2012]). El sesgo masculino puede relacionarse con mayor upregulation inmune/glial en varones ([@wang2025]).

### Perspectivas clave

- **Evidencia clínica:** imagen (fMRI, DTI, MRS, PET) y EEG como candidatos a biomarcadores digitales — ver [[Cap-09-Herramientas-cribado]].
- **Experiencia vivida:** biomarcadores no definen identidad.
- **Controversias:** causalidad de neuroinflamación y mtDNA.

## Referencias citadas

- [@wang2025] — [[2025-Wang-understanding-autism]]
- [@chaste2012] — [[2012-Chaste-Leboyer-autism-risk-factors]]

```dataview
LIST
FROM "01-Fuentes"
WHERE contains(capitulos_relacionados, this.file.link)
SORT fecha_captura DESC
```

## Enlaces relacionados

- [[Cap-05-Etiologia]]
- [[Cap-09-Herramientas-cribado]]
