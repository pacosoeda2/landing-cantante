# 📷 Instrucciones para Imágenes

Para que el sitio web funcione completamente, necesitas subir las siguientes imágenes a esta carpeta `/images/`:

## 🖼️ Imágenes Requeridas

### 1. **sandra_pastor_main.jpeg**
- **Uso**: Imagen principal de fondo del header
- **Tamaño recomendado**: 1920x1080px (Full HD)
- **Descripción**: Foto profesional de Sandra cantando, preferiblemente en un evento o estudio
- **Formato**: JPEG optimizado para web
- **Peso máximo**: 500KB

### 2. **cantante_boda_ceremonia.jpg**
- **Uso**: Tarjeta de servicios - Bodas
- **Tamaño recomendado**: 800x600px
- **Descripción**: Sandra cantando en una ceremonia de boda o con vestido elegante
- **Formato**: JPEG optimizado para web
- **Peso máximo**: 300KB

### 3. **evento_corporativo_cantante.png**
- **Uso**: Tarjeta de servicios - Eventos Corporativos
- **Tamaño recomendado**: 800x600px
- **Descripción**: Sandra en un evento corporativo, hotel, o ambiente profesional
- **Formato**: PNG o JPEG optimizado para web
- **Peso máximo**: 300KB

### 4. **sandra_pastor_actuacion.jpeg**
- **Uso**: Tarjeta de servicios - Karaoke Profesional
- **Tamaño recomendado**: 800x600px
- **Descripción**: Sandra cantando con micrófono, preferiblemente en ambiente festivo
- **Formato**: JPEG optimizado para web
- **Peso máximo**: 300KB

## 🔧 Cómo Obtener las Imágenes Originales

### Opción 1: Descargar desde el sitio actual
```bash
# Si tienes acceso al servidor original, puedes usar wget o curl:
wget http://sandrapastor.myartsonline.com/images/sandra_pastor_main.jpeg
wget http://sandrapastor.myartsonline.com/images/cantante_boda_ceremonia.jpg
wget http://sandrapastor.myartsonline.com/images/evento_corporativo_cantante.png
wget http://sandrapastor.myartsonline.com/images/sandra_pastor_actuacion.jpeg
```

### Opción 2: Desde el panel de control del hosting
1. Acceder al File Manager de myartsonline.com
2. Navegar a la carpeta `/images/`
3. Descargar cada imagen individualmente
4. Subirlas a esta carpeta del proyecto

### Opción 3: Contactar con el proveedor del hosting
- Solicitar backup completo del sitio web
- Extraer las imágenes de la carpeta `/images/`

## 🖼️ Alternativas si no tienes las imágenes originales

### Crear nuevas imágenes profesionales:
1. **Sesión fotográfica profesional** con las siguientes características:
   - Fondo neutral o de eventos reales
   - Buena iluminación
   - Sandra con micrófono o guitarra
   - Expresión profesional y amigable

2. **Especificaciones técnicas**:
   - **Resolución**: Mínimo 1200x800px
   - **Formato**: JPEG con calidad 85-90%
   - **Optimización**: Comprimir para web antes de subir
   - **Aspecto**: Rectangular horizontal (4:3 o 16:9)

## 🎨 Consejos de Fotografía

### Para la imagen principal (hero):
- **Fondo**: Escenario, evento real, o estudio profesional
- **Pose**: Sandra cantando o con guitarra
- **Expresión**: Profesional, confiada, sonriente
- **Vestimenta**: Elegante, acorde al público objetivo

### Para imágenes de servicios:
- **Bodas**: Vestido elegante, ambiente romántico
- **Corporativo**: Outfit profesional, ambiente de hotel/empresa  
- **Karaoke**: Ambiente festivo, micrófono visible

## 🔧 Optimización de Imágenes

### Herramientas recomendadas:
- **Online**: TinyPNG, Squoosh.app, ImageOptim
- **Software**: Photoshop, GIMP, Canva
- **Comando**: `imagemin` (si tienes Node.js instalado)

### Comando para optimizar automáticamente:
```bash
npm install -g imagemin-cli imagemin-mozjpeg imagemin-pngquant
imagemin images/*.{jpg,png} --out-dir=images/optimized --plugin=mozjpeg --plugin=pngquant
```

## ⚠️ Importante

- **Sin imágenes**: El sitio funcionará pero mostrará errores 404 en las imágenes
- **Nombres exactos**: Los nombres de archivo DEBEN coincidir exactamente
- **Formatos**: Respetar los formatos indicados (JPEG/PNG)
- **Peso**: Mantener archivos ligeros para buena velocidad de carga

## 📞 ¿Necesitas ayuda?

Si tienes dificultades para obtener las imágenes:
1. Contacta con el proveedor de hosting actual
2. Busca en tus archivos locales o backups
3. Programa una sesión fotográfica profesional
4. Usa herramientas de captura de pantalla como último recurso

**Una vez que tengas las imágenes, simplemente súbelas a esta carpeta y el sitio funcionará perfectamente.**