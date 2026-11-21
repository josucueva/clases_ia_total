# Estructura del curso en Moodle — IA Total

## Esquema de cada sesión

Cada sesión es una sección de Moodle cuyo nombre es el tema de la sesión, escrito como pregunta:

| Sección | Nombre en Moodle |
|---|---|
| Sesión 1 | ¿Qué es la inteligencia artificial? |
| Sesión 2 | ¿Cómo pedirle ayuda a la IA? |
| Sesión 3 | ¿Cómo crea imágenes, audio y video la IA? |

Dentro de cada sección van los mismos elementos y en este orden:

| Orden | Elemento | Tipo de recurso | Visible para estudiantes |
|---|---|---|---|
| 1 | Introducción a la sesión | Área de texto y medios | Sí |
| 2 | Video | URL | Sí |
| 3 | Presentación | Archivo (PDF) | Sí |
| 4 | Tareas de la sesión, si las hay | Tarea | Sí |
| 5 | Plan de la sesión | Archivo (PDF) | No, oculto |

Los recursos ocultos, como el plan, quedan dentro de la misma sección: solo los ve el equipo docente.

Además de las secciones de cada sesión, el curso tiene dos secciones fijas al inicio: **General** y **Proyecto final**.

---

## General

| Elemento | Tipo | Configuración |
|---|---|---|
| Avisos | Foro de anuncios (viene creado) | Solo publica el equipo docente. Un aviso antes de cada sábado. |
| Foro de dudas | Foro, tipo «Foro para uso general» | Los estudiantes pueden abrir temas. |

---

## Proyecto final

Antes de crear esta sección, arma los equipos en *Participantes → Grupos*: un grupo por equipo de proyecto y un agrupamiento **«Equipos del proyecto»** que los incluya a todos.

| Orden | Elemento | Tipo | Configuración |
|---|---|---|---|
| 1 | Introducción | Área de texto y medios | Texto abajo. |
| 2 | Foro de mi equipo | Foro | *Modo de grupo:* grupos separados. *Agrupamiento:* Equipos del proyecto. Cada equipo solo ve el suyo. |
| 3 | Estado de los proyectos | Archivo o enlace a hoja de cálculo, **oculto** | Una fila por equipo y una columna por sesión: idea clara, en definición o sin avance. |

**Introducción:**

> En equipos de 4 o 5 personas, van a diseñar un proyecto que use inteligencia artificial para resolver un problema real de San Juan Bosco o de Morona Santiago, y lo presentarán en la Feria Comunitaria. Cada sesión empieza con 2 minutos por equipo para contar cómo va el proyecto. Entre sesiones, suban en la tarea de avance lo que se les pide y usen el foro de su equipo para organizarse. Si entrevistan a alguien, no suban su nombre, teléfono ni fotos sin su permiso.

---

## ¿Qué es la inteligencia artificial? (sesión 1, ya publicada)

Ya tiene introducción, video, presentación y plan oculto. Solo falta una cosa:

| Orden | Elemento | Tipo | Configuración |
|---|---|---|---|
| 4 | Avance 1 · Información para el proyecto | Tarea | *Entrega en grupo:* sí. *Agrupamiento:* Equipos del proyecto. *Entrega:* texto en línea y archivos. *Fecha límite:* el día antes de la sesión 2. |

**Instrucciones de Avance 1:**

> Suban la información que recolectaron para su proyecto:
> 1. ¿Qué problema quieren resolver y a quién afecta?
> 2. ¿Qué información consiguieron? (notas, datos, entrevistas, fotos de lugares)
> 3. ¿De dónde salió cada dato?
>
> Quiten nombres y teléfonos de las personas entrevistadas. Esta información la usarán en la sesión 2.

La sesión 1 ya pasó, pero conviene crear esta tarea igual: así lo recolectado queda guardado y en la sesión 2 lo tienen a mano para el podcast de NotebookLM.

> **Antes de mantener publicada la presentación de la sesión 1:** tiene dos diapositivas «Mentimeter →» (después de «La IA en nuestra vida» y antes de «¿Qué aprendimos hoy?»). Conviene quitarlas o cambiarlas.

---

## ¿Cómo pedirle ayuda a la IA? (sesión 2)

| Orden | Elemento | Tipo | Configuración |
|---|---|---|---|
| 1 | Introducción | Área de texto y medios | Texto abajo. |
| 2 | Video: ¿cómo escribir un buen prompt? | URL | Ver criterios abajo. |
| 3 | Presentación de la sesión 2 | Archivo | `sesion2/presentation/presentation_2.pdf` |
| 4 | Tarea escolar con IA | Tarea | Individual. *Entrega:* texto en línea. *Fecha límite:* el día antes de la sesión 3. |
| 5 | Avance 2 · Lo que nos faltaba averiguar | Tarea | *Entrega en grupo:* sí. *Agrupamiento:* Equipos del proyecto. *Entrega:* texto en línea y archivos (acepta .mp3). *Fecha límite:* el día antes de la sesión 3. |
| 6 | Plan de la sesión 2 | Archivo, **oculto** | `sesion2/plan/plan_sesion_2.pdf` (incluye la lista de cotejo). |

**Introducción:**

> En esta sesión aprendemos a pedirle ayuda a la IA con claridad y a revisar lo que responde. Vamos a ver por qué una IA puede decir algo falso con total seguridad, a usar la fórmula de un buen prompt (rol, tarea, contexto, formato, tono y límite) y a practicarla en correos, documentos y hojas de cálculo. También probaremos herramientas como NotebookLM, Perplexity y Google Slides para avanzar en el proyecto final.
>
> **Para traer:** la información que su equipo recolectó para el proyecto.
>
> **Plantilla de la sesión:**
> Actúa como [rol]. Necesito que [tarea]. El contexto es [información clave]. El resultado debe estar en formato [correo / tabla / lista / informe]. Usa un tono [formal / amable / institucional / directo]. Limita la respuesta a [número de palabras / párrafos / puntos].

Dejé la plantilla en la introducción para que puedan copiarla después de clase sin abrir la presentación.

**Criterios para elegir el video:**
- En español y de menos de 8 minutos.
- Explica qué es un prompt y muestra la diferencia entre una petición vaga y una completa.
- Si es posible, menciona que la IA puede equivocarse y que hay que revisar.
- Es para ver antes o después de clase, no durante.

**Instrucciones de Tarea escolar con IA:**

> Usa una IA para preparar o mejorar una tarea real de esta semana, de cualquier materia. Responde aquí:
> 1. ¿Qué le pediste? Copia tu prompt.
> 2. ¿Qué cambiaste de lo que te respondió?
> 3. ¿Qué comprobaste y dónde?
>
> No pegues la tarea completa ni la respuesta larga de la IA: solo lo que se pide.

**Instrucciones de Avance 2:**

> En clase, la IA les hizo preguntas sobre su proyecto y anotaron las que no supieron responder. Averigüen esas respuestas y suban:
> 1. Las preguntas que quedaron pendientes.
> 2. Lo que averiguaron para cada una y de dónde lo sacaron.
> 3. Opcional: el podcast de NotebookLM, descargado en .mp3.
>
> Esto es lo que van a contar en los 2 minutos de avance de la sesión 3.

El podcast se sube como archivo y no como enlace de NotebookLM: así nadie tiene que compartir su cuaderno ni su cuenta.

---

## ¿Cómo crea imágenes, audio y video la IA? (sesión 3)

| Orden | Elemento | Tipo | Configuración |
|---|---|---|---|
| 1 | Introducción | Área de texto y medios | Texto abajo. |
| 2 | Video: ¿cómo crea imágenes una IA? | URL | Ver criterios abajo. |
| 3 | Presentación de la sesión 3 | Archivo | `sesion3/presentation/presentation_3.pdf` |
| 4 | Mi imagen y uso responsable | Tarea | Individual. *Entrega:* texto en línea y un archivo de imagen. *Fecha límite:* el día antes de la sesión 4. |
| 5 | Avance 3 · Piezas del proyecto | Tarea | *Entrega en grupo:* sí. *Agrupamiento:* Equipos del proyecto. *Entrega:* archivos (imagen, audio y video) y texto en línea. *Fecha límite:* el día antes de la sesión 4. |
| 6 | Plan de la sesión 3 | Archivo, **oculto** | `sesion3/plan/plan_sesion_3.pdf` (incluye la lista de cotejo). |

**Introducción:**

> En esta sesión la IA no solo escribe: también crea imágenes, voces y videos. Vamos a jugar a adivinar qué imágenes son reales y cuáles generadas, a entender cómo una IA pasa del ruido a una imagen y a usar una fórmula para pedir imágenes: sujeto, escena, estilo, encuadre, luz y color, y lo que hay que evitar. También convertiremos texto en voz y voz en texto, y cada equipo creará la portada, el logo, una locución y un reel de su proyecto.
>
> **Para traer:** el celular con la aplicación CapCut instalada (no hace falta crear cuenta) y una cuenta de Canva; se puede entrar con la cuenta de Google.
>
> **Fórmula para un prompt de imagen:**
> Sujeto + Escena + Estilo + Encuadre + Luz y color + Evita
> Ejemplo: «Un tucán sobre una rama junto a un río amazónico, ilustración plana, vista de cerca, luz de amanecer en tonos verdes y naranjas, sin texto».

**Criterios para elegir el video:**
- En español y de menos de 8 minutos.
- Explica de forma sencilla cómo una IA genera imágenes a partir de una descripción.
- Si es posible, muestra ejemplos de imágenes falsas o deepfakes y cómo reconocerlas.

**Instrucciones de Mi imagen y uso responsable:**

> 1. Sube tu mejor imagen de la clase y copia el prompt que usaste.
> 2. ¿Dónde publicarías esta imagen y cómo indicarías que la hizo una IA?
> 3. Piensa en un caso en el que usar una imagen, una voz o un video hecho con IA podría hacerle daño a alguien. ¿Qué harías para evitarlo?

**Instrucciones de Avance 3:**

> Suban las piezas de su proyecto:
> 1. La portada y el logo (imagen).
> 2. La locución (audio).
> 3. El reel de 30 segundos (video).
> 4. En el texto: los prompts que usaron para la portada y el logo.
>
> Revisen que cada pieza diga «Hecho con IA» y que no aparezcan caras ni voces de personas reales. En el avance de la sesión 4 cuentan qué cambiarían de estas piezas.

Revisa el tamaño máximo de archivo del curso en Moodle: un reel de 30 segundos suele pesar entre 10 y 40 MB. Si el límite es menor, permite que suban el video a Google Drive y peguen el enlace en el texto, con acceso «cualquier persona con el enlace».

---

## Próximas sesiones

Cada sesión nueva lleva como nombre su tema en forma de pregunta y repite el esquema: introducción, video, presentación, tareas (incluido el **Avance N** del proyecto como entrega en grupo) y el plan oculto al final.
