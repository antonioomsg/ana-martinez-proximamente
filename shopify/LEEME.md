# Página «Próximamente» para Shopify (Online Store 2.0)

Sustituye la página de contraseña de la tienda mientras se monta. Los correos se guardan en **Clientes** con las etiquetas `proximamente` y `newsletter`.

## Instalar en el tema
1. Admin de Shopify, Tienda online, Temas, `...` del tema, **Duplicar** (haz copia antes de tocar nada).
2. En la copia: `...`, **Editar código**.
3. Sube o pega cada archivo en su carpeta:
   - `assets/`: `ana-proximamente.css`, `ana-obra.jpg`, `ana-firma.png`, `ana-jost.woff2`, `ana-ebgaramond-roman.woff2`, `ana-ebgaramond-italic.woff2` (y las licencias `OFL-*.txt`)
   - `sections/ana-proximamente.liquid`
   - `templates/password.json` (sustituye el existente)
   - `layout/password.liquid` (sustituye el existente; el del tema suele cargar cosas que aquí sobran)
4. Preferencias de la tienda, **Contraseña**: activa la protección y escribe la contraseña.
5. En el personalizador, plantilla **Contraseña**, sección «Ana · Próximamente»: cambia textos, imagen y enlaces.
6. Publica el tema. La dueña entra con el enlace discreto «Acceso / Owner» del pie.

## Notas
- Para recibir los avisos por correo, en Clientes filtra por la etiqueta `proximamente` o crea un segmento (Shopify Email).
- Al abrir la tienda, desactiva la contraseña en Preferencias.
- El consentimiento es una casilla obligatoria del navegador; Shopify marca el alta como suscripción de newsletter.
