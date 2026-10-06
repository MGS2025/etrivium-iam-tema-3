# Tema 3 — Changelog

> **Título oficial**: El Reglamento Orgánico del Gobierno y de la Administración del Ayuntamiento de Madrid, de 31 de mayo de 2004 (I): Las Áreas de Gobierno y su estructura interna. Órganos superiores; Órganos Centrales directivos. Número y denominación de las actuales Áreas de Gobierno.

---

## v1.4 — 2026-10-06 — Respuestas de la revisión jurídica

**Motivo**: respuestas a las dudas planteadas a la revisión jurídica (06-10-2026).

### Cambios

- **Citas entre corchetes al final del párrafo** (`[CE, art. 14]`) pasan a paréntesis con la ley detrás (`(art. 14 CE)`), el formato de las demás citas de inciso, por decisión de la revisión jurídica (06-10-2026). Se actualiza también la explicación de la convención de citas en Fuentes. Las claves bibliográficas de la tabla de fuentes no cambian.

---

## v1.3 — 2026-10-06 — Revisión de diagramas

**Motivo**: barrido de los diagramas de los 40 temas tras la revisión jurídica y de normas.

### Cambios

- Revisión visual de todos los diagramas, captura a captura (la medición automática no detecta contraste, flechas mal dirigidas ni textos pegados al borde): corregidos textos que se salían de su caja o del lienzo, cajas que se tocaban, flechas que no llegaban a su destino y textos con poco contraste. Sin cambios de contenido.

---

## v1.2 — 2026-10-01 — Revisión jurídica

**Estado**: aplicada la revisión jurídica de los temas 1-10 y contrastado el articulado con el **texto consolidado vigente del ROGA** (Código «Normativa del Ayuntamiento de Madrid» del BOE, última modificación del ROGA: 15-02-2023), la LBRL y la Ley 22/2006 en el BOE consolidado.

### Cambios de la revisión
- Fuentes: eliminada la referencia al material de origen del texto del ROGA.

### Correcciones contra el texto vigente del ROGA
- Art. 7.3: en el ámbito de los Distritos los órganos directivos son los **coordinadores de Distrito** (no los gerentes). Corregido en contenido, índice, diagrama D3, caso 1 y test.
- Art. 8: los órganos directivos y las Subdirecciones Generales los crea, modifica o suprime la **Junta de Gobierno** mediante acuerdos de organización administrativa; servicios, departamentos y unidades inferiores, por la RPT (antes: «decreto del alcalde»). Corregido en contenido y test.
- Art. 11.1: el alcalde puede delegar en los **coordinadores de Distrito** (antes: «gerentes»).
- Retirada la fecha de modificación «30-09-2015» de los arts. 42.2, 46 y 47 (contenido, diagrama D6, test y fuentes): no figura en el texto consolidado consultado.
- Fuentes: corregido el BOE de la Ley 22/2006 (núm. 159, de 05/07/2006) y añadida la publicación del ROGA (BOCM núm. 148, BOAM núm. 5610).

### Reglas generales
- Cajas renombradas: «Dato clave», «Cita normativa», «Ejemplo de aplicación en el Ayto», «Relación con otros temas» (HTML, `.md` y `build_t3.py`). Leyenda sin promesas sobre el examen; marcas sueltas `[REFERENCIA CRUZADA]` eliminadas.
- Citas de artículos: «artículo» completo cuando forma parte de la oración (arts. 6, 123.1.c)/124.4.k) y 130.3 LBRL; caso 2).
- Eliminadas reflexiones y promesas fuera de las cajas («Es una de las distinciones más preguntadas del tema», «la bisagra» en D10) y el encuadre del ROGA en el régimen de capitalidad (la Ley 22/2006 es posterior al ROGA).
- Eliminadas las referencias al material aportado por el cliente (tabla Tier 2, `Test_Prompting/…`, `[MAT-…]`, fila de trazabilidad, observaciones de validación); `[BOAM-10032]` pasa a Tier 1.
- Test: 22 preguntas sustituidas por preguntas literales del ROGA (9, 12, 13, 15, 20, 27, 42, 50, 53, 55, 72, 93, 98, 99, 110, 114, 119, 129, 137, 138, 139, 140); referencias precisadas en 1, 8, 11, 14, 36, 118 y 141; respuestas repartidas 50/50/50 en el `.md`. Los distractores con «gerente de distrito» (figura que el art. 7.3 vigente ya no recoge) pasan a «coordinador de Distrito». Pedagógicas P6, P9, P11, P15, P18, P19 y P20 ajustadas al texto literal.

---

## v1.1 — 2026-09-06 — Ficha de extensión y tiempo de estudio

**Estado**: sin cambios de contenido. Solo se añade información sobre el propio tema.

**Motivo**: petición del IAM (Jesús Cuadrado, 02-09-2026) al validar el Tema 30. Acepta la extensión de los temas «compuestos» a condición de que se informe de «su extensión en palabras y tiempo estimado de estudio». Al revisarlo se vio que ese dato solo aparecía en 16 de los 40 temas, y que faltaba justo en los más largos.

### Alcance

- Ficha bajo la cabecera del tema, y al final de la pestaña Índice donde esa pestaña existe:
  - **Extensión**: ~2.500 palabras · 12 diagramas · 150 preguntas de test
  - **Tiempo estimado de estudio**: 9-11 horas (primera vuelta completa, sin contar repasos)
- La cifra de palabras de la tabla de entregables se sincroniza con la ficha, para que el tema no muestre dos recuentos distintos.
- Las horas salen de una fórmula común a los 40 temas, para que sean comparables entre sí: contenido a 1.500 palabras/hora (ritmo de estudio activo), diagramas a una hora por cada cinco y test a dos minutos por pregunta. Se publica como intervalo de dos horas.
- Generado con `_tools-qa/ficha_estudio.py`, idempotente y reejecutable tras cualquier regeneración con `build_tNN.py`.

---

## v1.0 — 2026-06-15 — Generación inicial completa

**Estado**: Pendiente de validación por María / Ana (IAM).

### Alcance y decisiones

- **Fuente nuclear**: ROGA 2004, arts. 5-11 y 40-49, contrastado con el **texto oficial completo** del Ayuntamiento de Madrid.
- **Áreas de Gobierno actuales** actualizadas con el **organigrama oficial vigente** (transparencia.madrid.es, consultado 2026-06-15): **7 Áreas de Gobierno** + Áreas Delegadas.
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
