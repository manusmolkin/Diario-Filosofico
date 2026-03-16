# Diario Filosófico · Manu

App personal de aprendizaje filosófico. Registra reflexiones, preguntas pendientes y conexiones entre conceptos.

## Instalación en el teléfono (GitHub Pages)

### 1. Crear repositorio en GitHub

1. Andá a [github.com](https://github.com) y creá un repositorio nuevo
2. Ponele el nombre que quieras, por ejemplo: `diario-filosofico`
3. Marcalo como **público** (necesario para GitHub Pages gratis)

### 2. Subir los archivos

Subí estos 4 archivos al repositorio:
- `index.html`
- `manifest.json`
- `icon-192.svg`
- `icon-512.svg` (podés usar el mismo que icon-192.svg)

Podés hacerlo directo desde el navegador en GitHub → "Add file" → "Upload files"

### 3. Activar GitHub Pages

1. En tu repositorio, andá a **Settings** → **Pages**
2. En "Source" elegí **Deploy from a branch**
3. Elegí la rama `main` y la carpeta `/ (root)`
4. Guardá

En 1-2 minutos tu app va a estar disponible en:
`https://TU_USUARIO.github.io/diario-filosofico/`

### 4. Agregar al homescreen del teléfono

**En iPhone (Safari):**
1. Abrí la URL en Safari
2. Tocá el botón de compartir (cuadrado con flecha)
3. "Agregar a pantalla de inicio"
4. Listo — aparece como app nativa con el logo

**En Android (Chrome):**
1. Abrí la URL en Chrome
2. Tocá los tres puntos del menú
3. "Agregar a pantalla de inicio" o "Instalar app"

## Estructura

```
diario-filosofico/
├── index.html      ← La app completa
├── manifest.json   ← Configuración PWA
├── icon-192.svg    ← Ícono del homescreen
└── icon-512.svg    ← Ícono splash screen
```

## Datos

Los datos (reflexiones, preguntas, conexiones) se guardan en el **localStorage del navegador** del teléfono. Son privados y locales — no se sincronizan entre dispositivos.

---

*Construido para aprendizaje profundo de filosofía e historia.*
