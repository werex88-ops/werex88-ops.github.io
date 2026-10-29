# Registro de cambios

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
