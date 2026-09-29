# portafolio

# Portfolio personal con Astro + Tailwind

Este proyecto es un portfolio personal hecho con Astro y Tailwind, pensado para presentarse como desarrollador en una búsqueda laboral real.

## Stack elegido

- Astro
- Tailwind CSS
- HTML semántico y diseño responsive

## Requisitos cubiertos

- Hero con nombre, rol, presentación y CTA
- Sección Sobre mí con habilidades por categoría
- 3 proyectos con descripción, stack, repositorio y demo
- Sección de contacto con email, GitHub, LinkedIn y formulario con validación básica
- Navbar con navegación por sección
- Responsive para mobile, tablet y desktop
- Accesibilidad básica y estructura semántica
- Modo oscuro y claro

## Cómo correrlo localmente

1. Cloná el repositorio.
2. Abrí la terminal en la raíz del proyecto.
3. Instalá las dependencias:

```bash
npm install
```

4. Iniciá el servidor de desarrollo:

```bash
npm run dev
```

5. Abrí la URL que indique Astro, normalmente:

```bash
http://localhost:4321
```

## Scripts disponibles

```bash
npm run dev
npm run build
npm run preview
```

## Deploy en Vercel

1. Subí el proyecto a GitHub como repositorio público.
2. Entrá a https://vercel.com y hacé login.
3. Clickeá en “Add New Project”.
4. Seleccioná tu repositorio.
5. Mantené la configuración por defecto.
6. Hacé click en “Deploy”.
7. Cuando termine, Vercel te dará la URL pública del sitio.

## Entrega para la materia

Necesitás subir al aula virtual:

- Link del repositorio público de GitHub
- Link del sitio deployado en Vercel/Netlify/etc.

## Importante

Si querés reemplazar el avatar actual por la foto real que mandaste, guardala en la carpeta `public` como `avatar.jpg` o `avatar.png` y cambiá la línea del HTML:

```astro
<img src="/avatar.svg" alt="Retrato de Luca Borghi" ... />
```

por:

```astro
<img src="/avatar.jpg" alt="Retrato de Luca Borghi" ... />
```
