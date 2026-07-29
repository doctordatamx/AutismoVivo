---
tipo: capitulo
parte: "Parte-I"
numero: 6
titulo: "Neurobiología: cerebro, conectividad, biomarcadores"
dg-publish: true
dg-home: false
dg-permalink: /capitulos/neurobiologia
ultima_actualizacion: "2026-07-28"
version: "1.3"
fuentes_integradas:
  - "[[2012-Chaste-Leboyer-autism-risk-factors]]"
  - "[[2025-Wang-understanding-autism]]"
  - "[[2025-Kim-An-precision-diagnosis-genomics]]"
estado: revision
resumen_ejecutivo: "Convergencia en disfunción sináptica (NC) y regulación génica temprana (GER), estrés oxidativo/mitocondria, y glía/inmunidad. Single-cell y organoides muestran efectos en progenitores vs. neuronas maduras; genes ASD-predominantes vs. DD-predominantes difieren en trayectoria temporal."
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

Vías NLGN–NRXN–SHANK y cientos de genes convergen en desarrollo neuronal ([@chaste2012]; [@wang2025]). Kim & An ([@kim2025]; [[2025-Kim-An-precision-diagnosis-genomics]]) distinguen:

- **GER** (regulación de expresión): pico prenatal (progenitores / neuronas tempranas) — p. ej. *ARID1B*, cromatina
- **NC** (comunicación neuronal): pico postnatal en neuronas maduras — p. ej. *SHANK3*, *PTEN*/mTOR

Genes **ASD-predominantes** vs. **DD-predominantes** tienen trayectorias distintas (Fu et al., citado en [@kim2025]). Organoides/CRISPR reproducen defectos de neurogénesis y circuitos.

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

- [@kim2025] — [[2025-Kim-An-precision-diagnosis-genomics]]
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
