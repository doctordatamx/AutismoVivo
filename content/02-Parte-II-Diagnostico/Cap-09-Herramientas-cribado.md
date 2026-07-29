---
tipo: capitulo
parte: "Parte-II"
numero: 9
titulo: "Herramientas de cribado (M-CHAT, ADOS, ADI-R, y otras)"
dg-publish: true
dg-home: false
dg-permalink: /capitulos/herramientas-cribado
ultima_actualizacion: "2026-07-28"
version: "1.1"
fuentes_integradas:
  - "[[2025-Wang-understanding-autism]]"
  - "[[2025-Yoon-eye-tracking-treatment-monitoring-meta]]"
estado: revision
resumen_ejecutivo: "El diagnóstico sigue basado en evaluación conductual estandarizada (p. ej. ADOS-2) más historia del desarrollo. Los biomarcadores digitales (eye-tracking, EEG, fMRI) y biológicos (citocinas, metabolómica, microbiota) son prometedores pero, por la heterogeneidad del TEA, no hay un marcador único validado para uso clínico universal."
preguntas_abiertas:
  - "¿Qué paneles multi-biomarcador logran validación multi-sitio y multi-país?"
  - "¿Cómo llevar eye-tracking/EEG a atención primaria sin sesgos poblacionales?"
tags:
  - tea/capitulo
bibliography: "03-Datos/references.bib"
---

# Capítulo 09 — Herramientas de cribado (M-CHAT, ADOS, ADI-R, y otras)

## Resumen ejecutivo

El diagnóstico sigue basado en evaluación conductual estandarizada (p. ej. **ADOS-2**) más historia del desarrollo. Los biomarcadores digitales (eye-tracking, EEG, fMRI) y biológicos son prometedores pero, por la heterogeneidad del TEA, **no hay un marcador único** validado para uso clínico universal ([@wang2025]; [[2025-Wang-understanding-autism]]).

## Contenido

### Estándar actual

Según Wang et al. ([@wang2025]):

- **ADOS-2** (y herramientas afines): administrado por clínicos entrenados
- Diagnóstico formal = conducta observada + historia + informes de cuidadores/escuela
- Variabilidad inter-evaluador existe, pero el marco es estandarizado

Cribados clásicos (M-CHAT, etc.) y ADI-R siguen siendo parte del ecosistema clínico habitual (ampliación pendiente con fuentes específicas).

### Por qué fallan los biomarcadores “únicos”

La heterogeneidad etiológica y clínica hace improbable un solo biomarcador; se requieren **paneles** y enfoques estratificados ([@wang2025]).

### Biomarcadores digitales (estado de la evidencia)

| Enfoque | Hallazgo destacado | Limitación |
|---------|-------------------|------------|
| Eye-tracking | AUC ROC ~**0,90** en toddlers (estudio grande citado) | No siempre replica en cohortes de alto riesgo |
| Análisis conductual digital | AUC ~0,90; sens. ~88%, esp. ~81% (proof-of-concept) | Generalización geográfica/edad |
| EEG | Respuestas a caras; predicción temprana posible | Heterogeneidad de paradigmas |
| fMRI / DTI / MRS / PET | Conectividad y metabolitos alterados | Coste, acceso, validación multi-sitio |
| Datos de vigilancia del desarrollo | AUC ~0,83 (18–24 meses) | Sensibilidad baja (~45%) en un modelo |

### Eye tracking: ¿cribado o monitoreo de tratamiento?

Un meta-análisis multinivel de 25 estudios (n=828) distingue dos usos del eye tracking: como medida de **cambio pre-post** tras intervención (efecto modesto, g=0,32) y como **predictor** de la respuesta al tratamiento (no significativo, z=0,20) ([@yoon2025]; [[2025-Yoon-eye-tracking-treatment-monitoring-meta]]). Implicación práctica: el eye tracking es más prometedor como herramienta de **monitoreo de cambio** que como marcador **pronóstico**; ver aplicaciones tecnológicas en [[Cap-38-Tecnologia-asistiva]].

### Biomarcadores biológicos

Citocinas (p. ej. G-CSF, IL-1, TNF-α), expresión génica (SOD2, RORA), miRNAs, proteómica/metabolómica plasmática/salival, autoanticuerpos maternos, y **microbiota** (modelo multi-dominio AUC ~0,91 en un estudio; requiere validación cross-población) ([@wang2025]).

### Perspectivas clave

- **Evidencia clínica:** ADOS-2 sigue siendo referencia; digitales/biológicos = investigación.
- **Experiencia vivida:** herramientas deben reducir demoras diagnósticas sin sobrediagnosticar.
- **Controversias:** “diagnóstico por IA/biomarcador” prematuro.

### Preguntas abiertas

- ¿Qué paneles se validan multi-país?
- ¿Cómo llevar eye-tracking a primaria?

## Referencias citadas

- [@yoon2025] — [[2025-Yoon-eye-tracking-treatment-monitoring-meta]]
- [@wang2025] — [[2025-Wang-understanding-autism]]

```dataview
LIST
FROM "01-Fuentes"
WHERE contains(capitulos_relacionados, this.file.link)
SORT fecha_captura DESC
```

## Enlaces relacionados

- [[Cap-10-Proceso-diagnostico]]
- [[Cap-11-Diagnostico-mujeres]]
- [[Cap-08-Senales-tempranas]]
