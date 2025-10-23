# Tormenta Solar - Un Relato Interactivo

[![Ver Demo en Vivo](https://img.shields.io/badge/GitHub%20Pages-Ver%20Demo%20en%20Vivo-2ea44f?style=for-the-badge&logo=github)](https://perech72.github.io/tormentaSolar/)

Este repositorio contiene el código de una página web estática diseñada para la presentación del relato corto "Tormenta Solar" de Pere Chardi Garcia.

El objetivo del proyecto es ofrecer una experiencia de lectura moderna, inmersiva y atmosférica, utilizando un diseño oscuro (`dark mode`) y animaciones sutiles que acompañan al lector a través de la historia.

## ✨ Características Principales

* **Diseño Moderno y Oscuro:** Una estética *dark mode* centrada en la legibilidad, con una tipografía elegante (Lato y Merriweather) y un toque de color violeta como acento.
* **Cabecera con Efecto Parallax:** La imagen de portada (`portada.jpg`) permanece fija mientras se hace scroll, creando un efecto de profundidad.
* **Aparición Progresiva (Fade-in on Scroll):** El texto del relato (títulos y párrafos) aparece suavemente a medida que el usuario baja por la página, utilizando `IntersectionObserver` de JavaScript para un rendimiento óptimo.
* **Animación de Texto "Vivo":** La palabra "FIN" al final del relato cobra vida al pasar el ratón por encima, con una animación aleatoria de movimiento y color para cada letra.
* **Botón de Descarga:** Incluye un botón destacado al final para descargar el relato completo en formato PDF (`tormentaSolar.pdf`).
* **SEO Optimizado:** La página incluye etiquetas `<meta>` (título, descripción) y etiquetas *Open Graph* (para Facebook, WhatsApp) y *Twitter Cards* (para X) para asegurar que se comparte correctamente en redes sociales y mejora su visibilidad en buscadores.
* **Diseño Responsivo:** Totalmente adaptable a dispositivos móviles, tablets y ordenadores de escritorio.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Para la estructura semántica del contenido.
* **CSS3:** Para todos los estilos, animaciones (`@keyframes`), diseño *responsive* (Media Queries) y el efecto *parallax* (`background-attachment: fixed`).
* **JavaScript (Vanilla):**
    * `IntersectionObserver`: Para detectar cuándo los elementos entran en la pantalla y activar la animación de aparición progresiva.
    * Manipulación del DOM y Eventos: Para gestionar la animación interactiva del texto "FIN" (`mouseenter`, `mouseleave`).

## 👤 Autor

* **Relato:** Pere Chardi Garcia (`pere.chardi@gmail.com`)
* **Diseño y Desarrollo Web:** Creado con la asistencia de Gemini.

## 🚀 Ver el Proyecto

Puedes ver la página en vivo en el siguiente enlace:
**[https://perech72.github.io/tormentaSolar/](https://perech72.github.io/tormentaSolar/)**
