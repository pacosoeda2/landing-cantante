# 🎤 Sandra Pastor - Sitio Web Oficial

**Cantante profesional para bodas y eventos en Málaga y Andalucía**

[![Website](https://img.shields.io/badge/Website-Online-green)](http://sandrapastor.myartsonline.com/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/usuario/sandra-pastor-website)

## 📋 Descripción

Sitio web profesional de Sandra Pastor, cantante especializada en bodas, eventos corporativos y karaoke en Málaga y toda Andalucía. Con más de 25 años de experiencia y un repertorio de 400+ temas.

## ✨ Características

- **🎨 Diseño Moderno**: Interfaz atractiva con animaciones CSS avanzadas
- **📱 Responsive**: Optimizado para todos los dispositivos
- **🚀 Performance**: Carga rápida y experiencia fluida
- **📝 Formulario de Contacto**: Sistema integrado de solicitud de presupuestos
- **💬 WhatsApp Integration**: Contacto directo instantáneo
- **🎥 Galería de Videos**: Videos de actuaciones en vivo
- **⭐ Testimonios**: Sistema de reseñas y testimonios
- **🔍 SEO Optimizado**: Meta tags y estructura optimizada para buscadores

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica moderna
- **CSS3**: 
  - Flexbox y CSS Grid
  - Animaciones y transiciones avanzadas
  - Responsive design
  - Backdrop filters y efectos glassmorphism
- **JavaScript ES6+**:
  - Intersection Observer API
  - Smooth scrolling
  - Animaciones dinámicas
- **Google Fonts**: Tipografía Poppins
- **YouTube API**: Integración de videos

## 🚀 Instalación y Uso

### Opción 1: Clonar el repositorio

```bash
git clone https://github.com/usuario/sandra-pastor-website.git
cd sandra-pastor-website
```

### Opción 2: Descargar ZIP

1. Descargar el archivo ZIP desde GitHub
2. Extraer en tu carpeta de proyectos
3. Abrir `index.html` en tu navegador

### Opción 3: Hosting en vivo

Puedes subir directamente los archivos a cualquier servicio de hosting:

- **GitHub Pages**: Hosting gratuito
- **Netlify**: Deploy automático desde GitHub
- **Vercel**: Hosting gratuito con dominio personalizado
- **cPanel/FTP**: Hosting tradicional

## 📁 Estructura del Proyecto

```
sandra-pastor-website/
├── index.html              # Archivo principal
├── images/                 # Carpeta de imágenes
│   ├── sandra_pastor_main.jpeg
│   ├── cantante_boda_ceremonia.jpg
│   ├── evento_corporativo_cantante.png
│   └── sandra_pastor_actuacion.jpeg
├── README.md              # Este archivo
├── .gitignore            # Archivos ignorados por Git
└── package.json          # Información del proyecto
```

## 🖼️ Imágenes Requeridas

Para que el sitio funcione completamente, necesitas las siguientes imágenes en la carpeta `images/`:

1. **sandra_pastor_main.jpeg** - Imagen principal del hero (1920x1080px recomendado)
2. **cantante_boda_ceremonia.jpg** - Imagen para servicios de boda
3. **evento_corporativo_cantante.png** - Imagen para eventos corporativos  
4. **sandra_pastor_actuacion.jpeg** - Imagen para karaoke profesional

### 📷 Especificaciones de Imágenes

- **Formato**: JPG, PNG, WebP
- **Tamaño máximo**: 800KB por imagen
- **Resolución recomendada**: 1200x800px para imágenes de servicios
- **Optimización**: Comprimir para web antes de subir

## 🎨 Personalización

### Cambiar Colores

En el archivo `index.html`, busca la sección de CSS y modifica las variables de color:

```css
/* Gradientes principales */
background: linear-gradient(-45deg, #667eea, #764ba2, #f093fb, #f5576c);

/* Colores de acento */
color: #4ecdc4; /* Verde azulado */
color: #ff6b6b; /* Rosa/Rojo */
```

### Modificar Contenido

1. **Información personal**: Editar las secciones de texto en el HTML
2. **Precios**: Actualizar en la sección de servicios
3. **Testimonios**: Añadir o modificar testimonios existentes
4. **Videos**: Cambiar los IDs de YouTube en los iframes

### Añadir Nuevas Secciones

El diseño utiliza una estructura modular. Para añadir una nueva sección:

```html
<section id="nueva-seccion" class="section">
    <div class="container">
        <h2>🎵 Nueva Sección</h2>
        <!-- Contenido aquí -->
    </div>
</section>
```

## 📞 Información de Contacto

- **Email**: info@sandrapastormusica.es
- **Teléfono**: 639 605 130
- **WhatsApp**: [Contacto directo](https://wa.me/34639605130)
- **Área de servicio**: Málaga y toda Andalucía

## 🔧 Mantenimiento

### Actualizar Contenido

1. **Testimonios**: Añadir nuevos testimonios periódicamente
2. **Videos**: Actualizar galería con nuevas actuaciones
3. **Precios**: Revisar y actualizar tarifas anualmente
4. **SEO**: Actualizar meta descriptions según temporada

### Optimizaciones Recomendadas

- **Imágenes**: Usar formato WebP para mejor compresión
- **Caché**: Implementar caché del navegador
- **CDN**: Usar CDN para recursos estáticos
- **Analytics**: Integrar Google Analytics para métricas

## 📈 SEO y Marketing

### Keywords Principales

- "cantante bodas málaga"
- "música eventos andalucía" 
- "cantante profesional costa del sol"
- "Sandra Pastor música"

### Estrategias de Contenido

1. **Blog**: Añadir sección de blog con consejos musicales
2. **Redes Sociales**: Integrar feeds de Instagram/Facebook
3. **Google My Business**: Optimizar perfil local
4. **Reseñas**: Incentivar reseñas en Google y redes sociales

## 🚀 Deployment

### GitHub Pages

1. Subir código a GitHub
2. Ir a Settings > Pages
3. Seleccionar source: Deploy from branch
4. Elegir branch: main
5. El sitio estará disponible en `https://usuario.github.io/sandra-pastor-website`

### Netlify

1. Conectar repositorio de GitHub
2. Configure build settings (no build required)
3. Deploy automático en cada push

### Hosting Tradicional

1. Subir archivos via FTP
2. Asegurar que `index.html` esté en la raíz
3. Configurar dominio personalizado

## 🐛 Solución de Problemas

### Imágenes no se muestran
- Verificar que las imágenes estén en la carpeta `images/`
- Comprobar que los nombres coincidan exactamente
- Verificar permisos de archivos en el servidor

### Formulario no funciona
- Verificar que el email esté configurado correctamente
- Considerar usar servicio como Formspree para formularios

### Videos no cargan
- Verificar que los IDs de YouTube sean correctos
- Comprobar configuración de privacidad de los videos

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crear una branch (`git checkout -b feature/nueva-caracteristica`)
3. Commit los cambios (`git commit -m 'Añadir nueva característica'`)
4. Push a la branch (`git push origin feature/nueva-caracteristica`)
5. Abrir un Pull Request

## 📞 Soporte

Para soporte técnico o consultas sobre el desarrollo web:

- **Issues**: Usar el sistema de issues de GitHub
- **Email**: [Contacto técnico]
- **Documentación**: Ver este README.md

---

**Desarrollado con ❤️ para Sandra Pastor**

*Transformando momentos especiales en recuerdos inolvidables a través de la música*