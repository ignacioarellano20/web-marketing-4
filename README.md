# Papel & Tinta — Web de prueba para Marketing Digital

Sitio ficticio pensado para practicar Google Tag Manager (GTM) y Google Analytics 4 (GA4).

## Páginas
- index.html
- productos.html
- nosotros.html
- contacto.html

## Eventos de dataLayer ya incluidos
- `add_to_cart_demo` al hacer clic en los botones de producto/plan.
- `generate_lead_demo` al enviar el formulario de contacto.

## Cómo usar
1. Sube esta carpeta a un repositorio de GitHub y activa GitHub Pages, o ábrela localmente.
2. Inserta tu contenedor de Google Tag Manager en el `<head>` de cada página (hay un comentario donde va).
3. Crea Tags/Triggers en GTM basados en los IDs de los botones (`btn-ver-productos`, `btn-contacto`, `btn-whatsapp`, `btn-enviar-formulario`, etc.) y en los eventos del dataLayer.

Todo el contenido (marca, productos, precios) es ficticio.
