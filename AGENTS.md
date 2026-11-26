# Pintores Fredy

## Sitio
- Sitio estático para GitHub Pages, sin servidor, base de datos ni formularios.
- El contacto se abre directamente en WhatsApp o teléfono.
- Las fotografías se cargan desde el bucket público de Supabase compartido en el chat.
- El sitio está marcado `noindex,follow` hasta que se apruebe la versión.

## Contenido
- El alcance visualizado en imágenes respalda pintura interior, exterior y de fachadas, preparación de paredes y trabajos en altura.
- El chat confirma cobertura de toda CABA.
- No agregar precios, certificaciones, garantías, plazos, testimonios ni experiencia no confirmados.
- No incluir otras imágenes de clientes ni datos personales del domicilio del lead.

## Analítica
- PostHog registra pageviews en el proyecto compartido, segmentados con `site_slug=pintores-fredy`.
- Autocapture y grabación de sesiones están desactivados. No enviar el teléfono del lead como propiedad de eventos.
