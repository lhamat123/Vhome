# 🏠 LHAMAT Vhome — Portal de venta de inmuebles

Portal web para publicar casas, apartamentos, fincas y locales. Diseño oscuro/claro con 4 temas, datos almacenados en este repositorio como `data.json`.

## Archivos

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Aplicación completa (HTML + CSS + JS en un solo archivo) |
| `data.json` | Base de datos de propiedades (se actualiza desde la app) |

## Configuración rápida

Editar estas 3 líneas al inicio del `<script>` en `index.html`:

```js
const GH_USER  = 'lhamat123';   // ✅ ya configurado
const GH_REPO  = 'Vhome';       // ✅ ya configurado
const APP_PASS = 'admin1234';   // ← CAMBIA esta contraseña
```

## Cómo publicar en GitHub Pages

1. Ve a **Settings → Pages** en este repositorio
2. En *Source* selecciona **Deploy from a branch**
3. Rama: `main`, carpeta: `/ (root)`
4. Guarda — en 1-2 minutos tendrás la web en:
   `https://lhamat123.github.io/Vhome`

## Cómo agregar propiedades

1. Abre la web publicada
2. Haz clic en 🔐 (icono de candado)
3. Ingresa la contraseña y un **GitHub Token** con permiso `repo`
   - Genera el token en: GitHub → Settings → Developer settings → Personal access tokens → Fine-grained tokens
4. Haz clic en **＋ Nueva** y completa el formulario

## Tipos de inmueble soportados

- 🏡 **Casa**
- 🏢 **Apartamento**
- 🌾 **Finca**
- 🏪 **Local**

## Comodidades disponibles

🚗 Garaje · 🌿 Jardín · ☀️ Terraza · 🏊 Piscina · 🔥 Barbacoa · 💧 Cisterna · ⚡ Placa Solar · 📶 WiFi/Cable
