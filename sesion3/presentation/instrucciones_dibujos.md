# Instrucciones para generar las imágenes de la sesión 3

Cada bloque es un encargo independiente: copia únicamente el bloque de la imagen que quieras generar.

**Uso en la presentación:** guarda cada imagen en `sesion3/presentation/images/` con el nombre de archivo indicado y vuelve a compilar con `latexmk -g -xelatex presentation_3.tex`. La diapositiva la incluye automáticamente; mientras falte, se muestra un recuadro verde con el nombre del archivo.

| Diapositiva | Archivo | Tipo |
|---:|---|---|
| 1 | `portada-crear.png` | Ilustración, serie de las sesiones 1 y 2 |
| 3 | `equipo-proyecto.png` | Ya está (copiada de la sesión 2) |
| 4 | `real-o-generada-1.jpg` … `real-o-generada-6.jpg` | Tres fotografías reales y tres imágenes generadas |
| 6 | `del-ruido-a-la-imagen.png` | Ilustración, serie de las sesiones 1 y 2 |
| 19 | `publicar-con-cuidado.png` | Ilustración, serie de las sesiones 1 y 2 |

## Ilustraciones (diapositivas 1, 6 y 19)

Mantienen el estilo de las sesiones 1 y 2: diagramas vectoriales planos de íconos, proporción 8:5, sin personas y con rótulos cortos.

### Diapositiva 1 — IA que crea (`portada-crear.png`)

Genera una ilustración de proporción **8:5**, resolución mínima **1600 × 1000 píxeles**. Fondo transparente; si no es posible, blanco puro. Estilo vectorial educativo y plano: formas simples, esquinas redondeadas, contornos azul oscuro de grosor uniforme y espacio libre. Sin sombras, degradados, texturas, 3D, fotografías, robots, cerebros luminosos ni logotipos. Paleta exclusiva: azul oscuro `#224765`, azul claro `#D9E1F2`, verde claro `#DDEBE3`, gris claro `#F5F5F5`, blanco y casi negro `#191A20`.

En el centro, una **computadora portátil genérica** abierta; en su pantalla azul clara hay una pequeña chispa de cuatro puntas. De la pantalla salen, en abanico hacia arriba, **tres tarjetas flotantes iguales** unidas a la pantalla por líneas finas punteadas: (1) un marco de foto con un paisaje simple de colinas y un sol; (2) una onda de audio formada por cinco barras verticales de distinta altura; (3) un rectángulo de video con un triángulo de reproducción. En el borde derecho, dos hojas grandes de planta tropical en verde claro dan un toque amazónico discreto. No hay personas. **No incluyas texto.**

### Diapositiva 6 — Del ruido a la imagen (`del-ruido-a-la-imagen.png`)

Genera una ilustración de proporción **8:5**, resolución mínima **1600 × 1000 píxeles**, fondo transparente o blanco puro, con el mismo estilo vectorial plano y la misma paleta de la diapositiva 1, más naranja suave `#E8AD88` solo para el sol.

Dibuja **cuatro cuadros iguales en una fila**, unidos por tres flechas azul oscuro que apuntan a la derecha. Cuadro 1: lleno de puntos pequeños azul oscuro, azul claro y verde claro repartidos al azar, como estática. Cuadro 2: los puntos empiezan a agruparse en dos manchas difusas, una verde abajo y una azul clara arriba. Cuadro 3: las manchas ya forman colinas verdes, un cielo azul claro y un círculo naranja suave, todavía con algunos puntos sueltos. Cuadro 4: la misma escena terminada y limpia: colinas verdes, un río azul claro que las cruza, un sol naranja suave y dos árboles simples. Debajo del cuadro 1, el rótulo exacto **«Ruido»**; debajo del cuadro 4, el rótulo exacto **«Imagen»**. No agregues otras palabras. Si no puedes escribir los rótulos exactamente, deja sus zonas vacías.

### Diapositiva 19 — Antes de publicar (`publicar-con-cuidado.png`)

Genera una ilustración de proporción **8:5**, resolución mínima **1600 × 1000 píxeles**, fondo transparente o blanco puro, con el mismo estilo vectorial plano y la misma paleta de la diapositiva 1.

En el centro, un **teléfono genérico** vertical que muestra una publicación: un marco de imagen con un paisaje simple de colinas y, en su esquina inferior, una **etiqueta pequeña con una chispa de cuatro puntas** (indica que se hizo con IA). Alrededor del teléfono, cuatro íconos circulares del mismo tamaño, separados y en equilibrio: (1) una chispa dentro de un círculo verde claro; (2) una silueta circular de persona con un candado pequeño azul oscuro; (3) una paleta de pintor con un pequeño símbolo de prohibido; (4) una lupa sobre un marcador de mapa. No dibujes personas completas ni cruces rojas. **No incluyas texto.**

## Fotografías reales y generadas (diapositiva 4)

La actividad «¿Real o generada?» necesita seis imágenes: **tres fotografías reales y tres generadas**, mezcladas. Guarda todas en formato **JPG**, recortadas en proporción **8:5** (por ejemplo, 1600 × 1000 píxeles), para que tengan el mismo tamaño en la diapositiva. Anota aparte cuáles son reales.

Orden sugerido:

| Número | Imagen |
|---:|---|
| 1 | Fotografía real |
| 2 | Generada A |
| 3 | Fotografía real |
| 4 | Generada B |
| 5 | Generada C |
| 6 | Fotografía real |

**Fotografías reales:** de San Juan Bosco o de la Amazonía, tomadas por el equipo docente o con permiso de uso. Conviene que tengan los mismos temas que las generadas (río, mercado, paisaje) para que no sea fácil distinguirlas por el tema. Que no aparezcan caras reconocibles de estudiantes ni de otras personas.

Las imágenes generadas deben verse como fotografías. Cada una deja una pista distinta, que coincide con la diapositiva 5. No agregues instrucciones de estilo vectorial a estos prompts.

### Generada A — Río (`real-o-generada-2.jpg`)

Fotografía realista de un río amazónico ancho al atardecer, con una canoa de madera vacía amarrada a la orilla y selva densa al fondo. Luz dorada, agua muy quieta que refleja el cielo, colores intensos y saturados, todo perfectamente limpio y ordenado. Formato horizontal 8:5. Sin personas y sin texto.

> Pista esperada: «demasiado perfecto» (reflejos impecables, colores exagerados).

### Generada B — Mercado (`real-o-generada-4.jpg`)

Fotografía realista, vista de cerca, de dos manos de una vendedora sosteniendo una cesta con frutas amazónicas (pitahaya, naranjilla, chontaduro) en un mercado al aire libre, con otros puestos desenfocados al fondo. Luz natural de mañana. Formato horizontal 8:5. Que no se vea la cara de ninguna persona.

> Pista esperada: «manos y dedos» (revisa que el resultado tenga alguna mano o dedo extraño; si sale perfecto, genera otra vez).

### Generada C — Letrero (`real-o-generada-5.jpg`)

Fotografía realista de la entrada de un sendero en la selva amazónica, con un letrero de madera que dice «Bienvenidos a San Juan Bosco», árboles altos, helechos y un camino de tierra húmedo. Luz suave entre las hojas. Formato horizontal 8:5. Sin personas.

> Pista esperada: «texto» (las letras del letrero suelen salir deformes o con errores).
