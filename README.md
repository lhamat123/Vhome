# VHome — Catálogo Inmobiliario

Sitio web estático y elegante para publicar propiedades en GitHub Pages. Sin backend, sin costos.

## 🚀 Publicar en GitHub Pages

1. Sube todos los archivos al repositorio `lhamat123/Vhome`
2. Ve a **Settings → Pages → Deploy from branch → main → / (root)**
3. Tu sitio quedará en: **`https://lhamat123.github.io/Vhome/`**

---

## 📁 Estructura

```
Vhome/
├── index.html                 ← Sitio completo (todo en uno)
├── data/
│   └── propiedades.json       ← ⭐ EDITA AQUÍ las propiedades
└── img/
    ├── casa1-principal.jpg    ← Fotos (súbelas aquí)
    └── ...
```

---

## ✏️ Agregar una propiedad

Edita `data/propiedades.json` y agrega un objeto al array:

```json
{
  "id": 2,
  "tipo": "Apartamento",
  "nombre": "Apartamento en Miramar",
  "precio": 25000,
  "moneda": "USD",
  "negociable": true,
  "direccion": "Calle 5ta No. 302 e/ 2 y 4, Miramar, La Habana",
  "mapsUrl": "https://www.google.com/maps/search/?api=1&query=Miramar+La+Habana",
  "contacto": {
    "nombre": "Nombre Vendedor",
    "telefono": "+5355551234",
    "whatsapp": true
  },
  "superficies": {
    "util": 80,
    "construida": 90,
    "total": 90
  },
  "descripcion": "Descripción completa de la propiedad...",
  "amenidades": ["2 Dormitorios", "1 Servicio Sanitario", "Cocina equipada"],
  "fotoPrincipal": "img/apto2-principal.jpg",
  "galeria": ["img/apto2-foto1.jpg", "img/apto2-foto2.jpg"]
}
```

**Tipos válidos:** `"Casa"` · `"Apartamento"` · `"Local"` · `"Finca"`

---

## 🖼️ Fotos

- Crea la carpeta `img/` y sube las imágenes
- Referencia en el JSON: `"img/nombre.jpg"`
- Recomendado: JPG, 1200×800px para principal · 800×600px para galería

---

## 🔄 Actualizar

```bash
git add .
git commit -m "Nueva propiedad: Apartamento Miramar"
git push
```
GitHub Pages se actualiza en ~1 minuto.
