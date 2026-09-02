# ADR — tu-bolsillo-app-web

## Contexto
No es la app en sí — es la **landing page de marketing/distribución** de "Tu Bolsillo App" (la misma app de finanzas personales que `tu-bolsillo-app` y `Jorge1282.github.io`). Sitio estático simple:
- `index.html` — landing (título: "Tu Bolsillo App — Tus finanzas, tus reglas"; describe: control en Bs./USD con tasa BCV real, presupuestos, metas, Coach Financiero, datos locales no en servidor).
- `privacidad.html` — política de privacidad.
- `Guia-Tu-Bolsillo-App.pdf` — guía de usuario descargable.
- `Tu_Bolsillo_App.apk` — instalador Android distribuido directo (fuera de Play Store).

## Implicación práctica
- Cambios de copy/branding acá deben mantenerse consistentes con las apps reales (`tu-bolsillo-app`, `Jorge1282.github.io`).
- Si cambian features del producto (nuevas del Coach, presupuesto, etc.), este landing puede necesitar actualización de copy.
- Repo muy pequeño, sin lógica de negocio — el grafo no aporta casi nada acá, es solo contenido estático.
