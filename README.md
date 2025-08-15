# 🚀 IT Facilities - Sitio Web Profesional

## 📋 Descripción del Proyecto

IT Facilities es un sitio web corporativo para una empresa argentina de servicios IT, desarrollado como proyecto final para el curso de desarrollo web. El sitio incluye 5 páginas HTML con diseño responsive, SEO optimizado, y técnicas avanzadas de CSS/SASS.

## ✨ Características Implementadas

### 🎨 **Diseño y Estructura**
- **5 páginas HTML** completas y bien estructuradas
- **Bootstrap 5.3.3** para responsive design
- **SASS/SCSS** con variables, mixins, extend y anidamiento
- **CSS Grid nativo** para layouts avanzados
- **Flexbox** para alineación y distribución de elementos

### 🔍 **SEO y Accesibilidad**
- **Meta tags** optimizados para cada página
- **Open Graph** para redes sociales
- **Twitter Cards** para mejor compartido
- **Schema.org markup** (datos estructurados)
- **Sitemap.xml** y **robots.txt**
- **Skip links** para navegación por teclado
- **Atributos ARIA** y mejor contraste

### 🎭 **Animaciones y Efectos**
- **Keyframes CSS** personalizados (fadeInUp, slideInLeft, pulse, bounce)
- **Transiciones suaves** en hover y focus
- **Animaciones de scroll** con Intersection Observer
- **Efectos hover** avanzados para cards y botones
- **Lazy loading** para imágenes

### 📱 **Responsive Design**
- **Mobile-first** approach con Bootstrap
- **Media queries personalizadas** para breakpoints específicos
- **Grid system** adaptable a todos los dispositivos
- **Navegación colapsable** para móviles

## 🗂️ Estructura del Proyecto

```
IT-Facilities-Web/
├── index.html          # Página principal
├── about.html          # Sobre nosotros
├── services.html       # Servicios
├── gallery.html        # Galería
├── contact.html        # Contacto
├── css/
│   └── styles.css      # Estilos compilados
├── scss/
│   └── styles.scss     # Archivo SASS fuente
├── img/                # Imágenes del sitio
├── robots.txt          # Instrucciones para crawlers
├── sitemap.xml         # Mapa del sitio
└── README.md           # Este archivo
```

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos y animaciones
- **SASS/SCSS** - Preprocesador CSS
- **Bootstrap 5.3.3** - Framework CSS
- **JavaScript ES6+** - Interactividad
- **Intersection Observer API** - Animaciones de scroll

## 🚀 Instalación y Uso

### 1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/It-Facilities-Web.git
cd It-Facilities-Web
```

### 2. **Instalar dependencias**
```bash
npm install -g sass
```

### 3. **Compilar SASS**
```bash
# Compilación única
npx sass scss/styles.scss css/styles.css --no-source-map

# Compilación en tiempo real
npx sass --watch scss/styles.scss:css/styles.css --no-source-map
```

### 4. **Abrir en navegador**
```bash
# Usar un servidor local
python -m http.server 8000
# o
npx serve .
```

## 📱 Páginas del Sitio

### **🏠 index.html**
- Página principal con hero section
- Servicios destacados
- Navegación principal
- Animaciones de entrada

### **👥 about.html**
- Historia de la empresa
- Misión y valores
- Equipo de trabajo
- Diseño con cards extendidas

### **🛠️ services.html**
- Catálogo de servicios
- Planes y precios
- Grid responsive
- Efectos hover avanzados

### **🖼️ gallery.html**
- Galería de imágenes
- CSS Grid nativo
- Efectos de zoom
- Lazy loading

### **📞 contact.html**
- Formulario de contacto
- Información de la empresa
- Mapa integrado
- Validación de formularios

## 🎯 Criterios de Evaluación Cumplidos

### ✅ **Código HTML y CSS Óptimo**
- Estructura HTML prolija y bien estructurada
- Sitio responsive a distintas resoluciones
- Librerías implementadas correctamente
- Uso completo de SASS

### ✅ **Diseño Responsive: Grids + Flexbox + Box Modeling**
- CSS Grid nativo implementado
- Flexbox avanzado en secciones
- Media queries personalizadas
- Sin overflow-x

### ✅ **Diseño Responsive: Framework (Bootstrap)**
- Bootstrap 5.3.3 implementado correctamente
- Clases utilizadas apropiadamente
- Responsive design optimizado
- Navegación colapsable

### ✅ **Contenido, Diseño y Estética**
- Diseño armónico y profesional
- Jerarquías claras de contenido
- Navegación intuitiva y dinámica
- Efectos de interacción implementados
- SEO completo y accesibilidad mejorada

## 🔧 Personalización

### **Variables SASS**
```scss
$main-bg: #333;
$main-color: white;
$accent-color: #ddd;
$border-radius: 5px;
```

### **Mixins Disponibles**
```scss
@mixin flex-center($direction: row)
@mixin transition($props...)
@mixin keyframe-animation($name, $duration, $timing, $iteration)
```

### **Clases de Animación**
- `.fade-in-up` - Aparece desde abajo
- `.slide-in-left` - Desliza desde la izquierda
- `.fade-delay-1` a `.fade-delay-5` - Delays escalonados
- `.btn-animado` - Botón con efectos avanzados

## 📊 Performance y Optimización

- **Lazy loading** para imágenes
- **CSS comprimido** sin source maps
- **JavaScript optimizado** con Intersection Observer
- **Transiciones CSS** para mejor performance
- **Media queries** eficientes

## 🌐 Despliegue

### **Hosting Gratuito Recomendado**
- **Infinity Free** - Hosting gratuito con dominio
- **000webhost** - Hosting gratuito de Hostinger
- **Netlify** - Despliegue desde GitHub
- **Vercel** - Despliegue automático

### **Pasos para Despliegue**
1. Subir archivos al hosting
2. Verificar que `index.html` sea el archivo principal
3. Comprobar rutas de imágenes y CSS
4. Verificar SEO con Google Search Console

## 📝 Notas de Desarrollo

- **SASS** compilado a CSS para producción
- **Bootstrap** CDN para mejor performance
- **JavaScript** modular y bien organizado
- **Accesibilidad** siguiendo estándares WCAG

## 🤝 Contribuciones

Este proyecto fue desarrollado como trabajo final del curso de desarrollo web. Las contribuciones son bienvenidas para mejorar la funcionalidad y el diseño.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

**Desarrollado con ❤️ para IT Facilities**
