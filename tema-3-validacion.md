# Tema 3 — Checklist de Validación

> **Título oficial**: El Reglamento Orgánico del Gobierno y de la Administración del Ayuntamiento de Madrid, de 31 de mayo de 2004 (I): Las Áreas de Gobierno y su estructura interna. Órganos superiores; Órganos Centrales directivos. Número y denominación de las actuales Áreas de Gobierno.
> **Versión**: 1.0
> **Fecha**: 2026-06-15
> **Revisoras**: María + Ana (IAM)

---

## Cómo usar este checklist

- **OK** → el criterio se cumple sin cambios.
- **REVISAR** → necesita ajuste o aclaración (indicar qué).
- **NO** → no se cumple o es incorrecto. Justificar.

---

## 1. Fuentes y trazabilidad

- [ ] La fuente nuclear es el **ROGA 2004** (arts. 5-11 y 40-49), coincidente con el PDF aportado por el cliente y con el texto oficial.
- [ ] El epígrafe "número y denominación de las **actuales** Áreas de Gobierno" se ha actualizado con el **organigrama vigente** (transparencia.madrid.es).
- [ ] Cada afirmación que reproduce el articulado está referenciada con `[ROGA, art. X]` o `[LBRL, art. X]`.
- [ ] Cada pregunta del banco y de los casos puede reconducirse a un artículo del ROGA, a la LBRL o al organigrama vigente.

## 2. Estructura del contenido

- [ ] El `tema-3-indice.md` refleja fielmente la estructura de `tema-3-contenido.md`.
- [ ] Las secciones cubren: ROGA y régimen de gran ciudad, órganos (centrales/territoriales/organismos), superiores/directivos, Áreas de Gobierno (concepto y número), estructura interna, jerarquía, órganos superiores de las Áreas, órganos centrales directivos, nombramiento, Áreas actuales y resumen.
- [ ] Los conceptos memorizables aparecen como `[DATO CLAVE EXAMEN]`.
- [ ] Las reproducciones del articulado aparecen como `[CITA NORMATIVA]`.
- [ ] Los ejemplos del Ayto de Madrid están marcados como `[EJEMPLO AYTO MADRID]`.
- [ ] Los enlaces a otros temas se marcan como `[REFERENCIA CRUZADA]`.

## 3. Rigor jurídico

- [ ] El ROGA es de **31 de mayo de 2004**.
- [ ] Los dos principios de organización (división funcional / gestión territorial) son correctos [art. 5].
- [ ] La clasificación órganos centrales/territoriales/organismos es correcta [art. 6].
- [ ] La distinción órganos superiores (política) / directivos (ejecución) es correcta [art. 7].
- [ ] El número máximo de Áreas de Gobierno (**15**) y la competencia del alcalde son correctos [art. 40.2].
- [ ] La estructura interna (Secretaría General Técnica + Direcciones Generales) es correcta [art. 41].
- [ ] El orden jerárquico (coordinador general → secretario general técnico → director general) es correcto [art. 42.2].
- [ ] Las funciones excluidas a los concejales de Coordinación (b, c, d, e, j) son correctas [art. 45.1].
- [ ] El rango de director general del secretario general técnico es correcto [art. 47.1].
- [ ] El nombramiento por la Junta de Gobierno entre funcionarios (art. 130.3 LBRL) y la excepción (coordinador general sí, secretario general técnico no) son correctos [art. 49].

## 4. Diagramas SVG

- [ ] Los 12 diagramas están presentes en `tema-3-diagramas.md`.
- [ ] Cada diagrama incluye `role="img"` y `aria-label` descriptivo.
- [ ] Paleta coherente: Ayto Madrid #0055a0 + #d13c3c + #2d8659 + #e89822.
- [ ] Ningún diagrama depende de CDN, fuentes externas ni scripts.

## 5. Banco de 150 preguntas

- [ ] Las 150 preguntas tienen 3 opciones y una única respuesta correcta verificable.
- [ ] La distribución A/B/C está equilibrada (~50/50/50) tras el balanceo automático.
- [ ] No hay preguntas ambiguas.
- [ ] La sección pedagógica de 20 preguntas incluye explicación y referencia.

## 6. Casos prácticos

- [ ] Los 6 casos mantienen escenario del Ayto de Madrid.
- [ ] Las cuestiones de cada caso suman 10 puntos.
- [ ] Cada caso tiene solución orientativa y criterios de evaluación.

## 7. Nivel y adecuación al C1

- [ ] Nivel de profundidad adecuado para C1.
- [ ] Se prioriza la memorización de artículos, números y órganos.
- [ ] Los ejemplos de Madrid son realistas.

## 8. Entregables HTML

- [ ] `index.html` autosuficiente (offline), 7 pestañas, motor de test con penalización 1/3.
- [ ] Imprimible a PDF.
- [ ] Branding Ayuntamiento de Madrid (#0055a0).

## 9. Consistencia inter-temas

- [ ] Referencias cruzadas al **Tema 2** (régimen especial de Madrid) y al **Tema 4** (Distritos) coherentes.
- [ ] Referencia al **Tema 5** (EBEP) para el régimen de los directivos coherente.

---

## Observaciones generales

### Decisiones conscientes que conviene confirmar

1. **Alcance**: fiel al PDF de cliente (resumen + anexo ROGA arts. 40-49), **ampliado** con el marco general del ROGA (arts. 5-11), la LBRL invocada y la actualización del organigrama vigente.
2. **"Áreas de Gobierno actuales" actualizadas** con el organigrama oficial vigente (7 Áreas + Áreas Delegadas), por su carácter cambiante. El PDF de cliente coincide en las 7 Áreas.
3. **150 preguntas + 20 pedagógicas + 6 casos + 12 diagramas + 7 pestañas**, replicando el formato del Tema 1/Tema 2.
4. **Balanceo automático A/B/C** mediante permutación determinista en `build_t3.py`.

### Punto a vigilar

- El apartado **"número y denominación de las actuales Áreas de Gobierno"** es **volátil**: depende del decreto de organización de cada mandato. Antes de cada convocatoria conviene reverificar el organigrama vigente.

---

## Decisión de cierre

- [ ] Aprobado sin cambios.
- [ ] Aprobado con cambios menores (listarlos).
- [ ] Requiere v2 (listar cambios sustanciales).

**Firmas**:

- María: _______________________________ Fecha: _____________
- Ana: _______________________________ Fecha: _____________
