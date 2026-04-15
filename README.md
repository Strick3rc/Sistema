# Sistema

Proyecto web tipo e-commerce / sistema de gestión construido como práctica de clase.

## Resumen del proyecto

- Contenido: sitio web estático con múltiples páginas HTML que simulan una tienda en línea.
- Estructura principal:
  - `Sistema/index.html` página principal.
  - `Sistema/cart.html` carrito de compras.
  - `Sistema/checkout.html` formulario de pago.
  - `Sistema/category.html` página de categorías/productos.
  - `Sistema/blog.html`, `Sistema/single-blog.html` sección de blog.
  - `Sistema/single-product.html` detalle de producto.
  - `Sistema/contact.html` y `Sistema/contact_process.php` contacto.
  - `Sistema/tracking.html` seguimiento de pedidos.

## Estructura de carpetas

- `Sistema/css/` archivos CSS ya generados.
- `Sistema/scss/` fuentes Sass/SCSS para el diseño.
- `Sistema/js/` scripts JavaScript del proyecto.
- `Sistema/vendors/` dependencias externas y bibliotecas de terceros.
- `Sistema/img/` imágenes utilizadas en la plantilla.
- `Sistema/fonts/` fuentes del proyecto.

## Dependencias y librerías usadas

- Bootstrap
- jQuery
- jQuery UI
- Owl Carousel
- Nice Select
- Lightbox
- Otras utilidades de frontend incluidas en `Sistema/vendors/`

## Cómo usar el proyecto

1. Abrir `Sistema/index.html` en un navegador.
2. Si se desea trabajar con Sass, editar y compilar los archivos en `Sistema/scss/`.
3. `Sistema/css/style.css` es la hoja de estilo resultante para producción.
4. Para probar el formulario de contacto, usar `Sistema/contact.html` y `Sistema/contact_process.php` en un servidor compatible con PHP.

## Notas sobre documentación TODO

- No se encontró un documento de tareas "TODO" específico en el repositorio raíz.
- Existen comentarios `TODO` dentro de la librería de terceros `Sistema/vendors/jquery-ui/jquery-ui.js`, pero no son parte del código de negocio del proyecto.

## Recomendaciones

- Si se desea continuar el desarrollo, empezar por personalizar `Sistema/scss/style.scss` y los archivos HTML.
- Mantener `Sistema/js/custom.js` como el lugar principal para las personalizaciones JavaScript.
- Revisar `Sistema/prepros-6.config` si se usa Prepros para compilar Sass.


