# 🥩 Menú Mensual Argentino

Sitio estático para planificar el menú mensual con recetas caseras argentinas y sugerencias por IA (Gemini).

## 🚀 Deploy en GitHub Pages

```bash
git init
git add .
git commit -m "primer commit"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/menu-argentino.git
git push -u origin main
```

Luego en GitHub → **Settings → Pages → Source: main / root → Save**

URL: `https://TU_USUARIO.github.io/menu-argentino`

## 🤖 Configurar Gemini (gratis)

1. Ir a [aistudio.google.com](https://aistudio.google.com)
2. Crear API Key gratuita
3. Abrir `index.html` y reemplazar `TU_API_KEY_AQUI` con tu clave
4. Guardar y hacer push

## 📁 Estructura

```
menu-argentino/
├── index.html          ← toda la app
├── assets/
│   ├── icons.svg       ← íconos de categorías
│   └── hero-pattern.svg
└── README.md
```

## ✨ Funcionalidades

- 📅 Calendario mensual con menú día a día
- 🔍 Filtros por categoría (pollo, carne, pescado, pasta, verdura, huevo)
- 📖 Popup con paso a paso al hacer clic en una receta
- 🤖 Buscador por ingredientes con IA (Gemini 1.5 Flash)
- 🛒 Lista de compras generada por IA
- ⭐ Guardar recetas favoritas (localStorage)
- 📱 Responsive — funciona en celular

## 🆓 Límites gratuitos Gemini

- 1500 requests/día con Gemini 1.5 Flash
- Sin tarjeta de crédito requerida
- Suficiente para uso personal diario
