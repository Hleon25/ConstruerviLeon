# Construservi León – Landing Page

Sitio web de presentación de Construservi León: servicios, trabajos
realizados y datos de contacto.

## Tecnologías
- [Astro](https://astro.build)
- [Tailwind CSS](https://tailwindcss.com)
- Íconos: Lucide / astro-icon

## Requisitos
- Node.js 22.23.4 o superior

## Instalación y uso
```sh
npm install      # instala dependencias
npm run dev      # servidor local en http://localhost:4321
npm run build    # genera el sitio en /dist
npm run preview  # previsualiza el build


# Estructura 
src/
├── assets/      # imágenes
├── layouts/     # Layout.astro (estructura base)
├── pages/       # index.astro (página principal)
└── styles/      # global.css
public/          # favicon y archivos estáticos


# Despliegue 
