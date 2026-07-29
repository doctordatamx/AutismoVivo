---
tipo: indice
titulo: "Índice — Libro Vivo sobre Autismo"
autor: "Dr. Fernando Avalos Reyes"
fecha_publicacion: "2026-07-28"
ultima_actualizacion: "2026-07-28"
dg-publish: true
dg-home: false
dg-permalink: /indice
estado: publicado
tags:
  - tea/indice
---

# Índice — Libro Vivo sobre Autismo

**Autor:** Dr. Fernando Avalos Reyes  
**Publicación:** 28 de julio de 2026  
**Última actualización:** 28 de julio de 2026  

← [[00-Portada|Portada]] · [[Donaciones|Apoyar el proyecto]]

Un compendio en constante actualización sobre el Trastorno del Espectro Autista (TEA), sintetizado desde artículos, papers y fuentes curadas. Escrito en español para familias, profesionales y personas autistas.

> **Metodología:** Las fuentes se capturan con Web Clipper, se procesan con IA, y los capítulos se actualizan periódicamente. Ver [[criterios-editoriales]].

<a href="https://ko-fi.com/TU_USUARIO" class="button" target="_blank" rel="noopener">☕ Apoyar con una donación</a>

---

## Tabla de contenidos

### Parte I — Fundamentos y contexto histórico

- [[Cap-01-Que-es-el-autismo]]
- [[Cap-02-Historia-del-autismo]]
- [[Cap-03-Criterios-diagnosticos]]
- [[Cap-04-Epidemiologia]]
- [[Cap-05-Etiologia]]
- [[Cap-06-Neurobiologia]]
- [[Cap-07-Comorbilidades]]

### Parte II — Diagnóstico y evaluación

- [[Cap-08-Senales-tempranas]]
- [[Cap-09-Herramientas-cribado]]
- [[Cap-10-Proceso-diagnostico]]
- [[Cap-11-Diagnostico-mujeres]]
- [[Cap-12-Diagnostico-adultos]]
- [[Cap-13-Diagnostico-diferencial]]
- [[Cap-14-Evaluacion-funcional]]

### Parte III — Perfil neurocognitivo

- [[Cap-15-Comunicacion-social]]
- [[Cap-16-Interaccion-social]]
- [[Cap-17-Intereses-rutinas]]
- [[Cap-18-Procesamiento-sensorial]]
- [[Cap-19-Funciones-ejecutivas]]
- [[Cap-20-Teoria-de-la-mente]]
- [[Cap-21-Enmascaramiento]]
- [[Cap-22-Fortalezas-cognitivas]]

### Parte IV — Desarrollo y ciclo vital

- [[Cap-23-Infancia-temprana]]
- [[Cap-24-Edad-escolar]]
- [[Cap-25-Adolescencia]]
- [[Cap-26-Adultez-joven]]
- [[Cap-27-Adultez-madura]]
- [[Cap-28-Transiciones-criticas]]

### Parte V — Intervenciones y apoyos

- [[Cap-29-Principios-intervencion]]
- [[Cap-30-Intervencion-temprana]]
- [[Cap-31-ABA-controversias]]
- [[Cap-32-Terapia-lenguaje-CAA]]
- [[Cap-33-Terapia-ocupacional]]
- [[Cap-34-Apoyos-educativos]]
- [[Cap-35-Habilidades-sociales]]
- [[Cap-36-Farmacoterapia]]
- [[Cap-37-Complementarios-pseudociencia]]
- [[Cap-38-Tecnologia-asistiva]]

### Parte VI — Educación, trabajo y vida independiente

- [[Cap-39-Educacion-inclusiva]]
- [[Cap-40-Planes-individualizados]]
- [[Cap-41-Educacion-superior]]
- [[Cap-42-Empleo]]
- [[Cap-43-Vida-independiente]]
- [[Cap-44-Transporte-vivienda]]

### Parte VII — Familia, relaciones y bienestar

- [[Cap-45-Crianza]]
- [[Cap-46-Dinamica-familiar]]
- [[Cap-47-Salud-mental]]
- [[Cap-48-Relaciones-pareja]]
- [[Cap-49-Autistas-criando]]
- [[Cap-50-Autocuidado-burnout]]

### Parte VIII — Sociedad, derechos y futuro

- [[Cap-51-Autodefensa-neurodiversidad]]
- [[Cap-52-Derechos-legales]]
- [[Cap-53-Representacion-medios]]
- [[Cap-54-Genero-diversidad]]
- [[Cap-55-Contextos-culturales]]
- [[Cap-56-Justicia-penal]]
- [[Cap-57-Investigacion-etica]]
- [[Cap-58-Fronteras-investigacion]]

### Apéndices

- [[Apendice-A-Glosario]]
- [[Apendice-B-Intervenciones]]
- [[Apendice-C-Recursos]]
- [[Apendice-D-Bibliografia]]
- [[Apendice-E-Changelog]]

---

## Dashboard del libro

```dataview
TABLE ultima_actualizacion AS "Actualizado", estado, dg-publish AS "Publicado"
FROM "02-Libro"
WHERE tipo = "capitulo"
SORT numero ASC
```

## Fuentes pendientes de integrar

```dataview
TABLE capitulos_relacionados AS "Capítulos", nivel_evidencia AS "Evidencia", fecha_captura AS "Capturada"
FROM "01-Fuentes"
WHERE estado = "procesado"
SORT fecha_captura DESC
```

## Ya ingeridos (no reprocesar)

```dataview
TABLE citekey, doi, fecha_ingesta AS "Ingerida", estado
FROM "01-Fuentes"
WHERE estado = "integrado"
SORT fecha_ingesta DESC
```

## Capítulos publicados

```dataview
LIST
FROM "02-Libro"
WHERE dg-publish = true
SORT numero ASC
```
