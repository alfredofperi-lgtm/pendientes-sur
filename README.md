# Pendientes FONACOT Sur — PWA

App personal de control de asuntos pendientes. Funciona sin internet y se instala en la pantalla de inicio del teléfono.

---

## Cómo publicar en GitHub Pages (paso a paso)

### 1. Crear el repositorio en GitHub

1. Ve a https://github.com/new
2. Nombre del repositorio: `pendientes-sur`
3. Selecciona **Public**
4. Clic en **Create repository**

### 2. Subir los archivos

Desde la página del repositorio recién creado:

1. Clic en **uploading an existing file** (o "subir archivo")
2. Arrastra o selecciona estos archivos/carpeta:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - La carpeta `icons/` con sus dos imágenes dentro
3. Escribe el mensaje: `Primera versión`
4. Clic en **Commit changes**

> ⚠️ La carpeta `icons` debe subirse con sus archivos adentro. Si GitHub no permite subir carpetas directamente, sube los archivos `icon-192.png` e `icon-512.png` y manualmente crea la ruta `icons/` al subirlos.

### 3. Activar GitHub Pages

1. En el repositorio ve a **Settings** (engrane)
2. En el menú izquierdo busca **Pages**
3. En "Branch" selecciona **main** y la carpeta **/ (root)**
4. Clic en **Save**
5. Espera 1-2 minutos

Tu app quedará disponible en:
```
https://alfredofperi-lgtm.github.io/pendientes-sur/
```

---

## Cómo instalarla en tu teléfono

### En iPhone (Safari)
1. Abre la URL en **Safari** (no Chrome)
2. Toca el botón de compartir (cuadro con flecha hacia arriba)
3. Selecciona **"Agregar a pantalla de inicio"**
4. Toca **Agregar**

### En Android (Chrome)
1. Abre la URL en Chrome
2. Aparecerá un banner automático "Instalar app"
3. Toca **Instalar**
4. Si no aparece el banner: toca los tres puntos (⋮) → "Agregar a pantalla de inicio"

---

## Funciones

- ✅ Registro de asuntos pendientes con prioridad (Urgente / Alta / Media / Baja)
- 📅 Fecha límite con conteo de días restantes
- ⚠️ Asuntos vencidos resaltados automáticamente
- 🔄 Traslado automático día a día (persisten hasta marcarlos como concluidos)
- 🔍 Búsqueda y filtros
- 📝 Campo de notas por asunto
- 💾 Datos guardados localmente en el teléfono (sin internet ni nube)
- 📲 Instalable como app nativa
