# QuestPass CR 

Plataforma web para el descubrimiento y reserva de experiencias de entretenimiento alternativo, escape rooms, torneos de videojuegos y partidas de rol en Costa Rica.

> **Proyecto Académico**  
> Universidad CENFOTEC  
> Octubre 2026  

---

## Integrantes del Equipo

* **[Jonathan Jared Solano Arredondo]** - *Tech Lead / Arquitectura Base & Estilos Globales*
* **[Andrea del Carmen Vargas Perez]** - *Desarrollo de Formularios (Reservas & Contacto)*
* **[Jimena Cordero Bolaños]** - *Desarrollo de Autenticación & Panel de Administración*

---

## Descripción del Proyecto

QuestPass CR es una aplicación web multipágina desarrollada con **HTML5 semántico** y **CSS3 puro** (sin frameworks ni librerías JS externas). El sitio busca ofrecer una navegación accesible, responsiva y minimalista con una estética "Tech/Geek" en modo oscuro.

### Estructura del Sitio (7 Páginas)
1. **`index.html`**: Página principal con hero section, experiencias destacadas y propuesta de valor.
2. **`experiencias.html`**: Catálogo completo de eventos con tarjetas informativas y badges.
3. **`detalle.html`**: Vista detallada de la experiencia *El Archivo 47* (QST-001) con requisitos y precio.
4. **`reservar.html`**: Formulario de reserva con validaciones nativas de HTML5 (`date`, `number`, `tel`, etc.).
5. **`contacto.html`**: Formulario de contacto, datos de soporte técnico y sección FAQ interactiva.
6. **`login.html`**: Formulario de inicio de sesión para usuarios registrados.
7. **`admin.html`**: Panel de administración para gestión de catálogo y visualización de reservas.


---

## Paleta de Colores & Diseño

* **Fondo Principal:** `#18181b` (Gris oscuro / Dark Theme)
* **Contenedores/Cards:** `#27272a`
* **Color Primario (Índigo):** `#6366f1`
* **Color Secundario / Acento (Coral):** `#f43f5e`
* **Texto Principal:** `#f43f5e` / `#f4f4f5`

---

## Accesibilidad & Estándares WCAG

* **Navegación:** Uso del atributo `aria-label="Navegación principal"` en el `<nav>` de todas las páginas.
* **Encabezados:** Jerarquía estricta con **un único `<h1>`** por página.
* **Formularios:** Asociación estricta de `<label for="...">` con los identificadores `id` de cada input.
* **Foco Visible:** Indicador de enfoque interactivo personalizado mediante `:focus-visible`.
* **Diseño Responsivo:** Adaptado para dispositivos móviles (375px) y pantallas de escritorio (1366px+).

---

## Tecnologías Utilizadas

* **HTML5** (Estructura y semántica)
* **CSS3** (Variables CSS, Flexbox y CSS Grid)
* **Git & GitHub** (Control de versiones y colaboración)

## Estructura de Carpetas

```text
QuestPassCR/
├── css/
│   └── styles.css
├── index.html
├── experiencias.html
├── detalle.html
├── reservar.html
├── contacto.html
├── login.html
├── admin.html
└── README.md