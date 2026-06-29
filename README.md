# MUDA · Design System de Koi Samsa

La casa de **MUDA**, el design system personal de Koi Samsa: documentación y entregables. Por ahora su cara visible es el **Storybook** — un muestrario navegable de los principios, tokens y componentes del sistema. Cuando el microsite completo esté montado, el Storybook pasará a ser una de sus páginas (Construir → Storybook) y esta raíz alojará la portada.

🔗 **[Abrir el Storybook](https://koisamsa.github.io/muda/)**
_(disponible una vez activado GitHub Pages en Settings → Pages)_

---

## Qué es

Una única página web, sin instalación ni servidor. Se abre en cualquier navegador y funciona sin conexión una vez cargada. Recorre el sistema por capas, al modo Atomic Design:

- **Introducción** — qué es MUDA, los tres principios (Silencio · Andamiaje · Cosmología) y el estado de la reconciliación.
- **Tokens de diseño** — las 14 piezas de color, las cuatro voces tipográficas, espaciado, radios y sombras.
- **Átomos** — chip, tag, botón (con sus estados y contraste WCAG), notice.
- **Moléculas** — callout, breadcrumbs, metadatos de artículo.
- **Énfasis y citas** — los tres callouts (`--brand` · `--note` · `--related`), pullquote, quote-hl y subrayado.
- **Organismos** — cards (portfolio neutra y de categoría con franja de color).
- **UI · estados** — alertas semánticas y formulario.
- **Plantillas** — prose editorial y la galería /lab.

## Diseño

La interfaz usa **MUDA**, el sistema de diseño de Koi Samsa: tipografía Newsreader · Albert Sans · Fira Sans · Fira Code, y la paleta cromática mineral de 14 piezas. El Storybook es, además, una pieza viva de ese sistema — se viste a sí mismo (principio de Andamiaje).

Los tokens se nombran con el prefijo `muda-` y las variantes siguen convención BEM (`--brand`, `--note`…). Los hex están verificados contra la decisión firmada del sistema cromático; lo no firmado lleva su sello de deuda visible.

## Estado

**Storybook en proceso de creación · v1.** Es un muestrario y explicación, no una librería de componentes de producción. Algunas piezas (dark mode, rampa cobre) están marcadas como deuda pendiente dentro del propio documento.

## Cómo usarlo

Solo abre el enlace de arriba. Para tenerlo en local: descarga `index.html` y ábrelo con doble clic.

## Licencia

[MIT](LICENSE) — úsalo, cópialo y adáptalo libremente citando la autoría.

---

Hecho por **Koi Samsa** · [koisamsa.com](https://koisamsa.com)
