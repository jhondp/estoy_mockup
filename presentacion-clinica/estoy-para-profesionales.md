# Estoy · Presentación para profesionales de salud mental

Versión del 25 de octubre de 2026. Documento de trabajo para revisión clínica. Las imágenes están en `docs/presentacion-clinica/img/`.

---

## Contexto para la IA

- **Quién escribe:** el autor de Estoy. No es profesional de salud mental ni programador. Diseña el producto y toma las decisiones; un asistente de IA construye el código.
- **Qué es este documento:** la descripción completa de la app, de sus mecánicas y de las razones terapéuticas que el proyecto les atribuye. Se escribió a partir de los documentos de diseño del proyecto y se contrastó con el código.
- **Qué te pido:**
  1. Critica la solidez clínica de cada mecánica: si la razón terapéutica es correcta, si está exagerada o si hay riesgos que no se ven.
  2. Señala el lenguaje que podría dañar, culpar o confundir a una persona en un mal día.
  3. Propón mejoras concretas y di qué evidencia las respalda. Si una afirmación no tiene evidencia sólida, dilo.
  4. Refiérete a las mecánicas por su ID (por ejemplo, `M-HUERTO` o `M-CALMA`) para que la conversación sea precisa.
- **Límites:** Estoy está en fase de piloto. No es un tratamiento ni una herramienta diagnóstica, y no reemplaza la terapia. No propongas funciones que diagnostiquen, que lean el texto libre de la persona o que avisen a terceros sin su decisión: el proyecto las descartó a propósito (ver sección 6).

---

## 1. Qué es Estoy y para quién

**Estoy es una app de acompañamiento en salud mental con forma de posada en un valle de fantasía.** Su idea central cabe en una frase: *"cuanto mejor estás, más lejos llegas, y siempre vuelves al fuego"*. En un día difícil basta con llegar y tocar **"Estoy"**, y eso ya cuenta como registro completo. Con más energía, la persona puede salir al bosque cercano o al camino abierto, donde hay actividades pequeñas, valores y metas por etapas. Nada se pierde por ausencia: no hay rachas, vidas ni niveles.

**A quién va dirigida:** personas adultas **neurodivergentes** (las fuentes piensan en especial en la carga sensorial y social, y piden frases literales por el autismo) que pasan por ánimo bajo, crisis o "apagones", ánimo bajo prolongado o vacío de rumbo, o que están estables y quieren propósito. Los recursos de ayuda son de **Chile**.

**Fase actual:** piloto privado. Hasta 20 personas neurodivergentes la usarán en su teléfono Android durante algunas semanas, y el autor entrevistará a cada una al final. Ninguna persona la recibirá antes de una revisión clínica profesional.

## 2. Por qué existe

Muchas herramientas de bienestar están pensadas para alguien que ya tiene energía, constancia y orden. Esta sección describe para quién se diseña Estoy, por qué esas herramientas le fallan, qué apuesta hace el proyecto y qué no pretende ser.

### Para quién: lo que vive en el día a día

Las fuentes no describen a la persona por un diagnóstico, sino por cómo está su camino en un periodo de la vida. Son personas adultas neurodivergentes que pueden pasar por alguna de estas situaciones:

- **Un día de crisis o un "apagón".** Hacer cualquier cosa cuesta. La meta no es avanzar, sino sostenerse.
- **Un ánimo bajo que dura semanas o meses.** Se funciona a medias, cuesta disfrutar lo que antes gustaba y se pierde el rumbo.
- **Estar "más o menos bien", pero sin dirección.** La persona funciona y disfruta algunas cosas, pero nada la mueve mucho. El concepto lo llama *languidecer* y no lo trata como un problema que arreglar.
- **Una etapa estable**, con ganas de propósito y de metas.

En todos los casos pesan la carga sensorial y la social: cansarse con la gente o con los lugares, aceptar demasiadas cosas o no poder decir que no. Las fuentes piden frases literales, una estructura fija y nada que haya que buscar. También piensan en olvidos concretos: la botica muestra siempre la última toma para que nadie tome la dosis dos veces por no recordar si ya la tomó. Las fuentes no usan el término "disfunción ejecutiva". Si ese marco corresponde a estas dificultades está *por definir* con criterio clínico.

### Por qué las herramientas habituales le fallan

Los registros de hábitos, los diarios de ánimo y las apps de productividad suelen medir el éxito por el uso. Para esta persona, ese diseño puede hacer daño de cuatro maneras:

- **La racha que se rompe.** Si la constancia es la regla, la ausencia se vuelve fracaso, y la ausencia suele llegar justo en los días difíciles. Quien lleva semanas sin poder vuelve con culpa o no vuelve. Por eso el principio dice: *"Volver después de semanas es igual de fácil que volver mañana."*
- **La autoevaluación con números.** Puntajes, porcentajes y contadores invitan a calificarse. El concepto advierte que a algunas personas mirar su ánimo a diario les aumenta la rumiación, y por eso la escala numérica es opcional. La guía prohíbe el progreso en números, aunque quedan algunos (sección 9).
- **La carga cognitiva.** Formularios, listas, menús y botones que hay que buscar gastan la poca energía de un mal día. Estoy usa pocos nombres propios, cada uno presentado con su historia, un modo de lenguaje simple y un solo registro diario.
- **El todo o nada.** Muchas apps tratan igual un día de crisis y uno estable: o se completa todo, o no cuenta. En Estoy, un toque ya es un registro completo, y la versión mínima de un hábito o de un paso también cuenta.

A esto se suman las mecánicas de enganche que el proyecto descarta a propósito: recompensas al azar, rankings, vencimientos y mensajes de culpa como "te extrañé". La app tiene éxito cuando ayuda, no cuando se usa más. Por eso, el indicador más honesto, según el concepto, es cuántas personas vuelven tras dos semanas o más sin entrar.

### La apuesta: un mundo que se habita

En lugar de una app que se rellena, Estoy propone un lugar al que se llega. Tiene cinco partes:

- **El tiempo afuera describe cómo está el camino.** La persona toca la ventana y responde *"¿Cómo está el camino hoy para ti?"*. Hay tres opciones: **Refugio** (nieva y hoy no hace falta salir), **Bruma** (hay niebla, pero lo cercano está despejado) y **Expedición** (el camino está abierto). Lo difícil se nombra como el tiempo afuera, no como un rasgo de la persona. Ella elige el clima, y la app nunca lo cambia sola. La distancia que se recorre sigue la lógica de la activación conductual graduada que invocan las fuentes. Ningún lugar se cierra: en el Refugio, lo lejano se ve nevado, pero se puede entrar. Las fuentes no nombran un marco teórico para la metáfora misma, así que su relación con técnicas como la externalización está *por definir*.
- **Los personajes acompañan, no juzgan.** Olmo recibe siempre igual, Brin acompaña afuera y Ascua respira contigo. Ninguno evalúa, diagnostica ni tiene necesidades que atender, y Ascua nunca usa la culpa. Según el diseño, una compañía cálida y predecible baja el umbral para empezar. En los momentos serios no habla ningún personaje.
- **Gestos en lugar de campos.** Registrar, calmarse o dar un paso hacia una meta son gestos en el mundo, como regar una planta o dejar leña en el fuego. La prueba de la guía: *"Si quito la ilustración y la pantalla funciona igual, es estilo web: rehacer."*
- **"Estar aquí ya cuenta."** Tocar "Estoy" es un registro completo. En el Refugio, el salón lo dice con todas sus letras: *"Afuera nieva. Hoy no hace falta salir. Estar aquí ya cuenta."*
- **Descansar es legítimo.** Al entrar al Refugio, Olmo guarda los viajes en el baúl, sin fechas, y dice *"Aquí no tienes que hacer nada"*. Al volver, se retoman donde quedaron, sin "ponerse al día". El guardián de la puerta, que está planificado (`M-UMBRAL`), lleva la idea a los límites: *"retirarte no es rendirte"*. Para que el descanso no se vuelva evitación, las personas de confianza siempre pueden pasar.

Una regla ordena todo: si no se puede decir qué ayuda a sanar o a sostenerse una mecánica, no se agrega.

### Lo que Estoy no es

> Estoy **no es un tratamiento, no diagnostica y no reemplaza la terapia.** No tiene evidencia propia de eficacia. La app muestra y no interpreta: la interpretación clínica es del profesional. En los momentos de riesgo, el lenguaje es directo y lleva a recursos reales, como el \*4141 y el 131.

El concepto la piensa como un **puente con la psiquiatría y la psicoterapia**, con apoyos para el tiempo entre sesiones. Prevé notas para la próxima sesión, "lo que me llevé" de cada una, tareas de terapia en el tablón y un informe de una página para la consulta. Esa parte está planificada (etapa 8, sección 7). Las fuentes no afirman de forma explícita que la app no sustituya la conexión humana, aunque orientan hacia las personas con la mesa común, la colina del cuervo y las personas de confianza. Cómo decirlo dentro de la app está *por definir*, y hoy la app todavía no muestra un aviso de que no reemplaza la terapia.

### Por qué su mirada importa ahora

Estoy está en fase de piloto: hasta 20 personas la usarán durante algunas semanas, y ninguna la recibirá antes de una revisión profesional. El autor no es profesional de salud mental, y las reglas clínicas actuales son un borrador sin validar. Antes de llegar a una persona real necesitan criterio clínico la pregunta de cuidado y su protocolo, los textos de "Esto tiene nombre", los recursos de ayuda en Chile, lo que dice la botica sobre una dosis olvidada, el manejo de la energía alta y los números que todavía existen. La sección 8 reúne las preguntas concretas.

## 3. Principios de diseño

| Principio | Cómo se aplica |
| --- | --- |
| **Estar ya cuenta** | Tocar "Estoy" es un registro completo. Contar más es siempre opcional. |
| **Calma primero** | Calma, Ayuda y "Estoy" están en una franja fija, en el mismo lugar en todas las escenas. Se abren al instante, sin caminatas, animaciones ni confirmaciones. |
| **Sin castigo ni vergüenza** | No hay rachas, vidas, rankings, vencimientos ni recompensas al azar. Lo que se cultiva no se marchita. No se usan mensajes de culpa ("te extrañé"). |
| **Sin puntuaciones** | El progreso se ve en el mundo (una planta que crece, una bandera en un sendero), no en números ni porcentajes. *Hay excepciones; ver la sección 9.* |
| **Nada se cierra por el clima** | En el Refugio los lugares lejanos se ven nevados, pero siempre se puede entrar. |
| **La persona elige** | Ella elige el clima, el ritmo y lo que comparte. La app sugiere con suavidad y nunca cambia nada sola. |
| **La app muestra, no interpreta** | Nunca diagnostica ni dice "pareces deprimido". La interpretación clínica es del profesional. |
| **La fantasía se retira cuando importa** | En Calma, en la ayuda, en la pregunta de cuidado, con los remedios y en el informe no habla ningún personaje y el lenguaje es directo. |
| **Ayuda a un toque** | El botón "Ayuda" aparece en todas las escenas, y "Necesito ayuda ahora" está dentro de Calma. |
| **Accesibilidad** | Lector de pantalla en todo, texto al doble sin cortes, movimiento reducido (nada se mueve y nadie camina), el ajuste "Ir directo" (llegar sin caminar), lenguaje simple, sonidos opcionales, contraste WCAG AA y tipografía Atkinson Hyperlegible. La fuente para dislexia que pide el diseño del piloto todavía no existe. |
| **Nada sobre nosotros sin nosotros** | Se debe validar con personas neurodivergentes durante el diseño, no solo al final. *Pendiente.* |

**El éxito se define así:** la app tiene éxito cuando ayuda, no cuando se usa más. No se persiguen los usuarios activos diarios ni el tiempo en pantalla.

## 4. Recorrido por el mundo

Cada mecánica tiene un ID estable. Para cada una se indica **qué hace la persona**, **la razón terapéutica** que dan las fuentes del proyecto y **el marco teórico** que se invoca. Las capturas marcadas como "app real" vienen de la versión web en construcción. Las marcadas como "maqueta" son diseños aprobados que todavía no están construidos. Las marcadas como "Diseño en construcción" vienen del prototipo de la etapa 6r, que se está construyendo ahora. Todo el arte es **provisional**.

### Los personajes

| Personaje | Quién es | Regla |
| --- | --- | --- |
| **Olmo** (tejón) | El posadero. Recibe en el salón. | Su saludo es fijo: *"Pasa. Aquí siempre hay un lugar junto al fuego para ti."* No cambia con el clima, la hora ni la ausencia, y nunca comenta cuánto tiempo pasó. |
| **Brin** (liebre) | La cartógrafa. Se perdió en la Bruma y salió dibujando lo que había caminado. | Acompaña afuera y guía las metas. Su frase es *"Yo no borro caminos."* |
| **Ascua** (dragona pequeña) | Duerme junto al fuego y respira contigo. | Nunca tiene necesidades, hambre, tristeza ni retrocesos. No es un Tamagotchi. |
| **Umbral** (oso) | Guardián de los límites. Duerme junto a la puerta. | *Planificado.* La metáfora es la hibernación: *"retirarte no es rendirte"*. |
| Presencias sin nombre | El cuervo, las luciérnagas, un caracol y la Niebla. | Un personaje solo existe donde hace algo que el lugar no puede hacer solo. La Niebla habla solo en primera persona, con la voz de la persona. |

En crisis, todos los personajes se retiran.

---

### M-INICIO · Llegada con Olmo (primeras preguntas)

![Olmo en la recepción, con su saludo fijo y sus opciones](img/01-recepcion-olmo.jpg)
*App real. La recepción: Olmo con su saludo fijo, la opción de responder otra vez las preguntas del inicio y, desde la etapa 6g, "Encontrar tus estrellas".*

- **Qué hace la persona:** responde siete preguntas, una por pantalla. Cada una tiene "No sé" y "Saltar", y todas se pueden saltar de una vez para elegir el clima directamente. Las preguntas tratan del funcionamiento diario, desde cuándo se siente así, el disfrute, la energía de 1 a 5 (con la opción "mucha, más de lo normal: duermo poco y no me canso"), el horizonte, **la pregunta de cuidado** y qué le gustaría encontrar en la app.
- **Razón terapéutica:** orientar sin diagnosticar y sugerir el clima de menor exigencia. El resultado sugiere y la persona elige. Ante la duda, se sugiere la opción más amable.
- **Marco:** tamizaje breve con fines de orientación. La pregunta de cuidado equivale al ítem 9 del PHQ-9. Las reglas de sugerencia están en un borrador **escrito por una IA en el rol de psiquiatra y no validado**. Incluyen un "estado mixto posible" (energía alta junto con disfrute bajo, funcionamiento bajo u horizonte negativo, que lleva al Refugio con una sugerencia de consultar) y un límite de un solo viaje activo cuando la energía es alta.
- **Estado:** construido.

### M-CUIDADO · Protocolo de cuidado

![Pantalla de cuidado sin fantasía](img/14-pantalla-cuidado.jpg)
*App real. La pantalla de cuidado: sin personajes ni fantasía, con las líneas de ayuda de Chile.*

- **Qué hace la persona:** si responde "A veces" o "Sí" a *"En las últimas dos semanas, ¿has pensado en no querer seguir viviendo o en hacerte daño?"*, el recorrido se detiene. Aparece una pantalla directa: *"Gracias por contármelo. No tienes que pasar esto sola ni solo. Hay personas disponibles ahora mismo."* Ofrece tres acciones: llamar al **\*4141** (prevención del suicidio, gratuito, a toda hora), **escribir a una persona de confianza** con el mensaje ya escrito ("¿Puedes hablar conmigo? No estoy bien") y llamar al **131 (SAMU)** si hay peligro inmediato. Debajo aparece Salud Responde (600 360 7777). El botón "Seguir al Refugio" aparece después de 10 segundos.
- **Razón terapéutica:** dar acceso inmediato a ayuda humana sin pedirle a la persona que afirme que está a salvo.
- **Qué no hace:** no guarda la respuesta como dato clínico (solo queda la marca de que se mostró la pantalla), no repite la pregunta de forma rutinaria, no lee palabras clave en notas ni en el diario y no avisa a nadie automáticamente.
- **Después del inicio:** la tarjeta "Si las cosas pesan mucho, aquí hay personas disponibles" se ofrece si la persona anota el ánimo más bajo (−3) en tres registros seguidos o si entra al Refugio por decisión propia. Se ofrece como máximo una vez cada 7 días.
- **Estado:** construido. **Bloqueante para el piloto:** debe pasar la revisión clínica, y los números deben verificarse con fuentes oficiales.

### M-ESTOY · El botón "Estoy" y el salón

![Salón en Refugio](img/02-salon-refugio.jpg)
*App real. El salón en el Refugio: "Afuera nieva. Hoy no hace falta salir. Estar aquí ya cuenta."*

- **Qué hace la persona:** toca "Estoy" en cualquier escena. Queda anotada una llegada y aparece una línea de bienvenida. En el salón están el fuego, Olmo, Ascua dormida, el tablón, la mesa común y la ventana.
- **Razón terapéutica:** bajar al mínimo el umbral para volver. "Estar ya cuenta" valida la presencia sin exigir rendimiento, y volver después de semanas es tan fácil como volver mañana.
- **Marco:** el principio de no castigar la ausencia. El concepto propone como métrica futura la "tasa de regreso" después de dos semanas o más sin entrar.
- **Estado:** construido.

### M-VENTANA · El clima: Refugio, Bruma y Expedición

![Salón en Bruma](img/03-salon-bruma.jpg)
*App real. El salón en la Bruma: "Hay niebla afuera. Lo cercano está despejado."*

![Salón en Expedición](img/04-salon-expedicion.jpg)
*App real. El salón en la Expedición: "El camino está abierto. Ve a tu ritmo."*

![La ventana: elegir cómo está el camino](img/05-ventana-camino.jpg)
*App real. La ventana: "¿Cómo está el camino hoy para ti?", con Nieve (Refugio), Bruma y Camino despejado (Expedición).*

- **Qué hace la persona:** toca la ventana y elige qué tiempo hace afuera para ella. El estado dura lo que haga falta, a menudo semanas, y es distinto de cómo está hoy, que se cuenta en el registro.
  - **Refugio:** ánimo bajo, crisis o apagón. La meta es sostenerse.
  - **Bruma:** ánimo bajo que dura mucho, vacío o rumbo perdido.
  - **Expedición:** estabilidad y ganas de propósito, *con destino* o *sin destino* (este último para quien está "más o menos bien" pero sin dirección, lo que el concepto llama "languidecer").
- **Razón terapéutica:** ajustar la exigencia a la capacidad real. Con poca energía la meta es estar, después vienen pasos cortos y, con estabilidad, cosas más grandes. La app puede sugerir un cambio con suavidad (bajar es más rápido que subir), pero **nunca cambia sola**.
- **Marco:** **activación conductual graduada**. Los estados son clima y no estaciones del calendario: se eliminaron "invierno", "otoño" y "primavera" porque el estado lo elige la persona, no la fecha. En la interfaz no aparecen etiquetas clínicas ("depresión", "distimia", "eutimia").
- **Estado:** la elección manual está construida. El motor de sugerencias automáticas está **planificado** (etapa 7).

### M-RADIO · El mapa del valle y la distancia

![Mapa del valle en Expedición](img/06-mapa-valle.jpg)
*App real. El mapa del valle en la Expedición: todos los lugares despejados, unidos por senderos.*

- **Qué hace la persona:** ve el valle completo y toca un lugar para ir. Puede caminar o llegar directo. Todos los lugares también están en una lista accesible ("Lugares").
- **Razón terapéutica:** el clima decide qué está *cerca hoy*, nunca qué está cerrado. Un lugar lejano muestra cada vez, sin recordar respuestas anteriores: *"Hoy está lejos con esta niebla. ¿Vamos igual?"*, con "Vamos" y "Mejor algo cerca". El mensaje es que hoy lo cercano basta, sin quitar nada.
- **Marco:** activación conductual sin presión, baja carga cognitiva y previsibilidad para personas neurodivergentes.
- **Estado:** construido. En la etapa 6r el mapa se vuelve a pintar con el arte nuevo y la llegada sigue siendo directa (ver `M-MUNDO-6R`).

### M-MUNDO-6R · Movimiento y espacios (en construcción)

![Diseño: el salón con cuatro carteles en una fila](img/20-diseno-salon-bruma.jpg)
*Diseño en construcción. El salón de frente, con la bruma en la ventana, las flechas "‹ Afuera" y "Habitación ›" y una fila de cuatro carteles (Ascua, Ventana, Tablón, Recepción) sobre Estoy · Calma · Ayuda.*

![Diseño: el camino lateral con la pregunta del Mirador](img/21-diseno-camino-mirador.jpg)
*Diseño en construcción. El Camino lateral con bruma: "Hoy está lejos con esta niebla. ¿Vamos igual?", con "Mejor algo cerca" y "Vamos".*

- **Estado:** **en construcción** (etapa 6r). Todavía no está en la app. Las capturas son del prototipo, y los carteles de cada lugar y el arte final pueden cambiar.
- **Qué cambia:**
  - **Escenas ilustradas de frente.** Cada lugar es una pintura nueva vista de frente que cabe entera en la pantalla.
  - **El cielo muestra el clima.** Detrás de la escena se ve nieve (Refugio), bruma (Bruma) o cielo despejado (Expedición), con movimiento lento o ninguno. En el interior se ve por la ventana.
  - **Caminar en una sola línea.** El viajero camina solo a izquierda y derecha sobre una línea del suelo y siempre mide lo mismo. Tocar el piso no hace nada: solo responden las cosas con nombre. La pista dirá "Toca un cartel para ir hasta ahí." (texto pendiente de aprobación).
  - **Una fila de carteles.** Como máximo 4 o 5 carteles por escena, en una sola fila abajo, justo encima de *Estoy · Calma · Ayuda*, en el mismo orden que las cosas de izquierda a derecha. Una línea punteada une cada cartel con lo que nombra. En el salón sale el cartel del fuego, porque "Estoy" ya hace lo mismo, y el fuego sigue pintado.
  - **Flechas a los lugares vecinos.** Arriba, a cada lado, una flecha dice a dónde lleva ("‹ Huerto", "Camino ›"). Se pasa de un lugar al vecino sin volver al mapa. El mapa del valle sigue siendo el centro, con llegada directa, y gana una flecha "‹ Volver".
  - **El Camino lateral.** Es el único lugar que se recorre de lado, porque ahí avanzar tiene sentido: "cuanto mejor estás, más lejos llegas". Reúne el Bosque, la Encrucijada, el Arroyo, el Lago y el Mirador. Con Bruma o Refugio, lo lejano se ve apagado y pregunta antes de caminar, pero nunca se cierra.
  - **La Encrucijada se divide.** Tenía demasiados puntos. Sus salidas pasan al Camino, y la Encrucijada se queda solo con la mesa de Brin y sus viajes.
- **Razón terapéutica y de accesibilidad:**
  - **Menos carga visual.** Un máximo de 4 o 5 carteles por escena, una sola fila y un fondo que cuenta el clima sin palabras. Es la misma razón de "baja carga cognitiva" que sostiene el resto del diseño.
  - **Al alcance del pulgar.** El prototipo pone los carteles "abajo, a la altura del pulgar", junto a la franja Estoy · Calma · Ayuda.
  - **Un diseño previsible.** Un solo eje, un solo tamaño del viajero, el mismo orden de carteles con cualquier tamaño de letra y vecinos con nombre. Con la letra al doble, la fila se parte en dos líneas y nada se corta.
  - **Todo sigue al alcance.** Lo que sale de una escena queda en el cajón "Lugares" y en otra escena o en el mapa. El lector de pantalla recorre la flecha izquierda, los carteles en orden, la flecha derecha y la franja.
  - **Lo que no cambia.** Estoy, Calma y Ayuda siguen a un toque e instantáneos, también a mitad de una caminata. Cada caminata dura como máximo 1,5 segundos y se salta con un toque. Con "Ir directo" o con movimiento reducido nadie camina. La lejanía sigue la misma regla del clima de hoy.
- **Marco:** las fuentes lo justifican por accesibilidad, carga cognitiva y previsibilidad. No citan un marco clínico. La frase "cuanto mejor estás, más lejos llegas" conecta el Camino con la activación conductual graduada de `M-RADIO`.

### M-PERSONAJES · Diálogo con Brin y Olmo

![Brin se presenta en la puerta de la posada](img/07-brin-dialogo.jpg)
*App real. Olmo presenta a Brin la primera vez que la persona sale: "Yo no borro caminos."*

- **Qué hace la persona:** lee frases cortas en un cuadro de diálogo con retrato y elige respuestas explícitas. Toda secuencia tiene una salida visible ("Ahora no"). Olmo presenta a Brin la primera vez que la persona sale ("Mira, ella es Brin. Dibuja los mapas del valle.") y después se puede "Volver a escuchar a Brin". Con movimiento reducido o con lector de pantalla, la línea aparece entera de una vez.
- **Razón terapéutica:** un compañero cálido y vivo baja el umbral para empezar. Una línea a la vez y opciones explícitas reducen la carga cognitiva. Los personajes son fijos y previsibles.
- **Marco:** las fuentes lo justifican por carga cognitiva y vínculo. No citan un marco clínico.
- **Estado:** construido (etapa 6d). Los textos nuevos esperan la aprobación del autor, y la prueba con TalkBack en un teléfono real está por hacer.

### M-CALMA · El rincón tranquilo

![Calma](img/10-calma.jpg)
*App real. Calma: vibración lenta, tarjetas para mostrar a otra persona y "Necesito ayuda ahora".*

- **Qué hace la persona:** abre Calma desde la franja fija. La pantalla dice *"Aquí nada te pide nada"* y ofrece una vibración lenta opcional y **tarjetas para mostrar a alguien** cuando no puede hablar ("No puedo hablar ahora", "Necesito un sitio tranquilo", "Por favor, no me toques"), además de "Necesito ayuda ahora".
- **Razón terapéutica:** regularse ante la sobrecarga o la crisis sin tener que hablar ni decidir mucho. Las tarjetas comunican necesidades durante un bloqueo o una sobrecarga.
- **Marco:** las fuentes lo describen como autorregulación y control sensorial. El concepto propone como métrica el *uso temprano*: entrar a Calma antes de llegar al límite. Las fuentes no lo vinculan explícitamente con un protocolo concreto (*por definir*).
- **Estado:** construido. Un acceso rápido desde Android (mosaico de Ajustes rápidos) está planificado (etapa 9).

### M-RESPIRAR · Respirar con Ascua y alternativas

![Respirar con Ascua](img/11-respirar-ascua.jpg)
*App real. Respirar con Ascua: "Sigue su pecho. Si pierdes el ritmo, no pasa nada: ella sigue respirando."*

- **Qué hace la persona:** sigue el pecho de Ascua a un ritmo **4 y 6** (inhalar y exhalar, en segundos) o **5 y 7**, con vibración opcional. Si respirar le inquieta, tiene alternativas: **5·4·3·2·1** (anclaje sensorial: nombrar 5 cosas que ves, 4 que puedes tocar, 3 que oyes, 2 que hueles y 1 que saboreas), **presión** (peso y abrazo) y **mirar el fuego**.
- **Razón terapéutica:** respiración pausada con exhalación más larga, y alternativas para quien la respiración le genera ansiedad.
- **Marco:** respiración pausada y anclaje (*grounding*) sensorial. Después de usarla, la app pregunta una sola vez "¿Te ayudó?" y alimenta el grimorio (`M-GRIMORIO`).
- **Estado:** construido. Que Ascua "aprenda" gestos de las técnicas que le ayudaron está **planificado** (`M-ASCUA-CRECE`).

### M-AYUDA · Dónde pedir ayuda

![Dónde pedir ayuda](img/13-ayuda.jpg)
*App real. La ayuda, a un toque desde todas las escenas.*

- **Qué hace la persona:** toca "Ayuda" y ve las mismas tres acciones que en la pantalla de cuidado (\*4141, una persona de confianza y 131), además de Salud Responde.
- **Razón terapéutica:** el acceso a ayuda humana nunca depende del estado, del clima ni de dónde esté la persona en el mundo.
- **Estado:** construido. Los números deben verificarse antes del piloto.

### M-REGISTRO · Contar cómo estás (registro único)

- **Qué hace la persona:** de forma opcional, anota el **"sol"** del día en una escala de −3 a +3, el **clima** del día (Niebla, Tormenta, Sol tibio, Viento, Lluvia mansa, Noche quieta) y, si quiere, más detalle: el cuerpo, la batería social, la carga sensorial, la energía, el sueño, la medicación, los eventos y preguntas para la consulta.
- **Razón terapéutica:** un solo lugar para el registro, que alimenta el diario y un futuro informe para la consulta.
- **Marco:** automonitoreo. El propio concepto advierte que *a algunas personas mirar su ánimo a diario les aumenta la rumiación*. Por eso la escala numérica se puede desactivar ("Puedes contar cómo estás sin números").
- **Estado:** construido. La lectura del sueño desde Health Connect está planificada (etapa 9).

### M-TABLON · El tablón de encargos y el maná

- **Qué hace la persona:** elige su **maná**, que es la energía de hoy (cinco gotas), y el tablón le ofrece la cantidad justa de encargos pequeños. "Descansar" es siempre una opción. Pie de pantalla: *"Nada se rompe si hoy no completas ninguno. Mañana todo sigue aquí."*
- **Razón terapéutica:** ajustar la cantidad de tareas a la energía disponible, para que el día no fracase de antemano.
- **Marco:** activación conductual y presupuesto de energía. El maná es el único "recurso" de la app y solo sirve para calibrar el tablón. Las fuentes no lo vinculan formalmente con la "teoría de las cucharas" (*por definir* si conviene nombrarla).
- **Estado:** construido. Los encargos vienen de un catálogo fijo.

### M-MESA · La mesa común

- **Qué hace la persona:** enciende una vela de trabajo de 15, 25 o 45 minutos, con sonido opcional de lluvia o chimenea y un aviso suave 10 minutos antes del final.
- **Razón terapéutica:** "trabajar acompañado". La compañía de otros viajeros necesita un servidor y quedó **fuera del piloto**, así que hoy es solo un temporizador.
- **Estado:** construido (solo el temporizador).

### M-BOTICA · Recordatorio de medicación

- **Qué hace la persona:** si la activa, ve una repisa con un frasco por remedio. A la hora indicada recibe un aviso directo ("Hora de tu remedio de la noche") con **Tomado · En 15 min · Hoy no**. La "última toma" está siempre visible para evitar dosis dobles. Hay un segundo aviso a los 30 minutos y después nada más. Una dosis olvidada no se marca en rojo.
- **Razón terapéutica:** apoyar la adherencia sin culpa, pensando en dificultades de memoria y de función ejecutiva.
- **Qué no hace:** nunca indica qué hacer ante una dosis olvidada ni sugiere cambiar la dosis. Solo muestra lo que la persona copió de su médico, o *"Si no sabes qué hacer, pregunta a tu médico o en la farmacia."* La pantalla bloqueada no muestra el nombre del medicamento.
- **Estado:** construido. **Bloqueante:** revisión clínica de los textos y pruebas en teléfonos reales.

### M-HUERTO · El huerto de hábitos

![El huerto con hábitos en distintas etapas](img/08-huerto.jpg)
*App real. El huerto: cada bancal es un hábito, y las plantas están en distintas etapas.*

![Regar un hábito](img/09-huerto-regar.jpg)
*App real. Regar: "Lo hice" o "Hice la versión mínima". "Nunca se marchita. Si no vienes, te espera como la dejaste."*

- **Qué hace la persona:** planta hasta cuatro hábitos. Cada uno tiene un **ancla** ("Después de…"), una acción ("Hago…"), una frecuencia deseada ("3 veces por semana, cuando puedas") y una **versión mínima**. Cada vez que lo hace, riega la planta, que crece de brote a arbusto, flores y fruto. La versión mínima también riega. Un hábito se puede "dejar descansar" sin perder lo crecido.
- **Razón terapéutica:** los hábitos pequeños anclados a una rutina tienen más probabilidad de mantenerse. El crecimiento nunca retrocede y la versión mínima cuenta, lo que ofrece autocompasión en vez de culpa por una racha rota. La frecuencia es un deseo y no un control: nunca aparece "faltó".
- **Marco:** **intenciones de implementación** ("Después de…, hago…"), **hábitos mínimos** (*tiny habits*), **activación conductual** y **autocompasión**.
- **Estado:** construido (etapa 6h). En el Refugio las plantas duermen bajo la nieve y se pueden seguir regando. Una planta que "descansa" queda junto al muro con lo crecido y se vuelve a plantar cuando se quiera. Cada visita deja una flor silvestre en el muro. La cosecha va a la despensa ("Lo que cosechaste en el huerto") y el diario dice qué se regó, con palabras. Desde la etapa 6g, un hábito puede colgar de una estrella, pero solo si Brin lo invita al terminar una etapa de un viaje (`M-VIAJES`).

### M-LENERA · La leñera (brasas)

- **Qué hace la persona:** después de hacer algo, anota "cuánta brasa dejó", es decir, cuánto calor o bienestar le dio. Puede salir a "buscar leña con Ascua" (diez minutos afuera, con luz de día). Encabezado: *"No todo da lo mismo, aunque así se sienta."*
- **Razón terapéutica:** contrastar la sensación de que nada vale la pena con la propia evidencia.
- **Marco:** **activación conductual** (registro de actividades y del placer que dan).
- **Estado:** construido.

### M-POZO · El pozo de los ecos (experimentos de curiosidad)

- **Qué hace la persona:** antes de probar algo pequeño, predice cuánto lo disfrutará. Después anota cuánto lo disfrutó y compara ("Predicción y realidad"). Encabezado: *"No hay que lograr nada. Solo probar y notar qué pasa."*
- **Razón terapéutica:** el ánimo bajo suele anticipar menos disfrute del que luego ocurre. Comparar la predicción con lo que pasó ofrece evidencia propia.
- **Marco:** activación conductual (predecir el disfrute y comparar). Antes se llamaba "Pozo del Oráculo" y se renombró porque el nombre sugería adivinación.
- **Estado:** construido. La comparación se muestra con números ("esperabas 2, fue 4"); ver la sección 9.

### M-PRADO · El prado de luciérnagas (destellos)

- **Qué hace la persona:** guarda "destellos", que son cosas pequeñas que notó. Brin: *"Las luciérnagas guardan lo pequeño que notas. La bruma no las apaga."*
- **Razón terapéutica:** entrenar la atención hacia lo pequeño y positivo en periodos de ánimo bajo.
- **Marco:** las fuentes no nombran un marco específico (*por definir*).
- **Estado:** construido.

### M-ARROYO · El arroyo (anclaje sensorial)

- **Qué hace la persona:** recorre uno de tres senderos cortos de anclaje con los sentidos, paso a paso y sin temporizador.
- **Razón terapéutica:** volver al presente a través de lo sensorial.
- **Marco:** anclaje (*grounding*). Los textos no tienen maqueta y **deben pasar la revisión clínica**.
- **Estado:** construido.

### M-LAGO · El lago quieto (la voz de la Niebla)

- **Qué hace la persona:** anota frases que "dijo la Niebla". La Niebla es la voz del ánimo bajo, escrita en primera persona y con las palabras de la persona. Texto: *"Si la Niebla habla, puedes oírla sin creerle."* Puede marcar "La reconocí hoy".
- **Razón terapéutica:** reconocer los pensamientos del ánimo bajo como algo que se escucha y no como verdad.
- **Marco:** las fuentes lo describen así pero no lo vinculan con un marco concreto. Se parece a la defusión cognitiva de ACT, pero esa relación es *por definir*. **Está en la lista de revisión clínica.**
- **Estado:** construido.

### M-COLINA · La colina del cuervo

- **Qué hace la persona:** envía un "me acordé de ti" a una persona de confianza a través del menú de compartir del teléfono, sin servidor. El cuervo también puede traer cartas que la persona se escribió a sí misma.
- **Razón terapéutica:** mantener el vínculo con poco esfuerzo cuando el ánimo aísla.
- **Marco:** el concepto apoya la motivación en "autonomía, competencia y vínculo". El vínculo social como factor protector no aparece citado con un marco formal (*por definir*).
- **Estado:** construido.

### M-ESTRELLAS · Valores: encontrar tus estrellas y "Tu cielo"

![Tu cielo](img/19-tu-cielo.jpg)
*App real. "Tu cielo": cada estrella es un valor, con su cartel. Abajo, "Encontrar estrellas", "El cielo del mes" y "Mirar atrás".*

- **Qué hace la persona:** desde la recepción, Olmo ofrece **"Encontrar tus estrellas"**: muestra un valor a la vez, de diez valores fijos con una descripción breve, y la persona elige "Me importa mucho", "Algo", "Ahora no" o "Escribir una mía". Si le importa, escribe qué significa para ella ("Para mí, … es…"). Cada valor elegido es una **estrella** en "Tu cielo", con un máximo de ocho entre fijas y propias.
- **La luz de la estrella:** tiene una luz base que **nunca baja** y crece un poco con lo hecho por ella: un paso de un viaje que cuelga de ella, regar un hábito que cuelga de ella o "Hice algo por esto hoy". El panel de la estrella dice con palabras, nunca con cuentas, lo hecho esa semana ("regaste la lavanda", "diste un paso en «Volver a caminar»"). Si no hubo nada: *"Su luz está aquí, como siempre."* En la Bruma las estrellas se ven veladas, no borradas.
- **El diario guarda lo hecho:** "Hice algo por esto hoy" admite una nota breve o ninguna ("Guardar sin escribir"). Las notas se suman y nunca se reemplazan. El capítulo del mes en el diario recoge la última nota de cada estrella: *"Hiciste algo por Cuidar («Llamé a mi hermana») y por Mi música («Toqué un rato»)."*
- **Razón terapéutica:** los valores funcionan como brújula y no como metas. Reconocer un valor es más fácil que inventarlo. La luz que nunca baja evita que un periodo difícil se lea como retroceso.
- **Marco:** **ACT (valores)**. La app menciona ACT por su nombre en un solo texto: si el vacío pesa mucho o dura años, *"hay terapias que trabajan el sentido y los valores, como la terapia de aceptación y compromiso (ACT). Puedes llevarlo a tu consulta."* Las descripciones de los valores y las sugerencias de "Hice algo" están marcadas para **revisión clínica**.
- **Estado:** construido (etapa 6g). El mirador sigue con su mazo de valores.

### M-VIAJES · Metas guiadas con Brin

![La segunda pregunta de Brin](img/17-brin-pregunta.jpg)
*App real. En la Encrucijada, "Un viaje nuevo con Brin": "¿Por qué te importa?", con la lista de estrellas.*

![Viaje en marcha](img/15-viaje-en-marcha.jpg)
*App real. El viaje como sendero dorado en el valle, con banderas, y "El paso de hoy": "Lo hice", "Más chiquito" y "Para más adelante".*

![El viaje en el Refugio](img/18-viaje-refugio.jpg)
*App real. En el Refugio: "Mientras dura la nieve, tus viajes descansan. El camino queda dibujado.", con "Dar un paso igual".*

- **Qué hace la persona:** en la Encrucijada toca a Brin y responde cuatro preguntas, una por pantalla y con su retrato: *"¿Qué te gustaría que fuera distinto?"*, *"¿Por qué te importa?"* (de qué estrella cuelga, o una estrella propia), *"¿Cuál sería un primer paso de 2 minutos?"* con una **versión mínima para días flojos**, y el camino que Brin dibuja con tres etapas con nombre de lugar ("El puente", "El árbol", "La colina"…), que la persona puede cambiar. Las etapas vienen de un catálogo escrito a mano según palabras de la meta (dormir, caminar, personas, estudio, casa u otra), sin IA. Las respuestas a medias se conservan con "Ahora no", Calma o Ayuda mientras la app siga abierta.
- **En el mapa:** el viaje es un **sendero dorado** que sube de la Encrucijada a la estrella. Cada etapa terminada vuelve cálida su bandera, y el viajero espera en el último tramo andado. "El paso de hoy" ofrece **"Lo hice"**, **"Más chiquito"** (cambia a la versión mínima, que cuenta igual) y **"Para más adelante"**. Al terminar una etapa, Brin dice *"Lo anoto en tu mapa. Este tramo ya es tuyo."* y ofrece "Seguir", "Descansar aquí" o plantar un hábito para ese camino. Las banderas también están escritas como texto en el panel.
- **Razón terapéutica:** que las metas cuelguen de valores, que el primer paso sea muy pequeño y que reconocer sea más fácil que inventar. Las tres opciones del paso de hoy son movidas iguales y ninguna muestra fracaso. Un viaje no vence ni tiene fechas. Nunca aparecen "pendiente", "atrasado" ni "abandonado".
- **Sin números:** la copia de viajes, estrellas y cielo no muestra cuentas de progreso, ni en cifras ni en palabras: no hay "etapa 2 de 3", "3 viajes en marcha" ni "ocho estrellas" (se cambió por "Tu cielo ya está lleno."). Quedan dos excepciones explícitas: la pregunta del "primer paso de 2 minutos" y las velas de orientación "Primera pregunta de cuatro".
- **Clima:** los viajes se pueden ver y cambiar con cualquier clima: nada se cierra. En el Refugio los viajes activos descansan y "Dar un paso igual" muestra el paso normal. En la Bruma el paso abre con la versión mínima si existe. Las preguntas de Brin se abren en todo clima, pero en el Refugio y la Bruma el viaje nuevo se guarda para más adelante (*"Lo guardé para más adelante. Te espera sin fecha."*). Esa regla está pendiente de revisión clínica.
- **Marco:** **ACT (acción comprometida desde los valores)**, **activación conductual** y hábitos mínimos. Hay como máximo 3 viajes activos (1 con energía alta). Al llegar al límite, la app pregunta sin cifras: *"Ya tienes varios viajes en marcha. ¿Quieres guardar este para más adelante?"*
- **Estado:** construido y publicado (etapa 6g). Los textos nuevos esperan la aprobación del autor.

### M-RASTROS · Expedición "sin destino"

- **Qué hace la persona:** responde de vez en cuando una pregunta breve ("¿Algo te llamó la atención hoy?", "¿Perdiste la noción del tiempo en algún momento?"). Con semanas de rastros, Brin propone constelaciones de valores, que la persona confirma o descarta. También hay "pequeñas maestrías", que son aprender algo concreto.
- **Razón terapéutica:** según el concepto, *"el sentido se construye haciendo, no se encuentra pensando"*. No se pregunta "¿cuál es tu sueño?". El mensaje guía es: *"No tienes que tener un sueño. Puedes salir a caminar y ver qué te llama la atención."*
- **Marco:** el concepto menciona el *languidecer* y ACT. Que una "chispa" repetida se convierta en viaje es una transición suave de "sin destino" a "con destino".
- **Estado:** construido.

### M-DIARIO · El diario

![El diario](img/12-diario.jpg)
*App real. El diario: "Solo suma. Nunca resta.", con semana, mes y capítulos.*

- **Qué hace la persona:** ve lo que ha vivido por semana y por mes, y en capítulos mensuales con hitos (por ejemplo, haber entrado a Calma antes de llegar al límite). Puede editar el capítulo.
- **Razón terapéutica:** construir una narrativa propia que solo crece, y una memoria de resiliencia.
- **Estado:** construido. La captura muestra contadores ("0 veces llegaste a la posada"); ver la sección 9.

### M-GRIMORIO · El grimorio (lo que te ayuda)

- **Qué hace la persona:** después de usar una técnica, responde una sola pregunta ("¿Te ayudó?": Sí, Un poco o No). Con el tiempo, el grimorio muestra su **propia evidencia** ("la presión te ayudó 9 de 11 veces").
- **Razón terapéutica:** que la persona descubra qué le funciona a ella, con su propia experiencia, y gane autoeficacia.
- **Estado:** construido. Usa conteos explícitos; ver la sección 9.

### M-BESTIARIO · El bestiario de emociones

- **Qué hace la persona:** pone nombre a lo que siente a través de criaturas (el Zorro inquieto para la ansiedad, la Garza de lluvia para la tristeza, el Jabalí de brasa para la rabia, la Niebla para el vacío, el Cervatillo tembloroso para el miedo, el Erizo encogido para la vergüenza, entre otras) y escribe su propia ficha. *"Ninguna es mala."*
- **Razón terapéutica:** entrenar el reconocimiento y la diferenciación de emociones. El texto de la app afirma: *"Ponerle nombre a una emoción ayuda a que baje su intensidad, y distinguir emociones finas ayuda a regularlas."* **Esta afirmación debe pasar la revisión clínica.**
- **Estado:** construido.

### M-SANTUARIO, M-DESPENSA · Memoria de resiliencia y provisiones

- **Qué hace la persona:** en el **santuario** aparece una piedra por cada vez que estuvo en el Refugio y salió. En la **despensa** y el **baúl** guarda "provisiones" para los días difíciles: canciones, fotos, personas, actividades, la cosecha del huerto y una **carta para su yo de los días de nieve**.
- **Razón terapéutica:** recordar que ya se atravesaron otros periodos difíciles, y preparar en un buen momento los recursos para uno malo.
- **Marco:** las fuentes hablan de "memoria de resiliencia" y, para los límites, de **prevención de recaídas**. La despensa funciona como un plan de afrontamiento personal (*por definir* si se lo presenta así).
- **Estado:** construido.

### M-UMBRAL · La puerta y los límites (planificado)

![Maqueta: Umbral y la puerta](img/16-maqueta-puerta-umbral.jpg)
*Maqueta (planificada). La puerta con tres estados: "La puerta es mía. Lo que no quieras que entre, no entra."*

- **Qué hará la persona:** elegir cómo deja la puerta (**abierta**, **entornada**, que deja pasar solo lo suave, o **cerrada**) y por cuánto tiempo. Umbral pregunta por necesidades y nunca por diagnósticos: "¿Qué te cuesta más? Decir que no / Me canso con la gente o los lugares / Acepto demasiadas cosas". También habrá un **taller de frases** (pedir tiempo, decir que no, responder a la insistencia) con ensayo guionado del "disco rayado", sin IA, y "reglas de la casa" (un límite, su porqué ligado a una estrella y qué hacer si se cruza).
- **Razón terapéutica:** los límites como autocuidado. **Descansar no es evitar:** las personas de confianza y la ayuda pasan siempre, y después de varios días cerrada Umbral pregunta una vez: *"¿Dejamos pasar a una sola persona hoy?"*
- **Marco:** **DBT, efectividad interpersonal (DEAR MAN)**, asertividad, **prevención de recaídas** y **activación conductual** (para no confundir el descanso con la evitación). La puerta nunca envía nada ni bloquea ninguna pantalla.
- **Estado:** **planificado** (etapa 6u).

### Otras mecánicas planificadas

- **M-ASCUA-CRECE:** Ascua crece solo con el tiempo compartido (nunca por rendimiento y nunca hacia atrás) y aprende gestos de las técnicas que le ayudaron a la persona, para hacerlas *con* ella. Las fuentes lo describen como "un espejo de autoeficacia" y "un vínculo afectivo sin necesidades ni culpa". *Planificado.*
- **M-ESTO-TIENE-NOMBRE:** psicoeducación cuando la Bruma dura 8 semanas o más. Dice que cuando el ánimo bajo dura mucho existe un nombre (distimia o trastorno depresivo persistente) y que tiene tratamiento, sin afirmar que la persona lo tenga, y ofrece preparar un informe. *Planificado* (etapa 7). Umbrales sin validar.
- **M-HORIZONTE:** las "Señales del Horizonte" solo funcionan si la persona las activa. Si duerme menos de 5 horas dos noches seguidas con energía alta, aparece una tarjeta suave que sugiere comentarlo con su profesional. *Planificado* (etapa 7).
- **M-INFORME:** un informe de una página para la consulta, en lenguaje clínico simple (ánimo, sueño, medicación, periodos en Refugio o Bruma, preguntas anotadas). La persona elige qué incluye y las notas personales quedan fuera por defecto. *Planificado* (etapa 8).

## 5. Fundamentos teóricos

Solo se nombran marcos que **aparecen en las fuentes del proyecto**. La descripción es deliberadamente conservadora: Estoy **toma ideas** de estos marcos para una herramienta de autoayuda. **No aplica** estas terapias ni tiene evidencia propia de eficacia.

| Marco | Qué es, en breve | Dónde lo usa Estoy | Cautela |
| --- | --- | --- | --- |
| **Activación conductual** | Intervención que reduce la evitación y aumenta de forma gradual las actividades con sentido o placer, registrando su efecto en el ánimo. | El radio del mundo por clima (`M-VENTANA`, `M-RADIO`), el tablón según la energía (`M-TABLON`), las brasas (`M-LENERA`), la predicción del disfrute (`M-POZO`) y los primeros pasos pequeños (`M-VIAJES`). | En terapia, la activación conductual se planifica con un profesional. Aquí es autoguiada y sin seguimiento. |
| **ACT: valores y acción comprometida** | Terapia de aceptación y compromiso: clarificar lo que importa y actuar en esa dirección aunque haya malestar. | Las estrellas como brújula (`M-ESTRELLAS`), las metas que cuelgan de valores (`M-VIAJES`) y los rastros (`M-RASTROS`). | Solo se usa el componente de valores. Otros procesos de ACT, como la defusión, no se nombran en las fuentes. |
| **DBT: efectividad interpersonal (DEAR MAN)** | Habilidades para pedir algo o decir que no manteniendo la relación y el respeto propio. | El taller de frases y el ensayo de Umbral (`M-UMBRAL`). | *Planificado.* Las fuentes no citan otros módulos de DBT, como la tolerancia al malestar. |
| **Intenciones de implementación y hábitos mínimos** | Planes "si o cuando X, entonces Y" y versiones muy pequeñas de una conducta para facilitar empezar. | El ancla "Después de…" y la versión mínima (`M-HUERTO`), y el paso de 2 minutos (`M-VIAJES`). | Su evidencia viene sobre todo de la investigación en hábitos, no de la clínica. |
| **Autocompasión** | Tratarse con amabilidad ante la dificultad en lugar de con autocrítica. | La versión mínima que también cuenta, lo que nunca se marchita y la ausencia de culpa. | Es un principio del diseño. No hay ejercicios formales de autocompasión. |
| **Presupuesto de energía** | Ajustar la carga del día a la energía disponible. | El maná (`M-TABLON`). | Las fuentes no lo vinculan explícitamente con la "teoría de las cucharas". |
| **Psicoeducación** | Información comprensible sobre lo que le pasa a la persona y sobre sus opciones de ayuda. | "Esto tiene nombre" (`M-ESTO-TIENE-NOMBRE`), el texto sobre ACT, la evidencia propia del grimorio y el bestiario. | Nunca debe parecer un diagnóstico. Los textos están pendientes de revisión clínica. |
| **Anclaje sensorial y respiración pausada** | Técnicas para volver al presente y bajar la activación: 5·4·3·2·1, presión y respiración con exhalación larga. | `M-CALMA`, `M-RESPIRAR` y `M-ARROYO`. | Son técnicas de apoyo, no tratamiento. |
| **Prevención de recaídas** | Identificar señales y preparar en un buen momento lo que se hará en uno malo. | Las reglas de la casa (`M-UMBRAL`, planificado), la despensa y la carta para los días de nieve (`M-DESPENSA`). | Las fuentes lo nombran sobre todo para los límites. |
| **Tamizaje breve (ítem 9 del PHQ-9)** | Pregunta estandarizada sobre ideación suicida y autolesión. | `M-CUIDADO`. | Se usa solo para dar acceso a ayuda, nunca para diagnosticar. |
| **Autonomía, competencia y vínculo** | Las tres bases de la motivación que el concepto declara (coinciden con la teoría de la autodeterminación, que las fuentes no nombran). | La ética de la gamificación: la persona elige, se vuelve capaz y no está sola. | Es un marco de diseño, no clínico. |

**Lo que Estoy no es:** no es psicoterapia, no es un tratamiento, no es una herramienta diagnóstica, no es un dispositivo médico (el límite legal entre app de bienestar y dispositivo médico está *pendiente de revisión con un abogado*) y no reemplaza la atención profesional. No tiene evidencia de eficacia: el piloto busca aprender qué ayuda, qué molesta y qué no se entiende.

## 6. Seguridad, privacidad y límites

**Acceso a crisis y ayuda**
- "Ayuda" está en la franja fija de todas las escenas y se abre al instante. "Necesito ayuda ahora" está dentro de Calma.
- Ayudas de Chile: \*4141 (prevención del suicidio), 131 (SAMU), Salud Responde 600 360 7777 y una persona de confianza que la persona elige. **Deben verificarse con fuentes oficiales antes del piloto.**
- En los momentos serios (cuidado, ayuda, Calma, remedios e informe) la fantasía se retira y no habla ningún personaje.

**Lo que la app nunca hace**
- Diagnosticar o interpretar ("pareces deprimido").
- Leer o analizar el texto libre de notas y diario, ni detectar palabras clave.
- Avisar a nadie automáticamente ni enviar nada sin una acción de la persona.
- Cambiar el clima sola, cerrar lugares o castigar la ausencia.
- Dar instrucciones sobre dosis de medicación.
- Usar rachas, rankings, recompensas al azar, rojos de alarma, globos con números o notificaciones de culpa.
- Cobrar por funciones de crisis.

**Arte y estímulos**
- No hay hojas ni herramientas afiladas, ni acantilados o caídas, porque pueden ser estímulos de riesgo. Todavía queda arte provisional por corregir: un mirador con un acantilado cubierto por niebla y pozos abiertos.
- Nada destella ni rebota. Con movimiento reducido, nada se mueve.

**Privacidad de los datos** (confirmado en el código)
- Todos los datos se guardan **solo en el dispositivo**: SQLite en Android e IndexedDB en el navegador. No hay cuentas, servidor, analítica ni telemetría.
- El respaldo automático de Android está desactivado para que los datos de salud no se suban sin decisión de la persona.
- La versión web del piloto es privada (acceso con código de un solo uso).
- **Límite actual:** el respaldo cifrado con frase todavía no está construido (etapa 9; revisado en el código el 25 de octubre). Si se borran los datos del navegador o se pierde el teléfono, hoy se pierde la historia.

**Límites de la app**
- No hay supervisión clínica ni seguimiento entre sesiones.
- La pregunta de cuidado se hace solo al inicio.
- Las reglas clínicas (umbrales, sugerencias, el estado mixto) son un borrador escrito por una IA y **no están validadas**.
- El aviso "Estoy no reemplaza la terapia", que el diseño del piloto exige en Ajustes, **no aparece todavía en el código** (revisado el 25 de octubre).

## 7. Estado actual del proyecto

La versión web privada está publicada con la etapa 6g (metas guiadas). La etapa 6r (movimiento y espacios) se está construyendo ahora, en una rama aparte, y todavía no está publicada.

**Construido** (versión web privada y base Android, con pruebas automáticas):
- La base: almacenamiento local, accesibilidad, lenguaje simple, el inicio con Olmo, las reglas clínicas en borrador, el protocolo de cuidado, "Estoy", la ventana y el registro único.
- Calma, respirar con Ascua y sus alternativas, y la mesa común (temporizador).
- La botica (recordatorios locales).
- La habitación: diario, grimorio, bestiario, ático, baúl, despensa, santuario y mapa.
- Afuera: el tablón con maná, la leñera, el pozo, el prado, el arroyo, el lago, la colina, el mirador, la encrucijada y la expedición "sin destino".
- El mundo caminable con escenas, la franja fija y la lista de lugares; los personajes con arte provisional; el diálogo (6d); el huerto de hábitos (6h).
- **Etapa 6g:** las metas guiadas con Brin, el sendero dorado en el valle, "Encontrar tus estrellas" con Olmo, "Tu cielo" con estrellas propias y el diario que guarda lo hecho por cada estrella.

**En construcción:** la etapa 6r, movimiento y espacios (`M-MUNDO-6R`): escenas de frente con arte nuevo, el cielo según el clima, caminar en una línea, la fila de carteles, las flechas a los vecinos, el Camino lateral y la Encrucijada dividida.

**Planificado:**
- Umbral y la puerta (6u), Ascua crece (6a) y el arte definitivo.
- Etapa 7: sugerencias de cambio de clima, "Esto tiene nombre", Señales del Horizonte y el descubrimiento gradual de lugares.
- Etapa 8: el informe para la consulta y el escritorio (notas para la sesión, "lo que me llevé" y la carta).
- Etapa 9: widget, acceso rápido a Calma, Health Connect y respaldo cifrado.
- Etapa 10: entrega del piloto.

**Sin validar:**
- **La revisión clínica completa, que es bloqueante:** el borrador de reglas clínicas, la pregunta de cuidado y su protocolo, la botica, los textos de la habitación (grimorio, bestiario, la Niebla, hitos y valores), los anclajes del arroyo, las descripciones de los valores y las sugerencias de "Hice algo".
- Los textos nuevos de 6d, 6h y 6g, pendientes de aprobación del autor.
- La verificación de los recursos de ayuda en Chile.
- Las pruebas con personas neurodivergentes (prueba de primer clic y de árbol con 5 a 8 personas).
- Las conversaciones con 2 o 3 profesionales sobre qué quieren ver en el informe.
- Las pruebas con TalkBack, con el texto al máximo y de recordatorios en teléfonos reales (Samsung, Xiaomi, Motorola), en una pasada Android pendiente.
- La revisión legal de la privacidad de los datos de salud y del límite con un dispositivo médico.

## 8. Preguntas para el o la profesional

1. **Riesgos clínicos.** ¿Qué riesgos ve en una app autoguiada como esta para personas en crisis, con ánimo bajo prolongado o con energía alta?
2. **Pregunta de cuidado (`M-CUIDADO`).** ¿Son adecuados el texto, las opciones y las tres acciones? ¿Esperar 10 segundos antes de "Seguir al Refugio" ayuda o se siente como una trampa? ¿Conviene repetir la pregunta en algún momento, por ejemplo al entrar al Refugio?
3. **Reglas de sugerencia (`M-INICIO`).** ¿Es razonable el orden de las reglas, en especial el "estado mixto posible"? ¿Sirve detectar energía alta con una sola opción de respuesta?
4. **Lenguaje.** ¿Hay frases que podrían dañar, culpar o confundir? Por ejemplo: "Estar aquí ya cuenta", "retirarte no es rendirte", "Escucharla no es creerle" o la afirmación del bestiario sobre nombrar emociones.
5. **Mecánicas y evidencia.** ¿Qué mecánicas le parecen coherentes con la evidencia y cuáles podrían contradecirla? Por ejemplo: el radio del mundo por clima, la puerta cerrada por defecto en el Refugio, no empezar viajes nuevos en Refugio o Bruma, y la predicción y comparación del disfrute.
6. **Números.** ¿El conteo del grimorio ("9 de 11"), la comparación del pozo y la escala del sol de −3 a +3 ayudan o pueden alimentar la rumiación y la autoevaluación?
7. **Poblaciones.** ¿A quién debería excluir el piloto o dejarle claro que no es para él o ella? Por ejemplo: riesgo suicida activo, trastorno bipolar sin tratamiento, trastornos de la conducta alimentaria, psicosis o menores de edad.
8. **Umbrales.** ¿Son adecuados 8 semanas para "Esto tiene nombre" y menos de 5 horas durante 2 noches para la señal del sueño?
9. **Botica.** ¿Es suficiente el texto para dosis olvidadas? ¿Hay riesgos en los recordatorios?
10. **Vínculo con los personajes.** ¿Ve riesgo de dependencia o de sustitución del vínculo humano en Ascua o en los otros personajes?
11. **Informe para la consulta (`M-INFORME`).** ¿Qué le gustaría ver en un informe de una página y qué no?
12. **Evaluación del piloto.** ¿Cómo evaluaría el piloto: qué preguntar en la entrevista final, qué señales de daño vigilar y qué instrumentos breves (si alguno) usar, sabiendo que la app no mide nada dentro de ella?
13. **Lo que falta.** ¿Qué echa en falta para que se pueda recomendar con tranquilidad a un o una paciente como complemento?
14. **Valores con guía (`M-ESTRELLAS`).** Olmo propone diez valores fijos, uno a la vez, con una descripción breve. ¿Elegir valores con esa guía puede llevar a adoptar valores "correctos" en vez de propios? ¿Son adecuadas las descripciones y el límite de ocho estrellas?
15. **Metas guiadas y presión (`M-VIAJES`).** ¿Las preguntas de Brin, el sendero con banderas y "El paso de hoy" pueden sentirse como una obligación diaria en un mal día? ¿Bastan "Más chiquito", "Para más adelante" y el descanso en el Refugio para evitarlo?
16. **La luz de las estrellas.** La luz nunca baja, pero crece con lo hecho. ¿Puede leerse como una puntuación encubierta o llevar a comparar estrellas entre sí?
17. **Viajes en Refugio y Bruma.** Hoy los viajes se pueden ver y cambiar con cualquier clima, pero uno nuevo se guarda para más adelante en el Refugio y la Bruma. ¿Le parece adecuada esa regla, o debería permitirse empezar un viaje muy pequeño?
18. **El mundo nuevo (`M-MUNDO-6R`, en construcción).** ¿Ve ventajas o riesgos en menos carteles por escena, en las flechas a los vecinos y en un Camino donde "más lejos" depende del clima? ¿Puede el cambio de un mundo ya conocido desorientar a alguien en un mal día?

## 9. Preguntas abiertas y tensiones conocidas

Están tomadas de las fuentes del proyecto y del contraste con el código.

**Brechas conocidas entre el diseño y la app:**

| Brecha | Estado | Qué se encontró |
| --- | --- | --- |
| El aviso "Estoy no reemplaza la terapia" | Abierta | No aparece en ningún texto de la app. La ACT se nombra una vez, pero no el aviso. |
| Números en el diario, el grimorio y el pozo | Abierta | El diario cuenta llegadas, días de descanso y respiros. El grimorio dice "Te ayudó 9 de 11 veces". El pozo muestra "Predicción: 2 de 5" y "esperabas 2, fue 4". Los viajes, las estrellas y el cielo no muestran cifras. |
| La fuente para dislexia | Abierta | Solo están Young Serif y Atkinson Hyperlegible. No hay ajuste de fuente. |
| El respaldo cifrado | Abierta | No existe todavía (etapa 9). El respaldo automático de Android está desactivado. |

**Tensiones:**

1. **"Sin números" frente a los números que existen.** La guía prohíbe los contadores. Los viajes, las estrellas y el cielo no usan cifras, ni siquiera escritas en palabras. Pero hay conteos en el diario ("0 veces llegaste a la posada", "días de descanso"), la evidencia del grimorio ("9 de 11 veces"), la comparación del pozo ("esperabas 2, fue 4"), la línea del santuario ("N piedras", una excepción explícita del autor), la frecuencia del huerto ("3 veces por semana, cuando puedas") y la escala del sol de −3 a +3 (opcional, pensada para el informe). En las metas guiadas quedan dos excepciones: "un primer paso de 2 minutos" y las velas "Primera pregunta de cuatro".
2. **El registro y la rumiación.** El concepto reconoce que mirar el ánimo a diario puede aumentar la rumiación. Se resolvió con una escala opcional, pero no hay criterio sobre a quién desaconsejarla (*por definir*).
3. **Descanso o evitación.** El Refugio dice "Hoy no hace falta salir" y la puerta estará cerrada por defecto en el Refugio. La activación conductual advierte contra la evitación. Las salvaguardas previstas son que las personas de confianza pasan siempre y que Umbral pregunta "¿Dejamos pasar a una sola persona hoy?". Falta validarlo.
4. **Reglas clínicas escritas por una IA.** Todo el borrador (sugerencias, umbrales, estado mixto, límite de viajes y frecuencia de la tarjeta de ayuda) lo redactó un asistente de IA en el rol de psiquiatra. No es criterio clínico.
5. **La pregunta de cuidado solo al inicio.** Se decidió no repetirla porque sería intrusiva y sin supervisión no está claro que ayude. A cambio, se ofrece la ayuda (no se pregunta) cuando hay −3 tres veces seguidas o al entrar al Refugio. Está abierto.
6. **Los 10 segundos antes de "Seguir al Refugio".** Pueden proteger de saltar la pantalla por reflejo o sentirse como una trampa.
7. **"Esto tiene nombre" a las 8 semanas.** El criterio clínico de la distimia exige dos años. La pantalla adelanta la invitación a consultar sin afirmar un diagnóstico.
8. **Energía alta e hipomanía.** Se detecta con una opción de respuesta y con el medidor del registro. La respuesta es solo limitar los viajes y sugerir hablarlo con un profesional. ¿Basta?
9. **No empezar viajes en el Refugio y la Bruma.** Ya está construida. Nada se cierra: el viaje nuevo se guarda "para más adelante", los activos descansan y "Dar un paso igual" sigue ahí. La regla todavía no tiene revisión clínica.
10. **Afirmaciones de eficacia en los textos.** El bestiario afirma que nombrar una emoción baja su intensidad. Los textos marcados como "clinical copy" en el código están pendientes de revisión.
11. **El aviso "no reemplaza la terapia".** El diseño del piloto lo exige en Ajustes, pero todavía no está en el código.
12. **Vínculo afectivo con Ascua.** El autor quiere que se forme un vínculo afectivo y la regla es "sin necesidades ni culpa". Falta criterio clínico sobre el apego a un personaje.
13. **Los recursos son de Chile y el idioma es español neutro.** Si la app se usa fuera de Chile, los números de ayuda no sirven (*por definir*).
14. **Población objetivo amplia.** "Personas neurodivergentes" abarca perfiles muy distintos. No hay criterios de inclusión ni de exclusión para el piloto (*por definir*).
15. **Sin medición dentro de la app.** El piloto aprende solo por entrevistas. Las métricas del concepto (tasa de regreso, utilidad percibida, uso temprano y estabilidad) son para después, y cómo evaluar el piloto está *por definir*.
16. **Pérdida de datos.** Sin el respaldo cifrado (etapa 9), un navegador o un teléfono perdido borra la historia. Además, las respuestas a medias de Brin viven solo mientras la app sigue abierta: si se reinicia, se pierden.
17. **Arte que todavía no cumple la regla de seguridad.** Un mirador con un acantilado cubierto por niebla, pozos abiertos y un tronco con un mango que parece un hacha. Se corregirá con el arte definitivo.
18. **Límite legal.** Falta definir con un abogado el límite entre app de bienestar y dispositivo médico.
19. **Plataforma.** El concepto original es para iPhone, pero el piloto es Android y web. iOS nativo vendría después.
20. **Validación con personas neurodivergentes.** El principio "nada sobre nosotros sin nosotros" exige validar durante el diseño, pero las pruebas con 5 a 8 personas todavía no se hicieron.
21. **La fuente para dislexia.** Está en el diseño del piloto, pero la app solo tiene Young Serif y Atkinson Hyperlegible.
22. **Valores guiados.** Los diez valores fijos y sus descripciones los escribió el proyecto, y Olmo los propone. Puede orientar o puede sugerir qué "debería" importar. Las descripciones esperan revisión clínica.
23. **Metas guiadas y presión.** El paso de hoy, las banderas y la luz que crece invitan a avanzar. Las salvaguardas son que nada vence, la versión mínima cuenta igual y la luz nunca baja. Falta saber si basta en un mal día.
24. **El mundo nuevo de la 6r** (en construcción) cambia la forma de moverse y quita carteles. Busca menos carga y más previsibilidad, pero quien ya aprendió el mundo anterior tendrá que reaprenderlo.

## Anexo · Imágenes

| Archivo | Origen | Qué muestra |
| --- | --- | --- |
| `img/01-recepcion-olmo.jpg` | App real | Olmo en la recepción, con "Encontrar tus estrellas" |
| `img/02-salon-refugio.jpg` | App real | El salón en el Refugio |
| `img/03-salon-bruma.jpg` | App real | El salón en la Bruma |
| `img/04-salon-expedicion.jpg` | App real | El salón en la Expedición |
| `img/05-ventana-camino.jpg` | App real | La ventana para elegir el clima |
| `img/06-mapa-valle.jpg` | App real | El mapa del valle |
| `img/07-brin-dialogo.jpg` | App real | La presentación de Brin |
| `img/08-huerto.jpg` | App real | El huerto de hábitos |
| `img/09-huerto-regar.jpg` | App real | Regar un hábito |
| `img/10-calma.jpg` | App real | Calma |
| `img/11-respirar-ascua.jpg` | App real | Respirar con Ascua |
| `img/12-diario.jpg` | App real | El diario |
| `img/13-ayuda.jpg` | App real | Dónde pedir ayuda |
| `img/14-pantalla-cuidado.jpg` | App real | La pantalla de cuidado |
| `img/15-viaje-en-marcha.jpg` | App real | El viaje en marcha: sendero dorado y "El paso de hoy" |
| `img/16-maqueta-puerta-umbral.jpg` | Maqueta | Umbral y la puerta (planificado) |
| `img/17-brin-pregunta.jpg` | App real | La segunda pregunta de Brin: "¿Por qué te importa?" |
| `img/18-viaje-refugio.jpg` | App real | Un viaje que descansa en el Refugio |
| `img/19-tu-cielo.jpg` | App real | "Tu cielo" con dos estrellas |
| `img/20-diseno-salon-bruma.jpg` | Diseño en construcción (6r) | El salón con la fila de carteles y las flechas |
| `img/21-diseno-camino-mirador.jpg` | Diseño en construcción (6r) | El Camino lateral y la pregunta del Mirador |
