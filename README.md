# Grupo Squadra — Website

## Estructura de archivos

```
gruposquadra_website/
├── index.html              ← Página principal
└── assets/
    ├── css/
    │   └── styles.css      ← Estilos globales
    ├── js/
    │   └── main.js         ← Scripts (scroll, reveal, cursor)
    └── img/
        ├── img_00.png      ← Logo completo (S + SQUADRA)
        ├── img_01.png      ← Ícono S (nav y diagrama)
        └── img_02.png      ← Ícono S (diagrama SVG)
```

## Cómo hostear

### Opción 1 — Netlify (recomendado, gratis)
1. Ve a https://netlify.com y crea una cuenta
2. En el dashboard arrastra la carpeta `gruposquadra_website/` completa
3. En segundos obtienes un link público

### Opción 2 — Vercel (gratis)
1. Ve a https://vercel.com
2. Import project → sube la carpeta
3. Link instantáneo

### Opción 3 — GitHub Pages (gratis)
1. Crea un repositorio en GitHub
2. Sube todos los archivos manteniendo la estructura
3. Settings → Pages → activa GitHub Pages

## Notas técnicas
- Las fuentes se cargan desde Google Fonts (requiere internet)
- Todas las imágenes están en assets/img/
- El sitio es responsive (mobile + desktop)
