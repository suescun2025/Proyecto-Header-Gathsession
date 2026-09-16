# GathSession — Landing Page Header & Hero

Landing page moderna, semántica y responsive construida para la plataforma **GathSession**.

## 🚀 Tecnologías

- **HTML5** semántico y accesible.
- **CSS3** con Custom Properties (Variables), Flexbox y diseño Responsive.
- **JavaScript (ES6+)** para interacciones y scroll fluido.
- **Webpack 5** con entorno de desarrollo (`webpack-dev-server`) y build de producción optimizado.

---

## 📁 Estructura del Proyecto

```text
├── index.html            # Estructura principal de la página
├── 404.html              # Página de error 404
├── css/
│   └── style.css         # Hoja de estilos con variables y media queries
├── js/
│   └── app.js           # Lógica JavaScript y scroll interactivo
├── img/                  # Imágenes, avatares, logotipos e iconos
├── webpack.common.js     # Configuración base de Webpack
├── webpack.config.dev.js # Configuración de Webpack para desarrollo
├── webpack.config.prod.js# Configuración de Webpack para producción
├── site.webmanifest      # Manifiesto PWA / Web App
├── robots.txt            # Reglas de indexación para motores de búsqueda
└── package.json          # Dependencias y scripts del proyecto
```

---

## 🛠️ Instalación y Uso

### 1. Instalar dependencias
```bash
npm install
```

### 2. Iniciar servidor de desarrollo
Inicia el servidor local con recarga en vivo (live reload):
```bash
npm start
```

### 3. Generar build de producción
Compila y minifica todos los archivos en la carpeta `dist/`:
```bash
npm run build
```

---

## ✨ Buenas Prácticas Aplicadas

1. **HTML5 Semántico**: Uso correcto de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, y etiquetas de encabezado `<h1>` y `<h3>` estructuradas lógicamente.
2. **Accesibilidad (a11y)**: Textos alternativos descriptivos (`alt`), roles ARIA (`aria-labelledby`, `aria-hidden`), e idiomas definidos (`lang="en"`).
3. **SEO y Metadatos**: Meta etiquetas de descripción, Viewport responsive, Open Graph para redes sociales y Favicons en múltiples formatos.
4. **CSS Estructurado**: Sin estilos en línea, carga de fuentes optimizada vía Google Fonts `preconnect`, uso de variables CSS para consistencia de color y diseño adaptable a móviles y tablets.
