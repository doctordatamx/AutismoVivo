---
tipo: apendice
titulo: "Bibliografía maestra (auto-generada con Dataview)"
dg-publish: true
dg-permalink: /apendices/bibliografia
ultima_actualizacion: "2026-07-28"
estado: revision
tags:
  - tea/apendice
bibliography: "03-Datos/references.bib"
---

# Bibliografía maestra

Referencias gestionadas en [`03-Datos/references.bib`](../../03-Datos/references.bib) + notas en `01-Fuentes/`.

Plugin: **Citations** — ver [[plugin-citations]].

## Entradas BibTeX actuales

| Citekey | Autores | Año | Nota |
|---------|---------|-----|------|
| `anderson2026` | Anderson | 2026 | [[2026-Anderson-STAT3-NFkB-melatonergic-ASD]] |
| `mitchell2025` | Mitchell, Dahly, Bishop | 2025 | [[2025-Mitchell-Bishop-microbiome-autism-critique]] |
| `ma2025vr` | Ma & Song | 2025 | [[2025-Ma-Song-VR-motion-serious-game-RCT]] |
| `sandham2025` | Sandham et al. | 2025 | [[2025-Sandham-translatability-communication-interventions]] |
| `wills2025` | Wills, Appelbaum et al. | 2025 | [[2025-Wills-psychosocial-impacts-autism-genetic-testing]] |
| `doherty2025` | Doherty, Foley, Schloss | 2025 | [[2025-Doherty-CAM-autism-systematic-review]] |
| `verkooijen2026` | Verkooijen et al. | 2026 | [[2026-Verkooijen-peer-support-autism-review]] |
| `grumbach2025` | Grumbach et al. | 2025 | [[2025-Grumbach-local-activity-neurotransmitters-ketamine]] |
| `leyhausen2026` | Leyhausen et al. | 2026 | [[2026-Leyhausen-transcriptomic-subgroup-IDP-autism]] |
| `weissenkampen2026` | Weissenkampen et al. | 2026 | [[2026-Weissenkampen-sleep-activity-actimetry-autism]] |
| `yang2025lgr1` | Yang et al. | 2025 | [[2025-Yang-LGR1-prenatal-microbiome-autism-mice]] |
| `zabetakis2026` | Zabetakis & Grabrucker | 2026 | [[2026-Zabetakis-Grabrucker-synaptic-protein-mutations]] |
| `boulton2026` | Boulton & Guastella | 2026 | [[2026-Boulton-Guastella-oxytocin-precision-medicine]] |
| `cole2026` | Cole, Happé et al. | 2026 | [[2026-Cole-Happe-autism-FND-association]] |
| `robas2025` | Robas, Stern et al. | 2025 | [[2025-Robas-Stern-digestive-neurobiology-ens]] |
| `zhang2025mgba` | Zhang et al. | 2025 | [[2025-Zhang-microbiota-gut-brain-axis-autism]] |
| `vanderschaf2025` | van der Schaaf et al. | 2025 | [[2025-van-der-Schaaf-maternal-asthma-autism-meta]] |
| `veilleux2025` | Veilleux, Ismail et al. | 2025 | [[2025-Veilleux-Ismail-autism-hormones-immune-gut]] |
| `ali2025` | Ali, Bougoure et al. | 2025 | [[2025-Ali-Bougoure-autistic-burnout-review]] |
| `cusson2025` | Cusson et al. | 2025 | [[2025-Cusson-empathy-measures-meta-analysis]] |
| `kim2025` | Kim & An | 2025 | [[2025-Kim-An-precision-diagnosis-genomics]] |
| `wang2025` | Wang et al. | 2025 | [[2025-Wang-understanding-autism]] |
| `thapar2021` | Thapar & Rutter | 2021 | [[2021-Thapar-Rutter-genetic-advances]] |
| `chaste2012` | Chaste & Leboyer | 2012 | [[2012-Chaste-Leboyer-autism-risk-factors]] |
| `hallmayer2011` | Hallmayer et al. | 2011 | Heredabilidad gemelos (citado en Chaste) |
| `sebat2007` | Sebat et al. | 2007 | CNVs de novo |
| `jamain2003` | Jamain et al. | 2003 | NLGN3/4 |
| `durand2007` | Durand et al. | 2007 | SHANK3 |

## Fuentes ingeridas (Dataview)

```dataview
TABLE citekey AS "Citekey", autor AS "Autor", fecha_publicacion AS "Año", estado, nivel_evidencia AS "Evidencia"
FROM "01-Fuentes"
WHERE tipo = "fuente"
SORT fecha_publicacion DESC
```

## Cómo citar en capítulos

```markdown
Texto afirmativo ([@chaste2012]; [[2012-Chaste-Leboyer-autism-risk-factors]]).
```

Al añadir una fuente nueva: 1) nota en `01-Fuentes`, 2) entrada en `references.bib`, 3) `ingest_manager.py mark-ingested`.
