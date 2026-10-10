# 🎤 MARTOCHA | Landing Page Oficial (Über Rastafari)

Landing page moderna, responsiva y optimizada para el rapero y freestyler argentino **Martocha** (*Über Rastafari*). Diseñada con estética urbana underground inspirada en la escena del rap porteño, las batallas de FMS Under y los vagones del subte.

---

## 📁 Estructura del Proyecto

```text
├── index.html          # Landing page principal (HTML5, Tailwind CDN, Pure JS)
├── 404.html            # Página de error 404 personalizada con estética de subte
├── sitemap.xml         # Mapa del sitio con soporte de indexación de video para Google
├── robots.txt          # Directivas de rastreo para buscadores web
├── site.webmanifest    # Manifiesto PWA para instalación como app en celulares
├── vercel.json         # Configuración de headers de seguridad y caché para Vercel
└── README.md           # Documentación del proyecto
```

---

## 🚀 Tecnologías y Características

- **HTML5 Semántico**: Estructura accesible con etiquetas semánticas y marcado optimizado.
- **Tailwind CSS (CDN)**: Estilos modulares, utilidades responsivas, temas oscuros y acentos neón sin necesidad de compilar paquetes.
- **JavaScript Puro (Vanilla JS)**: 
  - `IntersectionObserver` para revelado suave de componentes al hacer scroll.
  - Control de reproducción con **YouTube IFrame API** y botón interactivo para **Desmutear / Mutear**.
  - Procesador para el embed oficial del **Reel de Instagram**.
  - Menú hamburguesa dinámico para dispositivos móviles.
  - Inyección dinámica del año en el footer.
- **Google Fonts**: Tipografías de alto impacto visual (*Anton*, *Syne* y *Space Grotesk*).
- **FontAwesome 6**: Íconos vectoriales modernos para redes sociales y elementos de acción.
- **Schema Markup (JSON-LD)**: Metadatos estructurados bajo el estándar `MusicArtist` de [Schema.org](https://schema.org) para potenciar el SEO orgánico.
- **Open Graph & Twitter Cards**: Metadatos enriquecidos con portada oficial en alta definición para previsualizaciones en WhatsApp, Instagram, Telegram y X/Twitter.

---

## 🎨 Estructura y Secciones

1. **Header Sticky**: Logotipo con badges, widget visual de ecualizador animado, enlaces de navegación y botón directo a YouTube.
2. **Hero Section**:
   - Título impactante: `MARTOCHA` + `ÜBER RASTAFARI`.
   - Lema: *"Barras, Subte y Freestyle Argentino"*.
   - Botón CTA principal de alta conversión hacia su canal de YouTube.
   - Fondo con textura de asfalto y escena urbana.
   - Métricas y sellos (FMS Under, Cultura Subte, +100K reproducciones).
3. **Sobre Mí (Bio)**:
   - Reseña de su trayectoria combinando rap crudo, humor, anécdotas de viajes en Uber y competencia en plazas.
   - **Reel oficial de Instagram embebido** con halo neón y enlace directo al perfil `@martocha__`.
   - Tarjeta destacada con el hito viral del cruce de **Rap vs Ópera** en el subte.
4. **Música y Visuales**:
   - Contenedor destacado para el single: `ESTO NO SE ACABA - MARTOCHAxDINÁMICA` con reproductor responsivo de YouTube (aspect ratio 16:9), autoplay silenciado y botón de **Desmutear**.
   - Galería en grilla tipo *Shorts* / TikTok con miniaturas y tarjetas para batallas, comedia y momentos virales.
5. **Banner de Contacto / Colaboraciones**:
   - Enlace directo a Instagram para envío de beats o fechas.
6. **Footer**:
   - Enlaces directos a YouTube ([@Martochau](https://www.youtube.com/@Martochau)) e Instagram/TikTok ([@martocha__](https://www.instagram.com/martocha__)).

---

## 🌐 Cómo Desplegar

### Opción 1: Vercel (Recomendado)
1. Ingresá a [vercel.com](https://vercel.com) e importá este proyecto.
2. Como es un sitio estático basado en `index.html`, no requiere build step adicional.
3. El archivo `vercel.json` aplicará automáticamente los encabezados de seguridad y caché.

### Opción 2: GitHub Pages
1. Subí este repositorio a GitHub.
2. En GitHub, andá a **Settings** > **Pages**.
3. En **Branch**, seleccioná `main` (o `master`) y la carpeta `/ (root)`. Guardá y en pocos segundos la web estará en línea.

### Opción 3: Previsualización Local
Simplemente hacé doble clic sobre el archivo `index.html` en el explorador de archivos o levantá un servidor local:
```bash
# Con Python
python -m http.server 8000

# Con Node.js (npx serve)
npx serve .
```
