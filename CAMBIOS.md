# Registro de cambios

## 2026-11-12 (mejora diaria: demo de termas y spa)

Esta rama parte desde la del 11 de noviembre (solicitud #38, aún abierta, que a su vez incluye las #37, #36, #35, #34, #33, #32 y #31), para no duplicar trabajo ni generar conflictos.

### Currículum (`index.html`)
- Robustez: si JavaScript está desactivado o el navegador no soporta `IntersectionObserver`, las secciones con animación de entrada ya no quedan invisibles (`<noscript>` y respaldo en el script).
- Accesibilidad: con la preferencia del sistema "mayor contraste" (`prefers-contrast: more`), los textos grises y tenues se oscurecen.
- No se modificó texto, secciones, datos de contacto ni identidad visual.

### Revisión de demos y portafolio
- Se revisaron las 25 páginas (currículum, portafolio y 23 demos) a 320, 390 y 1440 px: sin desplazamiento horizontal, sin errores de JavaScript, sin 404, sin anclas rotas, aviso de datos ficticios en todas y páginas bajo 60 KB.
- Accesibilidad: cafetería, gimnasio, mascotas, plantas, sushi y velas no tenían la etiqueta `<main>`; se agregó (una por página, sin cambios visuales).

### Demo nueva
- `termas/`: Vapor Sur, termas ficticias en Futrono (noche volcánica, agua turquesa y cobre; tipografías Bodoni Moda y Mulish).
- Funciones: filtro de pozas por temperatura; armador de visita (fecha, turno, paquete, personas y extras) con recargos de fin de semana y noche, cupo simulado por turno, martes cerrado y pedido por WhatsApp que se bloquea si no hay cupo; estado abierto/cerrado y día resaltado según hora de Chile; preguntas frecuentes.
- Sin fotografías: ilustraciones SVG propias, porque `images.unsplash.com` sigue respondiendo 403 desde el entorno. Registrado en `CREDITOS.md`.
- Tarjeta en el portafolio (23 diseños) y captura `img/termas.jpg` (1200×800, 53 KB).

### Sugerencias pendientes para René
- Los cupos de Vapor Sur son una simulación determinista; un cliente real necesitaría un calendario conectado. Conviene decírselo al mostrar la demo.
- Verificar que el nombre "Vapor Sur" no coincida con un negocio real antes de usarlo con un cliente; los datos de salud de las preguntas frecuentes son genéricos y un cliente real debe validarlos.
- Agregar fotos de Unsplash verificadas (portada y pozas) cuando haya acceso al dominio.
- La captura se generó sin las tipografías de Google Fonts (bloqueadas) y muestra el aviso de demo; conviene regenerarla desde un navegador con acceso total.
- Currículum: agregar teléfono o LinkedIn y logros medibles si quieres; no se inventaron datos.
- Las solicitudes #31 a #38 siguen abiertas y encadenadas: conviene revisarlas y fusionarlas en orden.

## 2026-11-11 (mejora diaria: demo de hostal)

Esta rama parte desde la del 10 de noviembre (solicitud #37, aún abierta, que a su vez incluye la #36, la #35, la #34, la #33, la #32 y la #31), para no duplicar trabajo ni generar conflictos.

### Currículum (`index.html`)
- Formularios: `accent-color` con el azul del currículum, para que los controles nativos del formulario de WhatsApp (selectores, casillas) combinen con la identidad visual.
- No se modificó texto, secciones, datos de contacto ni identidad visual.

### Revisión de demos y portafolio
- Se revisaron las 24 páginas (currículum, portafolio y 22 demos) a 320, 390 y 1440 px: sin desplazamiento horizontal, sin errores de JavaScript, sin respuestas 404, sin anclas rotas, aviso de datos ficticios en todas las demos, páginas bajo 60 KB e imágenes bajo 300 KB. No hubo correcciones necesarias en las demos existentes.

### Demo nueva
- `hostal/`: Radal, hostal familiar ficticio en Valdivia (oliva, mostaza y teja; tipografías Caprasimo y Lexend).
- Funciones: armador de reserva (llegada, noches, personas, habitación y extras, con total en CLP, cupo por noche y solicitud por WhatsApp que se bloquea si no hay cupo); tira de cupos de 7 días; filtro de "qué hacer cerca" según cómo te muevas; preguntas frecuentes; estado de recepción abierta/cerrada y día resaltado según hora de Chile.
- Sin fotografías: ilustraciones SVG propias, porque `images.unsplash.com` sigue respondiendo 403 desde el entorno y no se podían verificar identificadores nuevos. No hay fotos nuevas que registrar en `CREDITOS.md`.
- Tarjeta en el portafolio (22 diseños) y captura `img/hostal.jpg` (1200×800, 69 KB).

### Sugerencias pendientes para René
- Los cupos de Radal son una simulación determinista (no hay base de datos); un cliente real necesitaría un calendario conectado o actualizado a mano. Conviene decírselo al mostrar la demo.
- Reemplazar las ilustraciones SVG de las demos sin fotos por fotos de Unsplash verificadas cuando haya acceso; en Radal bastaría una foto de fachada o de patio en portada.
- El nombre "Radal" es ficticio, pero es un árbol nativo y podría coincidir con algún negocio real; si lo usas con un cliente, verifica que no haya conflicto.
- Las capturas se generan sin las tipografías de Google Fonts (bloqueadas en el entorno); conviene regenerarlas desde un navegador con acceso total.
- Currículum: agregar teléfono o LinkedIn y logros medibles si quieres; no se inventaron datos.
- Las solicitudes #31 a #37 siguen abiertas y encadenadas: conviene revisarlas y fusionarlas en orden para que esta no crezca más.

## 2026-11-10 (mejora diaria: demo de heladería artesanal)

Esta rama parte desde la del 9 de noviembre (solicitud #36, aún abierta, que a su vez incluye la #35, la #34, la #33, la #32 y la #31), para no duplicar trabajo ni generar conflictos.

### Currículum (`index.html`)
- Estabilidad visual: `scrollbar-gutter: stable` evita que el contenido "salte" cuando aparece o desaparece la barra de desplazamiento.
- Móvil: color de resaltado al tocar enlaces y botones (`-webkit-tap-highlight-color`) acorde al azul del currículum, en vez del gris por defecto.
- No se modificó texto, secciones, datos de contacto ni identidad visual.

### Revisión de demos y portafolio
- Se revisaron las 23 páginas (currículum, portafolio y 21 demos) a 320, 390 y 1440 px: sin desplazamiento horizontal, sin errores de JavaScript, sin respuestas 404, sin anclas rotas, aviso de datos ficticios en todas las demos y páginas bajo 60 KB. No hubo correcciones necesarias en las demos existentes.

### Demo nueva
- `heladeria/`: Maqui, heladería artesanal ficticia en Panguipulli (ciruela, maqui, rosa y limón; tipografías Bagel Fat One y Nunito Sans).
- Funciones: armador de helado (formato, sabores según el formato y toppings, con vista previa, total en CLP y pedido por WhatsApp); carta de 14 sabores filtrable (cremas / sorbetes sin lácteos); estado abierto/cerrado y día resaltado según hora de Chile.
- Sin fotografías: ilustraciones SVG propias, porque `images.unsplash.com` sigue respondiendo 403 desde el entorno y no se podían verificar identificadores nuevos. No hay fotos nuevas que registrar en `CREDITOS.md`.
- Tarjeta en el portafolio (21 diseños) y captura `img/heladeria.jpg` (1200×800, 61 KB).

### Sugerencias pendientes para René
- Reemplazar las ilustraciones de las demos sin fotos (Maqui, Cuarto Claro, Lenga, Lleuque, taller, barbería, Mañío, Aire Sur) por fotos de Unsplash verificadas cuando haya acceso; en Maqui conviene una foto de portada de helados reales.
- Los precios y sabores de Maqui son de ejemplo; un cliente real debería ajustar el aviso de alérgenos (frutos secos, lácteos) con su propia información.
- Las capturas se generan sin las tipografías de Google Fonts (bloqueadas en el entorno); conviene regenerarlas desde un navegador con acceso total.
- Currículum: agregar teléfono o LinkedIn y logros medibles si quieres; no se inventaron datos.
- Las solicitudes #31 a #36 siguen abiertas y encadenadas: conviene revisarlas y fusionarlas en orden para que esta no crezca más.

## 2026-11-09 (mejora diaria: demo de estudio fotográfico)

Esta rama parte desde la del 8 de noviembre (solicitud #35, aún abierta, que a su vez incluye la #34, la #33, la #32 y la #31), para no duplicar trabajo ni generar conflictos.

### Currículum (`index.html`)
- Metaetiquetas: se agrega `og:site_name` para que al compartir el enlace se muestre el nombre.
- Robustez en móvil: `overflow-wrap: break-word` en el cuerpo, para que correos o textos largos no provoquen desplazamiento horizontal a 320 px.
- No se modificó texto, secciones, datos de contacto ni identidad visual.

### Revisión de demos y portafolio
- Se revisaron las 22 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, sin errores de JavaScript, sin enlaces, anclas ni imágenes locales rotas, aviso de datos ficticios en todas las demos y páginas bajo 60 KB. No hubo correcciones necesarias en las demos existentes.

### Demo nueva
- `fotografia/`: Cuarto Claro, estudio fotográfico ficticio en Valdivia (negro, cobalto y hueso; tipografías Syne y Albert Sans).
- Funciones: armador de sesión (tipo, horas, fotos editadas y extras, con total en CLP y envío por WhatsApp); comparador deslizable de foto sin editar / editada; galería filtrable por categoría; calendario de reserva con días y horas libres; estado abierto/cerrado según hora de Chile.
- Sin fotografías: ilustraciones SVG propias, porque `images.unsplash.com` sigue respondiendo 403 desde el entorno y no se podían verificar identificadores nuevos.
- Tarjeta en el portafolio (20 diseños) y captura `img/fotografia.jpg` (1200×800, 73 KB).

### Sugerencias pendientes para René
- Reemplazar las ilustraciones de las demos sin fotos (Cuarto Claro, Lenga, Lleuque, taller, barbería, Mañío, Aire Sur) por fotos de Unsplash verificadas cuando haya acceso; en esta demo bastaría cambiar los `<use>` de la galería por `<img>`.
- Los nombres de las personas del equipo de Cuarto Claro son ficticios y están rotulados así.
- Currículum: agregar teléfono o LinkedIn y logros medibles si quieres; no se inventaron datos.
- Las capturas se generan sin las tipografías de Google Fonts (bloqueadas en el entorno); conviene regenerarlas desde un navegador con acceso total.

## 2026-11-08 (mejora diaria: demo de estudio contable)

Esta rama parte desde la del 7 de noviembre (solicitud #34, aún abierta, que a su vez incluye la #33, la #32 y la #31), para no duplicar trabajo ni generar conflictos.

### Currículum (`index.html`)
- Accesibilidad: los separadores "·" de la línea de títulos se marcan como decorativos (`aria-hidden`), para que los lectores de pantalla no los lean.
- No se modificó texto, secciones, datos de contacto ni identidad visual.

### Revisión de demos y portafolio
- Se revisaron las 21 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, sin errores de JavaScript, sin enlaces, anclas ni imágenes locales rotas, aviso de datos ficticios en todas las demos y páginas bajo 60 KB. No hubo correcciones necesarias en las demos existentes.

### Demo nueva
- `contable/`: Lenga Asesorías, estudio contable y tributario ficticio en Paillaco (burdeos, latón y papel; tipografías Newsreader y Schibsted Grotesk).
- Funciones: cotizador de plan mensual (tipo de contribuyente, documentos, trabajadores y agregados, con neto y total con IVA) y envío por WhatsApp; calculadora de IVA neto/bruto; lista de documentos con avance y aviso por WhatsApp; reserva de reunión con días y horas disponibles; estado abierto/cerrado según hora de Chile.
- Sin fotografías: ilustraciones SVG/CSS propias, porque `images.unsplash.com` sigue respondiendo 403 desde el entorno.
- Tarjeta en el portafolio (19 diseños) y captura `img/contable.jpg` (1200×800, 81 KB).

### Sugerencias pendientes para René
- Reemplazar las ilustraciones de las demos sin fotos (Lenga, Lleuque, taller, barbería, Mañío, Aire Sur) por fotos de Unsplash verificadas cuando haya acceso.
- Las fechas del calendario tributario de Lenga (día 12, día 20 en línea, abril) son referenciales; un cliente real debe confirmarlas cada año.
- Currículum: agregar teléfono o LinkedIn y logros medibles si quieres; no se inventaron datos.
- Las capturas se generan sin las tipografías de Google Fonts (bloqueadas en el entorno); conviene regenerarlas desde un navegador con acceso total.

## 2026-11-07 (mejora diaria: demo de ferretería)

Esta rama parte desde la del 6 de noviembre (solicitud #33, aún abierta, que a su vez incluye la #32 y la #31), para no duplicar trabajo ni generar conflictos.

### Currículum (`index.html`)
- Impresión: los títulos de sección y de cargo ya no quedan solos al final de una página (`break-after: avoid`) y se evitan líneas sueltas (huérfanas y viudas).
- Accesibilidad: en modo de alto contraste de Windows, el anillo de foco usa el color del sistema.
- No se modificó texto, secciones, datos de contacto ni identidad visual.

### Revisión de demos y portafolio
- Se revisaron las 20 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, sin errores de JavaScript, sin enlaces, anclas ni imágenes locales rotas, aviso de datos ficticios en todas las demos y páginas bajo 60 KB. No hubo correcciones necesarias en las demos existentes.

### Demo nueva
- `ferreteria/`: Lleuque, ferretería ficticia en Río Bueno (azul petróleo, rojo óxido y papel; tipografías Bricolage Grotesque, Public Sans y DM Mono).
- Funciones: calculadora de materiales (cerco, radier, pintura de muros, cajones de huerto) con holgura opcional y total en CLP; catálogo de 29 productos con filtros y búsqueda; pedido con cantidades, entrega (despacho urbano gratis desde $60.000) y envío por WhatsApp sin número fijo; estado abierto/cerrado según hora de Chile.
- Sin fotografías: ilustraciones SVG propias, porque `images.unsplash.com` sigue respondiendo 403 desde el entorno y no se podían verificar identificadores nuevos.
- Tarjeta en el portafolio (18 diseños) y captura `img/ferreteria.jpg` (1200×800, 103 KB).

### Sugerencias pendientes para René
- Reemplazar las ilustraciones de Lleuque (y de taller, barbería, Mañío y Aire Sur) por fotos reales o de Unsplash verificadas cuando haya acceso a `images.unsplash.com`.
- Currículum: agregar teléfono o LinkedIn y logros medibles si quieres; no se inventaron datos.
- Las capturas del portafolio se generan sin las tipografías de Google Fonts (bloqueadas en el entorno); conviene regenerarlas desde un navegador con acceso total.
- Las cantidades de la calculadora de Lleuque son aproximadas; un cliente real debería validarlas con su propio maestro.

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
