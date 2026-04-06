# MisBancos — PWA de gastos personales

App para registrar y controlar gastos personales. Funciona offline e instala como app nativa en el móvil.

---

## 📁 Archivos del proyecto

```
misbancos/
├── index.html      ← La app principal
├── manifest.json   ← Configuración PWA
├── sw.js           ← Service worker (modo offline)
├── icon-192.png    ← Icono app
└── icon-512.png    ← Icono app (grande)
```

---

## 🚀 Cómo subir a GitHub Pages (paso a paso)

### Paso 1 — Crear cuenta en GitHub
Ve a [github.com](https://github.com) y crea una cuenta gratuita si no tienes.

### Paso 2 — Crear un repositorio nuevo
1. Pulsa el botón verde **"New"** o el **"+"** arriba a la derecha
2. Ponle un nombre, por ejemplo: `misbancos`
3. Selecciona **Public** (necesario para GitHub Pages gratis)
4. Pulsa **"Create repository"**

### Paso 3 — Subir los archivos
En la página del repositorio vacío:
1. Pulsa **"uploading an existing file"**
2. Arrastra los 5 archivos (`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`)
3. Abajo escribe un mensaje como `Primera versión` y pulsa **"Commit changes"**

### Paso 4 — Activar GitHub Pages
1. Ve a **Settings** (pestaña superior del repositorio)
2. En el menú izquierdo busca **Pages**
3. En "Branch" selecciona **main** y carpeta **/ (root)**
4. Pulsa **Save**
5. Espera 1-2 minutos

### Paso 5 — Tu URL
GitHub te dará una URL como:
```
https://TU_USUARIO.github.io/misbancos/
```
¡Esa es tu app! Ábrela desde el móvil.

---

## 📱 Instalar en el móvil

### En iPhone (Safari):
1. Abre la URL en **Safari** (importante, no Chrome)
2. Pulsa el botón de compartir **⬆**
3. Selecciona **"Añadir a pantalla de inicio"**
4. Pulsa **Añadir**

### En Android (Chrome):
1. Abre la URL en **Chrome**
2. Chrome mostrará un banner automático **"Instalar app"**
3. O pulsa los **⋮ tres puntos** → **"Añadir a pantalla de inicio"**

---

## 💾 ¿Dónde se guardan los datos?

Los datos se guardan en el **localStorage** del navegador del teléfono.
Al instalar como PWA el localStorage es persistente y no se borra con el caché normal.

Usa el botón **⬇ XLSX** dentro de la app para exportar una copia de seguridad.

---

## 🔄 Actualizar la app

Si modificas los archivos y los vuelves a subir a GitHub, la app se actualiza automáticamente la próxima vez que la abras con conexión.
