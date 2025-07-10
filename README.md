# Arca Noé - Landing Page

Landing page para el centro de eventos infantiles "Arca Noé" ubicado en Los Maitenes, San Vicente.

## 🎨 Características

- **Diseño responsive** con Tailwind CSS
- **Paleta de colores personalizada**: Lila, Celeste, Amarillo, Rojo CTA y Verde WhatsApp
- **Tipografías**: Poppins (títulos) e Inter (texto)
- **Scroll suave** con snap-scroll
- **Botones WhatsApp** integrados
- **Optimizado para SEO** con meta tags OpenGraph
- **Animaciones hover** y transiciones suaves

## 🚀 Despliegue en Vercel

### Opción 1: Desde GitHub

1. Sube el proyecto a un repositorio de GitHub
2. Ve a [vercel.com](https://vercel.com) y conecta tu cuenta de GitHub
3. Selecciona "New Project" y elige tu repositorio
4. Configura el proyecto:
   - **Framework Preset**: Other
   - **Build Command**: (dejar vacío)
   - **Output Directory**: (dejar vacío)
   - **Install Command**: (dejar vacío)
5. Haz clic en "Deploy"

### Opción 2: Desde CLI

```bash
# Instalar Vercel CLI
npm i -g vercel

# En la carpeta del proyecto
vercel

# Seguir las instrucciones del CLI
```

## 🚀 Despliegue en Netlify

### Opción 1: Drag & Drop

1. Ve a [netlify.com](https://netlify.com)
2. Arrastra y suelta toda la carpeta del proyecto en la zona de deploy
3. ¡Listo! Tu sitio estará disponible en minutos

### Opción 2: Desde GitHub

1. Sube el proyecto a GitHub
2. En Netlify, selecciona "New site from Git"
3. Conecta tu repositorio
4. Configura:
   - **Build command**: (dejar vacío)
   - **Publish directory**: (dejar vacío o "./")
5. Haz clic en "Deploy site"

## 📁 Estructura del Proyecto

```
arcanoe/
├── index.html              # Página principal
├── public/                 # Imágenes y assets
│   ├── hero.jpg.placeholder     # Imagen hero (reemplazar)
│   └── bg-services.png.placeholder # Fondo servicios (reemplazar)
└── README.md               # Este archivo
```

## 🖼️ Imágenes Requeridas

Reemplaza los archivos placeholder con las imágenes reales:

1. **hero.jpg** (1920x1080px, <100KB)
   - Imagen principal del centro Arca Noé
   - Debe mostrar las instalaciones de manera atractiva

2. **bg-services.png** (1920x1080px, <100KB)
   - Imagen de fondo para la sección de servicios
   - Opcional: puede usar solo gradientes CSS

## 🎯 Optimización

### Comprimir Imágenes

Usa herramientas como:
- [TinyPNG](https://tinypng.com/)
- [ImageOptim](https://imageoptim.com/)
- [Squoosh](https://squoosh.app/)

### Lighthouse Score

El sitio está optimizado para obtener 90+ en todas las métricas:
- **Performance**: 90+
- **Accessibility**: 90+
- **Best Practices**: 90+
- **SEO**: 90+

## 📱 Contacto

- **WhatsApp**: +56 9 6394 9824
- **Ubicación**: Los Maitenes, San Vicente

## 🔧 Personalización

### Cambiar Colores

Modifica las variables en el `tailwind.config`:

```javascript
colors: {
    'lila': '#D8C9F3',
    'celeste': '#84D6F7',
    'amarillo': '#FFE97A',
    'rojo-cta': '#FF4F4F',
    'verde-whatsapp': '#25D366'
}
```

### Modificar Contenido

Todo el contenido está en el archivo `index.html` con comentarios que identifican cada sección:

- `<!-- HERO -->`
- `<!-- SERVICES GRID -->`
- `<!-- LOCATION -->`
- `<!-- FIXED CONTACT -->`
- `<!-- FOOTER -->`

## 📄 Licencia

© 2025 Arca Noé • Sitio demo
