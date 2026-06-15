# Tema 3 — Catálogo de Diagramas

> **Título oficial**: El Reglamento Orgánico del Gobierno y de la Administración del Ayuntamiento de Madrid, de 31 de mayo de 2004 (I): Las Áreas de Gobierno.
>
> **Versión**: 1.0
> **Fecha**: 2026-06-15
> **Formato**: SVG inline (zero-dependencias, escalable, imprimible)
> **Paleta**: Ayuntamiento de Madrid #0055a0 (primario) + #d13c3c (alertas) + #2d8659 (ventajas) + #e89822 (callouts)

---

## Índice de diagramas

| ID  | Título                                                  | Sección | Tipo |
|-----|---------------------------------------------------------|---------|------|
| D1  | Los dos principios de organización del Ayuntamiento     | § 1     | Comparativa |
| D2  | Órganos centrales, territoriales y organismos (art. 6)  | § 2     | Árbol |
| D3  | Órganos superiores vs órganos directivos (art. 7)       | § 3     | Comparativa |
| D4  | Las Áreas de Gobierno: concepto y número (art. 40)      | § 4     | Esquema |
| D5  | Estructura interna de un Área de Gobierno (art. 41)     | § 5     | Árbol |
| D6  | Ordenación jerárquica de los directivos (art. 42)       | § 6     | Pirámide |
| D7  | Concejales de Gobierno vs de Coordinación (arts. 44-45) | § 8     | Comparativa |
| D8  | Órganos centrales directivos (arts. 46-48)              | § 9     | Esquema |
| D9  | Nombramiento de los órganos directivos (art. 49)        | § 9.4   | Flowchart |
| D10 | Alcalde, Junta de Gobierno y Pleno                      | § 11    | Esquema |
| D11 | Las 7 Áreas de Gobierno actuales                        | § 12    | Mapa |
| D12 | Mapa-resumen del Tema 3                                 | § 13    | Mapa conceptual |

---

## D1 · Los dos principios de organización del Ayuntamiento

**Sección**: § 1 — Introducción
**Propósito**: Mostrar la división funcional (Áreas) y territorial (distritos).

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 300" role="img" aria-label="Los dos principios de organización del Ayuntamiento de Madrid: división funcional en Áreas de Gobierno y gestión territorial en distritos">
  <style>
    .a-h{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .a-t{font:13px system-ui,sans-serif;fill:#1a1a1a;text-anchor:middle}
    .a-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="250" y="20" width="200" height="46" rx="8" fill="#003d75"/>
  <text x="350" y="40" class="a-h">ROGA 2004</text>
  <text x="350" y="57" class="a-h" style="font-weight:400;font-size:11px">art. 5 · organización municipal</text>
  <line x1="350" y1="66" x2="350" y2="86" stroke="#0055a0" stroke-width="1.5"/>
  <line x1="180" y1="104" x2="180" y2="86" stroke="#0055a0" stroke-width="1.5"/>
  <line x1="520" y1="104" x2="520" y2="86" stroke="#0055a0" stroke-width="1.5"/>
  <line x1="180" y1="86" x2="520" y2="86" stroke="#0055a0" stroke-width="1.5"/>
  <rect x="60" y="104" width="240" height="150" rx="8" fill="#e8f0f8" stroke="#0055a0" stroke-width="1.5"/>
  <text x="180" y="132" class="a-h" style="fill:#003d75">DIVISIÓN FUNCIONAL</text>
  <text x="180" y="160" class="a-t">Áreas de Gobierno</text>
  <text x="180" y="184" class="a-s">sectores homogéneos de</text>
  <text x="180" y="200" class="a-s">actividad · órganos centrales</text>
  <text x="180" y="228" class="a-s" style="font-weight:700;fill:#0055a0">→ TEMA 3 (este)</text>
  <rect x="400" y="104" width="240" height="150" rx="8" fill="#e8f5ee" stroke="#2d8659" stroke-width="1.5"/>
  <text x="520" y="132" class="a-h" style="fill:#1f5e3f">GESTIÓN TERRITORIAL</text>
  <text x="520" y="160" class="a-t">Distritos</text>
  <text x="520" y="184" class="a-s">gestión desconcentrada</text>
  <text x="520" y="200" class="a-s">por territorio · órganos territoriales</text>
  <text x="520" y="228" class="a-s" style="font-weight:700;fill:#2d8659">→ TEMA 4</text>
</svg>
```

---

## D2 · Órganos centrales, territoriales y organismos (art. 6)

**Sección**: § 2 — La organización del Ayuntamiento
**Propósito**: Clasificar la organización municipal en tres bloques.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" role="img" aria-label="Organización del Ayuntamiento: órganos centrales, órganos territoriales y organismos públicos según el artículo 6">
  <style>
    .b-root{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .b-box{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .b-t{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .b-h{font:700 13px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .b-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .b-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <rect x="250" y="20" width="200" height="46" rx="8" class="b-root"/>
  <text x="350" y="40" class="b-t">AYUNTAMIENTO DE MADRID</text>
  <text x="350" y="57" class="b-t" style="font-weight:400;font-size:11px">ROGA art. 6</text>
  <line x1="350" y1="66" x2="350" y2="92" class="b-l"/>
  <line x1="130" y1="110" x2="130" y2="92" class="b-l"/>
  <line x1="350" y1="110" x2="350" y2="92" class="b-l"/>
  <line x1="570" y1="110" x2="570" y2="92" class="b-l"/>
  <line x1="130" y1="92" x2="570" y2="92" class="b-l"/>
  <rect x="30" y="110" width="200" height="120" rx="8" class="b-box"/>
  <text x="130" y="138" class="b-h">Órganos CENTRALES</text>
  <text x="130" y="164" class="b-s">competencias sobre TODO</text>
  <text x="130" y="180" class="b-s">el municipio</text>
  <text x="130" y="206" class="b-s" style="font-style:italic">Áreas de Gobierno</text>
  <rect x="250" y="110" width="200" height="120" rx="8" class="b-box"/>
  <text x="350" y="138" class="b-h">Órganos TERRITORIALES</text>
  <text x="350" y="164" class="b-s">competencias en EL ÁMBITO</text>
  <text x="350" y="180" class="b-s">de un distrito</text>
  <text x="350" y="206" class="b-s" style="font-style:italic">distritos (Tema 4)</text>
  <rect x="470" y="110" width="200" height="120" rx="8" class="b-box"/>
  <text x="570" y="138" class="b-h">ORGANISMOS PÚBLICOS</text>
  <text x="570" y="164" class="b-s">ejecución / gestión</text>
  <text x="570" y="180" class="b-s">adscritos a un Área</text>
  <text x="570" y="206" class="b-s" style="font-style:italic">autónomos y EPE</text>
</svg>
```

---

## D3 · Órganos superiores vs órganos directivos (art. 7)

**Sección**: § 3 — Órganos superiores y directivos
**Propósito**: Contraponer las dos categorías y sus funciones.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" role="img" aria-label="Órganos superiores frente a órganos directivos según el artículo 7: los superiores dirigen políticamente y los directivos ejecutan">
  <style>
    .c-hb{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .c-s{font:11px system-ui,sans-serif;fill:#1a1a1a;text-anchor:start}
  </style>
  <rect x="30" y="20" width="310" height="270" rx="10" fill="#fff" stroke="#0055a0" stroke-width="1.5"/>
  <rect x="30" y="20" width="310" height="44" rx="10" fill="#0055a0"/>
  <text x="185" y="48" class="c-hb">ÓRGANOS SUPERIORES</text>
  <text x="50" y="92" class="c-s" style="font-weight:700;fill:#003d75">Función: dirección política</text>
  <text x="50" y="120" class="c-s">• El alcalde</text>
  <text x="50" y="144" class="c-s">• Miembros de la Junta de Gobierno Local</text>
  <text x="50" y="168" class="c-s">• Junta de Gobierno Local (órgano)</text>
  <text x="50" y="192" class="c-s">• Concejales con responsabilidades</text>
  <text x="62" y="208" class="c-s">de gobierno</text>
  <text x="50" y="232" class="c-s">• Concejales-presidentes de distrito</text>
  <text x="50" y="266" class="c-s" style="font-style:italic;fill:#777">dirección · planificación · coordinación</text>
  <rect x="360" y="20" width="310" height="270" rx="10" fill="#fff" stroke="#2d8659" stroke-width="1.5"/>
  <rect x="360" y="20" width="310" height="44" rx="10" fill="#2d8659"/>
  <text x="515" y="48" class="c-hb">ÓRGANOS DIRECTIVOS</text>
  <text x="380" y="92" class="c-s" style="font-weight:700;fill:#1f5e3f">Función: ejecución</text>
  <text x="380" y="120" class="c-s">• Coordinadores generales</text>
  <text x="380" y="144" class="c-s">• Secretarios generales técnicos</text>
  <text x="380" y="168" class="c-s">• Directores generales</text>
  <text x="380" y="192" class="c-s">• Asesoría Jurídica · interventor general</text>
  <text x="380" y="216" class="c-s">• Gerentes (distritos y organismos)</text>
  <text x="380" y="240" class="c-s">• Secretario general del Pleno</text>
  <text x="380" y="266" class="c-s" style="font-style:italic;fill:#777">ejecutan las decisiones</text>
</svg>
```

---

## D4 · Las Áreas de Gobierno: concepto y número (art. 40)

**Sección**: § 4 — Las Áreas de Gobierno
**Propósito**: Fijar el concepto, el máximo de 15 y quién las determina.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 280" role="img" aria-label="Las Áreas de Gobierno: niveles esenciales, número máximo de 15 y determinación por el alcalde, según el artículo 40">
  <style>
    .d-c{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .d-b{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .d-t{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .d-h{font:700 12px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .d-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <ellipse cx="350" cy="80" rx="160" ry="48" class="d-c"/>
  <text x="350" y="74" class="d-t">ÁREAS DE GOBIERNO</text>
  <text x="350" y="94" class="d-t" style="font-weight:400;font-size:11px">niveles esenciales · sectores homogéneos</text>
  <rect x="40" y="170" width="190" height="80" rx="8" fill="#fdf4e4" stroke="#e89822" stroke-width="1.5"/>
  <text x="135" y="200" class="d-h" style="fill:#a8650f">Número máximo</text>
  <text x="135" y="226" class="d-t" style="fill:#a8650f;font-size:24px">15</text>
  <rect x="255" y="170" width="190" height="80" rx="8" class="d-b"/>
  <text x="350" y="198" class="d-h">Las determina</text>
  <text x="350" y="220" class="d-h" style="font-size:14px">EL ALCALDE</text>
  <text x="350" y="238" class="d-s">nº, denominación y atribuciones</text>
  <rect x="470" y="170" width="190" height="80" rx="8" class="d-b"/>
  <text x="565" y="198" class="d-h">Pueden depender</text>
  <text x="565" y="220" class="d-s">Áreas de Coordinación</text>
  <text x="565" y="236" class="d-s">o Áreas Delegadas</text>
  <line x1="250" y1="120" x2="135" y2="170" stroke="#0055a0" stroke-width="1.2"/>
  <line x1="350" y1="128" x2="350" y2="170" stroke="#0055a0" stroke-width="1.2"/>
  <line x1="450" y1="120" x2="565" y2="170" stroke="#0055a0" stroke-width="1.2"/>
</svg>
```

---

## D5 · Estructura interna de un Área de Gobierno (art. 41)

**Sección**: § 5 — Estructura interna
**Propósito**: Árbol de la estructura de un Área.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 360" role="img" aria-label="Estructura interna de un Área de Gobierno: Secretaría General Técnica y Direcciones Generales, con Subdirecciones, Servicios, Departamentos y Secciones, según el artículo 41">
  <style>
    .e-root{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .e-box{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .e-low{fill:#e8f0f8;stroke:#0055a0;stroke-width:1}
    .e-t{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .e-h{font:700 12px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .e-s{font:10.5px system-ui,sans-serif;fill:#444;text-anchor:middle}
    .e-l{stroke:#0055a0;stroke-width:1.3;fill:none}
  </style>
  <rect x="260" y="16" width="180" height="42" rx="8" class="e-root"/>
  <text x="350" y="42" class="e-t">ÁREA DE GOBIERNO</text>
  <line x1="350" y1="58" x2="350" y2="78" class="e-l"/>
  <line x1="160" y1="96" x2="160" y2="78" class="e-l"/>
  <line x1="350" y1="96" x2="350" y2="78" class="e-l"/>
  <line x1="540" y1="96" x2="540" y2="78" class="e-l"/>
  <line x1="160" y1="78" x2="540" y2="78" class="e-l"/>
  <rect x="60" y="96" width="200" height="52" rx="8" class="e-box"/>
  <text x="160" y="118" class="e-h">Coordinador/es</text>
  <text x="160" y="135" class="e-h">general/es</text>
  <rect x="260" y="96" width="180" height="52" rx="8" class="e-box"/>
  <text x="350" y="118" class="e-h">Secretaría</text>
  <text x="350" y="135" class="e-h">General Técnica</text>
  <rect x="450" y="96" width="200" height="52" rx="8" class="e-box"/>
  <text x="550" y="118" class="e-h">Direcciones</text>
  <text x="550" y="135" class="e-h">Generales</text>
  <line x1="450" y1="180" x2="450" y2="148" class="e-l"/>
  <line x1="450" y1="148" x2="350" y2="148" class="e-l" style="stroke-dasharray:3"/>
  <rect x="190" y="210" width="320" height="120" rx="8" class="e-low"/>
  <text x="350" y="236" class="e-h">Unidades inferiores</text>
  <text x="350" y="262" class="e-s">Subdirecciones Generales</text>
  <text x="350" y="282" class="e-s">Servicios · Departamentos</text>
  <text x="350" y="302" class="e-s">Secciones y otras unidades</text>
  <text x="350" y="322" class="e-s" style="font-style:italic;fill:#777">art. 41.2</text>
  <line x1="350" y1="148" x2="350" y2="210" class="e-l"/>
</svg>
```

---

## D6 · Ordenación jerárquica de los directivos (art. 42)

**Sección**: § 6 — Ordenación jerárquica
**Propósito**: Pirámide del orden jerárquico de los órganos directivos.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 300" role="img" aria-label="Orden jerárquico de los órganos directivos: coordinador general, secretario general técnico y director general, según el artículo 42">
  <style>
    .f-t{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .f-n{font:700 12px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .f-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <polygon points="350,30 250,110 450,110" fill="#003d75"/>
  <text x="350" y="86" class="f-n">1.º</text>
  <text x="350" y="102" class="f-t" style="font-size:11px">Coordinador general</text>
  <rect x="210" y="118" width="280" height="58" fill="#0055a0"/>
  <text x="350" y="142" class="f-n">2.º</text>
  <text x="350" y="160" class="f-t">Secretario general técnico</text>
  <rect x="150" y="184" width="400" height="62" fill="#5a8fc0"/>
  <text x="350" y="208" class="f-n">3.º</text>
  <text x="350" y="226" class="f-t">Director general u órgano asimilado</text>
  <text x="350" y="276" class="f-s" style="font-style:italic">ROGA art. 42.2 (modif. 30/09/2015) · de mayor a menor rango</text>
</svg>
```

---

## D7 · Concejales de Gobierno vs de Coordinación (arts. 44-45)

**Sección**: § 8 — Órganos superiores de las Áreas
**Propósito**: Distinguir las funciones de unos y otros.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" role="img" aria-label="Comparación entre concejales de Gobierno y concejales de Coordinación: estos últimos ejercen las funciones del artículo 44 salvo las letras b, c, d, e y j">
  <style>
    .g-hb{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .g-s{font:11px system-ui,sans-serif;fill:#1a1a1a;text-anchor:start}
    .g-x{font:700 11px system-ui,sans-serif;fill:#a3271c;text-anchor:start}
  </style>
  <rect x="30" y="20" width="310" height="280" rx="10" fill="#fff" stroke="#0055a0" stroke-width="1.5"/>
  <rect x="30" y="20" width="310" height="58" rx="10" fill="#0055a0"/>
  <text x="185" y="44" class="g-hb">Concejales de GOBIERNO</text>
  <text x="185" y="64" class="g-hb" style="font-weight:400;font-size:11px">y consejeros-delegados de Gobierno</text>
  <text x="50" y="104" class="g-s" style="font-weight:700;fill:#003d75">Jefes SUPERIORES del Área (art. 44)</text>
  <text x="50" y="130" class="g-s">a) Representación, dirección, gestión</text>
  <text x="50" y="152" class="g-s">b) Fijar objetivos y planes</text>
  <text x="50" y="174" class="g-s">c) Elevar propuestas al Pleno</text>
  <text x="50" y="196" class="g-s">d) Proponer disposiciones a la Junta</text>
  <text x="50" y="218" class="g-s">e) Proponer organización al alcalde</text>
  <text x="50" y="240" class="g-s">f-i) Control, personal, conflictos…</text>
  <text x="50" y="262" class="g-s">j) Proponer nombramiento directivos</text>
  <text x="50" y="288" class="g-s" style="font-style:italic;fill:#777">ejercen TODAS las funciones</text>
  <rect x="360" y="20" width="310" height="280" rx="10" fill="#fff" stroke="#e89822" stroke-width="1.5"/>
  <rect x="360" y="20" width="310" height="58" rx="10" fill="#e89822"/>
  <text x="515" y="44" class="g-hb">Concejales de COORDINACIÓN</text>
  <text x="515" y="64" class="g-hb" style="font-weight:400;font-size:11px">y concejales-delegados</text>
  <text x="380" y="104" class="g-s" style="font-weight:700;fill:#a8650f">Jefes DIRECTOS del Área (art. 45)</text>
  <text x="380" y="132" class="g-s">Mismas funciones del art. 44…</text>
  <text x="380" y="160" class="g-x">EXCEPTO las letras:</text>
  <text x="380" y="184" class="g-x">b) objetivos y planes</text>
  <text x="380" y="206" class="g-x">c) elevar al Pleno</text>
  <text x="380" y="228" class="g-x">d) proponer disposiciones a la Junta</text>
  <text x="380" y="250" class="g-x">e) proponer organización al alcalde</text>
  <text x="380" y="272" class="g-x">j) proponer nombramiento directivos</text>
  <text x="380" y="294" class="g-s" style="font-style:italic;fill:#777">dependen del concejal de Gobierno</text>
</svg>
```

---

## D8 · Órganos centrales directivos (arts. 46-48)

**Sección**: § 9 — Órganos centrales directivos
**Propósito**: Resumir los tres órganos directivos y su función.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 280" role="img" aria-label="Órganos centrales directivos: coordinador general, secretario general técnico y director general, con sus funciones según los artículos 46 a 48">
  <style>
    .h-box{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .h-head{fill:#0055a0}
    .h-h{font:700 12px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .h-s{font:11px system-ui,sans-serif;fill:#444;text-anchor:middle}
    .h-a{font:700 11px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
  </style>
  <rect x="20" y="30" width="210" height="210" rx="8" class="h-box"/>
  <rect x="20" y="30" width="210" height="38" rx="8" class="h-head"/>
  <text x="125" y="54" class="h-h">Coordinador general</text>
  <text x="125" y="92" class="h-a">art. 46</text>
  <text x="125" y="120" class="h-s">Coordinación y dirección</text>
  <text x="125" y="138" class="h-s">de las Direcciones</text>
  <text x="125" y="156" class="h-s">Generales dependientes</text>
  <text x="125" y="196" class="h-s" style="font-style:italic">puede no ser funcionario</text>
  <text x="125" y="212" class="h-s" style="font-style:italic">(excepción art. 49)</text>
  <rect x="245" y="30" width="210" height="210" rx="8" class="h-box"/>
  <rect x="245" y="30" width="210" height="38" rx="8" class="h-head"/>
  <text x="350" y="54" class="h-h">Secretario general técnico</text>
  <text x="350" y="92" class="h-a">art. 47 · rango de director general</text>
  <text x="350" y="120" class="h-s">Servicios comunes</text>
  <text x="350" y="138" class="h-s">Asistencia jurídica y</text>
  <text x="350" y="156" class="h-s">técnica al titular del Área</text>
  <text x="350" y="196" class="h-s" style="font-style:italic">depende del titular</text>
  <text x="350" y="212" class="h-s" style="font-style:italic">del Área (siempre funcionario)</text>
  <rect x="470" y="30" width="210" height="210" rx="8" class="h-box"/>
  <rect x="470" y="30" width="210" height="38" rx="8" class="h-head"/>
  <text x="575" y="54" class="h-h">Director general</text>
  <text x="575" y="92" class="h-a">art. 48</text>
  <text x="575" y="120" class="h-s">Dirección y gestión de</text>
  <text x="575" y="138" class="h-s">ámbitos homogéneos</text>
  <text x="575" y="156" class="h-s">de competencia</text>
  <text x="575" y="196" class="h-s" style="font-style:italic">jefatura de las unidades</text>
  <text x="575" y="212" class="h-s" style="font-style:italic">adscritas</text>
</svg>
```

---

## D9 · Nombramiento de los órganos directivos (art. 49)

**Sección**: § 9.4 — Nombramiento
**Propósito**: Quién nombra y entre quién.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 280" role="img" aria-label="Nombramiento de los órganos directivos por la Junta de Gobierno, con carácter general entre funcionarios de carrera, según el artículo 49">
  <style>
    .i-c{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .i-b{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .i-t{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .i-h{font:700 12px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .i-s{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .i-l{stroke:#0055a0;stroke-width:1.5;fill:none}
  </style>
  <rect x="260" y="20" width="180" height="48" rx="8" class="i-c"/>
  <text x="350" y="42" class="i-t">JUNTA DE GOBIERNO</text>
  <text x="350" y="60" class="i-t" style="font-weight:400;font-size:11px">nombra y cesa (art. 49.1)</text>
  <line x1="350" y1="68" x2="350" y2="92" class="i-l"/>
  <rect x="200" y="92" width="300" height="50" rx="8" class="i-b"/>
  <text x="350" y="113" class="i-h">Coordinadores grales. · Secretarios grales.</text>
  <text x="350" y="131" class="i-h">técnicos · Directores generales</text>
  <line x1="350" y1="142" x2="350" y2="166" class="i-l"/>
  <rect x="90" y="166" width="240" height="86" rx="8" fill="#e8f5ee" stroke="#2d8659" stroke-width="1.5"/>
  <text x="210" y="190" class="i-h" style="fill:#1f5e3f">REGLA GENERAL</text>
  <text x="210" y="214" class="i-s">entre funcionarios de carrera</text>
  <text x="210" y="232" class="i-s">(art. 130.3 LBRL) · titulación</text>
  <text x="210" y="248" class="i-s">superior</text>
  <rect x="370" y="166" width="240" height="86" rx="8" fill="#fdf4e4" stroke="#e89822" stroke-width="1.5"/>
  <text x="490" y="190" class="i-h" style="fill:#a8650f">EXCEPCIÓN</text>
  <text x="490" y="214" class="i-s">puede no ser funcionario:</text>
  <text x="490" y="232" class="i-s">coordinador general SÍ</text>
  <text x="490" y="248" class="i-s">secretario gral. técnico NO</text>
  <line x1="350" y1="166" x2="210" y2="166" class="i-l"/>
  <line x1="350" y1="166" x2="490" y2="166" class="i-l"/>
</svg>
```

---

## D10 · Alcalde, Junta de Gobierno y Pleno

**Sección**: § 11 — Relación con el Alcalde y el Pleno
**Propósito**: Situar los tres órganos de gobierno y su papel.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 300" role="img" aria-label="Relación entre el alcalde, la Junta de Gobierno y el Pleno en la cadena de decisión municipal">
  <style>
    .j-box{stroke-width:1.5}
    .j-h{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .j-s{font:11px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .j-n{font:11px system-ui,sans-serif;fill:#555;text-anchor:middle}
  </style>
  <rect x="250" y="24" width="200" height="60" rx="8" fill="#003d75" class="j-box"/>
  <text x="350" y="50" class="j-h">ALCALDE</text>
  <text x="350" y="70" class="j-s">dirige y delega · máxima representación</text>
  <rect x="60" y="150" width="260" height="60" rx="8" fill="#0055a0" class="j-box"/>
  <text x="190" y="176" class="j-h">JUNTA DE GOBIERNO LOCAL</text>
  <text x="190" y="196" class="j-s">nombra directivos · aprueba disposiciones</text>
  <rect x="380" y="150" width="260" height="60" rx="8" fill="#2d8659" class="j-box"/>
  <text x="510" y="176" class="j-h">PLENO</text>
  <text x="510" y="196" class="j-s">funciones normativas y de control</text>
  <line x1="300" y1="84" x2="190" y2="150" stroke="#0055a0" stroke-width="1.5"/>
  <line x1="400" y1="84" x2="510" y2="150" stroke="#2d8659" stroke-width="1.5"/>
  <text x="350" y="252" class="j-n">Los concejales de Gobierno son la bisagra: elevan propuestas al Pleno (44.c)</text>
  <text x="350" y="270" class="j-n">y proponen disposiciones y nombramientos a la Junta de Gobierno (44.d, 44.j)</text>
</svg>
```

---

## D11 · Las 7 Áreas de Gobierno actuales

**Sección**: § 12 — Áreas de Gobierno actuales
**Propósito**: Listar las 7 Áreas vigentes.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 360" role="img" aria-label="Las siete Áreas de Gobierno actuales del Ayuntamiento de Madrid">
  <style>
    .k-h{font:700 14px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .k-b{fill:#e8f0f8;stroke:#0055a0;stroke-width:1.2}
    .k-t{font:12px system-ui,sans-serif;fill:#1a1a1a;text-anchor:start}
    .k-n{font:700 12px system-ui,sans-serif;fill:#0055a0;text-anchor:middle}
  </style>
  <rect x="120" y="16" width="460" height="40" rx="8" fill="#0055a0"/>
  <text x="350" y="41" class="k-h">7 ÁREAS DE GOBIERNO (vigentes)</text>
  <rect x="40" y="70" width="620" height="32" rx="6" class="k-b"/>
  <text x="58" y="91" class="k-n">1</text><text x="80" y="91" class="k-t">Vicealcaldía, Portavoz, Seguridad y Emergencias</text>
  <rect x="40" y="108" width="620" height="32" rx="6" class="k-b"/>
  <text x="58" y="129" class="k-n">2</text><text x="80" y="129" class="k-t">Urbanismo, Medio Ambiente y Movilidad</text>
  <rect x="40" y="146" width="620" height="32" rx="6" class="k-b"/>
  <text x="58" y="167" class="k-n">3</text><text x="80" y="167" class="k-t">Cultura, Turismo y Deporte</text>
  <rect x="40" y="184" width="620" height="32" rx="6" class="k-b"/>
  <text x="58" y="205" class="k-n">4</text><text x="80" y="205" class="k-t">Economía, Innovación y Hacienda</text>
  <rect x="40" y="222" width="620" height="32" rx="6" class="k-b"/>
  <text x="58" y="243" class="k-n">5</text><text x="80" y="243" class="k-t">Obras y Equipamientos</text>
  <rect x="40" y="260" width="620" height="32" rx="6" class="k-b"/>
  <text x="58" y="281" class="k-n">6</text><text x="80" y="281" class="k-t">Políticas Sociales, Familia e Igualdad</text>
  <rect x="40" y="298" width="620" height="32" rx="6" class="k-b"/>
  <text x="58" y="319" class="k-n">7</text><text x="80" y="319" class="k-t">Políticas de Vivienda</text>
  <text x="350" y="350" class="k-t" text-anchor="middle" style="font-style:italic;fill:#777">Dato actualizable: el alcalde fija el número (máx. 15) y la denominación cada mandato</text>
</svg>
```

---

## D12 · Mapa-resumen del Tema 3

**Sección**: § 13 — Resumen
**Propósito**: Mapa conceptual de cierre.

```svg
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 320" role="img" aria-label="Mapa resumen del Tema 3: ROGA, Áreas de Gobierno, estructura, órganos superiores y directivos">
  <style>
    .l-c{fill:#0055a0;stroke:#003d75;stroke-width:2}
    .l-n{fill:#fff;stroke:#0055a0;stroke-width:1.5}
    .l-ct{font:700 13px system-ui,sans-serif;fill:#fff;text-anchor:middle}
    .l-h{font:700 12px system-ui,sans-serif;fill:#003d75;text-anchor:middle}
    .l-s{font:10.5px system-ui,sans-serif;fill:#555;text-anchor:middle}
    .l-l{stroke:#0055a0;stroke-width:1;fill:none}
  </style>
  <line x1="350" y1="160" x2="160" y2="70" class="l-l"/>
  <line x1="350" y1="160" x2="540" y2="70" class="l-l"/>
  <line x1="350" y1="160" x2="160" y2="255" class="l-l"/>
  <line x1="350" y1="160" x2="540" y2="255" class="l-l"/>
  <ellipse cx="350" cy="160" rx="90" ry="44" class="l-c"/>
  <text x="350" y="156" class="l-ct">ROGA 2004</text>
  <text x="350" y="174" class="l-ct" style="font-weight:400;font-size:11px">Áreas de Gobierno</text>
  <rect x="40" y="42" width="240" height="56" rx="8" class="l-n"/>
  <text x="160" y="66" class="l-h">Concepto y número</text>
  <text x="160" y="84" class="l-s">niveles esenciales · máx. 15 · las fija el alcalde</text>
  <rect x="420" y="42" width="240" height="56" rx="8" class="l-n"/>
  <text x="540" y="66" class="l-h">Estructura interna</text>
  <text x="540" y="84" class="l-s">SGT + Direcciones Generales + unidades</text>
  <rect x="40" y="228" width="240" height="56" rx="8" class="l-n"/>
  <text x="160" y="252" class="l-h">Órganos superiores</text>
  <text x="160" y="270" class="l-s">concejales de Gobierno / de Coordinación</text>
  <rect x="420" y="228" width="240" height="56" rx="8" class="l-n"/>
  <text x="540" y="252" class="l-h">Órganos directivos</text>
  <text x="540" y="270" class="l-s">coord. gral. → SGT → director general</text>
</svg>
```
