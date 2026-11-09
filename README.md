# teorias-evolutivas

Recursos interactivos de biología para la clase.

| Recurso | Qué es |
|---|---|
| [`index.html`](index.html) | Quiz interactivo: Fijismo, Lamarckismo y Selección Natural. |
| [`caso-toby/`](caso-toby/index.html) | **El caso de Toby**: juego 3D educativo sobre cómo se forma el cáncer, explicado desde la genética. |

---

## 🐾 El caso de Toby

Es de noche, llueve y suena jazz bajito. Estás en tu apartamento de ladrillo y Toby, tu perro de 10 años, descansa en su camita bajo la ventana. Hoy la veterinaria encontró tumores en su piel. Para ayudarlo tienes que entender **qué es el cáncer y cómo se genera**, resolviendo 8 casos de genética sin tecnicismos.

### Cómo se juega

- Caminas por el apartamento en primera persona: te puedes levantar del computador, preparar un café, acariciar a Toby, mirar la lluvia, abrir la nevera, cambiar el disco o leer un libro.
- Cada caso empieza con un **correo** de la veterinaria en el **computador**. Luego haces una actividad (en el computador o en el **microscopio**), respondes una **trivia** y anotas la pista en la **cartelera** de corcho, donde un hilo la conecta con la foto del tumor.
- **Cada café ☕ te da una pista** para descartar una respuesta incorrecta en las trivias.
- En el **caso final** unes las 8 pistas con hilo rojo, en el orden en que se forma el cáncer.

| Caso | Dónde | Tema |
|---|---|---|
| 1. La célula y su manual | 🔬 microscopio | célula, núcleo, ADN y genes |
| 2. Copiar y equivocarse | 💻 copiadora de ADN | pares A–T / C–G, mutación |
| 3. Las causas | 💻 clasificador | azar, edad, agentes carcinógenos, herencia |
| 4. Acelerador y freno | 💻 simulador | oncogenes, genes supresores, p53 |
| 5. Los controles fallan | 🔬 fluorescencia | reparación del ADN, apoptosis, sistema inmune |
| 6. Errores que se suman | 💻 bioinformática | comparar secuencias, selección clonal (evolución dentro del cuerpo) |
| 7. El tumor | 🔬 biopsia | benigno vs. maligno, mitosis, angiogénesis, mastocitoma |
| 8. Viaje y tratamiento | 💻 informe genético | metástasis, quimio, radio y terapia dirigida (gen KIT) |

### Controles

`W A S D` / flechas para caminar · ratón para mirar (clic en la pantalla para capturarlo) · `E` o clic para interactuar · `Shift` para caminar rápido · `Esc` para pausa. En tablets y celulares hay joystick táctil y botón **E**.

### Para docentes

- **Modo docente** (menú principal): salta a cualquier caso para proyectarlo en clase.
- **Guía para docentes** (menú principal): objetivos, resumen de cada caso, preguntas para conversar e ideas erróneas que el juego corrige.
- El progreso se guarda en el navegador de cada equipo.

### Requisitos técnicos

- Un solo archivo: `caso-toby/index.html`. Funciona abierto con doble clic o publicado en GitHub Pages.
- Necesita internet la primera vez (carga three.js desde jsDelivr y fuentes de Google Fonts).
- Navegador actualizado con WebGL2 (Chrome, Edge, Firefox o Safari recientes). En equipos lentos, baja la calidad gráfica en **Pausa → Gráficos**.
- La música de jazz, la lluvia y los truenos se generan con código (Web Audio), sin archivos de audio.
