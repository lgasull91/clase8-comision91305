# InfoMates 🧉

Sitio web informativo sobre el mundo del mate y la yerba mate: estilos de mate, tipos de yerba y todo lo que hay que saber para cebar bien. Proyecto desarrollado como entregable del curso de Desarrollo Web de Coderhouse (Comisión 91305).

## 🔗 Sitio en vivo

[https://lgasull91.github.io/clase8-comision91305/](https://lgasull91.github.io/clase8-comision91305/)

## 📄 Páginas

- **Inicio** — carousel de imágenes y presentación del sitio
- **Contacto** — formulario de contacto
- **Nosotros** — sobre el proyecto
- **Estilos de Yerba** — tipos de yerba mate (tradicional, uruguaya, barbacuá)
- **Estilos de Mate** — tipos de mate (camionero, imperial, torpedo)

## 🛠️ Tecnologías utilizadas

- HTML5 semántico
- SCSS (arquitectura de partials: utilities, base, layout, components)
- Bootstrap 5 (Grid system, Navbar responsive, Cards, Forms)
- AOS (Animate On Scroll) — animaciones al hacer scroll
- Google Fonts (Poppins + Inter)
- Git / GitHub Pages

## 📁 Estructura del proyecto

```
├── index.html
├── pages/
│   ├── contacto.html
│   ├── nosotros.html
│   ├── estilos-de-yerba.html
│   └── estilos-de-mate.html
├── assets/
│   └── img/
├── styles/
│   └── styles.css          (compilado, generado desde scss/)
└── scss/
    ├── main.scss            (punto de entrada)
    ├── utilities/
    │   ├── _variables.scss
    │   └── _mixins.scss
    ├── base/
    │   ├── _base.scss
    │   └── _tipografia.scss
    ├── layout/
    │   ├── _header.scss
    │   ├── _nav.scss
    │   └── _footer.scss
    └── components/
        ├── _carousel.scss
        ├── _cards.scss
        └── _buttons.scss
```

## 💻 Cómo correrlo localmente

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/lgasull91/clase8-comision91305.git
   cd clase8-comision91305
   ```

2. Instalá Sass (requiere [Node.js](https://nodejs.org/) instalado):
   ```bash
   npm install -g sass
   ```

3. Compilá el SCSS (modo watch, recompila automáticamente al guardar cambios):
   ```bash
   sass --watch scss/main.scss:styles/styles.css
   ```

4. Abrí `index.html` en el navegador (recomendado: extensión **Live Server** de VS Code para recarga automática).

## ✨ Características

- Diseño mobile-first, totalmente responsive (mobile / tablet / desktop)
- Navbar de Bootstrap con menú hamburguesa en mobile
- Arquitectura SCSS con variables, mixins con parámetros, nesting y `@extend`
- Animaciones al hacer scroll con AOS
- Animación de entrada del logo con `@keyframes`

## 👤 Autor

Lautaro Gasull
