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
