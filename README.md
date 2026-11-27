# Calendario de Adviento

Regalo de 9 meses: 28 cajas, una por día, del 27 de noviembre al 24 de diciembre de 2026. Cada caja se abre sola cuando llega su fecha.

## Publicar en Cloudflare Pages

1. En el panel de Cloudflare: Workers & Pages → Create → Pages → Connect to Git.
2. Elige este repositorio y la rama `main`.
3. Framework preset: `None`. Build command: déjalo vacío. Build output directory: `/`.
4. Guarda y despliega. Cloudflare te da una dirección `https://nombre.pages.dev` para mandarle.

Cada `git push` a `main` vuelve a publicar solo.

## Probar antes de tiempo

Agrega `?todos=1` a la dirección para ver todas las cajas abiertas. Para el regalo real, usa la dirección sin eso.

## Personalizar

Los mensajes están en la lista `MSGS` dentro de `index.html`. Cada entrada es `[título, mensaje]`.
