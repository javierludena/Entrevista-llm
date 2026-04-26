# Entrevistas LLM

> Recopilación abierta de 22 preguntas y respuestas cortas para repasar entrevistas técnicas sobre IA Generativa, en español.

Landing técnica que acompaña al artículo de LinkedIn. Hecha solo con HTML, CSS y un poco de JavaScript vanilla — sin frameworks ni dependencias — pensada para desplegarse en GitHub Pages.

Autor: [@javierludena](https://github.com/javierludena)

## Contenido

5 bloques · 22 preguntas:

| #   | Bloque                | Preguntas |
| --- | --------------------- | --------- |
| 01  | Fundamentos           | 5         |
| 02  | Fine-tuning           | 5         |
| 03  | Generación            | 4         |
| 04  | Conceptos avanzados   | 4         |
| 05  | Matemáticas           | 4         |

## Estructura

```
.
├── index.html               # Landing autocontenida (CSS + JS inline)
├── assets/javierludena.png  # Avatar
├── .nojekyll                # Para que GitHub Pages no procese con Jekyll
├── .github/workflows/       # Despliegue automático en GitHub Pages
└── README.md
```

## Funcionalidades

- 🔎 **Búsqueda** en preguntas y respuestas (`⌘K` / `Ctrl+K` para enfocar).
- 🏷️ **Filtros por categoría** con chips.
- 📍 **Sidebar sticky** con sección activa según scroll.
- 📊 Indicador de progreso de lectura.
- 📱 Responsive · móvil y escritorio.
- ♿ Soporte de `prefers-reduced-motion` y enlace de "saltar al contenido".

## Uso local

Abre `index.html` directamente, o sirve la carpeta:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Despliegue en GitHub Pages

Hay dos formas — elige una:

### Opción A · Automática con GitHub Actions (recomendada)

Ya está configurada en `.github/workflows/deploy.yml`. Solo tienes que:

1. Sube el repo a GitHub.
2. **Settings → Pages → Source:** *GitHub Actions*.
3. Cada `push` a `main` desplegará automáticamente.

URL final: `https://javierludena.github.io/<repo>/`.

### Opción B · Deploy from a branch

1. Sube el repo a GitHub.
2. **Settings → Pages → Source:** *Deploy from a branch*.
3. **Branch:** `main`, **Folder:** `/ (root)`.

El archivo `.nojekyll` evita que GitHub intente procesar el repo con Jekyll.

## Artículo en LinkedIn

Acompaña a este repo un artículo en LinkedIn con explicaciones más extendidas:
👉 [Próximamente — añade aquí el enlace al artículo]

## Contribuir

¿Mejor explicación, errata o pregunta nueva? Abre un *issue* o un *pull request*.

## Licencia

MIT · [Javier Ludeña](https://github.com/javierludena)
