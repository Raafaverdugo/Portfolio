# BetterIfYouDoNotReadme

## Guía de Estilos

Bienvenidos a la guía de estilos de este proyecto. En este documento se detallan los colores, tipografías, logo personal, librerías utilizadas, los enlaces a las webs que han servido de referencia, y algunos problemas técnicos que se han encontrado a lo largo del desarrollo del proyecto y las soluciones implementadas.

---

## 1. Colores

Aquí están los códigos de colores utilizados en este proyecto:

- **Color principal de fondo**: `#f4f4f4`
- **Color de texto principal**: `#333333`
- **Color de fondo del header y footer**: `#222222`
- **Color del enlace en el header y footer**: `#FFFFFF`
- **Color de enlace en hover (cuando se pasa el ratón)**: `#CCCCCC`
- **Color de fondo en la sección de presentación**: `#87878741`
- **Color de fondo en secciones de contacto y hobbies**: `#E6E6E6`
- **Color de los botones**: `#222222` (con hover en `#444444`)

---

## 2. Tipografías

El proyecto utiliza las siguientes tipografías:

- **Tipografía principal**: `Arial, Helvetica, sans-serif`
  - Esta es la tipografía por defecto para el contenido y los encabezados.

---

## 3. Logo Personal

El logo personal está ubicado en la carpeta de imágenes (`/img`). Este logo se utiliza en el encabezado y se adapta en tamaño y posición para diferentes dispositivos.

---

## 4. Enlaces a Webs Utilizadas como Referencia

Durante el desarrollo de este proyecto, se tomaron en cuenta algunas referencias de otros proyectos y recursos:

- [W3Schools](https://www.w3schools.com/) - Tutoriales y ejemplos para aprender programación web.
- [Can I use](https://caniuse.com/) - Herramienta para comprobar la compatibilidad de características web en diferentes navegadores.

---

## 5. Problemas Técnicos y Soluciones

Durante el desarrollo del proyecto, se presentaron algunos problemas técnicos que se resolvieron de la siguiente manera:

### Problema 1: Rutas de los Archivos CSS e Imágenes no se Cargaban Correctamente

**Descripción**: Al subir el proyecto a GitHub Pages, los archivos CSS e imágenes no se cargaban correctamente en el navegador, lo que afectaba el diseño del sitio.

**Solución**: Se corrigieron las rutas relativas para los archivos CSS e imágenes. Se usaron rutas relativas desde el archivo HTML raíz hacia los recursos en las carpetas correspondientes (`css/`, `img/`, etc.). Por ejemplo:

```html
<link rel="stylesheet" href="css/style.css">
