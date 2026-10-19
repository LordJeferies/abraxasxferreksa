# FerreKsa · Landing

Sitio estático, sin instalación ni compilación. Destino solicitado: `LordJeferies/abraxasxferreksa`, GitHub Pages.

## Ver el diseño

- Escritorio: https://www.figma.com/design/IBSrbil70Ga1zjWFEPGxCH?node-id=1-2
- Móvil: https://www.figma.com/design/IBSrbil70Ga1zjWFEPGxCH?node-id=10-748
- Segundo banner, Luka + logo original: https://www.figma.com/design/IBSrbil70Ga1zjWFEPGxCH?node-id=46-203
- Segundo banner móvil: https://www.figma.com/design/IBSrbil70Ga1zjWFEPGxCH?node-id=46-227

## Publicar sin comandos

1. Inicia sesión en GitHub como **LordJeferies**. Crea un repositorio público llamado **abraxasxferreksa** en https://github.com/new. Si ya existe, abre ese repositorio.
2. En **Add file → Upload files**, arrastra el contenido de esta carpeta: `index.html`, `404.html`, `styles.css`, `app.js`, `config.js`, la carpeta `assets`, `robots.txt` y `sitemap.xml`. `index.html` debe quedar en la raíz, sin una carpeta adicional que lo envuelva. Confirma los archivos en la rama **main**. No hace falta subir este README ni el script para que funcione.
3. En **Settings → Pages → Build and deployment**, elige **Deploy from a branch**, rama **main**, carpeta **/(root)** y pulsa **Save**.
4. Espera a que GitHub confirme la publicación. La URL prevista es https://lordjeferies.github.io/abraxasxferreksa/ . Comprueba que carguen las imágenes y que «Revisar cotización» abra el número correcto antes de difundirla.

## Publicar con el asistente local

Con Git y GitHub CLI instalados, abre `publicar.command` en macOS. El script solicita iniciar sesión si es necesario, comprueba la cuenta, crea el repositorio público si falta, sube los archivos y configura Pages. Si macOS no permite abrirlo directamente, ejecuta `bash publicar.command` desde esta carpeta. No solicita claves en el chat ni sobrescribe el historial remoto. Si el repositorio ya contiene cambios incompatibles, Git detendrá la subida para que se revisen.

El script no se ejecutó en esta entrega porque la credencial local era inválida. La conexión GitHub confirmó la cuenta LordJeferies, pero respondió 404 para el repositorio y no ofrecía una operación de creación de repositorios ni configuración de Pages.

## Funciones

- Dos banners con controles manuales, pausa automática al interactuar y respeto por movimiento reducido.
- Menú móvil, navegación por tipo de proyecto, 10 categorías, búsqueda y filtros de una selección de 9 productos.
- Lista editable con cantidades entre 1 y 999, borrador local, revisión del mensaje, copia y descarga de texto.
- WhatsApp confirmado por el propietario: **+58 412 352 5139**. La web prepara el mensaje; el usuario decide enviarlo en WhatsApp.
- Preguntas frecuentes, contacto telefónico, navegación por teclado, etiquetas, foco visible y mensajes de estado.
- Título, descripción, Open Graph, datos estructurados Organization, URL canónica, robots y sitemap. Esto es preparación SEO, no una garantía de posicionamiento.
- Fuentes e imágenes alojadas localmente. Sin analítica ni rastreadores añadidos.

## Editar

- Contacto: `config.js`; al cambiarlo, actualizar también los enlaces, teléfono visible y datos estructurados de `index.html`.
- Productos y categorías: listas al principio de `app.js`.
- Colores y diseño: `styles.css`.
- Textos, SEO y secciones: `index.html`.

No se inventaron precios, stock, direcciones, horarios, reseñas, testimonios ni redes sociales. Esos datos se añaden cuando estén confirmados. Las categorías sin productos en la selección conducen a una consulta libre. Las imágenes de producto son referencias; se generó una serie cinematográfica consistente y se conservaron los originales aparte.

## Verificación realizada

Comprobación en navegador local: portada y banner de Luka, añadir producto, revisión del mensaje y destinatario WhatsApp, persistencia después de recargar, búsqueda sin resultados, validación del formulario vacío y apertura del menú móvil. Vista móvil revisada a través de marcos de 390 y 320 px. Sintaxis de JavaScript y vínculos locales comprobados. No se envió ningún mensaje real. La publicación pública y pruebas en un teléfono real quedan pendientes.

## Vista local

Desde esta carpeta: `python3 -m http.server 4173`, y abrir http://localhost:4173 . Abrir `index.html` directamente permite ver el diseño, pero el guardado y la copia dependen de las restricciones del navegador.


## Revisión cinematográfica

Se integró una escena generada con Luka y el logo como parte del taller, cuatro categorías con fotografías de uso y tres nuevas fotografías editoriales de producto. La galería usa tamaños distintos en escritorio y dos columnas en móvil. Hay filtros por intención de proyecto, fichas de producto con consejos para consultar, estados al añadir artículos, acceso flotante a WhatsApp, navegación que se compacta y botón para volver arriba.

Las instrucciones de Pages siguen la documentación oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site .

Verificación adicional: filtro por proyecto «Renovar y pintar», detalle de producto, añadir desde la ficha, abrir y cerrar la revisión de WhatsApp, nueva ficha de tornillos y fijaciones, nueve productos y carga de imágenes visibles. Se revisó la nueva escena de Luka a 390 y 320 px. No se comprobó un envío real, un teléfono físico ni una auditoría completa de accesibilidad.
