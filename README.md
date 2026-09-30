# Actividad 4: Portafolio Web Interactivo y Personalizado

---

## 📌 Datos de la Entrega

* **Alumno:** Hasiel Isai Mendoza Lucero
* **Materia:** Desarrollo Web
* **Profesor(a):** Adelina Martínez
* **Carrera:** Ingeniería en Sistemas Computacionales
* **Fecha:** Septiembre 2026
* **Modalidad:** Individual

---

## 💻 Descripción del Proyecto

El presente proyecto consiste en el diseño, personalización e implementación de un **Portafolio Web Profesional**, desarrollado como parte de la Actividad 4 de la asignatura. El objetivo principal fue adaptar una plantilla base para proyectar una imagen profesional como futuro Ingeniero en Sistemas Computacionales, mostrando habilidades técnicas, proyectos planificados y vías de contacto.

### Tecnologías Utilizadas
* **HTML5:** Estructuración semántica de la página.
* **CSS3 & Bootstrap 5:** Maquetación adaptable (*responsive design*) y personalización gráfica completa.
* **JavaScript (JS Vanilla):** Control de interacción de modales y prevención de gestos multitáctiles indebidos.
* **GitHub & GitHub Pages:** Control de versiones y despliegue continuo en la nube.

---

## 🎨 Plantilla Utilizada y Secciones del Sitio

* **Framework CSS:** Bootstrap 5
* **Plantilla Base:** *Freelancer* por Start Bootstrap
* **Enlace de descarga de la plantilla original:** [Start Bootstrap - Freelancer](https://startbootstrap.com/theme/freelancer)

### Estructura y Secciones del Portafolio:

1. **Barra de Navegación (`Navbar`):** Menú superior fijo con navegación fluida (*smooth scroll*) hacia cada sección del sitio.
2. **Encabezado (`Masthead`):**
   * **Foto de perfil real:** Fotografía profesional ubicada en la esquina superior izquierda.
   * **Información Personal:** Nombre completo (*Hasiel Isai Mendoza Lucero*) y subtítulo profesional (*Estudiante de Ingeniería en Sistemas Computacionales*).
3. **Proyectos Destacados (`Portfolio`):** Rejilla con 6 tarjetas interactivas que despliegan ventanas modales dinámicas al hacer clic, mostrando detalles de sistemas académicos, calculadoras y dashboards.
4. **Habilidades & Tecnologías (`Skills`):** Sección dedicada a mostrar el stack técnico principal (HTML5, CSS3, Bootstrap, JavaScript) y tecnologías que se buscan dominar.
5. **Sobre Mí (`About`):** Resumen sobre mi perfil profesional, enfoque de carrera y metas hacia el desarrollo web *Full-Stack*.
6. **Contacto (`Contact`):** Formulario dinámico e íconos de redes sociales para contacto profesional.

---

## 🛠️️ Proceso de Creación Paso a Paso

1. **Elección y Descarga de la Plantilla:**
   * Se descargó la estructura original de la plantilla *Freelancer* en Bootstrap 5.

2. **Organización del Repositorio:**
   * Se estructuró la raíz del proyecto según lo solicitado:
     ```text
     ├── index.html
     ├── README.md
     ├── css/
     │   └── portafolio.css
     ├── js/
     │   └── portafolio.js
     └── img/
         ├── mi-foto.jpg
         └── portfolio/
     ```

3. **Inclusión de Fotografía Real y Profesional:**
   * Se sustituyó el avatar genérico en formato SVG (`avataaars.svg`) por una fotografía profesional propia (`image_193161.jpg`), con buena iluminación y encuadre ideal para CV/LinkedIn.

4. **Alineación y Rediseño del Encabezado (`Masthead`):**
   * Mediante clases utilitarias de flexbox (`flex-md-row`, `text-md-start`), se movió la foto de perfil al extremo superior izquierdo con dimensiones controladas (`width: 90px; height: 90px; object-fit: cover;`), logrando una lectura más ejecutiva.

5. **Rediseño Completo de Estilos (Tema Tema Resident Evil / Dark Red):**
   * Se redefinieron las variables raíz de CSS (`:root`) en `css/portafolio.css` para sustituir la paleta original turquesa/verde por un tema oscuro con acentos en rojo borgoña (`#8b0000`).
   * Se personalizaron los modales (`.portfolio-modal`), botones (`.btn-primary`) y el comportamiento del cursor/focus en formularios.

6. **Optimización de Usabilidad y Prevención de Zoom:**
   * Se configuró el `viewport` en `index.html` y se implementaron *script listeners* en `js/portafolio.js` (`wheel` con `ctrlKey` y `gesturestart`) para bloquear el escalado accidental al interactuar con el *touchpad* de la laptop.

7. **Despliegue en GitHub Pages:**
   * Se subieron los cambios al repositorio público y se activó el hosting gratuito en la rama `main` a través de GitHub Pages.

---

## 📸 Capturas de Pantalla

*(Reemplaza los nombres de archivo por tus propias capturas dentro de la carpeta `img/`)*

### 1. Vista Principal (Encabezado con Foto y Menú)
![Encabezado y Menú Principal](img/captura-header.png)

### 2. Sección de Proyectos y Habilidades
![Proyectos y Habilidades](img/captura-proyectos.png)

### 3. Modal Interactivo y Tema Oscuro
![Ventana Modal](img/captura-modal.png)

---

## 🌐 Enlaces del Proyecto

* **Repositorio en GitHub:** `https://github.com/TU-USUARIO/NOMBRE-REPOSITORIO`
* **Sitio en vivo (GitHub Pages):** `https://TU-USUARIO.github.io/NOMBRE-REPOSITORIO/`
