# Nawar Plus — Preview standalone

Landing de preview para el plan **Nawar Plus** de [HolandésNawar](https://www.holandesnawar.com).

Este repo es una **versión standalone** de la página `/nawar-plus` para revisar el diseño y el copy de forma aislada antes de mergear al proyecto principal `nawar-web`. Todas las rutas externas (acceso, lista de espera, blog, etc.) apuntan al dominio principal.

## Stack

- Astro 5 (output static)
- React 19 (navbar interactivo)
- Tailwind CSS 4

## Scripts

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # output en dist/
npm run preview  # sirve dist/ localmente
```

## Deploy en Vercel

Conectar el repo a Vercel. No requiere variables de entorno. Framework: Astro. Output: static (carpeta `dist`).
