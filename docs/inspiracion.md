# Inspiración

Una entrada por elemento, no por página. Anotar el *por qué*, no solo el *qué*.

Plantilla:

```markdown
### Nombre corto del elemento
- Fuente: URL (sección o momento exacto)
- Qué me gusta:
- Dónde lo usaría:
- Prioridad: alta | media | baja
- Componente candidato: (a confirmar)
- Captura: ![](img/archivo.png)
```

## Estilo general
<!-- paleta, tipografías, sensación general -->

## Hero / presentación

## Tarjetas de proyectos
<!-- cómo se muestran, hover, filtros, página de detalle -->

### Carrusel de proyectos
- Fuente: idea propia (buscar referencias en minimal.gallery / directoryyy)
- Qué me gusta: recorrer los proyectos uno por uno en vez de una grilla
- Dónde lo usaría: sección principal de proyectos
- Prioridad: alta
- Variantes a evaluar:
  - Carrusel clásico con flechas, swipe y arrastre (Embla, que usa el Carousel de shadcn)
  - Scroll horizontal "pinneado": al scrollear hacia abajo, los proyectos se desplazan de costado (GSAP ScrollTrigger o `useScroll` de Motion)
- Requisitos: navegable con teclado, swipe en el celu, que se vea qué hay más tarjetas (indicadores o la siguiente asomando)
- Debe soportar filtrar por categoría (Desarrollo / Ciberseguridad) cuando se sumen los labs
- Componente candidato: (a confirmar)
- Captura: pendiente

## Navegación y transiciones
<!-- scroll, cambios de página, cursor -->

### Cursor personalizado
- Fuente: idea propia (buscar referencias)
- Qué me gusta: que el cursor tenga diseño propio y le dé personalidad al sitio
- Dónde lo usaría: todo el sitio
- Prioridad: alta
- Ideas a evaluar:
  - Punto + círculo que lo sigue con retraso suave (spring)
  - El círculo crece o cambia al pasar sobre links y tarjetas ("Ver proyecto")
  - Modo `mix-blend-mode: difference` para que invierta colores
  - Variante temática para ciberseguridad (cursor tipo terminal / mira)
- Requisitos: desactivado en pantallas táctiles, respetar `prefers-reduced-motion`, no tapar el texto ni dar lag
- Componente candidato: Motion (springs) hecho a mano, o cursores de Magic UI / React Bits (a confirmar)
- Captura: pendiente

## Efectos de fondo
<!-- 3D, partículas, gradientes -->

## Descartado
<!-- qué no convenció y por qué -->
