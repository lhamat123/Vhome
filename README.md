# 🏠 CasasYa — Portal Inmobiliario

> Plataforma inmobiliaria de una sola página (SPA) para publicar y gestionar propiedades en venta. Sin servidor, sin base de datos — todo funciona en el navegador.

🌐 **Demo en vivo:** [Ver CasasYa](https://lhamat123.github.io/Vhome/)

---

## ✨ Características

- **Catálogo público** con búsqueda y filtros (precio, tipo, habitaciones, estado legal)
- **Vista detalle** de cada propiedad con galería, QR code y formulario de contacto
- **Panel de administración** protegido con contraseña
- **Redes sociales** configurables (WhatsApp, Telegram, Instagram, Facebook, Email)
- **Exportar / Importar** backup en JSON
- **Contador de visitas** por página y por propiedad
- **100% sin servidor** — datos guardados en `localStorage`
- **Responsive** — funciona en móvil y escritorio

---

## 🚀 Despliegue en GitHub Pages

1. Sube este repositorio a GitHub
2. Ve a **Settings → Pages**
3. En *Source* selecciona **`main` branch / `/ (root)`**
4. Pulsa **Save** — en 1-2 minutos tu sitio estará en línea en:
   ```
   https://<tu-usuario>.github.io/<nombre-del-repo>/
   ```

---

## 🔐 Acceso al panel de administración

| Campo | Valor por defecto |
|-------|-------------------|
| Usuario | `admin` |
| Contraseña | `admin123` |

> ⚠️ **Cambia la contraseña** antes de publicar. Edita la línea `const PASS='admin123';` en `index.html`.

---

## 📋 Gestión de propiedades

Desde el panel de Admin puedes:
- **Añadir / Editar / Eliminar** propiedades
- Subir URLs de imágenes (Unsplash, Imgur, Cloudinary, etc.)
- Configurar los enlaces de redes sociales
- Exportar un backup `.json` y volver a importarlo en otro dispositivo

---

## 🗂 Estructura del repositorio

```
Vhome/
├── index.html        ← Aplicación completa (HTML + CSS + JS)
├── README.md         ← Este archivo
└── .nojekyll         ← Evita que GitHub procese el HTML con Jekyll
```

---

## 🛠 Tecnologías

- HTML5 · CSS3 · JavaScript vanilla
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) — generación de códigos QR
- `localStorage` — persistencia de datos en el navegador

---

## 📸 Imágenes de propiedades

Las imágenes se añaden por URL. Puedes usar:
- [Unsplash](https://unsplash.com) — fotos gratuitas de alta calidad
- [Cloudinary](https://cloudinary.com) — hosting de imágenes gratuito
- [ImgBB](https://imgbb.com) — subida directa y enlace permanente

---

## 📄 Licencia

MIT — libre para uso personal y comercial.
