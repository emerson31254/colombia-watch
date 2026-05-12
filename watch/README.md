# presell_colomdigital (AngelSense — "Senior Family Today" para colomdigital.online)

Variante visual del advertorial de `presell_mediguard` para **AngelSense GPS Tracker for Elderly**, preparada para desplegarse en el dominio **colomdigital.online**.

> Mismo producto, mismas UTMs, misma estructura narrativa — pero look, paleta, brand editorial y reorganización de secciones distintos al original.

## Diferencias respecto a `presell_mediguard`

### Visual
- **Paleta:** navy profundo (`#1a2542`) + mostaza dorada (`#b8862f`) sobre cream (`#faf6ec`), en vez de verde bosque + terracota.
- **Brand editorial:** "Senior Family Today" en vez de "Caregiver Journal".
- **Tagline:** "Independence · Memory Care · Family Tools".
- **Breadcrumb:** Home > Senior Safety > Memory Care.

### Estructural
- **Nueva sección "Red Flags Checklist"** justo después del hook (6 señales tempranas de MCI con checkboxes).
- **Tabla comparativa movida arriba** — justo después del CTA #1, antes de las 8 features detalladas.
- **"Why haven't I heard of it" reordenada antes de los testimonios** (en el original iba después).

### Copy
- **Autora:** Patricia Whitman (antes Sarah Kessler).
- **Madre:** Eleanor "Ellie" Whitman (antes Margaret "Maggie" Kessler).
- **Ciudad del incidente:** Sandusky, Ohio (antes Mansfield, Ohio — mismo ~60 millas de Cleveland).
- **Familia:** Brian (hermano), Hannah (hija), Greg (esposo), Susan (cuñada hospice nurse).
- **Headline reformulado** (sentido idéntico, otras palabras).
- **Testimonios:** mismas historias, ciudades distintas (Jacksonville, Des Moines, Tucson, Hartford).
- **Views:** 187,520 · **Comments:** 94.

### Técnico
- `<link rel="canonical">` y OG tags apuntando a `https://colomdigital.online/`.
- Páginas legales con `robots: noindex, follow`.

## Sin cambios
- **CTAs:** todos siguen apuntando a `angelsense.com/...?utm_source=caregiver_journal&utm_medium=native&utm_campaign=presell_reloj&ref=sary3125`. **No tocar las UTMs ni `ref=sary3125`** — son la attribution del usuario.
- Producto: AngelSense GPS Tracker for Elderly.
- 8 features y argumentación central.

## Quick start

```
open index.html
```

CSS inline. No requiere build.

## Estructura

```
presell_colomdigital/
├── index.html              ← Presell rebrandeada (CSS inline)
├── disclaimer.html         ← Disclaimer (brand actualizado)
├── privacy-policy.html     ← Privacidad (brand actualizado)
├── term-of-use.html        ← Términos (brand actualizado)
├── img/                    ← 8 imágenes (.webp) — sin cambios
├── style/style.css         ← (heredado, no usado)
├── public/style.css        ← CSS genérico para páginas legales
├── CLAUDE.md               ← Documentación detallada
└── README.md               ← Este archivo
```

## Despliegue

Sube los archivos directamente a la raíz de `colomdigital.online`.

## Notas
- Idioma: inglés (US).
- Tono: editorial/advertorial "super white" — sin claims médicos exagerados.
- Stats reales del Alzheimer's Association mantenidos.
