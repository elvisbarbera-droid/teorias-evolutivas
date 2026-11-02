# Turno de Residencia · Guía docente

Juego 3D en primera persona para **Ciencias Naturales**. El estudiante es un médico o médica residente que recorre un hospital con su libreta, atiende pacientes y estudia gráficos, maquetas y modelos gigantes. Las **15 preguntas del cuestionario de Biología** (pubertad, sistema reproductor, hormonas, investigación científica y métodos anticonceptivos) están en las consultas y salas de estudio. Con **10 respuestas correctas de 15** se abre el **Pabellón ITS**, donde hay **5 preguntas más sobre VIH y SIDA**: qué es el VIH, qué es el SIDA, su origen, las infecciones oportunistas y la transmisión.

Archivo del juego: `hospital-residencia/index.html` (un solo archivo, sin instalación).

---

## 1. Objetivos de aprendizaje

| Eje | Lo que el estudiante practica en el juego |
|---|---|
| Pubertad y hormonas | Reconocer caracteres sexuales secundarios, leer gráficos de testosterona, estrógenos, LH y FSH, y valorar las dimensiones biológica, afectiva y social de la pubertad. |
| Sistema reproductor y gametos | Relacionar estructura y función (epidídimo, uretra, ovario, endometrio) y comparar ovocito y espermatozoide. |
| Investigación científica | Distinguir preguntas investigables de opiniones o valores e identificar variables independiente, dependiente y controladas. |
| Métodos anticonceptivos | Clasificar métodos por su mecanismo, interpretar tasas de falla y corregir mitos sobre la pastilla, la vasectomía y la ligadura. |
| ITS, VIH y SIDA | Identificar agentes causales (virus, bacteria, parásito), diferenciar VIH y SIDA, conocer su origen, las infecciones oportunistas y las vías de transmisión. |

## 2. Cómo abrirlo

| Dispositivo | Qué hacer |
|---|---|
| Teléfono Android o iPhone | Abrir el enlace del juego en **Chrome** o **Safari**. Conviene girar el teléfono en horizontal. |
| Computador | Abrir el enlace en Chrome, Edge, Firefox o Safari. |
| Google Classroom | Publicar el enlace como **Material** o dentro de una **Tarea**. |
| Google Meet | Abrir el juego en una pestaña y usar **Presentar → Una pestaña** para jugarlo en vivo con el curso. |
| Google Drive | Drive guarda el archivo pero **no lo ejecuta**. Compartan el **enlace web** del juego, no el archivo `.html` subido a Drive. |

Requisitos: navegador actualizado con gráficos 3D (WebGL) y conexión a internet al abrirlo. El progreso se guarda solo en ese navegador.

**Controles**

| En el teléfono | En el computador |
|---|---|
| Círculo de la izquierda: caminar | W A S D o flechas: caminar |
| Deslizar el dedo a la derecha: mirar | Arrastrar con el mouse: mirar |
| Botón amarillo: atender / estudiar | Tecla E: atender · M: mapa · N: libreta |

## 3. Estructura del hospital

| Zona | Sala | Contenido | Preguntas del cuestionario |
|---|---|---|---|
| Hall central | Admisión | La enfermera Rosa explica el turno. | — |
| Puertas izquierdas | Consulta 101 · Camila, 13 años | Ficha de control de salud | N° 1 |
| | Consulta 102 · Matías, 13 años | Diagrama de las 3 dimensiones de la pubertad | N° 3 |
| | Consulta 103 · Valentina, 17 años | Mensaje del diario mural | N° 11 |
| | Consulta 104 · Roberto, 38 años | Esquema del testículo y los conductos | N° 12 |
| | Consulta 105 · Patricia, 39 años | Útero con trompas ligadas | N° 14 |
| Puertas derechas | Laboratorio 201 · Hormonas | Pantalla que traza los gráficos y gráfico 3D de hormonas | N° 2 y 8 |
| | Sala 202 · Anatomía | Maquetas gigantes femenina y masculina; ovocito y espermatozoide a la misma escala | N° 4 y 5 |
| | Laboratorio 203 · Investigación | Espermatozoide gigante con mitocondrias, jaulas del experimento con 3 dosis | N° 6, 7 y 9 |
| | Sala 204 · Métodos | Diafragma e inyección gigantes, gráfico de barras 3D de fallas | N° 10 y 13 |
| | Sala 205 · Microbiología | Vitrinas con gonorrea, VPH y tricomonas | N° 15 |
| Fondo del pasillo | Pabellón ITS (bloqueado) | Se abre con 10 correctas de las 15. | — |
| Pabellón ITS | Box 301 · Tomás | ¿Qué es el VIH? Virus gigante en vitrina | 16 |
| | Box 302 · Héctor | ¿Qué es el SIDA? Linfocito CD4 atacado | 17 |
| | Box 303 · Ricardo | Origen del VIH. Globo terráqueo con África central | 18 |
| | Box 304 · Fernanda | Infecciones oportunistas. Tuberculosis y Candida | 19 |
| | Espacio Amigable 305 · Ignacia | Transmisión del VIH | 20 |

**Luces sobre las puertas:** azul = por atender · amarilla = en curso · verde = todo correcto · naranja = con errores · roja (parpadea) = repasar.

**Si un estudiante no llega a 10:** al responder las 15 preguntas sin alcanzar 10 correctas, las salas con errores se ponen en rojo y permiten responder de nuevo solo lo fallado (con las opciones en otro orden). El certificado final muestra el puntaje **al primer intento**, sobre 20.

## 4. Cómo se adaptaron las preguntas del cuestionario

- Cada pregunta conserva **el caso original** del cuestionario (aparece en un recuadro) y lleva **un gráfico o dibujo** que se ve en la libreta y en las láminas de la sala.
- Como el juego es de **selección simple**, cada pregunta abierta se transformó en 4 opciones con **una sola correcta**. En las preguntas que pedían identificar varias cosas (N° 4, 7, 10 y 15), cada opción presenta la clasificación completa.
- Las opciones tienen largos parecidos y **la correcta nunca es la más larga** (verificado con un script sobre las 20 preguntas). El orden se mezcla cada vez.
- Después de cada respuesta aparece la **explicación**, que corresponde al "explica por qué" o "fundamenta" del cuestionario original. Se puede usar como pauta para la versión escrita.

## 5. Propuesta de clase (90 minutos)

| Momento | Tiempo | Actividad |
|---|---|---|
| Inicio | 10 min | Pregunta gatillo: "¿La pubertad es solo cosa del cuerpo?" (pregunta 3). Se anotan hipótesis. |
| Demostración | 5 min | El docente proyecta el juego, habla con la enfermera Rosa y muestra los controles. |
| Bloque 1 | 40 min | Parejas o individual. Meta: abrir el Pabellón ITS. Cada pareja copia en su cuaderno la explicación de 3 preguntas que hayan fallado. |
| Bloque 2 | 15 min | Pabellón ITS: VIH y SIDA. Captura de pantalla del certificado. |
| Cierre | 20 min | Se responde por escrito, de forma abierta, una pregunta del cuestionario original (sugeridas: 7, 8 o 12) usando lo aprendido en el juego. |

**Evaluación sugerida:** captura del certificado (puntaje al primer intento, máximo 20) + una respuesta abierta del cuestionario original.

| Puntaje del certificado | Estrellas | Lectura |
|---|---|---|
| 18 a 20 | ★★★ | Logrado |
| 14 a 17 | ★★☆ | Mayormente logrado |
| 13 o menos | ★☆☆ | Por lograr: repasar la pestaña Apuntes y volver a jugar |

## 6. Pauta de respuestas

### Bloque 1 · Cuestionario de Biología (15 preguntas · se necesitan 10 correctas)

| N° | Sala | Gráfico | Pregunta | Respuesta correcta |
|---|---|---|---|---|
| 1 | 101 · Camila | Ficha de control de salud | ¿Cuáles de estos cambios son exclusivamente caracteres sexuales secundarios? | El vello axilar y púbico, y el desarrollo de mamas |
| 2 | 201 · Hormonas | Gráfico testosterona/estrógenos 7–17 años | ¿Qué conclusión se desprende directamente del gráfico? | Desde los 9 años, en cada sexo sube más una hormona distinta |
| 3 | 102 · Matías | Diagrama de las 3 dimensiones de la pubertad | ¿Cómo evalúas la afirmación de Matías? | Es incorrecta: la pubertad también cambia emociones y relaciones |
| 4 | 202 · Anatomía | Maqueta con 4 estructuras numeradas | ¿Qué opción describe correctamente la función de cada estructura? | Epidídimo: madura espermatozoides; Uretra: saca el semen; Ovario: produce ovocitos; Endometrio: recibe al embrión |
| 5 | 202 · Anatomía | Ovocito y espermatozoide a la misma escala | ¿Qué comparación es correcta y se relaciona con su función? | El ovocito es más grande, con mucho citoplasma, y no se mueve |
| 6 | 203 · Investigación | Micrografía del espermatozoide | ¿Cuál es una pregunta de investigación científica adecuada? | ¿Más mitocondrias hacen nadar más rápido al espermatozoide? |
| 7 | 203 · Investigación | Esquema del experimento con 3 dosis | ¿Cuáles son las variables del experimento? | Independiente: dosis de estrógenos; Dependiente: grosor del endometrio; Controladas: peso, alimento y luz |
| 8 | 201 · Hormonas | Gráfico LH y FSH, ciclo de 28 días | ¿Qué indica ese aumento y qué ocurre después? | Provoca la ovulación; luego se forma el cuerpo lúteo y el endometrio sigue grueso |
| 9 | 203 · Investigación | Dos grupos de 100 usuarias | ¿Cuál es una pregunta investigable para este propósito? | ¿Con cuál de los dos hay menos embarazos por cada 100 usuarias en un año? |
| 10 | 204 · Métodos | Dibujos de los 4 métodos | ¿Qué clasificación es correcta? | Diafragma: barrera; Inyección: hormonal; Vasectomía: quirúrgico; Billings: natural |
| 11 | 103 · Valentina | Mensaje del diario mural | ¿Cómo evalúas este mensaje? | Es falso: la pastilla no protege de las ITS y el preservativo sí |
| 12 | 104 · Roberto | Esquema testículo y conductos | ¿Qué argumento biológico refuta esta idea? | Los testículos siguen produciendo testosterona, que pasa a la sangre |
| 13 | 204 · Métodos | Gráfico de barras 13 % vs < 1 % | ¿A qué se debe principalmente esta diferencia? | El condón depende de usarlo bien cada vez; el implante no |
| 14 | 105 · Patricia | Útero con trompas ligadas | ¿Qué es lo correcto? | Los ovarios siguen funcionando: el ciclo y la regla continúan |
| 15 | 205 · Agentes ITS | Los 3 agentes dibujados | ¿Cuál es el agente causal de cada una? | Gonorrea: bacteria; VPH: virus; Tricomoniasis: parásito |

### Bloque 2 · VIH y SIDA (5 preguntas agregadas)

| N° | Sala | Gráfico | Pregunta | Respuesta correcta |
|---|---|---|---|---|
| 16 | 301 · VIH | Estructura del VIH | ¿Qué es el VIH? | Un virus que ataca las defensas del cuerpo |
| 17 | 302 · SIDA | Gráfico de linfocitos CD4 en el tiempo | ¿Qué es el SIDA? | La etapa avanzada de la infección por VIH |
| 18 | 303 · Origen | Mapa de África y línea de tiempo | Según la ciencia, ¿cuál es el origen del VIH? | Un virus de chimpancés de África que pasó a las personas |
| 19 | 304 · Oportunistas | Defensas débiles y microbios | ¿Por qué una persona con SIDA se enferma con tanta facilidad? | Porque sus defensas están muy debilitadas |
| 20 | 305 · Transmisión | 4 situaciones dibujadas | ¿Cuál de estas situaciones SÍ puede transmitir el VIH? | Usar jeringas que otra persona ya usó |

## 7. Notas técnicas

- **Gráficos:** render a 720p nativo en teléfonos y 1080p en computador, sombras en tiempo real, mapas de relieve, muebles con aristas redondeadas y personajes esculpidos con rasgos distintos (ancho de cara, mandíbula, nariz, labios, lentes, canas, barba). Parpadean, mueven los labios al hablar y su pelo se mece con inercia.
- **Rendimiento:** el juego ajusta solo la resolución para mantenerse cerca de 60 cuadros por segundo y, si el teléfono no da abasto, desactiva las sombras.
- **Progreso:** se guarda automáticamente en el navegador del estudiante. Para empezar de cero: botón **Empezar de cero** en la portada, o **Libreta → Cómo jugar → Borrar mi progreso**.
- **Contenido:** datos de salud según la oferta pública chilena (examen y tratamiento de VIH gratuitos y confidenciales, Espacio Amigable para 10 a 19 años).
