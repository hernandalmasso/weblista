# WebLista

Landing page de **WebLista** — proyecto para vender páginas web profesionales, rápidas y a bajo costo.

Mercados objetivo: Argentina, España, Uruguay, Paraguay y Chile.

## Qué es

Una landing de una sola página (single-page), estática y autocontenida. Pensada para recibir tráfico frío desde anuncios y convertirlo en contacto por **mail** o **Instagram DM**.

## Características

- Diseño claro y minimalista con estética tech (paleta índigo/violeta + vidrio esmerilado).
- Animaciones: entrada del hero, gradiente animado, reveals al hacer scroll, franja de marcas en loop, navbar dinámica.
- Íconos SVG incrustados (sin librerías externas).
- Accesible: foco visible, skip link, `aria-*`, soporte de `prefers-reduced-motion`, contraste AA.
- Responsive (mobile-first).

## Tecnología

- HTML + [Tailwind CSS](https://tailwindcss.com/) vía CDN.
- Tipografía Inter (Google Fonts).
- JavaScript vanilla (sin build, sin dependencias que instalar).

## Cómo verlo

Abrí `index.html` en el navegador. No requiere servidor ni compilación.

Opcional, con un server local:

```bash
python3 -m http.server 8000
# luego abrí http://localhost:8000
```

## Deploy rápido (GitHub Pages)

1. Subí el repo a GitHub (ver más abajo).
2. En el repo: **Settings → Pages → Branch: `main` / `root` → Save**.
3. En un par de minutos queda online en `https://TU_USUARIO.github.io/weblista/`.

## Pendientes antes de publicar

- [ ] Reemplazar el mail `hola@weblista.com` por el real.
- [ ] Reemplazar el Instagram `@weblista` por el real.
- [ ] Reemplazar las marcas de fantasía (CasaViva, Café Delta, etc.) por logos de clientes reales.
- [ ] Conectar el formulario/botón de WhatsApp a un número o servicio real.
- [ ] Revisar textos para España/Chile si hiciera falta (hoy están en español neutro).

## Estructura

```
weblista/
├── index.html      # la landing completa (HTML + CSS + JS en un solo archivo)
├── README.md
├── LICENSE
└── .gitignore
```
