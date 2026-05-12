# Proyecto presell_colomdigital — AngelSense GPS Tracker for Elderly

> **Variante visual del `presell_mediguard` para despliegue en `colomdigital.online`.**
> Mismo producto, mismas UTMs, misma estructura narrativa central — pero paleta, brand, secciones reorganizadas y copy con variaciones menores para que parezca un sitio editorial distinto.

## Descripción
Presell advertorial estilo Taboola para **AngelSense GPS Tracker for Elderly**. Página estilo artículo editorial sobre wandering en adultos mayores con deterioro cognitivo. Sitio editorial: **Senior Family Today** (visual). UTM source: `caregiver_journal` (tracking — no se toca). Dominio de despliegue: **colomdigital.online**.

**ÁNGULO PRINCIPAL:** Hija de 56 años (Patricia Whitman) cuenta cómo su madre (Eleanor "Ellie", 82, MCI / mild cognitive impairment) salió a comprar pan y reapareció 8 horas después en un Walmart a 62 millas de distancia (Sandusky, Ohio). Después de probar Find My iPhone, Apple Watch, llamadas diarias y Life Alert, descubre AngelSense — un dispositivo de GPS en tiempo real diseñado específicamente para personas con pérdida de memoria.

## Producto real
- **Nombre:** AngelSense (GPS Tracker for Elderly)
- **URL oficial:** https://www.angelsense.com/gps-tracker-for-elderly/
- **Diferenciadores clave** (idénticos al original):
  - Real-time GPS continuo
  - Auto-answer two-way speakerphone
  - AI-powered wandering alerts
  - Indoor tracking via WiFi
  - Multi-guardian
  - Diseñado para memory loss / dementia

## URL de ventas (CTAs) — con tracking completo
**TODAS las CTAs apuntan a:**
```
https://www.angelsense.com/gps-tracker-for-elderly/?utm_source=caregiver_journal&utm_medium=native&utm_campaign=presell_reloj&ref=sary3125
```

**NO MODIFICAR los UTM params ni el `ref=sary3125`** — son la attribution/affiliate del usuario.

CTAs en `index.html`:
- Botón CTA #1 (después del product reveal)
- Botón CTA #2 (`#trigger-section` — activa sticky bottom bar)
- Botón CTA #3 (final, antes del cierre emocional, con bullets)
- Sidebar CTA
- Sticky bottom bar

## Diferencias visuales y estructurales vs. presell_mediguard

### Paleta nueva
- **Fondo body:** `#faf6ec` (cream cálido)
- **Texto oscuro:** `#131a2e` (navy casi negro)
- **Texto body:** `#2a3550`
- **Header/masthead:** `#1a2542` (navy profundo)
- **CTA botones:** `#b8862f` (mostaza dorada / dijon)
- **CTA hover:** `#95691f`
- **Accent:** `#9a3324` (rojo brick)
- **Estrellas:** `#d4a017`
- **Tagline color:** `#c9b66f` (mostaza claro sobre navy)

### Brand y header
- **Brand:** "Senior Family Today" (en vez de "Caregiver Journal")
- **Tagline:** "Independence · Memory Care · Family Tools"
- **Breadcrumb:** Home > Senior Safety > Memory Care
- **Category label:** "Memory Care"
- **Author title:** "Senior Safety Editor — Senior Family Today"

### Nombres
- Autora: Patricia Whitman (Sarah Kessler)
- Madre: Eleanor "Ellie" Whitman (Margaret "Maggie" Kessler)
- Hermano: Brian (Mike)
- Hija: Hannah (Lauren)
- Esposo: Greg (Tom)
- Cuñada hospice nurse: Susan (Karen)
- Ciudad incidente: Sandusky, Ohio (Mansfield, Ohio)
- Testimonios — nombres iguales, ciudades distintas: Jacksonville/Des Moines/Tucson/Hartford
- Comentario "Margaret G." renombrado a "Caroline G." para evitar choque con el nombre de la madre del original

### Reordenación de secciones (nuevo flow)
1. Barra ADVERTORIAL
2. Masthead "Senior Family Today"
3. Benefits bar
4. Breadcrumb
5. Headline + categoría "Memory Care"
6. Author card "Patricia Whitman"
7. Meta row (187,520 views, 8 min read)
8. Hero image (02.webp)
9. Hook narrativo (state trooper de Sandusky)
10. Imagen 03.webp
11. **🆕 NUEVA SECCIÓN: Red Flags Checklist** — 6 señales tempranas de MCI con checkboxes (`.redflags-box`)
12. Stats MCI (Alzheimer's Association)
13. Imagen 07.webp
14. Failed attempts
15. Imagen 06.webp
16. Discovery (sister-in-law Susan, hospice nurse)
17. Imagen 01.webp
18. Product reveal
19. Imagen producto.webp
20. **CTA #1**
21. **🔀 MOVIDO ARRIBA: Tabla comparativa** (antes iba después de "Why haven't I heard")
22. 8 features con checkmarks
23. First month
24. Imagen 04.webp
25. **CTA #2** (`#trigger-section`)
26. **🔀 INTERCAMBIADO: "Why Most Adult Children Have Never Heard of It"** (ahora antes de testimonios)
27. **🔀 INTERCAMBIADO: 4 testimonios** (ahora después de "Why haven't I heard")
28. **CTA #3** (final, con bullets y stock note)
29. Cierre emocional
30. Imagen 05.webp
31. 94 Comments
32. Sidebar sticky + Sticky bottom bar
33. Footer

### Nueva clase CSS `.redflags-box`
Borde mostaza, label superior con badge, checklist con 6 ítems (cada uno con un cuadrado vacío como checkbox visual), intro/outro. Ubicada después del hook narrativo.

### Variaciones menores en copy
- Headline reescrito (sentido idéntico)
- Views: 187,520 (era 213,894)
- Comments: 94 (eran 68)
- datePublished: 2026-05-04 (era 2026-05-07)
- Avatares de comentarios y reply: iniciales "PW" (era "SK") con colores de la paleta nueva
- CTAs labels: mantenidos del original
- Ciudades de testimonios cambiadas

## Tipografía
- **Serif (titulares):** Lora 400/700/900
- **Sans (cuerpo):** Source Sans 3 400/500/600/700/800

## SEO / Tags
- `<link rel="canonical">` apunta a `https://colomdigital.online/`
- OG tags (image, url, title, description, site_name) actualizados al nuevo brand y dominio
- JSON-LD con publisher "Senior Family Today" y mainEntityOfPage en colomdigital.online
- Páginas legales con `robots: noindex, follow`

## Directorio de trabajo
`/Users/emersoncordoba/Documents/Emerson/presell_create/presell_colomdigital`

## Dominio de despliegue
**colomdigital.online** — subir los archivos a la raíz del dominio.

## Origen
Variante visual del `presell_mediguard` (mismo producto AngelSense). Si se actualiza el copy nuclear del original, valorar propagar el cambio aquí manualmente.
