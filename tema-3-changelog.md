# Tema 3 — Changelog

> **Título oficial**: El Reglamento Orgánico del Gobierno y de la Administración del Ayuntamiento de Madrid, de 31 de mayo de 2004 (I): Las Áreas de Gobierno y su estructura interna. Órganos superiores; Órganos Centrales directivos. Número y denominación de las actuales Áreas de Gobierno.

---

## v1.0 — 2026-06-15 — Generación inicial completa

**Estado**: Pendiente de validación por María / Ana (IAM).

### Alcance y decisiones

- **Fuente nuclear**: ROGA 2004, arts. 5-11 y 40-49, a partir del PDF aportado por el cliente (`Tema 3.pdf`, resumen + anexo del articulado) y **contrastado con el texto oficial completo** del Ayuntamiento de Madrid (guardado en `Documentacion/fuentes-oficiales/`).
- **Áreas de Gobierno actuales** actualizadas con el **organigrama oficial vigente** (transparencia.madrid.es, consultado 2026-06-15): **7 Áreas de Gobierno** + Áreas Delegadas. Coincide con el PDF de cliente en las 7 Áreas.
- **Alcance ampliado** coherente con el resto de temas admin: marco general del ROGA (arts. 5-11), LBRL invocada (arts. 123, 124, 130) y régimen de capitalidad (Ley 22/2006).
- **Formato de referencia**: Tema 1 / Tema 2 (admin): 150 preguntas + 20 pedagógicas + 6 casos + 12 diagramas + 7 pestañas.

### Entregables generados

| Fichero | Contenido |
|---|---|
| `tema-3-indice.md` | Índice de 13 secciones + tablas de datos clave |
| `tema-3-fuentes.md` | Registro Tier 1/2/3 + normas de citación |
| `tema-3-contenido.md` | Contenido teórico ampliado (13 secciones, 4 callouts) |
| `tema-3-diagramas.md` | 12 diagramas SVG accesibles |
| `tema-3-test.md` | 150 preguntas + plantilla + 20 pedagógicas |
| `tema-3-caso-practico.md` | 6 casos prácticos (Ayto Madrid), 10 pts c/u |
| `tema-3-validacion.md` | Checklist de validación |
| `index.html` | Web autosuficiente, 7 pestañas, motor test 1/3 |

### QA aplicado

- Articulado contrastado con el texto oficial del ROGA 2004.
- Áreas de Gobierno verificadas contra el organigrama oficial vigente.
- Balanceo automático A/B/C de las respuestas del test.
- Refs cruzadas verificadas vs BOAM 10.032 (T2, T4, T5).
- Revisión ortográfica de los `.md`.

### Pendiente

- Validación de contenido por María / Ana (IAM).
- Reverificación del organigrama vigente antes de cada convocatoria (dato volátil).
