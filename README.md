# Valley Funji - Sitio Web

Un sitio web moderno y responsivo para experiencias de aventura y turismo en la naturaleza.

## 📋 Descripción

Valley Funji es un sitio web desarrollado con HTML5, CSS3 y JavaScript vanilla, utilizando Bootstrap 5 para el diseño responsivo. El proyecto presenta un diseño moderno, animaciones suaves y una experiencia de usuario optimizada.

## 🚀 Características

- **Diseño Responsive**: Adaptado para todos los dispositivos (móvil, tablet, desktop)
- **Animaciones Suaves**: Efectos de scroll, hover y transiciones CSS
- **Navegación Intuitiva**: Menú fijo con scroll suave entre secciones
- **Formularios Interactivos**: Validación en tiempo real y notificaciones
- **Optimización de Imágenes**: Uso de imágenes de alta calidad desde Unsplash
- **Performance**: Carga rápida con CDN y optimizaciones

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Propiedades avanzadas, variables CSS, animaciones
- **JavaScript (ES6+)**: Interactividad y animaciones
- **Bootstrap 5.3.2**: Framework CSS para diseño responsive
- **Font Awesome 6.4.0**: Iconos vectoriales
- **Google Fonts**: Tipografías (Poppins, Playfair Display)

## 📁 Estructura del Proyecto

```
valley-funji/
│
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos personalizados
├── js/
│   └── main.js         # JavaScript principal
├── images/             # Carpeta para imágenes locales (opcional)
├── assets/             # Otros recursos
├── .gitignore          # Archivos ignorados por Git
└── README.md           # Documentación del proyecto
```

## 🎨 Secciones del Sitio

1. **Hero Section**: Sección principal con imagen de fondo y call-to-action
2. **Servicios**: Tarjetas con información de servicios ofrecidos
3. **Sobre Nosotros**: Información de la empresa con estadísticas
4. **Galería**: Grid de imágenes con efectos hover
5. **Contacto**: Formulario de contacto e información de contacto
6. **Footer**: Enlaces, redes sociales y newsletter

## 🚀 Instalación y Uso

### Opción 1: Abrir directamente
1. Clona o descarga el repositorio
2. Abre `index.html` en tu navegador

### Opción 2: Servidor local
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (http-server)
npx http-server

# Con PHP
php -S localhost:8000
```

Luego abre `http://localhost:8000` en tu navegador.

## 📱 Responsive Design

El sitio está optimizado para:
- **Mobile**: < 576px
- **Tablet**: 576px - 992px
- **Desktop**: > 992px

## 🎯 Características Técnicas

### CSS Avanzado
- Variables CSS para colores y espaciado
- Flexbox y Grid para layouts
- Animaciones y transiciones
- Media queries para responsive
- Scrollbar personalizada

### JavaScript
- Intersection Observer para animaciones al scroll
- Validación de formularios
- Smooth scroll navigation
- Contador animado
- Efectos parallax
- Lazy loading de imágenes

### Optimizaciones
- Uso de CDN para librerías externas
- Imágenes optimizadas desde Unsplash
- Font-display: swap para fuentes
- Scroll behavior smooth

## 🌐 Navegadores Soportados

- Chrome (últimas 2 versiones)
- Firefox (últimas 2 versiones)
- Safari (últimas 2 versiones)
- Edge (últimas 2 versiones)

## 📝 Personalización

### Colores
Los colores principales se pueden modificar en las variables CSS en `css/style.css`:

```css
:root {
    --primary-color: #2c5f41;
    --secondary-color: #f4a261;
    --accent-color: #e76f51;
    /* ... más colores */
}
```

### Contenido
- Edita el contenido directamente en `index.html`
- Las imágenes se cargan desde Unsplash (puedes cambiar las URLs)
- Los textos están en español y pueden modificarse fácilmente

## 🔧 Próximas Mejoras

- [ ] Integración con backend para formularios
- [ ] Sistema de reservas online
- [ ] Galería con lightbox
- [ ] Modo oscuro
- [ ] PWA (Progressive Web App)
- [ ] Internacionalización (i18n)

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 👨‍💻 Autor

Desarrollado para Valley Funji

## 🙏 Agradecimientos

- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
- [Unsplash](https://unsplash.com/) por las imágenes

---

**Nota**: Este es un proyecto de demostración. Para producción, considera:
- Optimizar imágenes localmente
- Implementar backend para formularios
- Agregar análisis y tracking
- Configurar HTTPS
- Implementar SEO avanzado

