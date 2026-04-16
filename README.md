# 🌐 HAUSTALENT

Nueva web corporativa de **HAUSTALENT**, desarrollada con [Astro](https://astro.build/) y desplegada en Netlify.

HAUSTALENT es una empresa especializada en la construcción y rehabilitación de edificios singulares e instalaciones deportivas.

## 🛠 Stack

- [Astro](https://astro.build/)
- [Tailwind CSS v4](https://tailwindcss.com/)
- HTML semántico
- Despliegue en [Netlify](https://www.netlify.com/)

## 📌 Proyecto

Este repositorio contiene el desarrollo de la nueva web de HAUSTALENT, planteada como una **one-page corporativa** con una línea visual más sobria, premium y arquitectónica que la web anterior.

La web está construida con una estructura ligera basada en componentes Astro y contenido centralizado.

## 📎 Estructura

```text
.
├── public/
│   ├── apple-touch-icon.png
│   ├── favicon.ico
│   └── images/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   ├── pages/
│   └── styles/
├── astro.config.mjs
├── package.json
└── README.md
```

## Desarrollo local

Clona el repositorio:

```bash
git clone https://github.com/4gr3z0l4/haustalent.git
cd haustalent
```

Instala dependencias:

```bash
npm install
```

Inicia el entorno de desarrollo:

```bash
npm run dev
```

La web quedará disponible normalmente en:

```text
http://localhost:4321
```

## Scripts

```bash
npm run dev
npm run build
npm run preview
```

## Build de producción

Para generar la versión final:

```bash
npm run build
```

Astro generará los archivos estáticos listos para despliegue en la carpeta `dist/`.

## Despliegue

El proyecto está pensado para desplegarse en **Netlify**.

Dominio canónico previsto:

```text
https://haustalent.com
```

La intención es usar `haustalent.com` como dominio principal y evitar que los motores de búsqueda indexen la URL técnica de Netlify como versión preferida.

## SEO

La configuración SEO base del proyecto contempla:

- dominio canónico definido en Astro
- etiquetas `title` y `description`
- `robots.txt`
- `sitemap`
- favicon y `apple-touch-icon`

## Licencia

Este proyecto se distribuye bajo la licencia **MIT**.

Puedes consultar el archivo `LICENSE` para más información.

## 👨‍💻 Autor

Desarrollado por Álvaro García Rezola
