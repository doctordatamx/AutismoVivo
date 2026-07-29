---
tipo: capitulo
parte: "Parte-II"
numero: 10
titulo: "Proceso diagnóstico integral"
dg-publish: true
dg-home: false
dg-permalink: /capitulos/proceso-diagnostico
ultima_actualizacion: "2026-07-29"
version: "1.3"
fuentes_integradas:
  - "[[2021-Thapar-Rutter-genetic-advances]]"
  - "[[2025-Kim-An-precision-diagnosis-genomics]]"
  - "[[2025-Wills-psychosocial-impacts-autism-genetic-testing]]"
  - "[[2025-Arribas-Ayllon-wales-medicalisation]]"
  - "[[2024-Aishworiya-newborn-genetic-testing-ethics]]"
  - "[[2025-Couture-healthcare-trajectories-sex-idd]]"
estado: revision
resumen_ejecutivo: "El diagnóstico de TEA es clínico (historia + observación estandarizada). Instrumentos rigurosos (ADI/ADOS) son valiosos, pero no debe retrasarse la intervención por fronteras diagnósticas perfectas. Microarray/WES/WGS se indican según comorbilidad; PS (~2% liability) aún sin utilidad clínica rutinaria. Interpretación: umbral rara+poligénica, snRNA emergentes."
preguntas_abiertas:
  - "¿Qué paquete mínimo diagnóstico equilibra rigor y acceso en atención primaria?"
  - "¿Cuándo escalar a exoma/genoma completo con equidad ancestral?"
tags:
  - tea/capitulo
bibliography: "03-Datos/references.bib"
---

# Capítulo 10 — Proceso diagnóstico integral

## Resumen ejecutivo

El diagnóstico de TEA es **clínico** (historia + observación estandarizada). Instrumentos rigurosos (ADI/ADOS) son valiosos, pero no debe retrasarse la intervención por una búsqueda interminable de fronteras diagnósticas perfectas ([@thapar2021]; [[2021-Thapar-Rutter-genetic-advances]]). La evaluación genética se indica según comorbilidad y guías locales (ver [[Cap-05-Etiologia]]).

## Contenido

### Principios

1. Combinar categoría clínica y perspectiva dimensional ([@thapar2021])
2. Priorizar **apoyos** cuando la evidencia conductual es suficiente
3. Buscar comorbilidades (TDAH, DI, epilepsia, ansiedad) — [[Cap-07-Comorbilidades]]
4. Considerar genética clínica si DI, dismorfia o presentación compleja ([@thapar2021])

### Evaluación genética en el proceso

- Microarray: primera línea frecuente; política varía (EE.UU. vs. UK/NICE) ([@thapar2021])
- WES/WGS: aumentan rendimiento diagnóstico en TEA + DI/complejo; listas de genes a FDR estricto vs. SFARI amplio ([@kim2025]; [[2025-Kim-An-precision-diagnosis-genomics]])
- **Scores poligénicos (PS):** explican ≈**2%** de la liability; multi-PGS/ML mejoran discriminación en investigación, **no** predicción clínica de rutina ([@kim2025])
- Interpretar con cautela: pleiotropía, penetrancia variable, aditividad/compensación rara↔común ([@kim2025])
- Emergente: variantes en snRNA (*RNU4-2*, *RNU2-2*) asociadas a NDD con rasgos autistas ([@kim2025])
- Detalle: [[Cap-05-Etiologia]] § Pruebas genéticas

### Perspectivas clave

- **Evidencia clínica:** diagnóstico conductual sigue siendo estándar; genómica es **complemento** etiológico.
- **Experiencia vivida:** demoras diagnósticas dañan; rigor ≠ interminable.
- **Controversias:** testing genético universal vs. selectivo; sesgo ancestral en PS.

### Resultados genéticos: impactos psicosociales

Wills et al. ([@wills2025]; [[2025-Wills-psychosocial-impacts-autism-genetic-testing]]): al devolver resultados genéticos relacionados con TEA, padres reportan emociones mixtas (alivio/culpa/miedo) y a veces cambios en cuidado o planificación familiar; adultos autistas enfatizan **consentimiento** y riesgo de **discriminación**. Consejería: sopesar perspectivas parentales y de personas autistas.

### Cribado neonatal vs. pruebas diagnósticas: el debate bioético

Un análisis de ética médica sostiene que el cribado genético neonatal **poblacional** para autismo no está justificado por la penetrancia variable de los genes de riesgo y la heterogeneidad fenotípica, y propone en cambio facilitar y subsidiar **pruebas diagnósticas** tras el diagnóstico clínico —especialmente relevantes para decisiones reproductivas de los padres— mediante subsidios financieros y asesoramiento genético estructurado ([@aishworiya2024]; [[2024-Aishworiya-newborn-genetic-testing-ethics]]; ver [[Cap-57-Investigacion-etica]]).

### Gobernanza y estandarización de las vías diagnósticas

Un estudio de caso cualitativo en Gales muestra que las vías de servicio de neurodesarrollo del sistema público de salud no son meros canales administrativos: herramientas "neutrales" como el DSM-5 y el ADOS-2, junto con protocolos de derivación estandarizados, funcionan como tecnologías de **gobernanza** que regulan —no solo agilizan— el acceso al diagnóstico, redistribuyendo la autoridad diagnóstica entre profesionales, educadores y responsables de políticas públicas ([@arribasayllon2025]; [[2025-Arribas-Ayllon-wales-medicalisation]]; ver [[Cap-03-Criterios-diagnosticos]], [[Cap-52-Derechos-legales]]).

### Trayectorias de atención según sexo y discapacidad intelectual

Una cohorte administrativa de Quebec (n=5289) muestra que las trayectorias de atención sanitaria tras el diagnóstico difieren marcadamente por sexo, edad al diagnóstico y presencia de discapacidad intelectual/del desarrollo (DID): las mujeres son diagnosticadas sistemáticamente más tarde (edad media 22,2 vs. 13,9 años) y presentan casi el doble de días de hospitalización cuando son diagnosticadas en la infancia; las tasas de hospitalización más altas se observan en personas diagnosticadas en la adultez, particularmente mujeres y personas con DID, lo que plantea preocupaciones sobre continuidad de la atención ([@couture2025]; [[2025-Couture-healthcare-trajectories-sex-idd]]; ver [[Cap-11-Diagnostico-mujeres]], [[Cap-12-Diagnostico-adultos]]).

## Referencias citadas

- [@kim2025] — [[2025-Kim-An-precision-diagnosis-genomics]]
- [@thapar2021] — [[2021-Thapar-Rutter-genetic-advances]]
- [@aishworiya2024] — [[2024-Aishworiya-newborn-genetic-testing-ethics]]
- [@arribasayllon2025] — [[2025-Arribas-Ayllon-wales-medicalisation]]
- [@couture2025] — [[2025-Couture-healthcare-trajectories-sex-idd]]

```dataview
LIST
FROM "01-Fuentes"
WHERE contains(capitulos_relacionados, this.file.link)
SORT fecha_captura DESC
```

## Enlaces relacionados

- [[Cap-09-Herramientas-cribado]]
- [[Cap-05-Etiologia]]
- [[Cap-11-Diagnostico-mujeres]]
