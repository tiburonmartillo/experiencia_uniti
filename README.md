# experienciaUNITI

Sitio informativo de la comunidad de estudiantes de **Programación e Innovación Digital** de la Universidad Intercultural para la Igualdad (UNITI).

## Secciones

- **Inicio** (`index.html`): portada y navegación.
- **Recursos** (`recursos.html`): plataformas para aprender (Coursera, IBM SkillsBuild, SQL Murder Mystery, freeCodeCamp y más) con filtros por categoría.
- **Convocatorias y Becas** (`convocatorias.html`): becas y beneficios estudiantiles (GitHub Student Pack, Figma for Education, Azure for Students, JetBrains, Notion).
- **Comercial** (`comercial.html`): enlaces de referencia (Mercado Pago, Amazon) con aviso de transparencia.
- **Blog** (`blog.html`): artículos de la comunidad con búsqueda.
- **Transparencia** (`transparencia.html`): información pública de la universidad (finanzas, contratos, convocatorias).

## Stack

- HTML + [Tailwind CSS](https://tailwindcss.com) (vía CDN, sin build)
- [Alpine.js](https://alpinejs.dev) (vía CDN) para tabs, filtros, búsqueda y menú móvil
- Diseño basado en el Design Language System (DLS) de Airbnb:
  - Color de acento único: **Rausch** `#FF385C`, reservado para el CTA primario
  - Tipografía tipo **Cereal** (sustituida por Inter en pesos 500/600/700; el cuerpo usa peso 500, nunca 400)
  - Neutrales: ink `#222222`, ash `#6A6A6A`, hairline `#DDDDDD`, cloud `#F7F7F7`
  - Esquinas suaves (14–20px), profundidad por whitespace y bordes 1px, sin sombras pesadas
  - Enlaces legales/informativos en azul `#428BFF`

## Desarrollo

Abre `index.html` en tu navegador, no requiere instalación de dependencias.

## Publicación con GitHub Pages

1. Ve a **Settings → Pages**.
2. En *Source* elige la rama `main` y carpeta `/ (root)`.
3. Guarda; el sitio queda en `https://tiburonmartillo.github.io/experiencia_uniti/`.

## Contribuir

Los artículos del blog y las sugerencias de recursos son bienvenidos. Propón cambios con un pull request.

---

Sitio independiente hecho por estudiantes, para estudiantes. No representa oficialmente a la universidad.
