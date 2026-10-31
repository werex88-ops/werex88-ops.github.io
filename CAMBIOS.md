# Registro de cambios

## 2026-10-31 (mejora diaria + demo nueva: kayak y pesca)

Esta rama parte de la rama de la solicitud abierta #22 (panadería, 30-oct), para no duplicar trabajo; incluye además lo ya fusionado en `main`.

### Currículum (`index.html`) — 3 mejoras, sin tocar contenido
- Títulos con `text-wrap: balance` (sin líneas huérfanas) y párrafos con `text-wrap: pretty`.
- `scroll-padding-top` y `text-size-adjust` para un desplazamiento por anclas y una lectura móvil más estables.
- Números de sección con cifras tabulares (alineación uniforme).

### Portafolio y demos existentes (1 mejora por página, sin cambios de diseño)
- Color de la barra del navegador (`theme-color`) e ícono de pestaña propio, con la paleta de cada página, en el portafolio, sushi, gimnasio, cafetería, velas, plantas y mascotas.
- Revisión con Playwright de las 11 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, sin errores de JavaScript y sin respuestas 404. Todas tienen aviso de datos ficticios y respetan `prefers-reduced-motion`.

### Demo nueva: `kayak/` — Mawün Kayak (Lago Ranco, ficticia)
- Identidad: azul noche, azul lago y naranja; tipografías Fraunces y Outfit.
- Funciones: 6 salidas con filtro por dificultad, armador de reserva (salida, fecha, hora, personas y extras) con total en CLP y pedido por WhatsApp (sin número fijo), condición esperada del lago según la hora, y estado abierto/cerrado con hora de Chile.
- Secciones: propuesta de valor, salidas, seguridad y guías de ejemplo, opiniones rotuladas como ejemplo, preguntas frecuentes, horario y mapa ilustrativo en SVG.
- Fotos: `images.unsplash.com` sigue bloqueado desde el entorno; se enlazaron 3 fotos ya verificadas de Cabañas (kayak, lago con neblina, fogón). No se descargaron, así que la captura `demos/img/kayak.jpg` (72 KB) muestra la portada sin foto.
- Tarjeta en el portafolio y cifra actualizada a 11 diseños; créditos registrados.

### Sugerencias pendientes para René
- Regenerar `demos/img/kayak.jpg` con la foto de portada cuando se habilite `images.unsplash.com`.
- Mawün Kayak reutiliza fotos de Cabañas; conviene sumar fotos propias de pesca con mosca y de la isla.
- Verifica que el nombre "Mawün Kayak" no coincida con un negocio real antes de mostrarlo a clientes.
- Currículum: falta un `og:image` (imagen de vista previa al compartir); requiere una imagen que elijas tú.
- Cafetería, gimnasio, plantas, sushi y velas no usan la etiqueta `main` (cambio estructural, no aplicado hoy).

## 2026-10-30 (mejora diaria + demo nueva: panadería)

### Currículum (`index.html`) — 3 mejoras, sin tocar contenido
- Enlace "Saltar al contenido" para teclado y lectores de pantalla (oculto hasta recibir foco y en la versión impresa).
- Metaetiquetas: URL canónica, autor y Twitter Card.
- `main` con ancla `#contenido`, necesaria para el enlace anterior.

### Portafolio y demos existentes
- Foco visible de teclado (doble anillo, legible sobre cualquier fondo) en el portafolio, cafetería, gimnasio, plantas, sushi, velas y mascotas (1 mejora por página).
- Velas: corregido un desborde horizontal de 21 px a 320 px en el formulario del boletín.
- Revisión sin hallazgos de enlaces rotos, errores de JavaScript ni páginas sobre 60 KB.

### Demo nueva: `panaderia/` — Horno Pellín (Paillaco, ficticia)
- Identidad: ladrillo, harina, trigo y carbón; tipografías Bricolage Grotesque y Newsreader.
- Funciones: estado abierto/cerrado según hora de Chile, "hoy en el horno" con cuenta regresiva a la próxima horneada, carta con filtros, encargo con cantidades, día y hora de retiro, y envío por WhatsApp (sin número fijo).
- Fotos: `images.unsplash.com` sigue bloqueado desde el entorno; se reutilizaron 4 fotos ya verificadas de la cafetería (croissant, kuchen, galleta, tostado) y los panes son ilustraciones SVG. Registradas en `demos/CREDITOS.md`.
- Tarjeta y captura (`demos/img/panaderia.jpg`, 94 KB) en el portafolio; cifra actualizada a 10 diseños.

### Sugerencias pendientes para René
- Reemplazar las ilustraciones de panes de Horno Pellín por fotos reales de pan cuando se habilite `images.unsplash.com`.
- Currículum: un `og:image` (imagen de vista previa al compartir el enlace) mejoraría cómo se ve en WhatsApp; requiere una imagen que elijas tú.
- Cafetería, gimnasio, plantas, sushi y velas no usan la etiqueta `main`; conviene agregarla al revisar cada una (cambio estructural, no aplicado hoy).
- Mascotas ya tenía foco en las opciones; se sumó el general.

## 2026-10-29 (Estrella Austral: paleta roja, sin packs y con SEO)

- `navidad/`: nueva paleta navideña (rojos, dorado, acento verde pino y nieve), reemplazando el verde y crema.
- Se eliminan los packs; se agrega la sección "Nosotros" (presentación de la empresa) y botones "Cotizar" en cada servicio que preseleccionan el formulario.
- Formulario con servicio de interés y comuna; nieve animada en la portada (se desactiva con reducción de movimiento).
- SEO: título y descripción orientados a búsquedas locales, URL canónica, Open Graph, datos estructurados LocalBusiness y espacios comentados para Google Analytics 4 y Search Console.
- Tarjeta del portafolio y captura actualizadas.

## 2026-10-29 (demo nueva: decoración navideña, prioritaria)

### Portafolio de demos
- Demo nueva `navidad/`: Estrella Austral, decoración navideña ficticia en Valdivia y alrededores, pensada para replicarse en WordPress con Astra y Elementor (incluye comentario guía en el HTML).
- Secciones: encabezado transparente, portada con luces titilantes y guirnalda, cinta animada, servicios, cómo trabajamos, galería con filtros y visor, packs que se preseleccionan en el formulario, opiniones de ejemplo, preguntas frecuentes, contacto con formulario a WhatsApp (número de ejemplo) y pie.
- Fotos de Unsplash gratuitas, enlazadas desde images.unsplash.com: las 8 indicadas originalmente no se pudieron abrir desde el entorno, por lo que se usaron equivalentes verificadas.
- Tarjeta en primer lugar del portafolio, cifra de diseños actualizada y créditos registrados.

### Sugerencias pendientes para René
- Regenerar la captura `demos/img/navidad.jpg` con fotos cuando se habilite `images.unsplash.com` (hoy muestra el arco sin la foto).
- Si prefieres exactamente las fotos que elegiste, envíame sus enlaces de imagen o habilita el dominio para reemplazarlas.

## 2026-10-29 (contacto por WhatsApp, a pedido de René)

- Currículum y portafolio: botón flotante de WhatsApp (+56 9 7798 7960) y formulario de consulta (nombre, negocio, qué necesita, plazo y detalle) que abre WhatsApp con el mensaje listo.
- Currículum: la sección de contacto muestra correo y WhatsApp; el formulario y el botón flotante no aparecen en la versión PDF.

## 2026-10-29 (centro cultural rediseñado como sitio informativo, a pedido de René)

### Portafolio de demos
- `centro-cultural/` pasa de escuela de talleres (Casa Vertiente) a sitio institucional e informativo: Ribera, Centro Cultural de Valdivia (ficticio).
- Estilo sobrio: negro, blanco y carmín; tipografías Archivo y Newsreader.
- Contenido: exposiciones destacadas en carrusel, "Hoy en Ribera", exposiciones en exhibición y próximas, agenda con filtros por tipo y descarga al calendario, visita (horario con estado abierto/cerrado, entrada, cómo llegar, accesibilidad), educación y mediación, salas, noticias y boletín.
- Se actualizan la tarjeta del portafolio y los créditos.

## 2026-10-29 (demo nueva: centro cultural, a pedido de René)

### Portafolio de demos
- Demo nueva `centro-cultural/`: Casa Vertiente, centro de artes ficticio en Valdivia (cobalto, magenta y amarillo; tipografías Syne y Work Sans).
- Funciones: cartelera con filtros por disciplina, público y gratuidad, descarga de eventos al calendario (.ics), talleres con cupos y lista de espera, ficha de inscripción con validación de edad, programa de visitas mediadas para escuelas, convocatorias con cuenta regresiva y horario que marca el día actual.
- Se agrega su tarjeta al portafolio (8 diseños) y los créditos de fotos.

### Sugerencias pendientes para René
- Esta demo sirve como pieza para ofrecer sitios a centros culturales, municipios, escuelas de arte y agrupaciones; evaluar una versión más simple para agrupaciones pequeñas.
- Regenerar la miniatura con fotos cuando se habilite `images.unsplash.com`.

## 2026-10-29 (rediseño de currículum y demo de cabañas, a pedido de René)

### Currículum (`index.html`)
- Rediseño completo con identidad más sobria: azul marino y azul institucional, tipografías Inter e Instrument Serif; se eliminan las manchas de color y la cinta animada.
- Nuevas secciones: ficha de cargo actual, cifras de trayectoria, perfil profesional y competencias agrupadas (gestión pública y cultural, tecnología, formación y comunicación).
- Experiencia en viñetas; el cargo actual se complementa con funciones informadas por René (FAE, SLEP y municipios, compras públicas, convenios, presupuesto, ACCIONA/SIRAC y Revista Acciona Los Ríos 2026). El trabajo freelance suma sitios en GitHub Pages y reparación de notebooks.
- Botón para descargar el CV en PDF; la versión impresa queda en 3 páginas A4.

### Demo de cabañas
- Rediseño completo "Alerce Dormido": paleta azul petróleo, verde río y latón (reemplaza crema y terracota), tipografías DM Serif Display y Manrope.
- Fotografías de Unsplash enlazadas directamente, buscador en portada, calculadora de estadía con extras y descuentos, envío de la solicitud por WhatsApp sin número fijo, preguntas frecuentes y mapa ilustrativo.
- Nueva miniatura en el portafolio (generada sin fotos, porque el entorno no puede descargarlas).

### Sugerencias pendientes para René
- Revisar que las funciones del cargo actual estén redactadas como te acomoda.
- Agregar teléfono o LinkedIn al currículum si quieres que aparezcan.
- Regenerar la miniatura de cabañas con fotos cuando se habilite `images.unsplash.com`.

## 2026-10-29 (integración manual: demos con fotografías)

### Portafolio de demos
- Se integran las 6 demos originales con fotografías (antes en `~/proyectos/portafolio`, servidas con Docker): Kaiyō Sushi Bar, Forja Gym, Grano & Calma (cafetería), Luz de Cera (velas), Raíz Verde (plantas) y Pata Feliz (mascotas).
- La demo simple de cafetería (Café Lluvia Tibia) se reemplaza por Grano & Calma. Se mantiene Cabañas Alerce Dormido.
- `/demos/index.html` pasa a ser el portafolio "Werex Studio", con tarjeta nueva para cabañas (7 en total), aviso de datos ficticios, correo real de contacto, enlace al currículum y créditos de fotos.
- Barras de navegador de las tarjetas: se quitan dominios `.cl` que podrían corresponder a negocios reales.
- Cada demo nueva lleva un aviso fijo "Propuesta de diseño de ejemplo; datos ficticios" con enlace de vuelta al portafolio.
- 7 fotos de más de 300 KB recomprimidas; se corrige desplazamiento horizontal en móvil de gimnasio y mascotas.
- Créditos de fotografías (Unsplash) en `/demos/CREDITOS.md`.

### Sugerencias pendientes para René
- Las direcciones de ejemplo están en Santiago (Providencia, etc.); evaluar cambiarlas a Valdivia u otras comunas de Los Ríos para el nicho local.
- El número de WhatsApp de Pata Feliz (+56 9 5555 1234) podría pertenecer a alguien real; conviene reemplazarlo por un enlace sin número antes de mostrarlo a clientes.

## 2026-10-29

### Currículum (`index.html`)
1. Metaetiquetas: descripción, Open Graph, `theme-color` y favicon propio (monograma "RC" en SVG).
2. Accesibilidad y estilos: foco visible en enlaces, mayor contraste en la etiqueta "Desde noviembre 2017" (coral oscurecido para WCAG AA), cinta animada marcada como decorativa (`aria-hidden`) y hoja de estilos para imprimir o guardar en PDF.
3. Enlace discreto "Portafolio de páginas web" hacia `/demos/` (botón secundario en la portada y enlace en el pie).

No se modificó ningún texto, sección, dato de contacto ni tipografía/color de la identidad.

### Portafolio de demos
- Se crea `/demos/` con `index.html` (una tarjeta por demo).
- Demo 1: `cabanas/` — Cabañas Alerce Dormido (cabañas y turismo; verde bosque y terracota), con testimonios rotulados como ejemplo y WhatsApp ficticio.
- Demo nueva: `cafeteria/` — Café Lluvia Tibia (gastronomía y cafetería; espresso, ámbar y crema), con carta por pestañas accesibles.
- No hubo demos previas que revisar.

### Sugerencias pendientes para René
- Agregar un resumen profesional corto y logros medibles en el currículum (no se inventaron).
- Evaluar un enlace "Portafolio" también en la barra de navegación (en móvil no cabe sin recargar la barra).
- Reemplazar el número ficticio de WhatsApp si alguna demo se usa con un cliente real.
- Considerar subir fotos propias de proyectos reales (con permiso) a las demos.
