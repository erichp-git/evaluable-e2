# 📄 Evaluable 1

Este proyecto es una actividad evaluativa que consiste en recrear una página web utilizando **Astro**, control de versiones con **Git**, y el uso de **ramas en repositorios**.

- Layout original: [Live Demo - Elegant Themes](https://www.elegantthemes.com/layouts/legacy-premade/simple-home-page/live-demo)  
- Captura del layout:  
  ![Captura de pantalla](/simplelayout/public/img/simplelayout.png)
- Repositorio en GitHub: [https://github.com/erichp-git/evaluable-e2](https://github.com/erichp-git/evaluable-e2)  
- Página desplegada: [https://erichp-git.github.io/evaluable-e2/](https://erichp-git.github.io/evaluable-e2/)

## 📂 Estructura de Archivos

/evaluable-e2
├── README.md               # Documentación del proyecto
├── styles/
│   └── global.css          # Estilos globales
├── public/
│   ├── fonts/              # Fuentes utilizadas
│   └── img/                # Imágenes del sitio
└── src/
    ├── components/         # Componentes reutilizables
    ├── layouts/            # Plantillas base
    └── pages/              # Páginas del sitio

## 🧱 Descripción del Proyecto

### 📁 styles/
- `global.css`: Contiene el reset y los estilos globales aplicados a toda la web.

### 📁 layouts/
- `Layout.astro`: Estructura base del HTML, incluyendo `<head>`, `<body>` y slots.

### 📁 components/
- `BarrasPorcentaje.astro`: Sección con barras de porcentaje y texto informativo.
- `Boton.astro`: Botón estilizado reutilizable.
- `Cards.astro`: Tarjetas para mostrar entradas de blog.
- `Footer.astro`: Pie de página del sitio.
- `Header.astro`: Encabezado principal.
- `Intro.astro`: Sección introductoria destacada.
- `Nav.astro`: Menú de navegación.
- `TablaImagenes.astro`: Contenedor con imágenes y texto.

### 📁 pages/
- `index.astro`: Página principal.
- `aboutme.astro`: Información personal del creador.
- `aboutus.astro`: Información sobre la empresa.
- `blog.astro`: Página de blog con entradas simuladas.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica del contenido.
- **CSS3**: Estilización visual del sitio.
- **Flexbox**: Diseño responsivo y flexible.
- **Astro**: Framework moderno para sitios rápidos y estáticos.

---

## ✏️ Personalización

Puedes adaptar este proyecto fácilmente a tus necesidades:

1. Modifica los textos en los archivos `.astro` dentro de la carpeta `pages/`.
2. Ajusta los valores de las barras de progreso en `BarrasPorcentaje.astro` para reflejar tus habilidades.
3. Agrega tus propios entradas de blog en `blog.astro`.

---

## 🙌 Créditos

- 🎨 Diseño original por: [Elegant Themes](https://www.elegantthemes.com/layouts/legacy-premade/simple-home-page/live-demo)  
- 💻 Recreado por: [Eric Hernández](https://github.com/erichp-git)