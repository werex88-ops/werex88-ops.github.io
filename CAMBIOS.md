# Registro de cambios

## 2026-11-06 (mejora diaria: demo de yoga y pilates)

Esta rama parte desde la del 5 de noviembre (solicitud #32, aún abierta, que a su vez incluye la #31), para no duplicar trabajo ni generar conflictos.

### Currículum (`index.html`)
- Accesibilidad del formulario de contacto: anillo de foco visible (3 px) en los campos y alto mínimo de 44 px en cada campo.
- No se modificó texto, secciones, datos de contacto ni identidad visual.

### Revisión de demos y portafolio
- Se revisaron las 19 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, sin errores de JavaScript, sin enlaces, anclas ni imágenes locales rotas, aviso de datos ficticios en todas las demos y páginas bajo 60 KB. No hubo correcciones necesarias en las demos existentes.

### Demo nueva
- `yoga/`: Aire Sur, estudio ficticio de yoga y pilates en Futrono (verde bosque, arcilla y salvia; tipografías Gloock y Figtree).
- Funciones: horario semanal con pestañas de día y filtros por disciplina, nivel y momento del día; cupos que bajan al reservar (lista de espera al llenarse); reserva por WhatsApp sin número fijo; pausa guiada de respiración (inhala 4 s, exhala 6 s) que respeta la reducción de movimiento; próxima clase y estado abierto/cerrado según hora de Chile; planes en CLP.
- Sin fotografías: ilustraciones SVG/CSS propias (paisaje del lago, mapa), porque `images.unsplash.com` responde 403 desde el entorno y no se podían verificar identificadores nuevos.
- Tarjeta en el portafolio (17 diseños) y captura `img/yoga.jpg` (1200×800, 58 KB).

### Sugerencias pendientes para René
- Reemplazar las ilustraciones de Aire Sur (y de taller, barbería y Mañío) por fotos reales o de Unsplash verificadas cuando haya acceso a `images.unsplash.com`.
- Currículum: agregar teléfono o LinkedIn y logros medibles si quieres; no se inventaron datos.
- Las capturas del portafolio se generan sin las tipografías de Google Fonts (bloqueadas en el entorno); conviene regenerarlas desde un navegador con acceso total.
- Aire Sur podría ofrecerse a estudios de yoga, pilates, danza o terapias de Los Ríos; evaluar sumar pago en línea si el cliente lo pide.

## 2026-11-05 (mejora diaria: demo de artesanía en madera)

Esta rama parte desde la del 4 de noviembre (solicitud #31, aún abierta), para no duplicar trabajo ni generar conflictos.

### Currículum (`index.html`)
- Áreas táctiles: los enlaces "Ver servicios de soporte" y "Ver portafolio de páginas", el nombre de la barra superior y el botón PDF pasan a tener al menos 44 px de alto (mejor uso en celular, WCAG 2.5.8).
- No se modificó texto, secciones, datos de contacto ni identidad visual.

### Revisión de demos y portafolio
- Se revisaron las 18 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, sin errores de JavaScript, sin imágenes ni enlaces locales rotos, aviso de datos ficticios en todas las demos, ninguna foto sobre 300 KB y todas las páginas bajo 60 KB. No hubo correcciones necesarias en las demos existentes.

### Demo nueva
- `madera/`: Mañío, taller ficticio de artesanía en madera nativa en Panguipulli (nogal oscuro, cobre y musgo; tipografías Fraunces y Karla).
- Funciones: armador de piezas (tipo, madera, medidas con deslizadores, acabado, grabado y entrega) con vista previa dibujada y precio estimado en CLP, catálogo filtrable que precarga el armador, envío del diseño por WhatsApp sin número fijo, estado abierto/cerrado según horario de Chile y preguntas frecuentes.
- Sin fotografías: ilustraciones SVG/CSS propias, porque `images.unsplash.com` no es accesible desde el entorno y no se podían verificar identificadores nuevos.
- Tarjeta en el portafolio (16 diseños) y captura `img/madera.jpg` (1200×800, 73 KB).

### Sugerencias pendientes para René
- Reemplazar las ilustraciones de Mañío (y de taller y barbería) por fotos reales o de Unsplash verificadas cuando haya acceso a `images.unsplash.com`.
- Currículum: agregar teléfono o LinkedIn y logros medibles si quieres; no se inventaron datos.
- Las capturas del portafolio se generan sin las tipografías de Google Fonts (bloqueadas en el entorno); conviene regenerarlas desde un navegador con acceso total.
- Revisar si quieres que el armador de Mañío calcule también plazos según la carga del taller.

## 2026-11-04 (mejora diaria: demo de taller mecánico)

### Currículum (`index.html`)
- Anclas del menú: el margen de desplazamiento sube de 16 a 80 px para que los títulos de sección no queden tapados por la barra fija (64 px).
- Contraste: marcadores de la línea de experiencia pasan de #8A93A3 a #7A8497 (mejor contraste para elementos gráficos, WCAG 1.4.11).
- No se modificó texto, secciones, datos de contacto ni identidad visual.

### Revisión de demos y portafolio
- Se revisaron las 15 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, sin errores de JavaScript, sin enlaces ni imágenes locales rotas, aviso de datos ficticios presente en todas, ninguna foto sobre 300 KB y todas las páginas bajo 60 KB. No hubo correcciones necesarias.

### Demo nueva
- `taller/`: Newen, taller mecánico ficticio en La Unión (grafito, amarillo seguridad y hueso; tipografías Big Shoulders Display e IBM Plex Sans).
- Funciones: cotizador por tipo de vehículo y servicio, agenda de día y hora con horario real de Chile, envío por WhatsApp sin número fijo, guía interactiva de luces del tablero, estado abierto/cerrado en vivo.
- Sin fotografías: ilustraciones SVG/CSS propias, porque `images.unsplash.com` no es accesible desde el entorno y no se podían verificar identificadores nuevos.
- Tarjeta en el portafolio (15 diseños) y captura `img/taller.jpg`.

### Sugerencias pendientes para René
- Reemplazar las ilustraciones del taller por fotos reales (propias o de Unsplash verificadas) cuando se habilite `images.unsplash.com`.
- Currículum: considerar agregar teléfono o LinkedIn y logros medibles (no se inventaron datos).
- Las capturas del portafolio se generan sin las tipografías de Google Fonts (bloqueadas en el entorno); regenerarlas desde un navegador con acceso total para fidelidad exacta.

## 2026-11-03 (propuesta Celeste: sin cursiva, contraste y panel de fotos)

- Se reemplazan las tipografías cursivas e itálicas por Dosis (la del logo) y Cormorant recta.
- Paletas Bosque, Laguna, Océano y Roca: franjas más oscuras con texto blanco para que se lea bien.
- Aros y prendedores se leen desde `piezas.json`; nuevo panel `admin/` (Sveltia CMS) para que Celeste suba fotos, cambie nombres y ordene las piezas desde el celular.
- Fotos de aros movidas a `img/piezas/`.

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
