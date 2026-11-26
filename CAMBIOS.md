# Registro de cambios

## 2026-11-26 (mejora diaria)

Parte desde la rama de la solicitud abierta #53 (`claude/mejora-2026-11-25`); esta solicitud depende de ella hasta que se fusione.

### Referencias de competencia
- Yoga en Valdivia (2x3, AgendaPro, ClassPass): solo agregadores; muestran clases sueltas y piden elegir una por una. Idea aplicada en Aire Sur: proponer una semana completa según el objetivo.
- Contabilidad para pymes en Chile (contable.app, Lofwork, 2x3): ofrecen "todo incluido" sin decir qué pasa el primer mes. Idea aplicada en Lenga: mostrar qué llevar y qué ocurre después de la primera reunión. No se copió texto.
- Velas de soya (Falabella, Easy, Paris) y plantas de interior (Sodimac, Lider): fichas de producto sin ayuda de uso. Ideas aplicadas: duración de la vela en noches y diagnóstico de plantas por síntoma.

### Currículum
Sin cambios hoy: ya tiene barra de avance, línea de tiempo y navegación activa; prioricé las demos.

### Portafolio
- Insignia «Mejorada hoy» ahora en Aire Sur, Lenga, Luz de Cera y Raíz Verde (se quitó de las cuatro de ayer) y descripciones actualizadas.

### Demos tocadas (4)
- `yoga/` (Aire Sur): sección «Arma tu semana de práctica» (objetivo × veces por semana × horario → clases reales del horario repartidas en la semana, minutos totales y mensaje por WhatsApp); enlace «Tu semana».
- `contable/` (Lenga): sección «Llega con esto» con lista de 6 papeles para la primera reunión, barra de avance, qué pasa después y aviso por WhatsApp que dice lo que ya tienes y lo que falta; enlace «Reunión».
- `velas/` (Luz de Cera): calculadora «¿Cuántas noches te dura una vela?» (horas por noche → noches, fecha estimada y barra de llamas) con foto nueva; enlace «Duración».
- `plantas/` (Raíz Verde): sección «Mi planta se ve mal» con 5 síntomas, causa probable, tres pasos y mensaje por WhatsApp para enviar una foto; foto nueva; enlace «SOS».
- Fotos nuevas (velas y plantas) registradas en `demos/CREDITOS.md`. No regeneré capturas `demos/img/*.jpg`.

### Validación
27 páginas a 320, 390 y 1440 px con recursos externos bloqueados: sin errores de JavaScript, desplazamiento horizontal ni anclas rotas; una sola etiqueta `<main>` y aviso de datos ficticios en cada demo. Probé con clics las cuatro funciones y vi capturas (con la foto reemplazada por una de prueba).

### Sugerencias para René
- Las fotos nuevas van enlazadas (descarga bloqueada aquí) y se ocultan si fallan; revisa en el navegador que carguen.
- Los plazos de la primera reunión, las rutinas de cuidado de plantas y la duración de las velas son ejemplos ficticios; con un cliente real hay que ajustarlos.
- Próxima rotación: mascotas, cabañas, kayak, centro cultural, navidad y las de más tiempo sin tocar. Currículum: sigue pendiente teléfono o LinkedIn y logros medibles (no se inventaron datos).

## 2026-11-25 (mejora diaria)

Parte desde `main` (no había solicitudes abiertas; la #52 ya está fusionada).

### Referencias de competencia
- Gimnasios de Valdivia (Wellhub, ClassPass, AgendaPro): solo fichas de agregadores; destacan la clase de prueba y el horario visible. Idea aplicada en Forja: contar qué pasa en la primera visita, que es la duda de quien nunca ha entrenado.
- Sushi de Valdivia (Uber Eats, Wanderlog) y carpinterías de Los Ríos (2x3, Yapo, notas de La Tercera y DF sobre el auge de la carpintería): no abrí sitios propios de negocios; el aporte fue la idea de explicar el oficio y el cuidado de las piezas, no solo venderlas. No se copió texto ni imágenes.

### Currículum
Sin cambios hoy: priorizo las demos más antiguas de la rotación.

### Portafolio
- Insignia «Mejorada hoy» ahora en Kaiyō, Mañío, Forja y Horno Pellín (se quitó de las cuatro de ayer) y descripciones actualizadas. Pesa 62 KB (límite 90 KB).

### Demos tocadas (4)
- `sushi/` (Kaiyō): sección «Cómo se come» (nigiri con la mano, soya solo por el pescado, wasabi, jengibre) con foto de un chef armando sushi; enlace en el menú.
- `madera/` (Mañío): sección «¿Cada cuánto hay que aceitar tu pieza?» (pieza × ubicación → frecuencia, producto y calendario de 12 meses); enlace «Cuidados».
- `panaderia/` (Horno Pellín): tercera foto en la franja (manos amasando) y sección «¿Cómo guardo mi pan para mañana?» (campo, marraqueta, kuchen, empanadas); enlace «Guardar».
- `gimnasio/` (Forja): sección «Qué pasa cuando llegas» (4 pasos de la primera visita) con foto de barra en un rack; enlace «Primera visita».
- Fotos nuevas registradas en `demos/CREDITOS.md`. No regeneré capturas `demos/img/*.jpg`.

### Validación
27 páginas a 320, 390 y 1440 px con recursos externos bloqueados: sin errores de JavaScript, desplazamiento horizontal ni anclas rotas; una sola etiqueta `<main>` y aviso de datos ficticios en cada demo. Probé con clics las funciones de madera y panadería (encontré y corregí un choque de selectores en madera). Demos bajo 60 KB (sushi 32 KB, madera 43 KB, panadería 45 KB, gimnasio 35 KB).

### Sugerencias para René
- Las descargas de Unsplash siguen bloqueadas aquí: las 3 fotos nuevas van enlazadas y se ocultan si fallan. Revisa en el navegador que carguen.
- Frecuencias de aceitado, duración del pan y pasos de la visita son orientativos y ficticios; con un cliente real hay que ajustarlos.
- Próxima rotación: yoga, contable, velas, plantas, mascotas, cabañas y kayak. Currículum: sigue pendiente teléfono o LinkedIn y logros medibles (no se inventaron datos).

## 2026-11-24 (mejora diaria)

Parte desde la rama de la solicitud abierta #51 (`claude/mejora-2026-11-23`), que incluye las #49 y #50; esta solicitud depende de ellas hasta que se fusionen.

### Referencias de competencia
- Cafeterías de Valdivia: la búsqueda solo devolvió agregadores (Wanderlog, Foursquare, ClassPass), no sitios propios; poca profundidad hoy. Idea aplicada: pedido para retirar, que ahorra la fila.
- Shopify, "21 portafolios de diseño web memorables" y Seahawk, tendencias de portafolios: movimiento sutil, tarjetas con respuesta al cursor y señales claras de qué es nuevo. Idea aplicada en el portafolio. No se copió texto ni código.
- Taller, termas y ferretería: sin referencias de negocios reales hoy.

### Currículum
Sin cambios hoy: ya tiene barra de avance, línea de tiempo y navegación que marca la sección activa; priorizé las demos.

### Portafolio
- Barra de avance de color arriba de la página, inclinación 3D de las tarjetas al pasar el cursor (solo con mouse y sin `prefers-reduced-motion`) e insignia «Mejorada hoy» en las cuatro demos tocadas.
- Descripciones actualizadas de Grano & Calma, Newen, Vapor Sur y Lleuque. Pesa 62 KB (límite 90 KB).

### Demos tocadas (4)
- `cafeteria/` (Grano & Calma): ahora está en Valdivia (antes decía Barrio Italia, que es de Santiago); quité la cifra inventada de reseñas; sección «Pide y retira» con cantidades, total, nombre y hora, y mensaje de WhatsApp armado; foto nueva; 3 preguntas nuevas.
- `taller/` (Newen): sección «¿Qué le toca a mi auto?» (kilometraje con deslizador × bencina o diésel → revisiones que vienen, cuáles tocan ya y total referencial; pide hora por WhatsApp); enlace «Mantención» en el menú.
- `termas/` (Vapor Sur): sección «¿Cuándo hay menos gente?» (día de la semana → barras de ocupación por turno y consejo; abre en el día de hoy); enlace «Cuándo ir».
- `ferreteria/` (Lleuque): «La lista de mayo» para preparar la casa para el invierno (7 tareas con casillas, barra de avance, total de lo que falta y pedido por WhatsApp); enlace «Invierno».
- Foto nueva registrada en `demos/CREDITOS.md` (cafetería). No regeneré capturas `demos/img/*.jpg`.

### Validación
25 páginas a 320, 390 y 1440 px con recursos externos bloqueados: sin errores de JavaScript, 404 locales ni anclas rotas; una sola etiqueta `<main>` y aviso de datos ficticios en cada demo. Corregí un desborde horizontal a 320 px en termas. Probé con clics las cuatro funciones nuevas y vi capturas. Demos bajo 60 KB (cafetería 34 KB, taller 42 KB, termas 45 KB, ferretería 54 KB); currículum 53 KB y portafolio 62 KB.

### Sugerencias para René
- Intervalos de mantención, ocupación de las termas, precios y lista de invierno son ejemplos ficticios; con un cliente real hay que ajustarlos.
- Revisa en el navegador que la foto nueva de la cafetería cargue (aquí estaba bloqueada; sin ella se ve un degradado café).
- Pendiente: más fotos de contexto para demos que aún usan ilustraciones; próxima rotación: centro cultural, navidad, cabañas, kayak, yoga y las que llevan más tiempo sin cambios.
- Currículum: sigue pendiente agregar teléfono o LinkedIn y logros medibles (no se inventaron datos).

## 2026-11-23 (mejora diaria)

Parte desde la rama de la solicitud abierta #50 (`claude/mejora-2026-11-22`), que a su vez incluye la #49; esta solicitud depende de ellas hasta que se fusionen.

### Referencias de competencia
- Barberías de Valdivia (Fresha, AgendaPro): solo vi agregadores de reservas; muestran servicios con duración y precio y piden elegir profesional antes de la hora. Ya lo teníamos; idea aplicada en Tricahue: decirle al cliente cada cuántas semanas conviene volver. No se copió texto.
- Hostales de Valdivia (Kayak, Expedia, Hotels.com): fichas con precio por noche sin contexto de temporada. Idea aplicada en Radal: guía mes a mes de clima, qué hacer y anticipación para reservar. No abrí sitios propios de hostales; poca profundidad hoy.
- Heladerías y estudios fotográficos: sin referencias nuevas hoy.

### Currículum
- Nueva "línea de tiempo" visual (2007 a hoy) al inicio de Trayectoria: ocho barras con los cargos y períodos que ya figuran en el currículum, que crecen al hacer scroll. Se oculta al imprimir (A4 intacta), respeta `prefers-reduced-motion` y es decorativa (`aria-hidden`); el contenido textual no cambió. Un cargo termina "2025" sin mes en el currículum: lo dibujé hasta marzo 2025, cuando empieza el actual.

### Portafolio
- Actualicé las descripciones de las tarjetas de Radal, Cuarto Claro, Tricahue y Maqui (incluida la diapositiva del carrusel). Sin cambios de diseño hoy.

### Demos tocadas (4)
- `barberia/` (Tricahue): sección "¿Cada cuánto volver?" (6 estilos → semanas, semana sugerida con fecha calculada y barra); 2 preguntas nuevas (que dure el degradado, foto de referencia).
- `fotografia/` (Cuarto Claro): sección "Cuántas fotos te hacen falta" (5 usos → sesión, horas, fotos y valor referencial calculado con la misma lista de precios del armador); nueva sección de preguntas (ropa, fotos que no gustan, uso comercial, lluvia).
- `heladeria/` (Maqui): calculadora "¿Cuántos potes para tu once o cumpleaños?" (personas × bolitas → litros, potes, sabores y total con los precios de la carta; pedido por WhatsApp); 2 preguntas nuevas.
- `hostal/` (Radal): guía "Cómo es Valdivia mes a mes" (12 meses, abre en el mes actual: temporada, clima, qué hacer, anticipación); 2 preguntas nuevas (mes sin lluvia, equipaje).
- No agregué fotos nuevas (no pude verificar identificadores de Unsplash hoy), así que `demos/CREDITOS.md` no cambia. No regeneré capturas `demos/img/*.jpg`.

### Validación
25 páginas a 320, 390 y 1440 px con recursos externos bloqueados: sin desplazamiento horizontal, errores de JavaScript, 404 locales ni anclas rotas; una sola etiqueta `<main>` y aviso de datos ficticios en cada demo. Probé con clics las cuatro funciones y vi capturas, y vi la línea de tiempo a 390 y 1200 px. Demos bajo 60 KB (barbería 41 KB, fotografía 48 KB, heladería 36 KB, hostal 45 KB); currículum 53 KB y portafolio 61 KB (límite 90 KB).

### Sugerencias para René
- Los plazos de recorte, cantidades de helado, clima y temporadas son referenciales y ficticios; si se usan con un cliente real hay que ajustarlos a su negocio.
- Pendiente: el portafolio necesita un rediseño visual más notorio (hoy solo se mantiene); próxima rotación de demos: cafetería, taller, termas, ferretería y las que llevan más tiempo sin cambios.
- Fotos de contexto: sigo sin poder verificar identificadores de Unsplash; conviene revisar a mano cuáles demos aún usan ilustraciones.
- Currículum: sigue pendiente agregar teléfono o LinkedIn y logros medibles (no se inventaron datos); confirma el mes de término del cargo en Cecrea.

## 2026-11-22 (mejora diaria)

Parte desde la rama de la solicitud abierta #49 (`claude/mejora-2026-11-21`), porque aún no se fusiona; esta solicitud depende de ella.

### Referencias de competencia
- Meteored, "Pasaporte Cervecero de Valdivia": las cervecerías locales se presentan por ruta y sellos; ya teníamos el pasaporte en Hualle. Idea aplicada: guía de maridaje de mesón. No se copió texto.
- Veterinarias de Valdivia (AgendaPro, directorios 2x3 y Cronoshare): destacan visitas a domicilio, precios de consulta y reserva en línea. Idea aplicada en Weñi: precio de consulta y lista de qué llevar. Solo vi agregadores, no sitios de negocios; poca profundidad hoy.
- Centro cultural y navidad: sin referencias nuevas hoy.

### Currículum
Sin cambios hoy (priorizé las demos).

### Portafolio
- Actualicé las descripciones de las tarjetas de Hualle, Weñi, Ribera y Estrella Austral.

### Demos tocadas (4)
- `cerveceria/` (Hualle): sección "¿Qué tomo con lo que voy a comer?" (6 comidas → cerveza, estilo, precio y por qué) con foto de estanque; 3 preguntas nuevas (sin alcohol, growler, pago); enlace "Maridaje".
- `centro-cultural/` (Ribera): sección "¿Dónde me siento?" (4 prioridades → zona de la sala y valor) con foto de butacas; 3 preguntas nuevas (cafetería, llegar tarde, guardarropa); enlace "Butacas".
- `navidad/` (Estrella Austral): calendario "¿Para cuándo lo quieres encendido?" (tipo de trabajo × fecha → fechas para confirmar, visita, instalación); 2 preguntas nuevas (lluvia, retiro); enlace "Fechas".
- `veterinaria/` (Weñi): lista marcable "¿Qué llevo a la consulta?" (perro, gato, conejo o ave) con avance; 2 preguntas nuevas (precio de consulta, domicilio); enlace "Qué llevar".
- Fotos nuevas: 2, registradas en `demos/CREDITOS.md`. No regeneré capturas `demos/img/*.jpg`.

### Validación
Las 4 demos tocadas a 320, 390 y 1440 px con recursos externos bloqueados: sin desplazamiento horizontal, errores de JavaScript ni anclas rotas; una sola etiqueta `<main>`. Probé con clics las cuatro funciones y vi capturas. Todas bajo 60 KB (cervecería 39 KB, centro cultural 43 KB, navidad 49 KB, veterinaria 51 KB). No volví a renderizar las demás páginas.

### Sugerencias para René
- Las fotos nuevas no las pude ver; revisa que carguen y que no muestren personas ni un recinto reconocible (la de butacas es de un teatro sin identificar).
- Precios, plazos, butacas y recomendaciones son ejemplos ficticios.
- Pendiente: el currículum y el portafolio llevan varios días sin cambios visuales grandes; próxima rotación: barbería, fotografía, heladería, hostal. Falta teléfono o LinkedIn y logros medibles en el currículum (no se inventaron datos).

## 2026-11-21 (mejora diaria)

Parte desde `main` (no había solicitudes abiertas hacia `main`).

### Referencias de competencia
- 2x3.cl (directorio de contadores y asesorías en Valdivia y otras ciudades) y contable.app: las asesorías contables explican en lenguaje simple qué incluye cada servicio, muestran precios o rangos y avisan fechas de vencimiento. Idea aplicada en Lenga: lista interactiva de papeles para la primera reunión y preguntas sobre atrasos y cambio de contador. No se copió texto.
- Fichas de cabañas en Lago Ranco y Futrono (interpatagonia.com, Airbnb): destacan tipo de cama, tinaja, distancia al lago y cómo llegar; los alojamientos se eligen por quién viaja. Idea aplicada en Alerce Dormido: test «¿cuál cabaña te conviene?» y recorrido de un día. No abrí sitios de negocios individuales; poca profundidad hoy.
- Yoga y kayak: sin referencias nuevas hoy.

### Currículum
Sin cambios hoy (priorizé las demos). Sigue con barra de progreso, chips en cascada y versión A4.

### Portafolio
- Actualicé las descripciones de las tarjetas de cabañas, kayak, yoga y contable con las funciones nuevas. Pesa 60 KB (límite 90 KB). Sin cambios visuales mayores hoy.

### Demos tocadas (4)
- `cabanas/` (Alerce Dormido): test «¿Cuál cabaña te conviene?» (con quién vienes × qué buscas → recomendación con foto y botón que preselecciona la calculadora); sección «Así se pasa un sábado» con horarios y foto en banda; 3 preguntas nuevas (leña y desayuno, llegada tardía, niños); enlace en el menú.
- `kayak/` (Mawün Kayak): «¿Qué me pongo para remar?» (época × clima → lista de ropa y nota sobre la temperatura del agua); 2 preguntas nuevas (baño y cambiador, ir solo); enlace «Qué llevar».
- `yoga/` (Aire Sur): «¿Por dónde empiezo?» (cómo llegas × experiencia → clase sugerida y horario de ejemplo); sección de 6 preguntas frecuentes (mat, ropa, flexibilidad, cancelación, embarazo y lesiones); enlace «Empieza».
- `contable/` (Lenga): «¿Qué papeles traigo?» (tipo de negocio → checklist marcable con barra de avance); sección de 6 preguntas frecuentes (cambio de contador, atrasos de IVA, plan, entrega de información, plazo del IVA); enlace «Papeles».
- Fotos: 3 de cabañas en `demos/CREDITOS.md`. No regeneré capturas `demos/img/*.jpg`.

### Validación
Las 4 demos tocadas a 320, 390 y 1440 px con recursos externos bloqueados: sin desplazamiento horizontal, errores de JavaScript ni anclas rotas; una sola etiqueta `<main>` y aviso de datos ficticios. Corregí un desborde propio en yoga (los radios ocultos heredaban el ancho global de `input`). Probé con clics las cuatro funciones nuevas y vi capturas de yoga y contable. Todas bajo 60 KB (cabañas 46 KB, kayak 40 KB, yoga 44 KB, contable 44 KB). No volví a renderizar las otras 21 páginas, que no cambiaron.

### Sugerencias para René
- Revisa en el navegador que las 3 fotos nuevas de cabañas carguen y que se vean del sur de Chile; no pude verlas, así que no sé si hay personas ni dónde fueron tomadas.
- Horarios, plazos de cancelación, fechas de IVA y recomendaciones de ropa son ejemplos; con un cliente real hay que validarlos. Las preguntas de embarazo/lesiones en yoga deben revisarlas la instructora.
- Pendiente: currículum y portafolio llevan varios días sin cambios visibles grandes; próxima rotación: centro-cultural, navidad, cerveceria, veterinaria. Falta agregar teléfono o LinkedIn y logros medibles al currículum (no se inventaron datos).

## 2026-11-20 (mejora diaria)

Parte desde `main` (no había solicitudes abiertas desde ramas `claude/...`; la #47 ya está fusionada).

### Referencias de competencia
- Artículo de Shopify sobre portafolios de diseño web memorables: los mejores abren con un mensaje directo, muestran el trabajo a todo color, usan acentos de color sobre fondo neutro y ponen el contacto a pocos pasos; el movimiento aparece en tarjetas y al pasar el cursor, con moderación. Ya lo cumplimos en gran parte; idea aplicada: describir en cada tarjeta la función concreta de la demo.
- Gimnasios de Valdivia: la búsqueda solo devolvió agregadores (Wellhub, AgendaPro, ClassPass); no abrí sitios de negocios. Idea propia: ayudar a decidir cuántos días entrenar antes de elegir plan.
- Poca investigación hoy en velas, plantas y mascotas (sin referencias nuevas).

### Currículum
- Los chips de competencias aparecen en cascada al hacer scroll (desactivado con `prefers-reduced-motion` y al imprimir). Contenido y versión A4 sin cambios.

### Portafolio
- Las tarjetas de gimnasio, velas, plantas y mascotas describen ahora las funciones nuevas. Pesa 60 KB (límite 90 KB).

### Demos tocadas (4)
- `gimnasio/` (Forja): sección "¿Cuántos días te sirven?" (días por semana × objetivo → semana de ejemplo y plan sugerido); 3 preguntas nuevas; enlace "Tu rutina" en el menú.
- `velas/` (Luz de Cera): test "¿Qué aroma te toca?" (dónde la prendes × olores que te gustan → vela recomendada con precio); 2 preguntas nuevas sobre duración y vaso ennegrecido.
- `plantas/` (Raíz Verde): guía "¿Cada cuánto la riego?" (planta × estación → frecuencia); enlace "Riego" en el menú.
- `mascotas/`: sección "Se hornea el mismo día" (tres pasos de producción) y 3 preguntas nuevas (porciones, congelar, alergia al pollo).
- No agregué fotos nuevas (estas demos ya tenían las suyas), así que `demos/CREDITOS.md` no cambia. No regeneré capturas.

### Validación
25 páginas a 320, 390 y 1440 px con recursos externos bloqueados: sin desplazamiento horizontal, errores de JavaScript, 404 locales ni anclas rotas; una sola etiqueta `<main>` y aviso de datos ficticios en cada demo. Probé con clics las tres funciones nuevas. Todas las demos bajo 60 KB; currículum 50 KB.

### Sugerencias para René
- Precios, frecuencias de riego, porciones y descuentos nuevos son ejemplos ficticios; las pautas de riego y de porciones para mascotas deberían validarlas especialistas si se usan con un cliente real.
- Pendiente: portafolio con carrusel y filtros ya completo; falta fotos de contexto para las demos que aún usan ilustraciones (no pude verificar identificadores de Unsplash hoy).
- Próxima rotación de demos: cabañas, kayak, yoga, contable.
- Currículum: sigue pendiente agregar teléfono o LinkedIn y logros medibles; no se inventaron datos.

## 2026-11-19 (mejora diaria)

Parte desde `main` (no había solicitudes abiertas desde ramas `claude/...`; la #46 ya está fusionada).

### Referencias de competencia
- Meteored, "Dónde encontrar pan de masa madre en Santiago": las panaderías destacan fermentación lenta, horarios visibles y pedido anticipado. Idea aplicada: en Pan de Paillaco, un calculador de encargo para la once y más preguntas sobre pedidos. No se copió texto.
- Búsquedas de ferretería, carpintería y sushi: solo devolvieron páginas de fotos y agregadores; no abrí sitios de negocios. Poca investigación en esos rubros hoy.

### Portafolio y currículum
Sin cambios hoy: priorizé las demos pendientes de la rotación.

### Demos tocadas (4)
- `sushi/` (Kaiyō): sección "¿Cuánto pido?" (personas × apetito → propuesta y precio referencial) con foto de tabla de sushi; 2 preguntas nuevas (duración del omakase, estacionamiento); corregí el pie de página, que decía Viña del Mar en vez de Valdivia; nuevo enlace en el menú.
- `ferreteria/` (Lleuque): sección "El consejo del mesón" (qué tornillo para madera, hormigón, zinc o yeso-cartón) con foto; 3 preguntas nuevas (ayuda para calcular, despacho, arriendo de herramientas); enlace "Consejos" en el menú.
- `madera/` (Mañío): sección "Qué madera elegir" (raulí, roble, lenga y pino seco: para qué sirve y qué cuidar) con foto de taller; 2 preguntas nuevas (plazo de una mesa, uso en exterior); enlace "Maderas" en el menú.
- `panaderia/` (Pan de Paillaco): calculador "¿Cuánto pan para la once?" con deslizador (2 a 30 personas) y total referencial; 3 preguntas nuevas (tortas, pago, cantidad para 6 personas).
- Fotos nuevas registradas en `demos/CREDITOS.md`. No regeneré capturas `demos/img/*.jpg`.

### Validación
27 páginas a 320, 390 y 1440 px con las fotos externas bloqueadas: sin desplazamiento horizontal, errores de JavaScript ni anclas rotas; una sola etiqueta `<main>` en cada demo. Probé las cuatro funciones nuevas con clics y vi capturas de sushi y madera con imagen de prueba. Todas las demos pesan menos de 60 KB; portafolio 60 KB y currículum 50 KB.

### Sugerencias para René
- Revisa en el navegador que las 3 fotos nuevas carguen (Unsplash; no pude verificar dónde fueron tomadas).
- Precios, cantidades y plazos nuevos son ejemplos ficticios.
- Pendiente: portafolio y currículum llevan dos jornadas sin cambios visibles; próxima rotación de demos: yoga, contable, gimnasio, velas, plantas, mascotas, cabañas, kayak.
- Currículum: sigue pendiente agregar teléfono o LinkedIn y logros medibles; no se inventaron datos.

## 2026-11-18 (mejora diaria)

Esta rama parte desde la del 17 de noviembre (solicitud #45, aún abierta), para no duplicar trabajo ni generar conflictos.

### Referencias de competencia
- Pasaporte Cervecero de Valdivia (nota de Meteored): pasaporte gratuito con mapa de 24 locales que se timbra en cada visita. Idea aplicada: en Hualle, un pasaporte de seis sellos (uno por cerveza) que se puede probar en la página. No se copió texto.
- Centro cultural: la búsqueda solo devolvió PDFs de revistas mensuales y notas de prensa; no abrí ninguna. Idea propia: recorrido sugerido según el tiempo disponible, útil para quien llega por primera vez.
- Poca investigación hoy en navidad y veterinaria (sin referencias nuevas).

### Portafolio y currículum
Sin cambios hoy: ya tienen carrusel, filtros, buscador, selector de color, barra de progreso y cinta animada. Prioricé las demos pendientes de la rotación.

### Demos tocadas (4)
- `cerveceria/` (Hualle): sección "Pasaporte Hualle" con foto de tanques de acero y seis sellos que se marcan al tocar; preguntas del mostrador (reserva, niños, tours, duración de la lata, venta a locales); nuevo enlace "Pasaporte" en el menú.
- `centro-cultural/`: sección "¿Cuánto tiempo tienes?" que arma un recorrido de 30 minutos, 1 hora o 2 horas.
- `navidad/`: cotizador rápido (tipo de espacio, metros, árbol opcional) con rango de precio referencial.
- `veterinaria/`: calendario de referencia por edad (cachorro, adulto, senior).
- Foto nueva registrada en `demos/CREDITOS.md`. No regeneré capturas `demos/img/*.jpg`.

### Validación
25 páginas a 320, 390 y 1440 px con las fotos externas bloqueadas: sin desplazamiento horizontal, errores de JavaScript, 404 locales ni anclas rotas; una sola etiqueta `<main>` y aviso de datos ficticios en cada demo. Probé las cuatro funciones nuevas con clics. Todas las demos pesan menos de 60 KB; portafolio 60 KB y currículum 50 KB (límite 90 KB).

### Sugerencias para René
- Revisa en el navegador que la foto de tanques de Hualle cargue. Es de Unsplash; no pude verificar dónde fue tomada.
- Los precios del cotizador de navidad, el premio del pasaporte y el calendario de vacunas son ejemplos ficticios; ajústalos si usas la demo con un cliente real (el de vacunas debe validarlo un veterinario).
- Próximas demos: panadería, sushi, ferretería, madera, yoga, contable.
- Currículum: sigue pendiente agregar teléfono o LinkedIn y logros medibles; no se inventaron datos.

## 2026-11-17 (mejora diaria)

Parte desde `main` (no había solicitudes abiertas desde ramas `claude/...`; la #43 y la #44 ya están fusionadas).

### Referencias de competencia
- chile.travel, "Termas de Los Ríos": estructura "Planifica tu viaje" con cómo llegar por aire y tierra y lista de qué llevar. Idea aplicada: en Vapor Sur, sección "Un turno, paso a paso" y preguntas sobre llegar sin auto y llevar comida. No se copió texto.
- Búsquedas de hostales en Valdivia: solo aparecieron agregadores (Kayak, Atrápalo, Hotels.com); no abrí ninguno. Poca investigación hoy, sin referencias de talleres ni heladerías.

### Portafolio y currículum
Sin cambios hoy (jornada acotada). Intenté agregar un botón "volver arriba" al currículum, pero ya existía; lo revertí.

### Demos tocadas (4)
- `hostal/` (Radal): sección "El desayuno" con foto y 2 preguntas nuevas (llegada tarde, wifi).
- `termas/` (Vapor Sur): sección "Un turno, paso a paso" con foto y 2 preguntas nuevas (sin auto, comida).
- `taller/`: sección "Antes de sacar la billetera, te mostramos la pieza" con foto y 2 preguntas nuevas (sin hora, auto de reemplazo).
- `heladeria/` (Maqui): sección "La fruta manda" (sabores por mes) con foto y sección de preguntas de mostrador (antes no tenía).
- Fotos registradas en `demos/CREDITOS.md`. No regeneré capturas `demos/img/*.jpg`.

### Validación
25 páginas a 320, 390 y 1440 px, con las fotos externas bloqueadas: sin desplazamiento horizontal ni errores de JavaScript. Todas las demos pesan menos de 60 KB.

### Sugerencias para René
- Revisa en el navegador que las 4 fotos nuevas carguen. La del sauna fue tomada en EE. UU. y se usa solo como ambiente; si prefieres una del sur de Chile, cámbiala.
- Los horarios y datos nuevos son ejemplos ficticios.
- Pendiente: más rotación de demos (centro-cultural, navidad, cerveceria, veterinaria, panaderia), y rediseño del portafolio y del currículum.

## 2026-11-16 (mejora diaria)

Esta rama parte desde la del 15 de noviembre (solicitud #43, aún abierta; incluye la #42), para no duplicar trabajo ni generar conflictos.

### Referencias de competencia
- Lofwork (lofwork.cl): consultora chilena para pymes. Tono tuteado y práctico, titulares que nombran el problema ("Página web para pyme: costos y decisión") y varios botones de WhatsApp con mensaje precargado. Idea aplicada: el formulario de "primera semana gratis" del gimnasio abre WhatsApp con el mensaje ya escrito.
- Ficha de un centro de entrenamiento de Valdivia en AgendaPro: lista 15 servicios sin precio, sin horario confiable y sin descripción del espacio. Idea aplicada: en Forja Gym los planes llevan precio, horarios y una explicación de cómo parte la primera semana, que es lo que esa ficha no entrega.
- Restaurantes de sushi de Valdivia: solo aparecieron fichas de Uber Eats y Wanderlog; no abrí ninguna. Poca investigación de sushi y cafetería hoy; siguen pendientes sitios propios de esos rubros.

### Portafolio (`demos/index.html`)
- Selector de color del portafolio (4 paletas: fuego, bosque, lago, frambuesa) en la barra superior; recuerda la elección. Se oculta bajo 400 px de ancho.
- Descripciones nuevas de las tarjetas de sushi y gimnasio. Peso: 60 KB (límite 90 KB).

### Currículum (`index.html`)
Dos mejoras visibles, sin tocar texto ni secciones: (1) selector de color de acento (azul, verde, violeta, terracota; todos con contraste AA sobre blanco), que recuerda la elección y no aparece al imprimir; (2) botón "Copiar correo" junto al correo en el contacto. Peso: 50 KB.

### Demos tocadas (4)
- `sushi/` (Kaiyō): ubicada en Valdivia, teléfono con código 63, textos más concretos (caleta en vez de "terminal pesquero", sin frases de folleto) y sección de preguntas (reserva, no como pescado crudo, alergias, delivery, niños, propina).
- `gimnasio/` (Forja): textos más directos (calefacción para la lluvia, coach que corrige la técnica), sección "Así parte tu semana" con formulario que abre WhatsApp, los botones de plan ahora llevan a ese formulario y preguntas frecuentes (congelar plan, estacionamiento, horario de noche).
- `cafeteria/` (Grano & Calma): titular y textos nuevos, sección "Pastel del día" que resalta el de hoy según el día de la semana (con foto de arte latte), preguntas frecuentes y dirección consistente (Barrio Italia).
- `mascotas/` (Pata Feliz): titular y textos más concretos, calculadora de porciones por tamaño del perro (con foto de perro en sendero) y preguntas frecuentes (edad, alergias, duración, despacho, pupcakes con nombre).
- No regeneré capturas `demos/img/*.jpg`: las portadas no cambiaron.

### Validación
25 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, errores de JavaScript, 404 locales ni anclas rotas; una sola etiqueta `<main>` y aviso de datos ficticios en cada demo. Las fotos externas no cargan desde el entorno (403); los cuadros de las fotos nuevas quedan con degradado y se ocultan si fallan. Todas las demos pesan menos de 60 KB.

### Sugerencias para René
- Revisa en el navegador que las dos fotos nuevas (café y perro) carguen y se vean bien.
- Los precios, horarios y condiciones nuevos (propina 10 %, bolsas de café $8.900, congelar plan 60 días) son ejemplos; ajústalos si usas la demo con un cliente real.
- Próximas demos: hostal, termas, taller, heladería.
- Currículum: sigue pendiente agregar teléfono o LinkedIn y logros medibles; no se inventaron datos.

## 2026-11-15 (mejora diaria)

Esta rama parte desde la del 14 de noviembre (solicitud #42, aún abierta), para no duplicar trabajo ni generar conflictos.

### Referencias de competencia
- LAB NAVE (labnave.com/portafolio): portafolio de agencia con filtros por industria y por capacidad, buscador por marca y contador de proyectos; cada tarjeta lleva una frase de objetivo, no una descripción larga. Idea aplicada: buscador por texto y contador "Mostrando X de 23" en el portafolio. No se copió texto ni código.
- Búsqueda de cabañas en Futrono, Panguipulli y Pucón: solo aparecieron fichas de Airbnb, Booking y Hotels.com; no abrí ninguna. Idea tomada de esas fichas: responder en preguntas concretas cuándo conviene ir y cómo se calefaccionan las cabañas. Poca investigación hoy; pendiente revisar sitios propios de cabañas.

### Portafolio (`demos/index.html`)
- Buscador por nombre, rubro o comuna (ignora tildes), combinado con los filtros por rubro.
- Contador "Mostrando X de 23 diseños".
- Botón "Sorpréndeme": abre una demo al azar entre las visibles.
- Peso: 59 KB (límite 90 KB).

### Currículum (`index.html`)
Cuatro mejoras visibles, sin tocar el contenido: (1) anillos de color que flotan en la portada; (2) cinta oscura en movimiento con las áreas de trabajo (se pausa con el cursor); (3) números de sección grandes, con contorno; (4) la ficha del cargo actual se inclina suavemente con el cursor. Todo respeta `prefers-reduced-motion` y se oculta al imprimir (la impresión A4 usa de nuevo el número pequeño). Peso: 47 KB.

### Demos tocadas (4)
- `kayak/` (Mawün): sección "Un sábado en el muelle, paso a paso" con horarios y foto real de un muelle en Llifén, Lago Ranco; 3 preguntas nuevas (agua fría, celular, forma de pago).
- `cabanas/` (Alerce Dormido): sección "El bosque cambia cada estación" (cuándo venir, según el mes) y 2 preguntas nuevas (calefacción, desayuno de campo).
- `velas/` (Luz de Cera): sección "Tres gestos para cuidar tu vela" y preguntas frecuentes (despacho, regalo, mascotas, reciclaje del vaso, pedidos para empresas).
- `plantas/` (Raíz Verde): sección "¿Cuánta luz tiene tu casa?" con tres tarjetas de color y 2 preguntas nuevas (riego y trasplante).
- No regeneré capturas `demos/img/*.jpg`: son secciones nuevas, no cambian la portada.

### Validación
25 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, errores de JavaScript ni anclas rotas; una sola etiqueta `<main>` y aviso de datos ficticios en cada demo. Las fotos externas no cargan desde el entorno; el cuadro de la foto nueva de kayak queda de color azul si no carga. Todas las demos pesan menos de 60 KB.

### Sugerencias para René
- Revisa en el navegador que la foto del muelle de Llifén cargue y se vea bien (kayak).
- Los horarios, precios (saco de leña $6.000) y condiciones nuevos (pago al llegar, pedidos desde 20 unidades) son ejemplos; ajústalos si los usas con un cliente real.
- Próximas demos: sushi, gimnasio, cafetería, mascotas, hostal, termas, taller.
- Currículum: sigue pendiente agregar teléfono o LinkedIn y logros medibles; no se inventaron datos.

## 2026-11-14 (mejora diaria)

Esta rama parte desde `main` (no había solicitudes abiertas).

### Referencias de competencia
- Reportaje de Diario Estrategia sobre una panadería de masa madre en Valdivia (Casa Moulin): destaca el origen concreto (vender primero a vecinos), productos con nombre propio y respaldo real. Idea aplicada a Horno Pellín: preguntas concretas (anticipación, duración, despacho, opciones sin lácteos). Los directorios de veterinarias de Los Ríos (mercantil.com, AgendaPro) son solo fichas; no aportaron estructura. No se copió texto ni imágenes.
- Poca investigación de agencias hoy; sigue pendiente revisar 2 o 3 portafolios de agencias para el portafolio.

### Portafolio (`demos/index.html`)
- Nueva sección "Preguntas antes de escribirme" (6 respuestas, sin inventar precios: el valor se informa por WhatsApp antes de empezar).
- Botón flotante "Escríbeme →" que aparece al bajar y se oculta cuando ya estás en el formulario.
- Peso: 57 KB (límite 90 KB).

### Currículum (`index.html`)
Cuatro mejoras visibles, sin tocar texto ni secciones: (1) cifras de la portada que cuentan hasta su valor; (2) brillo que sigue al cursor en la ficha del cargo actual; (3) subrayado de color que se dibuja bajo cada título de sección; (4) botón "volver arriba". Todo respeta `prefers-reduced-motion` y se oculta al imprimir. Peso: 44 KB.

### Demos tocadas (4)
- `panaderia/` (Horno Pellín): foto real de panes de masa madre en la portada y una franja de galería con dos fotos; sección de preguntas frecuentes.
- `veterinaria/` (Weñi): sección "Cómo es la consulta" con foto real de revisión veterinaria y tres pasos concretos.
- `centro-cultural/` (Ribera): preguntas frecuentes (entrada, accesibilidad, niños, fotos, estacionamiento).
- `navidad/`: titular de portada más concreto (comunas, visita sin costo, montaje en una tarde).
- No regeneré capturas `demos/img/*.jpg`: los cambios son secciones nuevas, no la portada.

### Validación
25 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, errores de JavaScript, 404 locales ni anclas rotas; una sola etiqueta `<main>` y aviso de datos ficticios en cada demo. Las fotos de Unsplash no se pueden descargar desde el entorno (403): se enlazan directo y se ocultan si no cargan; las probé con una imagen de reemplazo.

### Sugerencias para René
- Revisa en el navegador que las 3 fotos nuevas carguen y calcen con el rubro.
- Próximas demos a trabajar: sushi, gimnasio, cafetería, velas, plantas, mascotas, cabañas, kayak.
- Currículum: sigue pendiente agregar teléfono o LinkedIn y logros medibles; no se inventaron datos.

## 2026-11-13 (segunda pasada: portafolio vistoso)

Esta rama parte desde `main` (no había solicitudes abiertas).

### Referencias de competencia
- La búsqueda de portafolios de diseñadores chilenos devolvió sobre todo directorios (2x3.cl, Behance) y artículos de tendencias de portafolios; no abrí ninguno a fondo. Idea tomada de esa lectura: mostrar pocos proyectos destacados primero y el resto después con filtros, y un llamado a contacto repetido. No se copió texto, imágenes ni código. (Esta pasada tuvo poca investigación; conviene reforzarla mañana con 2 o 3 sitios de agencias concretos.)

### Portafolio (`demos/index.html`) — rediseño completo
- Portada con degradados animados, titular con color y cinta amarilla de rubros en movimiento.
- Cifras animadas (23 diseños, 6 rubros, 100 % celular, menos de 24 h).
- Carrusel de 6 proyectos destacados (Cabañas Alerce Dormido, Vapor Sur, Mawün Kayak, Kaiyō Sushi, Maqui, Ribera): botones, puntos, teclado (flechas), deslizar en móvil, autoavance que se pausa con cursor, foco o `prefers-reduced-motion`.
- Filtros por rubro (turismo, comida, tiendas, servicios, bienestar, cultura) sobre las 23 tarjetas, con brillo que sigue al cursor y color propio por proyecto.
- Nueva sección "Cómo trabajo" (4 pasos); se mantienen soporte técnico, "Qué incluye", formulario de WhatsApp y enlace al currículum.
- Peso: 53 KB (límite 90 KB).

### Currículum (`index.html`)
Cuatro mejoras visibles, sin tocar texto ni secciones: (1) portada con luces de color y nombre con degradado; (2) barra de progreso de lectura; (3) línea de tiempo con punto pulsante en el cargo actual y efecto al pasar el cursor; (4) tarjetas de servicios, competencias y estudios con color y microinteracciones. Impresión A4 sin cambios (los adornos se ocultan). Todo respeta `prefers-reduced-motion`.

### Demos tocadas
- `cerveceria/`: la portada y una foto de la galería eran de una cabaña; ahora son cerveza tirada y un vaso recién servido.
- `kayak/`: una foto de la galería cambia por un muelle en un lago de la Patagonia chilena al amanecer. Créditos en `CREDITOS.md`.
- No alcancé a reescribir textos ni regenerar capturas de otras demos en esta pasada.

### Validación
25 páginas a 320, 390 y 1440 px: sin desplazamiento horizontal, errores de JavaScript, 404 locales ni anclas rotas. Las fotos externas no se pudieron ver desde el entorno (bloqueadas).

### Sugerencias para René
- Revisa en el navegador el carrusel y los filtros del portafolio, y que las fuentes de Google carguen bien.
- Pendiente: textos más reales y fotos nuevas en veterinaria, panadería y las demás demos; hay otras demos con fotos que quizá no calzan con el rubro (revisar).
- Currículum: sigue pendiente agregar teléfono o LinkedIn y logros medibles si quieres; no se inventaron datos.

## 2026-11-13 (a pedido de René: fotos reales en las demos)

Esta rama parte desde `main` (ya no hay solicitudes abiertas).

- Nueva instrucción de René: no crear páginas nuevas y concentrarse en las existentes, reemplazando ilustraciones por fotos reales gratuitas.
- Se agregaron fotos de Unsplash (licencia libre, uso comercial) a 10 demos que no tenían: termas, hostal, heladería, taller, ferretería, madera, yoga, contable, barbería y fotografía. Cada una tiene portada con foto de fondo (excepto yoga, que solo recibe la galería para no alterar su portada) y una franja de galería con 2 o 3 imágenes. Créditos en `demos/CREDITOS.md`.
- Las fotos se enlazan directo desde `images.unsplash.com` porque el entorno automático no puede descargarlas (error 403) ni abrirlas; si una no carga, se oculta sola y la página queda con sus ilustraciones.
- Validación: 25 páginas sin desplazamiento horizontal, errores de JavaScript ni 404 locales.

### Sugerencias pendientes para René
- Revisa en el navegador que todas las fotos carguen y se vean bien; no pude verlas desde aquí. Si alguna no te gusta, dime cuál y la cambio.
- La portada de Vapor Sur usa una foto de aguas termales de EE. UU. y la de Radal una casa de madera de Finlandia; son ilustrativas, conviene cambiarlas por fotos del sur de Chile cuando tengas las tuyas.
- Cuando tengas acceso a Unsplash desde un navegador, conviene descargar las fotos a cada demo para que la página no dependa de un sitio externo.
- Quedan sin foto real: centro cultural y navidad usan imágenes propias o antiguas; el portafolio sigue pendiente de rediseño (carrusel).

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
