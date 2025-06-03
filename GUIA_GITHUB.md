# 🚀 Guía Rápida para GitHub

## 📦 ¿Qué incluye este proyecto?

✅ **index.html** - Sitio web completo con todas las mejoras implementadas  
✅ **README.md** - Documentación completa del proyecto  
✅ **package.json** - Configuración del proyecto  
✅ **.gitignore** - Archivos ignorados por Git  
✅ **LICENSE** - Licencia MIT  
✅ **images/** - Carpeta para imágenes (con instrucciones)

## 🎯 Paso a Paso para Subir a GitHub

### 1. **Crear Repositorio en GitHub**
```bash
# Ve a https://github.com/new
# Nombre: sandra-pastor-website
# Descripción: Sitio web profesional de Sandra Pastor - Cantante para bodas y eventos
# Público o Privado (según prefieras)
# ✅ Add README file (ya tienes uno)
# Crear repositorio
```

### 2. **Subir archivos**

**Opción A: Interfaz Web (Más Fácil)**
1. Descarga y extrae el ZIP
2. En GitHub, click "uploading an existing file"
3. Arrastra todos los archivos del proyecto
4. Commit message: "Initial commit - Sitio web completo"
5. Click "Commit changes"

**Opción B: Git en Terminal**
```bash
# Extrae el ZIP en tu computadora
cd sandra-pastor-website

# Inicializar Git
git init
git add .
git commit -m "Initial commit - Sitio web completo"

# Conectar con GitHub (reemplaza 'tu-usuario')
git remote add origin https://github.com/tu-usuario/sandra-pastor-website.git
git branch -M main
git push -u origin main
```

### 3. **Activar GitHub Pages**
1. Ve a tu repositorio en GitHub
2. Click **Settings** (pestaña superior)
3. Scroll hasta **Pages** (menú izquierdo)
4. En **Source** selecciona: "Deploy from a branch"
5. Branch: **main**
6. Folder: **/ (root)**
7. Click **Save**
8. ¡Tu sitio estará en: `https://tu-usuario.github.io/sandra-pastor-website`

### 4. **Añadir las Imágenes**
```bash
# Ve a la carpeta images/ y sigue las instrucciones en INSTRUCCIONES_IMAGENES.md
# Opción 1: Subir via GitHub web interface
# Opción 2: Usar Git para añadir las imágenes

git add images/
git commit -m "Añadir imágenes del sitio web"
git push
```

## 🎨 Personalización Inmediata

### Cambios Rápidos en `index.html`:

**1. Actualizar Información Personal**
```html
<!-- Buscar y cambiar -->
<title>Sandra Pastor - Tu Nombre</title>
<h1>Tu Nombre</h1>
<p>info@tuemail.com</p>
<p>tu-telefono</p>
```

**2. Actualizar Enlaces de Contacto**
```html
<!-- WhatsApp -->
href="https://wa.me/34TU-TELEFONO?text=..."

<!-- Email -->
href="mailto:tu@email.com"

<!-- YouTube -->
href="https://www.youtube.com/@TU-CANAL"
```

**3. Cambiar Videos de YouTube**
```html
<!-- Reemplazar IDs de video -->
<iframe src="https://www.youtube.com/embed/TU-VIDEO-ID"></iframe>
```

## 🔧 Desarrollo Continuo

### Instalar Herramientas de Desarrollo (Opcional)
```bash
# Si quieres servidor local
npm install -g live-server

# Ejecutar servidor local
live-server --port=3000

# Tu sitio estará en: http://localhost:3000
```

### Comandos Útiles
```bash
# Ver el sitio localmente
npm start

# Validar HTML
npm run validate

# Optimizar imágenes
npm run optimize

# Deploy a GitHub Pages
npm run deploy
```

## 📱 Dominios Personalizados

### Opción 1: GitHub Pages con dominio personalizado
1. En Settings > Pages
2. Custom domain: `www.tusitio.com`
3. Configurar DNS en tu proveedor de dominio

### Opción 2: Hosting tradicional
1. Descargar archivos del repositorio
2. Subir via FTP a tu hosting
3. Configurar dominio

## 🚀 Características Incluidas

✅ **Formulario de contacto** funcional  
✅ **Botón WhatsApp** con mensaje predefinido  
✅ **Diseño responsive** para móviles  
✅ **Animaciones CSS** profesionales  
✅ **SEO optimizado** con meta tags  
✅ **Sección FAQ** informativa  
✅ **Galería de videos** de YouTube  
✅ **Testimonios** con estrellas animadas  
✅ **Navegación suave** entre secciones  
✅ **Barra de progreso** de scroll  

## 📈 Próximos Pasos

### Mejoras Futuras:
1. **Analytics**: Añadir Google Analytics
2. **Blog**: Crear sección de blog
3. **Galería**: Ampliar galería de fotos
4. **Reservas**: Sistema de reservas online
5. **Multi-idioma**: Versión en inglés

### Marketing:
1. **SEO Local**: Google My Business
2. **Redes Sociales**: Instagram, Facebook
3. **Reviews**: Solicitar reseñas de clientes
4. **Content**: Blog con consejos musicales

## 💡 Consejos Pro

- **Backup regular**: Siempre mantén copias de seguridad
- **Updates frecuentes**: Actualiza testimonios y videos
- **Mobile first**: Prueba siempre en móvil
- **Performance**: Optimiza imágenes regularmente
- **SEO**: Actualiza contenido estacionalmente

## 🆘 Soporte

**¿Problemas con GitHub?**
- [Documentación oficial](https://docs.github.com/en/pages)
- [Comunidad GitHub](https://github.community/)

**¿Problemas técnicos del sitio?**
- Revisar consola del navegador (F12)
- Validar HTML en W3C Validator
- Usar Lighthouse para performance

---

## 🎉 ¡Felicidades!

Tu sitio web profesional está listo para GitHub. Con estos archivos tienes:

- ✅ Código fuente completo y optimizado
- ✅ Documentación profesional
- ✅ Configuración lista para deploy
- ✅ Estructura preparada para crecimiento

**¡Ahora puedes desarrollar y mantener tu sitio web como un profesional!**