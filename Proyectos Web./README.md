# Sal y Coral Marisquerías

Demostración comercial conceptual **no oficial**. No representa una página publicada ni implica autorización del establecimiento. Implementada con HTML, CSS y JavaScript vanilla; no requiere instalación ni compilación. Abre `index.html` directamente o usa Live Server desde la raíz del proyecto.

## Contenido editable

- **Fotografías:** cambia las URL de `photos` en [`js/config.js`](js/config.js). Las imágenes actuales son referencias de demostración alojadas en Unsplash y no son fotografías reales de Sal y Coral. Reemplázalas por fotografías propias autorizadas antes de publicar.
- **Ejemplos del menú:** edita `dishes` en `js/config.js`. Son categorías y descripciones ilustrativas, no una carta confirmada. Añade un valor a `price` y cambia `pricesConfirmed` a `true` solo después de confirmar los precios con el establecimiento.
- **Horarios y teléfono:** completa `hours` y `phone` solamente después de confirmarlos con el propietario. Si `phone` queda vacío, no se genera enlace de WhatsApp. No actives el teléfono publicado en directorios sin confirmación.
- **Ubicación:** edita `address` y `mapQuery`; los botones de ubicación construyen una búsqueda de Google Maps con esos datos.
- **Colores y tipografía:** modifica las variables CSS al inicio de `css/style.css`. La paleta está definida en `:root`.

## Fotografías de referencia actuales

Las URL están centralizadas en `js/config.js` para facilitar su sustitución. Cada foto se carga desde Unsplash con `images.unsplash.com`. Se emplean en hero, ambiente, pescado, camarones, ceviche, arroz y sopa. No deben presentarse como fotografías de los platos o del local real.

Puedes colocar fotografías autorizadas en `images/` y cambiar las URL de `photos` por rutas relativas, por ejemplo `images/ceviche.jpg`.

## Antes de una publicación comercial

Solicita al establecimiento la confirmación de carta, precios, horarios y teléfono; fotografías autorizadas del local y sus platos; y la revisión del texto de presentación. Esta carpeta contiene únicamente una propuesta demostrativa.
