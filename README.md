# Lattice Works · Seguimiento de producción

Página pública de rastreo de pedidos (`index.html`). Los clientes la abren con el
link que genera CorteClaro (`?t=<token>`); muestra solo el avance — sin precios.

- `rastreo-config.js` — URL del proyecto Supabase + anon key (se genera desde
  CorteClaro → Ajustes → ERP · Supabase → "⬇ Config de rastreo"). El anon key es
  público por diseño; los datos los protege RLS + una función validada por token.
- Hosting: GitHub Pages (Settings → Pages → Deploy from branch → main, / root).
